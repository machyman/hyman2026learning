# Assignment templates for a course with AI
*Reusable patterns that grade the judgment, not the product*

These are assignment patterns you can adapt and drop into a STEM course. They share one logic, drawn from the semester redesign: grade the part a student must be able to do unaided, not the part AI now does for them, and make disclosure routine. Each template below gives the pattern, what it builds and grades, why a student cannot shortcut it by pasting it into an AI, a skeleton you can fill in, and short illustrations across fields. Use them as starting points, and set the difficulty and the topic to your course.

A note that applies to all three: ask every submission to carry one line on where and how AI was used. `students/disclosure-templates.md` gives students short wording for that line, so it becomes a normal part of handing work in rather than a confession.

## Template 1: Audit a provided solution

**The pattern.** Give students a complete, finished solution to a problem, its result and reasoning laid out, and ask them to judge it rather than produce their own. They decide whether the approach was appropriate, whether the conclusion follows, where any error occurs, and what they would check before trusting it. You can generate the solution with AI, and you can plant a realistic flaw or leave it correct without telling them which.

**What it builds and grades.** The unaided judgment that is usually the real core of the course: reading critically, catching the flaw that matters, knowing what a trustworthy answer would need. Production is not graded, because production is what the tools already do.

**Why it cannot be shortcut.** The work is the judgment. A student who pastes the solution into an AI and asks "is this right" inherits the same unreliability the assignment is teaching them to guard against, since AI is poor at confirming work of this kind, and your low-stakes checks will show whether the judgment is the student's.

**Skeleton.** "Below is a complete solution to [problem]. Decide whether the approach is appropriate for this problem, whether the conclusion follows, and identify any step that fails. State what you would check before trusting the result, and explain your reasoning."

**Illustrations.**
- *Statistics:* an analysis that is run correctly but treats a relationship as causal when the design cannot support that claim. Students must catch the overreach, not the arithmetic.
- *Programming:* a function that passes an obvious test but fails on an untested case, such as an empty input. Students must find the case the author did not consider.
- *Physics:* a solution whose algebra is clean but whose starting principle is wrong, for instance using energy conservation in a collision where energy is not conserved. Students must catch that the right principle was not used.

The study sessions in `students/study-sessions/` walk through this kind of thinking from the student's side and make good preparation before the first such assignment.

## Template 2: Verify and correct an AI draft

**The pattern.** Invite students to use AI to produce a first attempt at something, a function, a derivation, a short analysis, and then require them to verify it themselves. They test it, document what they checked and what they found, correct any errors, and disclose how the tool was used. The submission includes the verification record, not only the finished product.

**What it builds and grades.** The habit of checking AI output instead of trusting it, and the ability to catch what it gets wrong. The graded artifact is the verification reasoning and the corrections, which is exactly the work the tool cannot reliably do for them.

**Why it cannot be shortcut.** A correct final product with no verification record earns little, because the point is the checking. A student who skips the verification has nothing to submit for the part that counts.

**Skeleton.** "Use an AI tool to draft [artifact]. Then verify it: list the cases or conditions you checked, report what you found, and correct any errors. Submit the corrected work, your verification record, and one line on how you used AI."

**Illustration.**
- *Programming:* a student has the AI write a function, then writes tests of their own, including the edge cases the AI did not mention, finds that the AI's version crashes on empty input, fixes it, and documents the catch. The grade rests on the tests and the fix, not the first draft. `students/study-sessions/coding-debugging.md` shows this verification mindset at work.

## Template 3: Choose and justify before solving

**The pattern.** Before any computation, students must state which principle, method, or test applies and why, and commit to a rough estimate of what the answer should be. Only then do they carry out the work, with or without AI, and confirm the result matches their expectation, explaining any mismatch.

**What it builds and grades.** Method selection and sanity-checking, the judgment that survives even when a tool does the mechanics. This catches the failure where the steps are valid but the starting point is wrong, and the failure where a clean-looking answer is never checked against common sense.

**Why it cannot be shortcut.** The graded work is the upfront choice and the estimate, recorded before the answer exists, plus the reconciliation afterward. Producing the final number contributes little on its own.

**Skeleton.** "Before solving [problem], state which principle or method applies and why, and estimate the answer. Then solve it, by hand or with a tool, and check the result against your estimate. If they disagree, find out why and explain."

**Illustrations.**
- *Physics:* state whether momentum or energy is the right principle for a collision and why, estimate the outcome, then compute and reconcile. A student who has chosen the right principle and a sensible estimate will catch a wrong answer immediately. `students/study-sessions/physics-which-principle.md` models this.
- *Mathematics:* predict the answer for the smallest case before deriving a general rule, then check the rule against that case. `students/study-sessions/mathematics-counting-argument.md` shows the same move catching a flawed argument.

## Using these

Pick the template that fits what you most want students to be able to do without help, and adapt the skeleton to a problem in your course. Set the difficulty by how subtle you make the planted flaw or the edge case. Keep these assignments paired with the low-stakes unaided checks described in `instructors/semester-redesign.md`, so a student who is leaning too hard on the tool finds out early. The three patterns combine well across a term: audit builds the eye for flaws, verify-and-correct builds the habit of checking, and choose-and-justify builds the judgment that has to come first.
