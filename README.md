# hyman2026learning — *Learning with AI*

Companion repository for the book *Learning with AI: A Framework for Students, Instructors, and Universities* by James M. Hyman.

**Subtitle:** *From Graduate Mathematics to Undergraduate Education, Departmental Practice, and Institutional Policy*

**Current version:** v2.10 (canonical, 2026-05-25)
**Status:** Under review with SIAM Books on Education
**Pages:** 196
**License:** MIT (see `LICENSE`)

---

## About this book

*Learning with AI* is a framework for engaging with AI in higher education across three audiences:

- **Part I — Students:** How to use AI to learn rather than to substitute for learning. Introduces the Core/AI-assisted/Trustworthy (CAT) framework, the Learning Spiral, the Student's Trilemma, the translation test, and operational practices for thoughtful AI use.
- **Part II — Instructors:** How to design courses and assessments that work with AI rather than around it. Develops the Instructor's Trilemma, the Honest-A Bind taxonomy, and the calibration-restoring design philosophy for assessment. The v2.10 release adds canonical learning-science grounding for the framework's pedagogical claims, citing Ambrose et al. *How Learning Works*, Freeman et al.'s 2014 PNAS active-learning meta-analysis, Wiggins and McTighe on backward design, Soderstrom and Bjork on the learning-versus-performance distinction, Hattie and Timperley and Black and Wiliam on feedback and formative assessment, Mazur on peer instruction, Sweller et al. on cognitive load, and the *How People Learn II* National Academies report.
- **Part III — Departments and Institutions:** How to set policy frameworks that protect learning without pretending AI can be kept outside academic life. Develops the institutional vocabulary for AI-era curriculum, assessment, and academic-integrity procedure.

The book's argument is grounded in graduate mathematics teaching (the Graduate Mathematics Intelligence Profile, GMIP) and the AI-Integrated Graduate Mathematics Assessment Framework, both included as appendices. The framework generalizes from graduate mathematics to the full range of university courses.

---

## What's in this repository

| Item | Status | Path |
|---|---|---|
| **Book PDF** | v2.10 (2026-05-25) | `book/learning_with_ai_v2_10.pdf` |
| **License** | MIT | `LICENSE` |
| **Citation metadata** | CFF format | `CITATION.cff` |
| **Changelog** | Full history; v2.10 entry at top | `CHANGELOG.md` |
| **Companion paper: AI and the Next Layer of Human Work** | **v1.0 locked 2026-05-25** (10 pp) | `companion-papers/hyman2026next/` |
| **Companion paper: Teaching AI Responsibly to Principled Skeptics** | **v1.0 locked 2026-05-25** (18 pp) | `companion-papers/hyman2026teaching/` |

The book PDF in this archive is the canonical version following the Session 18 Part II citation-grounding integration. The two companion papers are included at their canonical v1.0 lock state. Each directory contains the LaTeX source, the bibliography file, the compiled PDF, and a Delta document summarizing the v1.0 changes.

---

## Companion papers

Two companion position papers develop intellectual foundations the book draws on. Both are included in this repository at their canonical v1.0 lock state (2026-05-25).

### AI and the Next Layer of Human Work (`companion-papers/hyman2026next/`)

A position paper that develops the historical-pattern argument the book introduces in the Foreword's "Why this is not the first time" subsection. Six historical analogies (photography, calculators, programming libraries, power tools, spellcheck, operational vs. mechanical knowledge) ground the central thesis: powerful tools change what skill means rather than eliminating skill. Three audience-specific sections (Students, Faculty, Administrators) parallel the book's three parts.

- **Bibkey:** `hyman2026next`
- **Length:** 10 pages
- **Files:** `hyman2026next.tex`, `hyman2026next.bib`, `hyman2026next.pdf`
- **Compile recipe:** `pdflatex → bibtex → pdflatex → pdflatex` (natbib backend)

### Teaching AI Responsibly to Principled Skeptics (`companion-papers/hyman2026teaching/`)

A position paper that develops the framework the book introduces in Part I's principled-skepticism paragraph. Five-layer literacy framework (technical, environmental, ethical, practical, civic). Engages seriously with the case for principled refusal of AI engagement on environmental, ethical, or political grounds. Citations include IEA energy data, OECD on hidden costs, Crawford's *Atlas of AI*, Bender et al. on stochastic parrots, EU AI Act Article 4. Three audience-specific sections mirror the book.

