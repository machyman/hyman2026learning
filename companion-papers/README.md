# Companion Papers for *Learning with AI*

Two companion position papers develop intellectual foundations the book draws on. Both are at their canonical **v1.0 lock state** (2026-05-25) and are included in this directory with source, bibliography, compiled PDF, and a Delta document.

## AI and the Next Layer of Human Work

A position paper developing the historical-pattern argument the book introduces in the Foreword's "Why this is not the first time" subsection. Six historical analogies (photography, calculators, programming libraries, power tools, spellcheck, operational vs. mechanical knowledge) ground the central thesis: powerful tools change what skill means rather than eliminating skill. Three audience-specific sections (Students, Faculty, Administrators) parallel the book's three parts.

- **Bibkey:** `hyman2026next`
- **Status:** **v1.0 locked 2026-05-25** (post MREP v6.5 cycle)
- **Length:** 10 pages, ~3,732 words
- **Bibliography:** 23 entries (3 added in pre-ship 2025 empirical refresh: Gerlich, Kosmyna, Hyatt)
- **Files:**
  - `hyman2026next/hyman2026next_v1_0.tex`: locked LaTeX source
  - `hyman2026next/hyman2026next.bib`: canonical bibliography
  - `hyman2026next/hyman2026next.pdf`: compiled output
  - `hyman2026next/Delta_v2_to_v1_0.md`: v1.0 change summary (5 substantive changes documented)
- **Compile recipe:** `pdflatex → bibtex → pdflatex → pdflatex` (natbib backend; standard TeXLive distribution)

**Key v1.0 enhancements** (per the Delta document):
- Displacement honesty strengthened to match the book Foreword's framing
- Named Dell'Acqua jagged-frontier empirical anchor added inline
- Three 2025 empirical studies added for the cognitive-atrophy and AI-detector claims
- Asymmetry-of-displacement paragraph added (engages strongest critique of the historical-pattern thesis)

## Teaching AI Responsibly to Principled Skeptics

A position paper developing the principled-skepticism framework the book introduces in Part I. Five-layer literacy framework (technical, environmental, ethical, practical, civic). Engages the case for principled refusal on environmental, ethical, or political grounds. Citations include IEA energy data, OECD on hidden costs, Crawford's *Atlas of AI*, Hao's *Empire of AI*, Bender et al. on stochastic parrots, EU AI Act Article 4, CCCC 2026 resolution.

- **Bibkey:** `hyman2026teaching`
- **Status:** **v1.0 locked 2026-05-25** (post MREP cycle with full HR finding closure)
- **Length:** 18 pages
- **Bibliography:** 17 entries (unchanged from pre-lock draft)
- **Files:**
  - `hyman2026teaching/hyman2026teaching_v1_0.tex`: locked LaTeX source
  - `hyman2026teaching/hyman2026teaching.bib`: canonical bibliography
  - `hyman2026teaching/hyman2026teaching.pdf`: compiled output
  - `hyman2026teaching/Delta_v1_0.md`: v1.0 change summary (filename/header normalization only; no prose changes from prior draft)
- **Compile recipe:** `pdflatex → biber → pdflatex → pdflatex` (biblatex backend; requires `biber` and `biblatex.sty`, typically in `texlive-bibtex-extra` package on Debian/Ubuntu)

**Note on v1.0 lock for this paper:** Per the Delta document, the v1.0 lock for `hyman2026teaching` was a versioning ceremony (filename normalization, header version line update, `\addbibresource` pointer update) rather than a content cycle. The prose is byte-for-byte identical to the prior draft. HR findings (14 total) were closed during prior sessions; 100% of edit-addressable findings resolved before the v1.0 lock.

---

## Cross-references with the book

The book references both papers as `@unpublished` entries with `note` fields pointing to this repository. **Both v1.0 lock states are fully consistent with the book's existing cross-reference text.** Neither paper required changes to the book's cited claims, titles, or framing. Specifically:

- **`hyman2026next`** is cross-referenced at the book's Foreword §"Why this is not the first time" subsection closing. The v1.0 paper's Change 1 (displacement honesty strengthened) was specifically aligned to match the Foreword's framing.
- **`hyman2026teaching`** is cross-referenced at the book's Part I §sec:purpose principled-skepticism paragraph. The v1.0 paper's content unchanged from the draft the book was already calibrated against.

```bibtex
@unpublished{hyman2026next,
  author = {Hyman, James M.},
  title = {AI and the Next Layer of Human Work: A Position Paper for Students, Faculty, and Administrators},
  year = {2026},
  note = {v1.0 lock 2026-05-25. Available at https://github.com/machyman/hyman2026learning/tree/main/companion-papers/hyman2026next}
}

@unpublished{hyman2026teaching,
  author = {Hyman, James M.},
  title = {Teaching AI Responsibly to Principled Skeptics: A Framework for Students, Faculty, and Administrators},
  year = {2026},
  note = {v1.0 lock 2026-05-25. Available at https://github.com/machyman/hyman2026learning/tree/main/companion-papers/hyman2026teaching}
}
```

---

## Version history

- **v1.0** (2026-05-25): Canonical lock state for both papers. Companion `Delta_*.md` files in each directory document what changed from the pre-lock draft.
- **Pre-v1.0 drafts** (2026-05-24/25): Original drafts bundled in the v2.10 CGR archive (early build, since superseded by this v1.0-companions archive).

---

*Companion papers updated 2026-05-25 alongside the v2.10-with-v1.0-companions CGR rebuild. The papers are now at their canonical lock state. When papers are published in venues (arXiv, journal, or otherwise), the bib entries in the book will be updated to point to the venue rather than to this repository directory.*
