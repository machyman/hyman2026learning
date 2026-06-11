# Redesigning a course for a term with AI
*A worked example: introductory statistics*

The first-time guide lays out the principles. This is a worked example of applying them to one specific course across a term, so you can see what the redesign actually looks like and adapt it to your own. The course here is introductory statistics, chosen because it is taught across nearly every field and because AI disrupts it sharply: a student can now hand an AI a data set and a question and receive a finished analysis with a written interpretation. The same five steps apply to any course, and the closing section shows how to map them.

## The course before

A traditional introductory statistics course often runs on homework sets where students carry out analyses and write up what the results mean, with exams that ask for more of the same. The unspoken assumption is that doing the analysis and explaining it requires understanding the analysis.

That assumption no longer holds. An AI can run the test, produce the output, and write a fluent interpretation, all without the student forming any judgment about whether the analysis was appropriate or the conclusion sound. A course built on the old assumption now measures what the AI can do, not what the student can.

## Step 1: Name the core competence

Start by deciding what a student must be able to do unaided, because that is what the course exists to build and what your assessments have to reach. In introductory statistics, the unaided core is mostly judgment rather than computation:

- deciding whether a given analysis is the right one for the question and the data,
- reading output critically rather than taking the headline number at face value,
- telling a sound conclusion from one that overreaches, for instance treating a relationship as causal when the design cannot support it.

Notice what is not on that list. Carrying out the arithmetic of a test is no longer the core competence; the tools do it reliably. The judgment about whether the test means anything is the part that has to live in the student.

## Step 2: Decide and state the policy

With the core named, set your AI policy to protect it and write it into the syllabus in plain language. For this course, a workable stance is that AI is allowed for running analyses and exploring ideas, and that every student must be able to defend the judgment behind any submitted work without the tool in front of them. The ready-to-adapt paragraphs in `instructors/briefings.md` give wording for a stricter or looser stance if this one does not fit your setting. The point is that students know the rule and the reason.

## Step 3: Redesign the assignments

This is where most of the work is, and the move is to shift assignments from producing an analysis to judging one. A homework problem that used to read "run a test on this data and interpret the result" becomes "here is an analysis someone has already run, with its output and a written conclusion; decide whether the analysis was appropriate, whether the conclusion follows, and what you would check before trusting it."

An assignment in that form cannot be finished by pasting a prompt, because the work is the judgment, and the judgment is exactly what you want to build and grade. It also lets you plant realistic flaws, an analysis that is run correctly but answers the wrong question, or a conclusion that quietly assumes causation, so that students practice catching the failures that matter.

Build disclosure into every assignment with a single required line on where and how AI was used. Treat that line as normal practice rather than a confession, the same standard you hold yourself to.

The worked study session in `students/study-sessions/statistics-causal-claim.md` is a good model of the thinking these assignments should provoke, and it makes useful assigned reading early in the term.

## Step 4: Redesign the assessment

You need some way to see the unaided judgment directly, or you are back to grading the AI. This does not mean returning to high-pressure closed exams. A few low-stakes, recurring checks do the job:

- a short in-class exercise where students read a piece of output and say what it does and does not support,
- a brief conversation about a submitted assignment, where the student explains why they judged an analysis sound or not,
- a few minutes asking a student to talk through their own reasoning on a problem.

Each of these reveals quickly whether the judgment is the student's. Keep the stakes low and the frequency steady, so the checks guide learning rather than threaten it, and so a student who is leaning too hard on the tool finds out early enough to change.

## Step 5: Point students to support

Tell students where to build the habits the course now rewards. `students/start-here.md` orients a student who is new to using AI for coursework, and `students/from-answers-to-learning.md` is for the student who has been using AI to get answers and wants to shift to using it to learn. Making these the first reading of the term sets the expectation that the tool is for understanding, not for avoiding it.

## What changes, and what to expect

The visible change is small: the course still covers the same statistics. What moves is the weight, from carrying out analyses toward judging them, and the assessment follows that shift. The first term will be a calibration. You will find that some of what you used to grade is now done by the tool, and that some judgment you assumed students had needs explicit teaching. Adjust the balance as you learn where the real difficulty sits.

## How to adapt this to your course

The five steps are the same in any field. Name the unaided core competence, the judgment or skill the tool cannot stand in for. Set and state a policy that protects it. Rewrite assignments so the graded work is that core rather than the part the tool now does. Add low-stakes unaided checks so you can see the core directly. Point students to the habits that will get them there.

What differs is only the content of step one. In a programming course the unaided core might be reading code and reasoning about why it fails rather than producing it. In a physics course it might be choosing the right principle for a problem rather than grinding through the algebra. In a writing-heavy course it might be building and defending an argument rather than generating prose. Name that core honestly for your own course, and the rest of the redesign follows from it.
