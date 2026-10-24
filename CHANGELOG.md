# Changelog

Notable changes to this companion repository. This is a reader-facing log; it
does not track the book manuscript.

## [2026-10-23, later]

### Added
- `docs/hyman2026avoiding_v2_108_2.pdf` (559 pages), the current pre-publication draft. It replaces the v2_104_1
  draft, which is removed. The application chapters (vector-borne disease, dengue, COVID-19, HIV and the PDE chapter)
  now write new infections per infectious source, as the rest of the book does; every sensitivity in the case
  studies is taken with respect to a mean duration; and every exercise and Further Reading task was checked against
  the chapter text. Several chapter epigraphs are reworded to be plainer.
- `docs/AUDIT_LEDGER_v2_108_2.md`, the claim audit ledger as of v2_108_2. It keeps every row of the v2_104_1 ledger,
  which is removed, and adds the corrections since.

### Changed
- Version stamp: tracks book v2_108_2 (previously v2_104_1), in `README.md`, `index.md`, `book/README.md`,
  `docs/README.md` and `REPRODUCIBILITY.md`. The figures and their generators are unchanged; the 20 generators were
  re-run from this repository and reproduce the book's 32 figures byte for byte.

## [2026-10-23]

### Added
- `docs/hyman2026avoiding_v2_104_1.pdf` (559 pages), the current pre-publication draft. It replaces the v2_96_11 draft, which is removed.
  Every chapter now ends with a Further Reading section that guides readers to the works best suited to going
  further.
- `docs/AUDIT_LEDGER_v2_104_1.md`, the claim audit ledger as of v2_104_1. It adds the corrections made since v2_96_11,
  among them a check of every citation in the book against what the cited work says. It keeps every row of the
  v2_96_11 ledger, which is removed.
- In the draft, the HIV chapter gains an account of the first models of the epidemic, among them the
  back-calculation of HIV infections from AIDS cases, set beside the estimates of the time. A new pitfall, "Fitting
  versus Explaining the Data", and a section on model discrepancy in the chapter on fitting in practice show that a
  close fit, and narrow bands from a sensitivity analysis of the fitted model, do not by themselves justify a forecast.

### Changed
- Version stamp: tracks book v2_104_1 (previously v2_96_11), in `README.md`, `index.md`, `book/README.md`,
  `docs/README.md` and `REPRODUCIBILITY.md`. No code changed: run from this layout, the 20 scripts still reproduce the
  book's 32 figures byte for byte.

## [2026-10-18]

### Added
- `docs/`: the book's pre-publication draft, `docs/hyman2026avoiding_v2_96_11.pdf` (535 pages), posted for
  comment with Springer's permission, and `docs/AUDIT_LEDGER_v2_96_11.md`, the claim audit ledger: each correction
  to a printed claim, the check behind it, and the draft version in which it landed. Every file in `docs/` carries
  the draft version in its name, so feedback can name the version it read. A README describes them.
- The five generators that were not here: `notebooks/ch04/ch4_alpha_vs_lambda.py`,
  `notebooks/ch08/ch8_weighting.py`, `notebooks/ch11/ch11_same_R0.py`, `notebooks/ch12/ch12_herd_boundary.py`
  and `notebooks/ch16/ch16_generation_interval.py`, with READMEs for the three new directories. The repository
  now carries all 20 of the book's figure generators.

### Changed
- The book's new title, *Foundations and Pitfalls in Epidemic Modeling: An Introduction to Formulating,
  Analyzing, and Fitting Models*, in `README.md`, `index.md`, `book/README.md`, `CITATION.cff` and the site
  configuration. The repository name and citation key stay `hyman2026avoiding`.
- Version stamp: tracks book v2_96_11 (previously v2_87_1).
- Three generators come to the book's current versions: `notebooks/ch09/ch9_figures.py` (v2.6: the profile
  likelihood figure is computed from profile fits), `notebooks/ch10/ch10_figures.py` (v1.4: endemic prevalence
  uses the general-contact closed form; schematic labels) and `code/python/ch10_sensitivity/ch10_sobol_panel.py`
  (the same general-contact form).
- `REPRODUCIBILITY.md`: all 20 generators and 32 figures, the Python versions that reproduce the figures byte
  for byte, and where the three new scripts write. Checked before this update: run from this layout, the 20
  scripts reproduce the book's 32 figures byte for byte.
