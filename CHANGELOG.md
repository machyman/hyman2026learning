# Changelog

Notable changes to the *Learning with AI* book and its companion repository. Most recent first.

**Two version lines run through this file.** Repository releases are numbered `v1.x.y`, and each one is
archived with its own Zenodo DOI. That is the number to cite. The book has a separate version line,
`v3.x.y`, and every release states which book version it carries. Entries below the v1.0.0 release of
2026-07-11 predate the archived releases and are labeled by book version.

## v1.4.0 (2026-07-19, book v3.14.0)

The judgment release, prompted by a reader's question. The book already taught students to sense that a result is wrong before locating the error. This adds the harder direction: interrogating a result that is right.

- **Book PDF updated to v3.14.0** (228 pages). Part I's verification section gains a paragraph on which assumption an answer actually depends on, using a statistical test as the example, since a test run on data that violates independence returns a number that looks exactly like a valid one. The verification checklist now asks which assumptions the answer rests on, not only whether they were identified.
- **[companion/course-case-study/](companion/course-case-study/)**: two new questions in the worked numerical-analysis course. An essentiality question in the iterative-methods assignment, asking whether positive definiteness is essential or convenient and what the weakest sufficient condition is; and a counterfactual prediction in the computational project, asking students to predict what happens to the observed order of convergence when smoothness fails, then test it.
- **[students/study-sessions/](students/study-sessions/)**: the statistics session now names the move it was already teaching. Having found the flaw in a causal claim, the student states what the conclusion rested on, and the session gives the reader the portable question: which assumption here is essential, and which is only convenient?

With thanks to Thomas Hou, whose question about mathematical taste prompted all three.


## v1.3.0 (2026-07-18, book v3.13.0)

The adoption-infrastructure release. Three audiences in one push: instructors get the teaching-preparation guide the book now points to, students get a research on-ramp, and the book's third audience, departments and institutions, gets its folder.

- **New: [companion/instructor-capabilities/](companion/instructor-capabilities/)**, a practical guide to AI for teaching preparation. For each capability: what the tool is good for, how to use it well, what a good result looks like, and how to obtain current ones. Most have free versions.
- **New: [students/undergraduate-research.md](students/undergraduate-research.md)**, for an undergraduate starting a first mentored research project: an REU, an honors or senior thesis, a lab project, a first poster. It carries the Part I practices into the research setting and hands off to the book's appendix on ethical AI-assisted scientific writing when work heads toward a journal.
- **New: [institutions/](institutions/)**, Part III's framework in paste-and-adapt form. The [departmental adoption kit](institutions/department-adoption-kit.md): a model policy statement, the shared vocabulary, the four assignment categories, and a one-semester rollout. The [policy self-audit](institutions/policy-self-audit.md): 32 checks marked institution, department, or gap, with benchmarks from published policy research. The [regulatory landscape note](institutions/regulatory-landscape.md): a dated, counsel-first orientation to where AI use crosses from policy into law, reviewed each semester.
- **Book PDF updated to v3.13.0** (228 pages). A focused Part III update: regulation named as a governance category, the missing-middle finding cited, a date-and-cadence rule for policy, a procurement clause on the access risk, an empirical corroboration, and a pointer to the new research guide.
- **README**: the chair path in "Find your path" now routes to `institutions/`; a new audience table lists the folder; the layered-explanation prompt and the worked course case study now appear in the materials tables.
- **This changelog rebuilt**: release entries dual-label their book version, the missing v1.0.0 and v1.2.0 entries were written from the release record, and historical book-version entries carry a `Book` prefix.

The manuscript remains under review with SIAM Books; v3.12.1 is the version the reviewers hold.


## v1.2.0 (2026-07-17, book v3.11.7)

A refresh of the companion materials, with two new resources.

- **New: [companion/layered-explanation/](companion/layered-explanation/)**, a template for getting AI to explain a difficult concept at three levels at once: an everyday analogy, your working level, and one step deeper. Paired with the new study move in Part I.
- **New: [companion/course-case-study/](companion/course-case-study/)**, a first numerical-analysis course designed end to end with the book's framework. A syllabus AI policy, three representative assignments with their AI-use categories, an in-person exam, and the reasoning behind each choice. A response to instructors who asked to see how the pieces fit together into one design.
- **Book PDF updated to v3.11.7** (228 pages), adding an exam-weight assessment model, a passage on mathematical judgment, and the author's own account of the recognition-production gap.
- Repository README and errata updated to match.