- **Bibkey:** `hyman2026teaching`
- **Length:** 18 pages
- **Files:** `hyman2026teaching.tex`, `hyman2026teaching.bib`, `hyman2026teaching.pdf`
- **Compile recipe:** `pdflatex → biber → pdflatex → pdflatex` (biblatex backend; requires `biber` and `biblatex.sty`)

---

## How to use this material

### As a reader

Download `book/learning_with_ai_v2_10.pdf` and read in your preferred PDF viewer. The book is structured for three different reading paths:

- **Students:** Read the Foreword and Part I. Parts II and III are for context, not necessary for student practice.
- **Instructors:** Read the Foreword and Part II. Part I will help you understand what students are being taught; Part III will help you understand the institutional context you're working in.
- **Department chairs, deans, and administrators:** Read the Foreword and Part III. Parts I and II are for context on what the framework is asking you to enable.

For deeper background, the two companion papers in `companion-papers/` develop the historical-pattern argument and the principled-skepticism framework that the book introduces in summary form.

### As a citation source

Use the metadata in `CITATION.cff` for reference managers (Zotero, Mendeley, etc. that support the Citation File Format). For BibTeX:

```bibtex
@book{hyman2026learning,
  author = {Hyman, James M.},
  title = {Learning with AI: A Framework for Students, Instructors, and Universities},
  subtitle = {From Graduate Mathematics to Undergraduate Education, Departmental Practice, and Institutional Policy},
  publisher = {SIAM Books},
  year = {2026},
  edition = {Canonical v2.10},
  note = {Under review with SIAM Books on Education. Available at https://github.com/machyman/hyman2026learning}
}
```

For the companion papers:

```bibtex
@unpublished{hyman2026next,
  author = {Hyman, James M.},
  title = {AI and the Next Layer of Human Work},
  year = {2026},
  note = {v1.0 lock 2026-05-25. Available at https://github.com/machyman/hyman2026learning/tree/main/companion-papers/hyman2026next}
}

@unpublished{hyman2026teaching,
  author = {Hyman, James M.},
  title = {Teaching AI Responsibly to Principled Skeptics},
  year = {2026},
  note = {v1.0 lock 2026-05-25. Available at https://github.com/machyman/hyman2026learning/tree/main/companion-papers/hyman2026teaching}
}
```

### As a framework for your course or institution

The book's frameworks (CAT, Learning Spiral, two-transcript idea, GMIP) are released under MIT license. You are free to use, adapt, and integrate them into your own courses, syllabi, policies, and institutional documents. Attribution is requested but not required (per MIT). Modifications are welcome.

If you adapt the framework substantively for your context, the author would be interested to hear about it: mhyman@tulane.edu.

---

## Version history

See `CHANGELOG.md` for the full version history of the book.

Major milestones:

- **v2.10 (2026-05-25):** Part II citation-grounding integration. Seven inline integrations across Part II linking the framework's pedagogical claims to the canonical teaching-effectiveness and learning-science literature. Bibliography grew 58 → 67 entries. 196 pages.
- **v2.9 (2026-05-24):** Round-2 reviewer release. Added historical-pattern frame, calculator-touchstone threading across three audiences, principled-skepticism acknowledgment, companion-paper references. 194 pages.
- **v2.8 (2026-05-13):** SIAM submission baseline (round 1). Completed Yuwei Bao student-reviewer integration arc.
- **v1.0 (2026-05-04):** Original SIAM-submission baseline (141 pages).
- Earlier versions: v0.95-v0.999 MREP review cycles (Sessions 1-8).

---

## Development Tools

This research used AI-assisted workflows for manuscript preparation and review.
See the manuscript's Acknowledgments section for the full disclosure.
All mathematical content, proofs, code, and computations are the sole work of the author(s).

---

## Contact

James M. Hyman
Department of Mathematics
Tulane University
6823 St. Charles Avenue
New Orleans, LA 70118
mhyman@tulane.edu

---

*This repository is the companion archive for the book *Learning with AI*. The book itself is under review with SIAM Books on Education. This README reflects the v2.10 canonical state as of 2026-05-25. The v2.9 round-2 reviewer release remains in reviewer hands; reviewer feedback will drive v2.11.*