- `notebooks/README.md` and the per-chapter READMEs for `ch08/` and `ch11/` list every script, as links;
  `notebooks/ch17/README.md` names the model SEIAR; `index.md` names the model SIR.

## [2026-10-15]

### Added
- `notebooks/ch17/` — the Chapter 17 (COVID-19 case study) script, `ch17_figures.py`, which the book
  cites by path, with its README.

### Changed
- Version stamp: tracks book v2_87_1 (previously v2_78_0). From v2_86_0 the book's chapters are
  renumbered; directory names keep the numbers the book prints, and each README names its chapter.
- The book's notation, from v2_87_0 (v2_87_1 sets the remaining model names upright): fractions of the carrying capacity are lowercase (s, i, r, n, j),
  counts are uppercase (S, I, R, N, J), model names are upright (SIR), and the sensitivity indices print
  as Υ (local) and 𝒮 (Sobol). Twelve scripts carry the new figure labels; only label strings changed,
  so every plotted value is as before: `notebooks/ch06/` (three scripts), `notebooks/ch07/ch7_figures.py`,
  `notebooks/ch08/` (two scripts), `notebooks/ch09/ch9_figures.py`, `notebooks/ch10/ch10_figures.py`,
  `notebooks/ch11/ch11_multistage_ic.py`, `notebooks/ch17/ch17_figures.py` and two scripts in
  `code/python/ch10_sensitivity/`.
- Four of those scripts also come to the book's current versions: `ch7_figures.py` (no axis limit
  clipping the peak), `ch8_preprocessing.py` (v1.2), `ch9_figures.py` (v2.5) and `ch10_figures.py`
  (v1.2, the PRCC sample on [p/2, 2p]).
- The capstone index and all nine capstone READMEs: chapter and section references follow the new
  numbering, and the model is named SIR.
- Quick start in `README.md` and `index.md`: run scripts with `PYTHONPATH=src` so they find the shared
  model. `REPRODUCIBILITY.md` gains a section on this repository's layout and the v2_86_0 counts.
- Chapter numbers in `notebooks/README.md`, the per-chapter READMEs,
  `code/python/ch10_sensitivity/README.md` and `data/README.md`.

## [2026-08-26]

### Changed
- Version stamp: tracks book v2_78_0 (previously v2_62_1).
- Eight capstone project READMEs (ch04, ch06, ch07, ch08, ch10, ch12, ch14,
  ch17) updated to the conformed template used by the book's front-matter
  project table; ch03 was already conforming.
- `notebooks/ch03/ch3_exp_vs_linear_beta.py`: annotation and legend fonts
  raised 8/9pt to 10pt to match the chapter's other figures (book Fig. 2.2 at
  v2_78_0). Regenerated output is registered in the book's figure registry.

## [2026-08-15]

### Added
- `capstone-projects/` — the book's nine chapter capstone projects, one
  directory per project with the six-step workflow specification skeleton;
  detailed materials follow as they are finalized.
- `code/python/ch10_sensitivity/` — the Chapter 10 sensitivity module
  (`ch10_index_divergence.py`, `ch10_sobol_panel.py`).
- `notebooks/README.md` (per-chapter code index) and `notebooks/ch03/` (the
  Chapter 3 transmission-comparison script, moved from `notebooks/ch02/`).
- `.gitattributes` (release-archive hygiene).

### Changed
- All per-chapter scripts and `src/sir_i_model.py` refreshed to the book's
  current baseline (contact-rate parameterization c_S=20, c_I=4, beta=0.040);
  the previous copies predated it and reproduced superseded numbers.
- Chapter directories now follow the book's current chapter numbering
  (`notebooks/ch02/` → `notebooks/ch03/`; a pointer README remains at `ch02/`).
- Entry pages: capstone and module links, reproducibility-conventions link,
  repository-history link, and an absolute issues link.

## [Unreleased]

### Added
- Initial repository: per-chapter figure-reproduction scripts
  (`notebooks/ch06`–`ch11`), the shared `src/sir_i_model.py` model, and the
  companion site.
- Data provenance and pointers (`data/`), including the WSU 2009 H1N1 dataset via
  the MIDAS Network catalog.
- Citation metadata (`CITATION.cff`) and issue templates for corrections,
  questions, and suggestions.

### Pending
- Narrated teaching notebooks and the guided lab set (`labs/`).
- ISBN and a Zenodo DOI for this repository.
- Link to the published book (pending permission from Springer).
