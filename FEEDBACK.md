# Giving feedback on the book

This book is a living project. If you spot an error, have a question, or want to suggest an improvement, your note can make the next edition better. Here is how to reach us, whether or not you use GitHub.

## No GitHub account needed

Email **<mhyman@tulane.edu>** with `Learning with AI` in the subject line.

**If you are reporting a correction, please include:**

1. **The page number**, and the version from the title page (for example, v3.8.1).
2. **What it says now**, quoted or paraphrased, so it can be found.
3. **What is wrong**, and what it should say if you know.

Three lines is plenty. That information is what makes a correction actionable; without a page and a version, a report is hard to act on and may not reach the next edition.

**For a question or a suggestion**, just write. No format needed.

## If you use GitHub

Open an issue and pick the template that fits:

- **Report a correction** for a typo, a factual error, a broken link, or anything that reads as wrong.
- **Ask a question** if something in the book or the companion materials is unclear. Common questions become entries in the [FAQ](FAQ.md).
- **Suggest an improvement** for an idea, an example, or a resource you think would help.

New to issues? Start here: https://github.com/machyman/hyman2026learning/issues/new/choose

## Two kinds of feedback

The **book text** is under SIAM copyright, so corrections to the book are collected and reviewed rather than edited directly. Confirmed corrections are listed in [ERRATA.md](ERRATA.md) and folded into the next edition.

The **companion materials** in this repository are released under the MIT license. For those, you are welcome to open a pull request with a fix or an addition. Small, focused changes are easiest to review.

## What happens to your feedback

Feedback is reviewed on a regular cycle. When a report is confirmed:

- A correction is added to [ERRATA.md](ERRATA.md) with the page, the version, and the fix.
- A recurring question is added to the [FAQ](FAQ.md).
- The original issue is closed with a link to the entry, so you can see where it landed.

A note may be marked *fixed-in-next-edition* when the correction cannot appear in the current printing but will be in the next one.

Thank you for reading closely. Careful readers are how a book gets better.

---

## For the maintainer

**Labels.** Six labels support the triage flow. Four are applied automatically by the issue templates and **must exist, or GitHub silently drops them**. Create them once under Settings, then Labels.

| Label | Color | Description |
| --- | --- | --- |
| `erratum` | `#B60205` | Confirmed book error; promote to ERRATA.md |
| `question` | `#0E8A16` | Reader question |
| `faq-candidate` | `#FBCA04` | Question worth promoting to FAQ.md |
| `suggestion` | `#1D76DB` | Idea, example, or resource to consider |
| `fixed-in-next-edition` | `#5319E7` | Confirmed, but cannot appear in the current printing |
| `wont-fix` | `#CFD3D7` | Reviewed and declined |

With the GitHub CLI, this is six lines:

```bash
gh label create erratum               --color B60205 --description "Confirmed book error; promote to ERRATA.md"
gh label create question              --color 0E8A16 --description "Reader question"
gh label create faq-candidate         --color FBCA04 --description "Question worth promoting to FAQ.md"
gh label create suggestion            --color 1D76DB --description "Idea, example, or resource to consider"
gh label create fixed-in-next-edition --color 5319E7 --description "Confirmed, but not in the current printing"
gh label create wont-fix              --color CFD3D7 --description "Reviewed and declined"
```

**Cadence.** Review new issues on a set schedule (monthly, or more often as volume grows). For each item, apply a label, then either promote it to `ERRATA.md` or `FAQ.md`, or reply and close. Confirmed book errors carry forward to the SIAM production file for the next edition.

**Optional: a feedback form.** A form lowers the barrier for readers without GitHub accounts, and it can require the page number and version that make a correction actionable. If you add one (a Google Form takes a few minutes), it needs only five fields: kind of feedback (correction, question, or suggestion); page number and book version, if a correction; the note itself; email, optional, for a reply; and whether the reader is a student, instructor, or administrator, optional. Then add it as a contact link in `.github/ISSUE_TEMPLATE/config.yml` and at the top of this file.
