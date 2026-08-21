# Contributing

This repository holds the companion materials for *Learning with AI: A Framework for Students,
Instructors, and Universities* (SIAM Books). The materials are MIT-licensed and contributions are
welcome.

If you are reporting an error in **the book** rather than in these materials, see
[FEEDBACK.md](FEEDBACK.md) instead. The book text is under SIAM copyright, so corrections are
collected in [ERRATA.md](ERRATA.md) rather than edited here.

## What is most useful

In rough order of what the repository needs:

- **Worked examples.** A study session, a course case study, a redesigned assignment. These are the
  materials the book points to and the ones readers actually use. See
  [`students/study-sessions/`](students/study-sessions/README.md) and
  [`companion/course-case-study/`](companion/course-case-study/README.md) for the shape.
- **Tool-specific guidance.** The book is deliberately tool-agnostic because products change faster
  than print. This is where that material belongs, and where it can be revised when a tool changes.
- **Corrections and clarifications** to anything already here.
- **Translations and adaptations.** The MIT license permits them; a pointer from the relevant index
  page helps others find them.

## One hard rule: twenty-three paths are printed in the book

The book prints these paths. **Once it is in print they cannot be changed**, so a rename here becomes
a permanent dead reference for every reader:

```
companion/                    institutions/            instructors/
students/
companion/compact/            companion/dpp/           companion/instructor-capabilities/
companion/layered-explanation/                         companion/spiral-problems/
companion/spp/
institutions/department-adoption-kit.md                institutions/policy-self-audit.md
institutions/regulatory-landscape.md
instructors/briefings.md      instructors/rubrics/     instructors/what-to-assign.md
instructors/first-time-guide.md
students/checklist.md         students/disclosure-templates.md
students/sharing-ai-conversations.md
students/start-here.md        students/study-sessions/ students/undergraduate-research.md
```

Improve their contents freely. **Do not rename or move them**, and do not remove the `README.md` from
any directory in that list, since a directory link resolves only if it has one.

## Two conventions worth knowing

**Every content directory serves its index from `README.md`.** Add a new example as a descriptively
named file and add one line to that directory's index. Do not name the example itself `README.md`;
the index lists the examples, and each example keeps its own name.

**In an index, a filename is a link or it is decoration.** A filename in backticks renders as text a
reader can see and cannot click. This has bitten the repository before.

## Submitting

Small, focused pull requests are easiest to review. One example or one fix per request.

Open an issue first if you are proposing something substantial, so the shape can be agreed before you
write it.

## Timing, while the book is in production

Until the book is published, contributions that **change one of the twenty-three printed paths above** are
held on a branch and merged after publication. Everything else is merged normally. Reviewers are
reading the current site, and those twenty-three files are the surface the book commits to.

## What to expect

This repository has one maintainer. Reviews happen in batches rather than immediately, and a slow
reply is not a lack of interest. Every merged contribution is credited in the commit and, for
substantial additions, in the repository's changelog.
