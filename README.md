# Foundations and Pitfalls in Epidemic Modeling — Companion Repository

Companion code and materials for the book *Foundations and Pitfalls in Epidemic
Modeling: An Introduction to Formulating, Analyzing, and Fitting Models*, by
**James M. Hyman**, **Zhuolin Qu**, and **Ling Xue** (Springer,
Interdisciplinary Applied Mathematics series — under review).

**Rendered companion site:** <https://machyman.github.io/hyman2026avoiding>

**Tracks book v2_108_2.** This line records the manuscript version this repository
was last synchronised against, so drift between the book and the code is visible
rather than silent. If it is many versions behind the current draft, the code here
may not match the book's printed numbers.

> **The book is under review with Springer.** With Springer's permission, the
> current pre-publication draft, v2_108_2, is posted here for comment in [`docs/`](docs/),
> together with the [claim audit ledger](docs/AUDIT_LEDGER_v2_108_2.md). The published book
> will be available from Springer. See [`book/`](book/).

## What's here

This repository collects the reproducible code behind the book's figures and
numerical results, organized to match the book's Appendix B:

| Path | Contents |
|---|---|
| [`notebooks/`](notebooks/) | Per-chapter scripts that reproduce each chapter's figures and computations (`ch03/`, `ch04/`, `ch06/`–`ch12/`, `ch16/`, `ch17/`) |
| [`src/`](src/) | Shared Python modules — the `sir_i_model.py` integrator used across chapters |
| [`code/`](code/python/ch10_sensitivity/) | Standalone modules the book cites by path — currently the Chapter 9 sensitivity module |
| [`capstone-projects/`](capstone-projects/) | The book's chapter capstone projects, one directory per project |
| [`data/`](data/) | Provenance and pointers for the empirical case-study datasets |
| [`labs/`](labs/) | Guided lab notebooks *(in preparation)* |
| [`docs/`](docs/) | The pre-publication draft of the book (PDF) and the claim audit ledger |
| [`book/`](book/) | Book availability and citation *(under review)* |

Fuller narrated teaching notebooks and the lab set are being finalized alongside
the book.

## Quick start

```bash
git clone https://github.com/machyman/hyman2026avoiding
cd hyman2026avoiding
pip install -r requirements.txt
mkdir -p figs
PYTHONPATH=src python notebooks/ch07/ch7_figures.py     # writes figures to figs/
```

Run scripts from the repository root with `PYTHONPATH=src`, which lets them import
the shared model. Anything involving randomness is seeded,
so results are reproducible; the conventions are documented in
[`REPRODUCIBILITY.md`](REPRODUCIBILITY.md).

## Who it's for

Graduate students and researchers learning to formulate, analyze, and fit
compartmental epidemic models — and instructors teaching from the book. The code
is meant to be read alongside the corresponding chapter.

## Citing

Please cite the book:

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

Machine-readable citation metadata is in [`CITATION.cff`](CITATION.cff). The
ISBN and a Zenodo DOI for this repository are pending and will be added here.

## Feedback and corrections

Found an error, or have a question or suggestion? Please
[open an issue](https://github.com/machyman/hyman2026avoiding/issues/new/choose) — the templates will guide you:

- **Correction** — report an error in the book or the code
- **Question** — ask about the material
- **Suggestion** — propose an improvement

## Repository history

Reader-facing changes to this repository are logged in
[`CHANGELOG.md`](CHANGELOG.md).

## License

Code in this repository is released under the [MIT License](LICENSE). The book
text and figures are © the authors and Springer and are not included here.
