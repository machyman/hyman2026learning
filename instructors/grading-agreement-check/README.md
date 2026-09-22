---
title: Grading-agreement check
permalink: /instructors/grading-agreement-check/
---

# The grading-agreement check

*Before an AI tool scores student work, show that it agrees with you. Page dated 2026-09-22.*

Part II of *Learning with AI* gives the four conditions under which an AI grading tool can be used and the reasoning behind them. This page is the working form: what to write down, what to measure, and what to keep. The measures are durable. The tools are not, which is why the page carries a date and the record below carries a version string.

| File | What it is |
|---|---|
| [grading-agreement-check.xlsx](grading-agreement-check.xlsx) | A workbook that computes the three measures from your score columns. Every number is a formula; paste scores in and read the results. Rows 2 to 21 of the Scores sheet are a made-up example; delete them before entering your sample. |

## Before the term

**1. The rubric.** One row per thing you are grading. Each row needs explicit levels and one scored example per level, taken from real work if you have it and written by you if you do not. If you cannot write an example of a level, the level is not yet a criterion. The rubrics in [rubrics/](../rubrics/) are a starting point.

**2. The record.** Fix and write down: the tool, the model and its version string, the date, the rubric version, and who will read the disagreements.

## The sample comparison

**3. Grade by hand first.** Choose a sample that covers every level of every rubric row, including the work you expect to be hard to score. Grade it yourself without seeing any AI score. Twenty to forty items is enough to start; the workbook holds two hundred.

**4. Run the tool on the same sample**, with the rubric and the scored examples in the prompt.

**5. Compare.** Enter your scores, a second human grader's scores, and the tool's scores in the workbook's Scores sheet, one row per item and rubric row. The Measures sheet computes:

| measure | what it computes | passes if |
|---|---|---|
| agreement with you | quadratic weighted kappa between your scores and the tool's | at or above 0.70 |
| the human baseline | the same statistic between you and the second grader on the same sample | the tool is no worse than the two humans |
| where it fails | the rubric rows and the student groups holding the tool's disagreements with you | no cluster in one row or one group |

If the first two pass and the third shows a cluster, the tool is usable on the rows that passed and not on the rest.

**Kappa in three sentences.** Weighted kappa compares the disagreement you observed with the disagreement two graders would produce by chance, given how often each of them uses each level. Quadratic weights count a two-level miss four times as heavily as a one-level miss, which is what you want when the levels are ordered. Kappa is 1 for perfect agreement, 0 for chance agreement, and negative when the graders agree less often than chance.

**One worked example**, the made-up scores shipped in the workbook: twenty items on a four-level rubric with three rows (verification, ownership, disclosure). The tool matches you exactly on 13 of 20 items, and its kappa against you is 0.83; the second grader's kappa against you is 0.77. Both measures pass. But five of the tool's seven disagreements fall on the disclosure row, an 83% disagreement rate against 14% on each of the other two rows. Verdict: use the tool on verification and ownership, score disclosure yourself, and look at why the disclosure rubric reads differently to the tool than to you.

## During the term

**6. Re-check** a small sample when the tool or its version changes, and once at mid-term.

**7. Read every disagreement** between the tool's score and your spot check. The grade is yours.

**8. Tell the students**, in the syllabus and on the returned work when it matters: that AI helped, what it did, that a person decided, and how to ask for another look. The three syllabus paragraphs in [briefings.md](../briefings.md) have a place for this.

## What to keep, per course, per term

- rubric version and scored examples
- tool, model, version string, prompt
- the hand-graded sample and all three score columns
- the three measures and their results, which the workbook holds
- each disputed score and the instructor's decision

A grade that cannot be reconstructed from this record cannot be defended on appeal.

Back to the [instructor materials](../).
