---
title: AI learning tools
permalink: /companion/learning-tools/
---

# AI tools built for learning

*A companion working guide for* Learning with AI: A Framework for Students, Instructors, and Universities.

The book teaches how to judge a learning tool. This page lists current tools, because the list changes faster
than any book can. Products get renamed, move behind menus, and disappear. The questions for judging them do not.

**Status as of 11 November 2026.** Every entry was researched on that date. Check a tool's own site before you
rely on it, and see the date at the top of this page before you trust a detail. The evidence behind each entry,
with full references, is on the [evidence page](evidence.md).

## What the evidence says, in one paragraph

Guardrails prevent harm, but learning gains come from structure that makes the student do the work. In a large
high-school trial, unrestricted GPT-4 raised practice scores and then cut later exam scores by 17 percent. A
tutor that withheld answers removed that loss but added no gain. Gains appeared when the setup made students
work: step-by-step prompts that held back the final answer, a mastery requirement, or a person in the loop. When
the AI does the work, scores rise and learning does not. None of the tools below has shown lasting learning
gains in a university STEM course. Treat them as places to practice the book's method, not as the method.

## Four questions for judging any tool

1. **Does it hold back the answer until the student has tried?**
2. **Can the instructor give it the course context** (the assignment, the allowed help, what is off limits)?
3. **Can students turn its guardrails off?** If they can, the students who most need them will, near deadlines.
4. **Has anyone measured what students can do later without it?** Scores while the AI is on are not evidence
   of learning.

Two more questions matter before anyone uploads coursework: who sees the conversations, and how long are they
kept? Use your institution's education account where one exists. Education terms usually exclude your data from
model training; personal accounts often do not.

## Course tutors an instructor sets up

These give the instructor real control: course context, guardrails the student cannot switch off, and often a
view of what students ask. Their weakness is evidence. Most have usage data, not learning data.

| Tool | What it is | Cost | Evidence | Caveats |
|---|---|---|---|---|
| [CodeHelp](https://codehelp.app/) | A programming assistant that explains errors and concepts without writing solution code. Instructors add course and assignment context. *Focused Tutors* turn module objectives into short tutor chats. Open source ([Gen-Ed](https://github.com/liffiton/GenEd)). Run by Mark Liffiton, Illinois Wesleyan University. | Free software. The instructor pays the AI provider, about $0.50 per student per term. | One course of 52 students: usage and surveys, no learning measure. Stronger students used it more. | Read the privacy policy before adopting; we could not open it on the check date. |
| [OATutor](https://github.com/CAHLR/OATutor) | An open-source adaptive tutor for college algebra and statistics from UC Berkeley. AI help appears as hints inside structured problems, not as an open chat. Works with Canvas. | Free; self-hosted. | A randomized study of 274 learners: AI-written hints worked as well as human-written ones. Before quality checks, a third of the AI hints were wrong. | Needs technical setup. Covers precalculus and statistics only. |
| [CS50.ai](https://cs50.readthedocs.io/cs50.ai/) | Harvard's guarded tutor for its CS50 course, the "CS50 Duck". | Free to CS50 students. | Large deployment data; no learning measure. | Only for CS50. In 2026 it still returned code up to a quarter of the time: prompt-only guardrails leak. A good design reference for instructors building their own. |
| Harvard physics tutor design | Not a product. The tutor in the randomized study by Kestin and colleagues, which beat in-class active learning on an immediate test. It was given instructor-written solutions and was never trusted to solve problems alone. | Free. The prompt guidelines are in the paper's [supplementary material](https://doi.org/10.1038/s41598-025-97652-6). | Peer-reviewed randomized study, one course, immediate test only. | A recipe to copy, not a tool to sign up for. |

## Study modes a student turns on

All four major assistants now offer a mode that asks questions instead of handing over answers. Each is a
setting the student chooses. A student can leave it with one click, and no vendor lets a university lock it on.
Each also gives wrong answers with confidence, so the verify habit still applies.

| Mode | How to find it (11 Nov 2026) | Evidence | Caveats |
|---|---|---|---|
| [Gemini Guided Learning](https://blog.google/outreach-initiatives/education/guided-learning/) | In Gemini's tools menu, and inside Google Classroom. U.S. college students can get Google AI Pro free for a year. | The most trials of any mode, all run by Google, including one with university students. | Vendor-run evidence only. Use an education account. |
| ChatGPT Study mode | Removed from the main menu for adult accounts in spring 2026. Type "/" in a chat to find it. Kept for education customers and promoted for teens. | One OpenAI study of 300+ college students: a gain in microeconomics, no difference in neuroscience. No paper. | The entry point keeps moving. No instructor lock. |
| [Claude Learning](https://support.claude.com/en/articles/10181068-styles-are-moving-to-skills) | In Claude.ai, now a skill you install (Customize, then Skills); it was a style until November 2026. In Claude Code, the Learning output style leaves a `TODO(human)` for the student to write. | None found. | The docs say plainly that nothing enforces it. |
| [Microsoft Copilot Study and learn](https://support.microsoft.com/education/study-learn-agent) | A mode in Copilot; a Study and Learn Agent in Microsoft 365 Education. Admins can pre-select it; it is off by default in higher education. | None found. | The most admin control of any mode, but pre-selected does not mean required. |

**Gemini Notebook** (called NotebookLM until July 2026) is a different kind of tool. It builds flashcards and
quizzes from course sources you upload, which supports retrieval practice. It also summarizes readily, so it can
replace the reading instead of reinforcing it. Use the quizzes; read the sources.

## Checkers

These do not tutor. They check, which serves the verify half of the book's method.

| Tool | Use | Cost | Caveats |
|---|---|---|---|
| [Waterproof](https://arxiv.org/abs/2211.13513) | A proof assistant for introductory proof courses. Students write proofs in near-natural language, and it checks every step. It cannot hand over a proof. From TU Eindhoven and partners. | Believed free; licence not confirmed. | One non-randomized 2026 study: students wrote more explicit proofs. |
| [Wolfram\|Alpha](https://www.wolframalpha.com/) | Reliable computation where chatbots slip on arithmetic. | Free basic; student Pro $5 a month or $60 a year for step-by-step solutions. | The step-by-step view is an answer key. Do the problem first, then check. |

## Watching

These are promising or popular but not yet listed, for the reason given.

- **Digital Student Assistant** (Yusuf Pisan, UW Bothell): the strongest guardrail design we found, with a
  built-in teach-back persona that asks the student to explain. Tested so far only on scripted students, the
  code is private, and its own pages disagree on who can use it.
- **MathGPT.ai**: built to withhold answers for college math, with instructor controls. Current status, pricing
  and privacy terms not yet confirmed; no independent evidence.
- **Khanmigo**: well guarded but built for K-12. Its one independent randomized trial found small effects and
  thin engagement.
- **Tutor CoPilot**: coaches human tutors rather than students. Useful as a model for training teaching
  assistants.
- **Jill Watson, Coursera Coach, Canvas IgniteAI, Eedi with LearnLM**: developer-reported results, instructor-side
  features only, or school-level studies.

Tools that simply hand over answers (Photomath, for example) are left off on purpose.

## How this page is kept

The list is reviewed each term, and the date at the top changes when it is. If a tool here has changed, or you
know one that belongs, open an issue (see [FEEDBACK.md](../../FEEDBACK.md)). This page was compiled with AI
research assistance and reviewed by the author. The evidence page marks each source as peer reviewed, working
paper, vendor-reported, or retracted.
