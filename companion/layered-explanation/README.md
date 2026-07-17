# The Layered-Explanation Prompt

*A companion template for* Learning with AI: A Framework for Students, Instructors, and Universities.
*See Part I, "Ask for help, not replacement."*

Use this when a concept sits above your current level and a single explanation is not getting you
unstuck. It asks the AI to explain the same idea at three depths at once, so you get an entry point, a
working understanding, and a sense of where the idea leads.

## The prompt

Paste this, then name your concept and your course:

> Explain **[concept]** three ways, for a student in **[course / level]**.
>
> 1. **Everyday analogy.** Explain it with a plain analogy, no technical terms, as you would to someone
>    who has never taken this subject.
> 2. **At my level.** Explain it as it would be taught in my course, using the terms and notation I am
>    expected to know.
> 3. **One step deeper.** Explain it one level beyond where I am now, so I can see what it connects to
>    and where it leads.
>
> After the three explanations, give me two or three short questions I can use to check whether I
> actually understand it, and do not include the answers yet.

## How to use it well

The three levels are not the finish line. They give you a way in; the understanding is yours only when
you can produce it without the AI in front of you.

1. **Read all three levels before deciding which helped.** Often the gap between two levels is where the
   idea finally clicks, not any single explanation on its own.
2. **Answer the check questions with the window closed.** If you cannot, you have found what to work on
   next, which is the point.
3. **Then rebuild the idea in your own words** — a few sentences, a diagram, or a worked example from
   memory. This is the step that turns a good explanation into something you know.
4. **If a level still does not land, go back one level.** A hint that keeps missing usually rests on an
   idea underneath it. Make that idea solid first, then climb back up.

## A worked example

Concept: *eigenvectors*. Course: *first linear-algebra course*.

- **Everyday analogy.** Some directions in a stretch or push do not turn; they only get longer or
  shorter. Those special directions are the eigenvectors, and how much they stretch is the eigenvalue.
- **At my level.** For a matrix `A`, an eigenvector `v` satisfies `A v = λ v`: applying `A` scales `v`
  by the number `λ` without changing its direction. You find them by solving `det(A − λI) = 0` for the
  eigenvalues, then solving for each `v`.
- **One step deeper.** When a matrix has a full set of independent eigenvectors, you can write it as
  `A = P D P⁻¹`, which turns hard repeated operations like `Aⁿ` into easy ones on the diagonal matrix
  `D`. This is why eigenvectors show up everywhere from differential equations to the stability of
  systems.

Check questions: Why does an eigenvector keep its direction under `A`? What does an eigenvalue of 0
tell you about the matrix? Can you give a 2×2 matrix and one of its eigenvectors from memory?

---

*This template is for your own study. Treat any AI explanation as a draft to verify, not a source to
cite, and follow your course's policy on when AI use is permitted.*