## v1.1.0 (2026-07-13, book v3.10.1)

The adoption release. The book now states how Part I reaches students, and the repository hands instructors the schedule for doing it.

- **New: [instructors/what-to-assign.md](instructors/what-to-assign.md)**, the adoption quickstart. A one-page schedule of what to hand students and when, with a three-item minimum for instructors with no bandwidth.
- **Learning Spiral alignment.** The four study sessions now use the book's canonical step names: `Work independently` and `Verify` replace `Work it` and `Check the AI`. The physics session was restructured so the student works the momentum calculation themselves before checking the AI's energy answer. Step names in `start-here.md` and `from-answers-to-learning.md` aligned.
- **first-time-guide.md** now links all seven instructor materials; the stale "planned materials" paragraph is gone.
- **Book PDF updated to v3.10.1** (228 pages). Part II states the distribution model and points to the assignment schedule; two UNESCO figure captions repaired; acknowledgments correction.
- **Cleanup:** em-dashes removed from companion-papers metadata per the manuscript prose standards.


## v1.0.0 (2026-07-11)

The first archived release of the companion materials, and the start of the Zenodo DOI chain. These are the practical materials the book points readers to: protocols a student can paste into an AI tool, rubrics and assignment templates an instructor can adapt, policy language a department can start from. All of it is MIT licensed. Copy it, cut it, rename it, make it yours.

- **[students/](students/)**: a pre-submission checklist, disclosure templates, guidance on sharing AI conversations, and worked study sessions in mathematics, physics, statistics, and computing.
- **[instructors/](instructors/)**: assignment templates, assessment models, syllabus language, discipline overlays, a first-time guide, and the worked AI-as-Collaborator rubric with writing and coding variants.
- **[companion/](companion/)**: the Study Partner Protocol, the Define Personal Preferences guide, and the student compact.


## Book v3.8.1 (2026-07-11)

Integration of an external review cycle, plus several additions prompted by teachers and students.

**New material in the book**

- **Keeping an AI tutor inside your course.** AI tutors reach for the most efficient method they know, which is often one the course has not taught yet. The book now shows students how to give the tutor a map (the syllabus or table of contents) and a pin (where the class is now), and shows instructors how a one-line scope note on an assignment does the job more reliably.
- **Office hours as a lost early-warning signal.** When students take their questions to a chatbot, instructors lose the informal read on who is struggling. The book now names this and argues for building the signal into the course rather than waiting for the office to fill.
- **Student buy-in.** Assignment design protects the will to learn but cannot create it, and productive struggle only happens where being wrong feels safe.
- **Persistence erosion.** A fourth learning-science mechanism: after brief AI use, people not only perform worse once the tool is removed, they also give up sooner.
- **Backward diagnosis.** Good help sometimes goes backward before it goes forward. If a hint keeps missing, the idea underneath may be the problem.

**New in this repository**

- **[instructors/rubrics/](instructors/rubrics/)**: the worked AIC rubric from Part II, with variants for writing and coding courses.
- **[companion/compact/](companion/compact/)**: the five-part student compact, printable and signable.
- The Study Partner Protocol now holds the tutor to what the course has covered, and steps back to find where a student's understanding breaks before building up again.
- Define Personal Preferences gains a course-scope setting.

**Corrections and clarity**

- Three citations retargeted to the source that actually documents the claim; two cross-references pointed at the sections that define their terms.
- The appendices are now numbered sections and appear in the table of contents, so they can be navigated and cited.
- The three core framework terms are now defined in identical words everywhere they appear, so a syllabus or policy can quote them verbatim.
- Each Part's glossary now includes the terms that Part coins.
- Repeated passages consolidated to a single full telling with pointers.

224 pages.

## Book v3.2.2 (2026-07-03)

- Broadening pass for a general STEM audience: removed gratuitous math jargon from two general-purpose checklists ("differentiate your integral" became "reach the same result by a second method"; "lemma or theorem" became "an established result"). Length-neutral; other flagged passages were already discipline-diverse and left unchanged.

