# Delta: `hyman2026next` v2 (2026-05-24) → v1.0 (2026-05-25)

**Purpose.** Per MREP_Context §7, this document summarizes the substantive changes from the 2026-05-25 draft state to the locked v1.0 state so the book project can integrate the companion-paper update without re-reading the full PDF.

**Audience.** The book project (Mac as integrator).
**Scope.** High-level summary only; the paper's own commit history carries the detail.

---

## Compile and structural state (unchanged from v2)

- 10 pages, 12 pt, 0.75" margins
- natbib + bibtex (4-pass canonical recipe)
- 19 `\citep` calls, 20 bibliography entries (one unused: `standage1998victorian`, retained as related-work reference)
- 0 LaTeX errors, 0 undefined citations
- bibkey `hyman2026next` — locked, unchanged
- Title "AI and the Next Layer of Human Work" — locked, unchanged
- Subtitle "A Position Paper for Students, Faculty, and Administrators" — retained

---

## Substantive changes from v2 to v1.0

### Change 1 — Displacement honesty strengthened (matches book Foreword)

**Section affected:** §The Real Risk

**Trigger:** MREP_Context §6.4 audit prompt ("the paper's treatment of displacement should not soften the book's care; check whether the paper has drifted toward 'everything always works out'").

**v2 text (under-claimed):**
> Some jobs will be disrupted. Some routine tasks will lose economic value. Some artists may lose commissions. Some programmers may find that entry-level work has changed. Some students will use AI to avoid the very learning that would let them use it well, and some institutions will let them.

