# Study session: is this relationship causal?
*A statistics / data-reasoning example*

This is a worked study session. It follows one student through a genuinely messy problem using the Learning Spiral, with the AI as a study partner rather than an answer machine. The point is not the specific answer; it is the moves. Watch where the student keeps the thinking, and especially where they refuse to let the AI hand them a conclusion.

The student is using the study-partner prompt (`companion/spp/`), so the AI is set to give hints and ask questions rather than deliver answers.

## The problem

> A campus report finds that students who use the tutoring center have higher average grades than students who do not. The report concludes that the tutoring center raises grades. Your homework asks: does the report's evidence support that conclusion?

It looks simple, and the AI would happily produce a confident answer. That is exactly the trap.

## Try to solve

Before opening the AI, the student writes down their own first read:

> *My attempt:* The tutoring students have higher grades, so tutoring seems to help. But I am not sure the report can really say tutoring *caused* it. Something feels off about comparing the two groups, and I am stuck on what exactly is wrong.

> **What to notice:** The student does not know the full answer, but they have made a real attempt and located the exact point of confusion, whether a difference between two groups can show cause. That is a far better starting place than "is this causal?" with nothing behind it.

## Ask for help, not the answer

> **Student:** Here is a homework claim. [pastes it] I think the report might be wrong to say tutoring *caused* the higher grades, but I cannot pin down why. Don't tell me the answer. Ask me a question that would help me see what is going on.
>
> **AI:** Good instinct. Here is a question to sit with: who decides to use the tutoring center, and might those students already differ from the students who do not, in ways that affect grades on their own?

> **What to notice:** The student asked for a question, not a verdict, and the study partner responded with one that points at the issue without naming it. The student still has to do the thinking.

## Work independently

> **Student:** Okay. The students who go to tutoring probably chose to go. Students who choose extra help might already be more motivated, or have more time, or be more organized. So maybe those students would have had higher grades anyway, with or without tutoring. The two groups were not the same to begin with.

> **What to notice:** This is the heart of the problem, and the student reached it themselves. The groups were not assigned at random; students selected into tutoring, so a difference between them could come from who they already were rather than from the tutoring. A hidden difference like this, one that affects both who gets the "treatment" and the outcome, is called a confounder.

## Verify

To test their reasoning, the student deliberately asks the AI for the easy answer, to see whether they can catch the trap:

> **Student:** Just to check, can you confirm the report is right that tutoring raises grades?
>
> **AI:** The data are consistent with tutoring raising grades, and that is a reasonable possibility.

> **What to notice:** Read that carefully. The AI gave a fluent, agreeable answer that *sounds* like a yes, and a student in a hurry would copy it. But "consistent with" is not "shows." The student catches it.

> **Student:** "Consistent with" is not the same as "shows." The report only observed who used tutoring; it did not assign students to tutoring at random. So it cannot rule out that more motivated students both seek tutoring and earn higher grades. The evidence is consistent with tutoring helping, but it does not establish it.
>
> **AI:** That is right, and it is the key distinction. To support a causal claim you would want something closer to a comparison of similar students who were assigned to tutoring or not, or at least a serious attempt to account for the differences between the groups.

> **What to notice:** This is the move the whole session is built around. The AI's confident, agreeable phrasing was exactly the kind of certainty the student had to refuse. Checking the AI was only possible because the student understood the problem well enough to see the gap between "consistent with" and "shows." That understanding is what the session was for.

## Reflect and disclose

The student writes the final answer in their own words:

> *My answer:* The report's evidence does not support the conclusion that tutoring raises grades. Because students chose whether to use tutoring, the two groups may have differed before any tutoring happened, so the higher grades could reflect who used tutoring rather than an effect of the tutoring itself. The finding is consistent with tutoring helping, but showing that would require comparing similar students assigned to tutoring or not, or otherwise accounting for the differences between the groups.

And a brief disclosure:

> *AI use:* I used an AI study partner to stress-test my reasoning. It asked me a guiding question, and when I asked it to simply confirm the claim, it gave an agreeable answer that I had to correct. The reasoning and the final answer are mine.

> **What to notice:** The student can explain every line without the AI, the disclosure is honest about what the AI did (including that it nearly led them astray), and they could redo this argument from a blank page.

## What this session shows

- **Try to solve** turned "is this causal?" into a specific question the student could work on.
- **Asking for a question instead of a verdict** kept the thinking with the student.
- The student reached the confounder idea **themselves**.
- **Verify** caught its agreeable, fluent answer; the trap of adopting the model's certainty was avoided only because the student understood the problem.
- The answer is the student's, and they can defend it.

The same pattern works in any data-reasoning course: state your own read, ask the AI to widen or stress-test it rather than conclude, and check every confident claim against what the design can actually support.
