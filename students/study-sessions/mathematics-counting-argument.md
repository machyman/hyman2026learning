# Study session: is this count right?
*A mathematics example (a counting argument)*

This is a worked study session. It follows one student through a counting problem using the Learning Spiral, with the AI as a study partner. The point is not the final number; it is whether the AI's reasoning for that number actually holds. Watch the student audit a confident, plausible argument by testing it on a case small enough to count by hand.

The student is using the study-partner prompt (`companion/spp/`), so the AI is set to explain its reasoning and give hints rather than just hand over answers.

## The problem

> At a small gathering, every person clinks glasses exactly once with every other person. If six people are there, how many clinks happen in total?

There is a tidy general rule for this, and the AI will state one confidently. The question is whether the rule it states is the right one.

## Try to solve

The student is not sure of a general rule, so they get a feel for the problem by counting a smaller case by hand. They try four people, call them A, B, C, and D, and list every clink:

> A-B, A-C, A-D, B-C, B-D, C-D.

> *My attempt:* For four people I count six clinks. That is fewer than I expected. I do not yet have a rule for any number of people, but at least I know the right answer for four, so I can check whatever rule I come up with.

> **What to notice:** Instead of guessing a formula, the student counted a small case they could fully see, and they did it deliberately to have something to check a general rule against. That hand count is about to do real work.

## Ask for help, not the answer

> **Student:** I am counting how many clinks happen when everyone clinks once with everyone else. I worked out that four people make six clinks, but I want a rule for any number of people. Don't just give me the number for six. What is the reasoning behind the rule?
>
> **AI:** Here is the idea. Each person clinks with everyone else, and everyone else is one fewer than the whole group. So you multiply the number of people by one less than that. For six people, that is six times five, which is thirty clinks.

> **What to notice:** The student asked for the reasoning, not the number, which is what lets them check the argument rather than just copy a result. The AI's explanation sounds completely reasonable, and the number thirty looks fine on its own. Nothing yet says it is wrong.

## Work independently

The student does not just accept thirty. They run the AI's rule on the case they already counted by hand:

> *My check:* The AI's rule says multiply the number of people by one less. For my four-person case that would be four times three, which is twelve. But I counted the clinks by hand and got six, not twelve. The rule gives exactly double what actually happens.

> **What to notice:** This is the move the session is built around. The student tested the AI's general argument on the smallest case they could verify themselves, and the rule failed it, giving twelve where the truth is six. They did not need to know in advance that the rule was wrong; the small case exposed it.

## Verify

A mismatch tells the student the rule is wrong. The audit is figuring out exactly which step fails and why:

> *Where it breaks:* When the rule counts "A clinks with three others" and then "B clinks with three others," the clink between A and B gets counted twice, once from A's side and once from B's side. Every clink is shared by two people, so counting from everyone's side counts each one twice. The rule multiplies correctly but then forgets that each clink was already counted twice. The real total is half of what the rule gives.

The student tests the corrected rule on the case they trust before believing it for six:

> *My corrected check:* Half of twelve is six, which matches my hand count for four people. Now I trust it. For six people, the rule gives thirty, so the real answer is half of thirty, which is fifteen clinks.

> **What to notice:** The student located the precise flawed step, the double-count, rather than just declaring the answer wrong. Then they re-verified the fix on the four-person case they could see before applying it to six. The conclusion rests on a check they performed, not on the AI's confidence.

## Reflect and disclose

> *My answer:* Six people make fifteen clinks. The rule is to multiply the number of people by one less than that, and then take half, because each clink is shared by two people and so gets counted twice if you count from everyone's side.

> *AI use:* I used an AI study partner to find a general rule. Its first explanation double-counted, giving twice the real number, which I caught by testing it on a four-person case I had counted by hand. I found the doubled step and corrected the rule myself. The reasoning is mine.

> **What to notice:** The student can state the rule, explain why the halving is there, and the disclosure honestly records the AI's error and how they caught it. They could rebuild this argument from scratch.

## What this session shows

- **Try to solve** produced a small case the student had counted by hand, which became the test that caught the error.
- **Asking for the reasoning instead of the number** put the AI's argument in view, where it could be checked.
- The AI's rule was confident and plausible but **wrong**, off by a factor of two because of a double-count.
- **Verify** meant testing its general argument on the smallest case the student could verify, then pinpointing the exact step that failed, not just spotting a bad number.
- The rule and the reasoning are the student's.

The same pattern works for any counting argument or short proof: when you are unsure whether the reasoning holds, test it on the smallest case you can work out by hand. If the argument disagrees with what you can see directly, the argument is where the mistake is, and tracking down the failing step is how you fix it.