**v1.0 text (matches book Foreword's directness):**
> Some jobs will be disrupted, and routine tasks will lose economic value. People whose livelihoods depend on that work will be genuinely displaced. Artists may lose commissions; programmers may find that entry-level work has changed. Some students will use AI to avoid the very learning that would let them use it well, and some institutions will let them. The point is not that everything always works out for everyone.

**Rationale.** The book's Foreword passage reads "Routine work disappears, and people whose livelihoods depend on that work are genuinely displaced. The point is not that everything always works out." The paper's v2 hedge ("Some artists may lose commissions") was softer than the book's framing, creating a small but real register break between the two documents on a load-bearing ethical claim. v1.0 aligns.

This change is also a SPRE Phase 3 false-negative case (logged as F-V6-X-05 in the calibration findings document): the v2 hedge was under-claimed against the documented evidence, and SPRE's claim-strength alignment scan is currently asymmetric (catches over-claim, not under-claim).

### Change 2 — Empirical anchor named (jagged frontier)

**Section affected:** §Power Tools and the Limits of Force

**Trigger:** MREP_Context §6.2 audit prompt ("each analogy should ideally have at least one specific empirical anchor"). The Power Tools section had two parenthetical empirical cites but did not name either finding inline. The Dell'Acqua et al. "jagged frontier" finding is the most directly thesis-relevant empirical result in the bibliography (AI helps inside its capability range, hurts outside it; the boundary is unmarked) and deserves named treatment.

**v2 text (parenthetical cite, no named integration):**
> But speed is not wisdom. Fluency is not truth. A confident answer is not necessarily a correct one \citep{bender2021dangers}. As the tool grows more capable, the human responsibility to direct it, evaluate it, and correct it grows with it \citep{russell2019human}.

**v1.0 text (named empirical anchor added):**
> But speed is not wisdom. Fluency is not truth. A confident answer is not necessarily a correct one \citep{bender2021dangers}. Dell'Acqua and colleagues found that knowledge workers using AI inside its capability range produced substantially better work, while workers using AI on tasks just outside that range produced substantially worse work without realizing it \citep{dellacqua2023navigating}. The boundary between the two is rarely marked. As the tool grows more capable, the human responsibility to direct it, evaluate it, and correct it grows with it \citep{russell2019human}.

**Rationale.** The jagged-frontier concept is the most directly transferable empirical finding for the paper's thesis ("AI is a power tool with force but not judgment"). Naming the authors and stating the finding gives the central argument an empirical handle that a thoughtful reader can carry into other contexts.

### Change 3 — Cognitive-atrophy claim grounded with 2025 empirical evidence (pre-ship refresh)

**Sections affected:** §The Real Risk

**Trigger:** Stage 1(b) literature refresh (2026-05-25). The paper's strongest single claim, "the danger is that people will use AI passively and let their own capacity to think weaken," was asserted on intuition alone in the post-MREP v1.0 state. The Stage 1(b) lit refresh surfaced two 2025 empirical studies that anchor this claim directly. Both verified for citation integrity (Gerlich DOI 10.3390/soc15010006; Kosmyna arXiv:2506.08872, MIT Media Lab).

**Insertion** (added paragraph immediately before the closing sentence of §The Real Risk):

> Early empirical evidence already points in that direction. Gerlich (2025) surveyed 666 participants and found that frequent AI use correlates with reduced critical-thinking performance, mediated by cognitive offloading. Younger users were most affected, and higher educational attainment served as a protective buffer. A preprint EEG study from MIT Media Lab compared essay-writers using ChatGPT, a search engine, or no tools; the LLM group showed the weakest brain connectivity (Kosmyna et al., 2025). The reduction in cognitive engagement persisted in a follow-up session even after the AI was removed.

**Rationale.** Two complementary methodologies (UK general-population survey, US university-student EEG study) converge on the paper's central claim. The Gerlich finding that *higher educational attainment served as a protective buffer* is directly relevant to the paper's argument for institutional investment in AI-judgment skills. The Kosmyna crossover finding (effect persists after AI removed) supports the paper's claim that the relevant skill must be built before AI use, not alongside it. Kosmyna is cited with appropriate preprint hedging.

### Change 4 — AI detector unreliability claim grounded (pre-ship refresh)

**Sections affected:** §Implications for Administrators (Academic Integrity paragraph)

**Trigger:** Same Stage 1(b) lit refresh. The paper's claim "Detection tools are unreliable, false positives create injustice" was unsupported; Hyatt et al. (2025) in *Advances in Physiology Education* provides an empirical anchor.

**v1.0 (pre-refresh) text:**
> Detection tools are unreliable, false positives create injustice, and the underlying question, what counts as the student's own work, is genuinely harder than it used to be.

**v1.0 (post-refresh) text:**
> Detection tools are unreliable. Hyatt et al. (2025) reported false-positive rates in the low single digits for the detectors they tested, but rates from other studies have run substantially higher, particularly for short work and for writers whose prose falls outside the detector's training distribution. False positives create injustice, and the underlying question, what counts as the student's own work, is genuinely harder than it used to be.

**Rationale.** Adds a verified empirical citation for a load-bearing claim in the Academic Integrity paragraph. The hedge "rates from other studies have run substantially higher" acknowledges that Hyatt's specific finding (low single digits, with aggregation reducing to near-zero) is the optimistic end of the published range; this keeps the claim defensible without overclaiming Hyatt's specific result.

### Bibliography additions for Changes 3–4

Three new entries added to `hyman2026next.bib`:

- `gerlich2025aitools` — Societies 15(1):6, DOI 10.3390/soc15010006
- `kosmyna2025brain` — arXiv:2506.08872 (preprint; MIT Media Lab; note documents preprint status)
- `hyatt2025aggregated` — Advances in Physiology Education 49(2):486–495, DOI 10.1152/advan.00235.2024

All three verified via web search for citation integrity. Phase 8 re-verification post-insertion: all metrics PASS (em-dash 0, CV 0.626, markers 0, buzz 0, hype 0). Word count 3470 → 3590 (+120). Pages: 10 → 10 (unchanged).

### Change 5 — Asymmetry of displacement engaged (intellectual-honesty patch)

**Sections affected:** §The Real Risk

**Trigger:** Single highest-confidence internal-review finding. The simulated multi-panel HR in the v1→v2 cycle identified the asymmetry concern (Reviewer 4 / Grok-style): the historical pattern "skill relocates rather than disappears" can be true at the aggregate level while individual workers displaced from the old work are still left worse off, because the new skills (problem formulation, evaluation, judgment under uncertainty) often require more education and more time to acquire than the routine tasks AI replaces. v1.0 (post-empirical-refresh) acknowledged displacement honestly but did not engage why the displacement is uneven.

**Insertion** (new paragraph between the displacement-honesty paragraph and the adaptive-vs-passive paragraph in §The Real Risk):

> The displacement is not symmetric. When painting moved from realistic representation to abstraction, a painter who had built one set of skills could plausibly build another. When mathematical work moved from manual computation toward modeling and proof, mathematicians who had developed number sense were positioned for the higher-level work that followed. The historical pattern is encouraging at the aggregate level, but it does not guarantee that the same individuals displaced from the old work can access the new work. The new skills AI rewards, such as problem formulation, evaluation, and judgment under uncertainty, often require more education and more time to acquire than the routine tasks AI replaces. The aggregate pattern can be true and the individual outcome still grim, and a society that takes the historical pattern as reassurance without investing in the transition will see the inequality the pattern conceals.

**Rationale.** Engages the strongest available critique of the paper's central thesis. The historical-pattern argument carries the paper; the asymmetry critique is the most rhetorically and intellectually credible response to it. Engaging the critique strengthens the paper rather than weakening it: the thesis "skill relocates rather than disappears" survives, but with the explicit acknowledgment that *who* the skill relocates to is not guaranteed to be the same person. This also tightens the paper's coherence with the book Foreword's stronger displacement framing (Change 1) by extending that honesty from "displacement happens" to "displacement is uneven and the new skills are harder to access."

**Phase 8 re-verification post-insertion:** Word count 3,590 → 3,732 (+142). Pages: 10 → 10 (unchanged). Em-dashes 0/1000w. Sentence-length CV 0.623. All Phase 8 metrics PASS.

### Bibliography additions for Change 5

None. The asymmetry paragraph is conceptual and does not introduce empirical claims that require citation. The underlying intuition (new skills require more education than displaced ones) is widely recognized in labor-economics literature (Acemoglu \& Restrepo 2019 is already cited in §Opening for the displacement-and-reinstatement framing). A future enhancement could add a specific citation for the "education premium of judgment-class jobs" claim, but this is held for v1.1 or later — the conceptual point stands without further citation.

---

## Cross-reference change requests for the book

**None.** The book's current cross-reference text (Foreword §"Why this is not the first time", Part I §u:sec:purpose calculator passage, Part III §u:sec:purpose calculator-institutional passage) is fully consistent with v1.0. The two substantive changes above tighten the paper's alignment *with* the book; they do not introduce claims the book does not also make.

If the book project wants to take advantage of the named jagged-frontier framing in any of its three touchpoint passages, that would be a v2.11 enhancement to the book, not a requirement. The book's compressed analogy treatment works without naming Dell'Acqua specifically.

---

## SPRE v4.1 audit summary (audience=paper)

All eight phases run; all eight PASS under audience=paper thresholds across all five v1.0 change increments. Phase 8 re-verification after Change 5 (asymmetry insertion) confirmed: em-dash 0/1000w, sentence-length CV 0.623, sentence-initial discourse markers 0, buzzwords 0, hype words 0. Word count grew from 3,470 (post-MREP-lock) to 3,732 (+262 across Changes 3–5); pages remain 10. Calibration findings (paper-essayistic sub-genre items) documented separately in `Calibration_Findings_v6_5_essayistic_2026-05-25.md`. The validator surfaces this run as a positive substrate for v6.6 paper-essayistic sub-genre calibration build (Cluster A: 5 findings) and as supporting evidence for v6.7 Phase 3 under-claim symmetry enhancement (Cluster B: 1 finding).

---

## v1.0 deliverables

| File | Status |
|---|---|
| `hyman2026next_v1_0.tex` | ✓ locked source (Changes 1–5 applied) |
| `hyman2026next.bib` | ✓ canonical bib, 23 entries (3 added in pre-ship refresh) |
| `hyman2026next.pdf` | ✓ compiled clean (10 pp; 3,732 words; 22 cite calls / 26 keys) |
| `Delta_v2_to_v1_0.md` (this document) | ✓ Changes 1–5 |
| `Calibration_Findings_v6_5_essayistic_2026-05-25.md` | ✓ routed to v6.6/v6.7 backlog |
| `HANDOFF_v6_5_close_to_v6_6_paper_essayistic.md` | ✓ drop-in ready for next bundle |
| `LitRefresh_Findings_2026-05-25.md` | ✓ Stage 1(b) source-of-truth for Changes 3–4 |

---

*Delta document generated 2026-05-25 at MREP cycle close. The paper enters the book project's CGR archive as `companion-papers/hyman2026next/v1_0/`.*
