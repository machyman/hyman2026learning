# hyman2026teaching v1.0 — Delta from 2026-05-25 draft state

**Per MREP Context §7 deliverable spec.** This document summarizes what changed between the 2026-05-25 draft state (post-Session 9, semantically "v3") and the v1.0 canonical lock (Session 12). Detailed session-by-session history lives in `CHANGELOG.md`; this is the high-level brief Mac brings back to the book project.

---

## TL;DR

**No prose changes between v3 (2026-05-25 draft state) and v1.0.** Session 12 was a versioning ceremony, not a content cycle.

The two sessions between v3 and v1.0 lock — Session 11 (SPRE v4.1 calibration pass) and Session 12 (v1.0 lock) — produced calibration feedback for MREP v6.6 and renamed the canonical artifact files per the MREP Context §7 deliverable spec, respectively. Neither changed the substrate prose.

---

## What changed

### 1. Filenames (per MREP Context §7)

| Role | Pre-v1.0 (working naming) | v1.0 canonical (bibkey-based) |
|---|---|---|
| Main source | `Teaching_AI_Responsibly.tex` | `hyman2026teaching_v1_0.tex` |
| Bibliography | `Teaching_AI_Responsibly.bib` | `hyman2026teaching.bib` |
| Compiled output | `Teaching_AI_Responsibly.pdf` | `hyman2026teaching.pdf` |

The session-archive files remain in outputs for rollback; the v1.0 lock files are the canonical artifacts going forward.

### 2. Internal header

The italic version line in the manuscript header was updated:

| Before | After |
|---|---|
| `\noindent\textit{Position paper, v3 (full HR-finding closure).}` | `\noindent\textit{Position paper, v1.0.}` |

### 3. Bibresource pointer

Inside `hyman2026teaching_v1_0.tex`, the `\addbibresource{}` line was updated to point at the canonical bib filename:

| Before | After |
|---|---|
| `\addbibresource{Teaching_AI_Responsibly.bib}` | `\addbibresource{hyman2026teaching.bib}` |

### 4. Status YAML

`MANUSCRIPT_STATUS.yaml` `manuscript.current_version`: `v3` → `v1.0`. Other fields updated: `last_compiled`, `bib_file`, `last_updated`, `last_updated_by`, plus a new `v1_0_lock_state` block under `position_paper_context`.

### 5. Distribution package

A new COR package was built at v1.0 lock: `hyman2026teaching_COR_v1_0_2026-05-25.zip`. The prior v3 package (`hyman2026teaching_COR_2026-05-24.zip`) is retained as a superseded reference in the YAML's `superseded_packages` list.

---

## What did not change

- **Prose:** byte-for-byte identical between v3 and v1.0 (modulo the header version line). The `Teaching_AI_Responsibly_v3.md` markdown source is semantically equivalent to the v1.0 LaTeX.
- **Bibliography:** all 17 entries unchanged; same keys, same content.
- **Page count:** 18 (unchanged).
- **Compile state:** clean (0 errors, 0 warnings, 0 overfull hboxes, 0 undefined refs) — both v3 and v1.0.
- **Bibkey:** `hyman2026teaching` (locked since project inception per MREP Context §3.2).
- **Title:** "Teaching AI Responsibly to Principled Skeptics" (locked since Mac's 2026-05-25 confirmation per MREP Context §3.2).

---

## HR finding closure carried forward to v1.0

| Severity | Total | Resolved | Partial | Workflow-open |
|---|---:|---:|---:|---:|
| HIGH | 4 | 2 | 1 (R6-02 composite branch closed; documented-case branch declined by Mac 2026-05-25) | 1 (R4-01 distribution) |
| MEDIUM | 5 | 4 | 0 | 1 (R4-02 derivatives) |
| LOW | 5 | 5 | 0 | 0 |
| **Total** | **14** | **11** | **1** | **2** |

100% of edit-addressable findings closed. Open items are workflow decisions (Mac).

---

## Cross-reference change requests for the book

**None.** Sessions 7–12 surfaced no claim the book makes about this paper that should be revised. The book's existing references hold up:

| Book passage | Substrate state at v1.0 |
|---|---|
| "The case for engaging with AI critically rather than refusing it absolutely is developed in a companion paper" | ✅ Accurate (developed across all four Parts) |
| "approaches the question through a five-layer literacy framework (technical, environmental, ethical, practical, civic)" | ✅ Accurate (Part II.1) |
| "treats principled refusal as a defensible position rather than a problem to be talked around" | ✅ Accurate (Parts I.2, III.1) |

The book's v2.11 cycle does not need to absorb anything from this v1.0 lock.

---

## MREP v6.6 calibration substrate availability

Session 11's SPRE v4.1 calibration pass surfaced five findings (F-V6-6-P-01 through F-V6-6-P-05) attributable to paper-class threshold heritage. All five routed to MREP v6.6 backlog as paper.position subgenre calibration items. The full report is `SPRE_v4_1_Calibration_Feedback_PaperPosition.md`; the routing memo is `MREP_v6_6_Backlog_Routing_PaperPosition_Subgenre.md`.

The locked `hyman2026teaching_v1_0.tex` substrate (8,355 prose words) is available as the calibration substrate when v6.6 paper.position subgenre work executes.

---

## Open items at v1.0 lock (workflow, not content)

1. **R4-01: Distribution channel selection.** Tulane institutional repository / OSF / Zenodo / SSRN / arXiv / informal. The v1.0 lock package is channel-agnostic.
2. **R4-02: Derivative documents.** Student handout / faculty memo / administrator brief. Optional follow-on cycle.

---

*End of v1.0 delta document.*
*Companion to: `CHANGELOG.md` (session-by-session detail), `README.md` (status dashboard), `MANUSCRIPT_STATUS.yaml` (structured source of truth).*
