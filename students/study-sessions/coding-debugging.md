# Study session: finding a bug yourself
*A coding / debugging example*

This is a worked study session. It follows one student debugging a small program using the Learning Spiral, with the AI as a study partner rather than a repair service. The point is not the fix; it is how the student finds it, and how they catch the AI when its own fix is wrong.

The student is using the study-partner prompt (`companion/spp/`), so the AI is set to ask questions and give hints rather than rewrite the code.

## The problem

A student wrote a function to find the highest score in a list. It passed their quick test, but the autograder fails it on some hidden cases.

```python
def highest_score(scores):
    highest = 0
    for score in scores:
        if score > highest:
            highest = score
    return highest
```

> Their quick test: `highest_score([72, 88, 95, 60])` returns `95`. Looks right. So why does it fail?

## Try to solve

Before asking the AI, the student reads their own code and forms a guess:

> *My attempt:* It works on my test, so the loop logic seems okay. The hidden tests must use inputs I did not think of. I have a vague feeling the starting value `highest = 0` might matter, but I am not sure why.

> **What to notice:** The student did not paste the code and ask "what's wrong." They read it, confirmed what works, and narrowed the problem to "inputs I did not think of," with a hunch about the starting value. That hunch is exactly what a good question can sharpen.

## Ask for help, not the fix

> **Student:** Here is my function. [pastes it] It passes my own test but fails some hidden ones. Don't fix it. Ask me a question that would help me find why it fails on certain inputs.
>
> **AI:** Sure. What value does `highest` start at, and what would the function return if every number in the list were below that starting value?

> **What to notice:** The student asked for a question, not a rewrite, and used the book's diagnostic move: let the AI help you locate the bug rather than remove it. The understanding stays with the student.

## Work independently

> **Student:** It starts at 0. So if all the scores were below 0, say a list of penalties like `[-5, -2, -9]`, the function would never find anything bigger than 0, and it would return 0, which is not even in the list. The starting value of 0 is the bug.

> **What to notice:** The student found it themselves. The function silently assumed every score is positive; with all-negative input it returns a number that was never in the list. They reached this by reasoning about the case the question pointed at, not by being handed the answer.

## Verify

Now the student asks the AI for the fix, and then does the thing that matters: checks it.

> **Student:** Okay, now you can suggest a fix.
>
> **AI:** Start `highest` at the first element instead of 0:
> ```python
> def highest_score(scores):
>     highest = scores[0]
>     for score in scores:
>         if score > highest:
>             highest = score
>     return highest
> ```

> **What to notice:** This looks right, and it does fix the all-negative case. A student in a hurry would paste it and move on. Instead the student tests it against the inputs they can think of:

> **Student:** That handles negative scores. But what if the list is empty? `scores[0]` would crash, because there is no first element. The original returned 0 for an empty list, which was also wrong, but this version errors out instead. The fix is not complete.
>
> **AI:** Good catch. You are right that an empty list needs its own handling, and deciding what `highest_score([])` should do is a real choice, not an afterthought.

> **What to notice:** This is the move the session is built around. The AI's fix was confident and looked correct, but it introduced a new failure on the empty-list case. The student caught it by checking the AI's code against an edge case, which is exactly the kind of self-confirmation AI is unreliable at. Catching it was only possible because the student understood what the code was doing.

## Reflect and disclose

The student decides what an empty list should do (here, return `None` to signal "no scores"), writes the fix, and tests both the all-negative case and the empty case:

```python
def highest_score(scores):
    if not scores:
        return None
    highest = scores[0]
    for score in scores:
        if score > highest:
            highest = score
    return highest
```

> *AI use:* I used an AI study partner to debug. It asked me a diagnostic question that helped me find the starting-value bug, and when I asked it to fix the code, its fix handled negatives but crashed on an empty list, which I caught and corrected. The final code and the decision about empty input are mine.

> **What to notice:** The student can explain every line and every case, the disclosure is honest about the AI's contribution and its mistake, and they could rewrite this from a blank page.

## What this session shows

- **Try to solve** turned "what's wrong with my code?" into a sharper question about untested inputs.
- **Asking for a diagnostic question instead of a fix** kept the debugging skill with the student.
- The student found the starting-value bug **themselves**.
- **Verify** caught the new bug the AI's fix introduced (the empty-list crash). The book's warning that AI is unreliable at confirming its own code is exactly what played out, and the student's understanding is what caught it.
- The final code is the student's, edge cases and all.

The same pattern works for any debugging: read your own code first, ask the AI to help you locate the problem rather than remove it, and test anything the AI hands you against the cases it did not mention.
