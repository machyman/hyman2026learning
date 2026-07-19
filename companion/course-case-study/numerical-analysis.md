# Case Study: An Introductory Numerical Analysis Course

*A companion artifact for* Learning with AI: A Framework for Students, Instructors, and Universities.

This is a worked example of the book's framework applied to one course, end to end: a syllabus, three
representative assignments with their AI policies, an exam, and the reasoning behind each choice. It is
not a template to copy. It shows how the pieces of the framework, the assignment categories,
Plan--Use--Verify, transfer and repair questions, and evidence of thinking, fit together into a single
coherent design.

The course is a first course in numerical analysis, taken by senior undergraduates and beginning
graduate students. The design goal is the one the book argues for throughout: preserve the reasoning
students must own, let AI help where it genuinely teaches, and assess in a way that shows the difference.

---

## 1. The design decision, before any policy

The first question is not "should AI be allowed." It is: **what must a student in this course still be
able to do when AI is unavailable, inappropriate, or untrustworthy?**

For numerical analysis, the answer is a short list:

- Derive and check error bounds, and know when an assumption is used.
- Recognize when a computed result is wrong before locating the error: a convergence rate that is too
  fast, an answer of the wrong magnitude, a solution that violates a conservation law.
- Choose an appropriate method for a problem, and say why a plausible-looking method would fail.

Everything else in the design follows from protecting that list. The mathematical content and the course
structure do not change; only the assessment does.

---

## 2. Syllabus language (AI policy section)

> **Use of AI in this course.** AI tools are part of how computational work is now done, and you will
> use them in your career. This course is designed so that AI helps you learn without doing the learning
> for you. Every assignment states which of the following applies:
>
> - **No AI (NAI).** The work must be entirely your own. These assignments protect skills you must be
>   able to perform unaided: deriving bounds, hand computation on small cases, and the judgment that a
>   result is or is not reasonable.
> - **AI as tutor (AIT).** You may use AI to explain concepts, work through examples, or check your
>   understanding while you study, but the submitted work must be written by you, unaided, afterward.
> - **AI as collaborator (AIC).** You may use AI on the submitted work itself. You must verify what it
>   produces, and you must include a short disclosure of what AI contributed and how you checked it.
>
> Unverified AI output submitted as your own is the one thing this policy does not permit. A wrong answer
> you can explain is worth more here than a right answer you cannot.

The disclosure requirement is light on purpose: a sentence or two, not a form. Its value is that it makes
verification a visible habit rather than an afterthought.

---

## 3. Three representative assignments

### Assignment A: Floating point and error (No AI)

*Protects: the ability to reason about error by hand.*

Students compute, by hand on small examples, the absolute and relative error of a floating-point
subtraction that loses significance, and explain in words why the relative error is large even though
the absolute error is small.

- **Why NAI.** This is the list from Section 1. If AI does it, the student never builds the intuition
  that a small residual can hide a large error, which the whole course later depends on.
- **A transfer question inside the assignment.** "Give a different pair of numbers whose subtraction
  loses even more significance, and one where it loses none. Explain the difference." Transfer, not
  recall: it cannot be answered by pattern-matching a worked example.

### Assignment B: Iterative methods, with AI as tutor (AIT)

*Protects: independent reconstruction of an argument the student first meets with help.*

Students study the convergence of an iterative method (for example, conjugate gradients or a fixed-point
iteration). They may use AI as a tutor while learning: ask it to explain the convergence argument, walk
through an example, or explain a step they do not follow, using the layered-explanation prompt in
`companion/layered-explanation/`.

The submitted work is then done unaided: reconstruct the convergence argument from memory, and answer a
**repair question**.

- **The repair question.** "A classmate claims the method converges for any matrix because the residual
  decreases every step. Here is their argument. What is wrong with it, and for what matrices does the
  claim actually hold?" This is exactly the skill AI makes more valuable: judging a plausible-sounding
  but flawed argument, the kind AI itself will sometimes produce.
- **The essentiality question.** "The convergence argument assumes the matrix is positive definite. Is
  that hypothesis essential, or is it convenient? State the weakest condition you can find under which
  the argument still goes through, and name the step that forces it." The repair question asks what is
  wrong with a flawed argument. This one asks why a correct argument is shaped the way it is. It is the
  harder habit, and the one AI is least able to supply, because a system that reproduces a theorem
  correctly has no stake in which hypothesis was doing the work.
- **Why AIT and not AIC.** The learning goal is that the student can produce the argument. AI as tutor
  helps them get there; AI on the submission would let a fluent explanation stand in for the ability to
  reconstruct it, which is the recognition--production gap the book warns against.

### Assignment C: A small computational project, with AI as collaborator (AIC)

*Protects: verification and judgment in realistic, tool-assisted work.*

Students implement a method (for example, a finite-difference solver for a boundary-value problem),
study its convergence numerically, and write up what they find. AI is permitted on the submission: for
code, for debugging, for drafting the write-up.

Three requirements carry the assessment:

1. **Verification is graded, not assumed.** The write-up must include a convergence study that checks the
   observed order against the theoretical one, and must state what would have signaled a bug had the
   orders disagreed. Getting a plot is not the deliverable; showing that the result is *right*, and how
   you know, is.
2. **A judgment paragraph.** "Before you ran the final version, what did you expect the answer to look
   like, and how would you have known if it was wrong?" This makes the pre-error intuition visible and
   gradeable.

3. **A counterfactual prediction.** The error bound assumes the solution is smooth. "Predict what should
   happen to the observed order of convergence when it is not, then test the prediction against a problem
   with a corner or a jump in a coefficient." A student who can predict the failure understands the
   theorem. A student who can only run the code does not, and the convergence study alone will not tell
   them apart.

- **Disclosure example (what a good one looks like).** "I used AI to draft the solver and to find a
  sign error in the boundary handling. I verified the result with a convergence study (observed order
  1.98, theoretical 2) and checked the solution against the known exact answer at three points."

---

## 4. The exam (in person, closed book)

The exam is where the No-AI list is assessed directly, and it is weighted to carry the grade, which is
what lets the homework be a place to learn rather than a place to police. Three question types:

- **Derivation.** State and prove an error bound, with one step left blank to fill in, testing whether
  the student knows where each assumption enters.
- **Transfer.** A method shown in class, applied to a nearby problem it was not demonstrated on, with a
  short question about what changes.
- **Judgment / repair.** A worked computation with a plausible but wrong conclusion. "Something here is
  wrong. Identify it, and explain what should have signaled that the result was not reasonable." This is
  the intuition from Section 1, assessed under exam conditions where no tool can supply it.

---

## 5. How the grade is weighted, and why

| Component | Weight | What it protects |
|---|---|---|
| Homework (A, B, C combined) | 20% | A place to learn, including with AI, without high stakes on any single submission |
| In-person exams | 65% | The No-AI list: derivation, transfer, and judgment, assessed directly |
| Computational project (C) write-up and verification | 15% | Responsible tool-assisted work and visible verification |

The weighting is the quiet engine of the whole design. Because the grade rests on in-person assessment,
it matters far less how a student did the homework, which removes the incentive to hide AI use rather
than trying to detect it. No AI detector is used anywhere in the course. The homework can then do what
homework is for: practice, including the kind of AI-assisted practice that genuinely helps, while the
exam confirms what the student can do alone.

This is one design, not the design. A course with a strong project component might invert the weights; a
large course with limited grading support might lean harder on the exam still. The framework gives the
vocabulary for those choices. It does not make them for you.
