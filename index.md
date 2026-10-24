---
title: Home
layout: default
nav_order: 1
description: Companion site for the book "Foundations and Pitfalls in Epidemic Modeling."
---

# Foundations and Pitfalls in Epidemic Modeling

*An Introduction to Formulating, Analyzing, and Fitting Models*
James M. Hyman · Zhuolin Qu · Ling Xue — Springer (Interdisciplinary Applied
Mathematics), under review.

This is the companion site for the book. It hosts the reproducible code behind
the book's figures and numerical results, together with datasets and guided labs
as they are finalized.

> **The book is under review with Springer.** With Springer's permission, the
> [current pre-publication draft (v2_108_2)](https://github.com/machyman/hyman2026avoiding/blob/main/docs/hyman2026avoiding_v2_108_2.pdf)
> is posted for comment, with the
> [claim audit ledger as of v2_108_2](https://github.com/machyman/hyman2026avoiding/blob/main/docs/AUDIT_LEDGER_v2_108_2.md).
> The published book will be available from Springer.

## What the book is about

Even simple epidemic models can mislead when basic considerations are
overlooked. The book works through a catalogue of such pitfalls — in
formulating, analyzing, and fitting compartmental models, using the SIR model
as a running example — and shows how to avoid them. A recurring theme is that
quantities like the basic reproductive number should be *derived* from a model's
structure rather than assumed; for the SIR model,

$$\mathcal{R}_0 = \frac{c_I\,\beta}{\gamma_R + \nu_m},$$

and the "infected-viewpoint" estimator $\hat\alpha = J/I$ that the book develops
is structurally immune to uncertainty in the susceptible population size.

## Who it's for

Graduate students and researchers learning compartmental modeling, and
instructors teaching from the book.

## Navigating the materials

- **[Code](https://github.com/machyman/hyman2026avoiding/tree/main/notebooks)** —
  per-chapter scripts (`ch03`, `ch04`, `ch06`–`ch12`, `ch16`, `ch17`) that reproduce the figures, built on a
  [shared model](https://github.com/machyman/hyman2026avoiding/tree/main/src).
- **[Data](https://github.com/machyman/hyman2026avoiding/tree/main/data)** —
  provenance and pointers for the case-study datasets (e.g., the WSU 2009 H1N1
  data via the MIDAS catalog).
- **[Capstones](https://github.com/machyman/hyman2026avoiding/tree/main/capstone-projects)** —
  the book's chapter capstone projects, one directory per project.
- **[Draft and audit ledger](https://github.com/machyman/hyman2026avoiding/tree/main/docs)** —
  the pre-publication draft (PDF) and the record of corrections to printed claims.
- **Labs** — guided, multi-step notebooks *(in preparation)*.
- **Errata & questions** — please
  [open an issue](https://github.com/machyman/hyman2026avoiding/issues/new/choose).
- **[Repository changelog](https://github.com/machyman/hyman2026avoiding/blob/main/CHANGELOG.md)** —
  reader-facing changes to the companion materials.

## Running the code

```
pip install -r requirements.txt
mkdir -p figs
PYTHONPATH=src python notebooks/ch07/ch7_figures.py
```

Run from the repository root with `PYTHONPATH=src`; figures are written to `figs/`. Anything involving
randomness is seeded for reproducibility.

## Citing

```bibtex
@book{hyman2026avoiding,
  title     = {Foundations and Pitfalls in Epidemic Modeling: An Introduction to
               Formulating, Analyzing, and Fitting Models},
  author    = {Hyman, James M. and Qu, Zhuolin and Xue, Ling},
  year      = {2026},
  publisher = {Springer},
  series    = {Interdisciplinary Applied Mathematics},
  note      = {Under review}
}
```

See also
[`CITATION.cff`](https://github.com/machyman/hyman2026avoiding/blob/main/CITATION.cff).
The ISBN and a Zenodo DOI for this repository are pending.