## Book v3.2.1 (2026-07-03)

- Finalized the Preface genesis: named the sensitivity-analysis textbook written with Leon Arriola, and rewrote the passage in first person to match the Acknowledgments.

## Book v3.2.0 (2026-07-01)

- Added a new Preface subsection, "How this book began," telling the book's genesis: writing a textbook with Leon Arriola and realizing it ignored the AI tools students already use alongside their books, then discovering how little guidance existed on learning and teaching with AI. Presented as a hybrid with the graduate-mathematics origin, which now distinguishes the framework's origin from the book's.

## Book v3.1.1 (2026-07-01)

- Added Svetlana Barkanova (Memorial University of Newfoundland) to the Acknowledgments, crediting her feedback that broadened the detector-fairness argument beyond language to neurodiversity.

## Book v3.1.0 (2026-07-01)

- Integrated reviewer feedback (Svetlana Barkanova, Memorial University of Newfoundland). Defined the assignment-category acronyms (NAI, AIT, AIC, AIS) at first use in the abstract, disclosure paragraph, and figure caption.
- Added a paragraph on neurodiversity and detector fairness to the academic-integrity discussion: the same detection mechanism that flags non-native writers also exposes autistic and neurodivergent students, and the risk extends to automated proctoring and behavior analytics.
- Cross-referenced the companion study-sessions from the verification section so students can find worked examples.
- Content audit clean: all object counts identical to v3.0.1; 222 pages.

## Book v3.0.1 (2026-06-30)

- Converted the book to the official SIAM book format (SIAMbook2023 class, 7x10 trim, Times + Helvetica). Format-only change; the text is unchanged except for folding the Foreword into the Preface. 222 pages; 87 bibliography entries.
- Prepared as the display copy for the SIAM Annual Meeting.
- Added a reader-feedback system to the repository: a feedback guide (`FEEDBACK.md`), GitHub issue-form templates, a seeded reader FAQ, and an errata log ready for corrections.

## Book v2.17.2 (2026-06-29)

- Closing pass of the AI-panel revision arc (two rounds of multi-model review integrated across all three Parts).
- Redesigned the Learning Spiral (centered question, five-step never-closing cycle).
- Sharpened the AI-as-Tutor / AI-as-Collaborator boundary to separate provenance (where AI's work ends up) from ownership (whether the student can reproduce it via the translation test).
- Added a closing institutional theory-of-change frame (the incentive gradient and two structural levers).
- Subtitle updated to "STEM Education"; prose refined to a consistent plain, declarative voice. 226 pages; 87 bibliography entries.

## Book v2.15 – v2.17 (2026-06)

- Per-section readability and scholarly-prose-refinement passes across the manuscript.
- Reviewer-panel integration cycles (round 1 and round 2 multi-model review); acknowledgments and citation updates.

## Book v2.14.38 (2026-06-11)

- Expanded the "About the companion repository" section to cover the new guided materials.
- Companion repository enhanced with student-facing and instructor-facing materials:
  - Students: onboarding guides (`start-here`, `from-answers-to-learning`) and a worked study-sessions library (statistics, coding, physics, mathematics).
  - Instructors: a toolkit of six pieces (first-time guide, semester-redesign worked example, assignment templates, assessment models, syllabus briefings, faculty FAQ).
- Repository operational artifacts completed so that in-text links from the book resolve (SPP, DPP, checklist, disclosure templates, sharing guide, briefings, ERRATA).
- README rebuilt as a persona-routing hub. 217 pages.

## Book v2.14.37 (2026-06)

- Reviewer-feedback integration cycle: undergraduate "first attempt" on-ramp to the Learning Spiral (Part I), institutional detector-equity guidance (Part III), and the cross-unit enrollment-competition (RCM) risk in the institutional analysis. 216 pages.

## Book v2.9 – v2.14 (2026-05 to 2026-06)

- Round-2 reviewer release and subsequent integration cycles: learning-science grounding in Part II, historical-pattern and principled-skepticism framing, and companion-paper references.

## Book v2.8 (2026-05-13)

- SIAM submission baseline (round 1).

## Book v1.0 (2026-05-04)

- Original SIAM submission baseline. 141 pages.
