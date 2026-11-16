# Changelog

Notable changes to the companion repository for *Learning with AI*. Most recent first.

**Two version lines.** Repository releases are numbered `vX.Y.Z`. The book has its own version line, and each
entry says which book version the repository carries. Tagged releases are archived on Zenodo; the concept DOI
[10.5281/zenodo.21315920](https://doi.org/10.5281/zenodo.21315920) resolves to the latest one.

## Unreleased

- The README opens with a link to the website, [machyman.github.io/hyman2026learning](https://machyman.github.io/hyman2026learning).
- The website has a sidebar and a search box. It now uses the Just the Docs theme (v0.12.0, pinned). Every page keeps its address, so every link printed in the book still works. The sidebar is set in `_config.yml`; no page changed for it.
- A monthly link check (`.github/workflows/links.yml`) opens an issue if a link in the repository breaks.
- The Study Partner Protocol page's title, shown in browser tabs and now in the sidebar, read "Student practice problems". It now matches the book.
- The book page no longer says the README records what changed in each version; that history now lives in the commit log.
- Readers who want to teach a course with the book are now pointed to [teaching-the-book/](teaching-the-book/) from the README's "Find your path" list, from its overview of the book, and from the book page.

## v2.0.0 — 2026-11-12 — the starting point for readers of the SIAM edition

This release is the baseline for readers of the published book. It carries the book's final preprint (v6.1.1),
the author's pre-edit draft, and the companion materials for students, instructors, and institutions, including
[exercises for every chapter](teaching-the-book/exercises/) with sample strong and weak answers.

- The changelog starts here. The repository's development history before this release, v1.0.0 to v1.28.0 (July
  to November 2026), is in the commit history and the tagged releases.
- The README's version history is now a short pointer to this file.
- `CITATION.cff` gains the version and release date, and its abstract names the chapter exercises.

The book stays at v6.1.1.
