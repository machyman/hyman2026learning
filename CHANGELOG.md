# CHANGELOG — *Learning with AI* Bound Volume

All notable changes to this manuscript are recorded here, most recent first.

---

## v2.10 — 2026-05-25 (Session 18: Part II citation-grounding integration)

**Trigger.** Round-2 reviewer transmission (v2.9) is in flight; reviewer feedback is not yet available. Session 18 used the wait to address a structural gap in Part II: a citation-grounding asymmetry where Part II's pedagogical framework claims rested overwhelmingly on AI-era empirical studies (2023–2026) while the established teaching-effectiveness and learning-science literature on which the framework actually rests was largely uncited. A reviewer from education research would be likely to notice this asymmetry, and closing it strengthens the framework's foundations without changing its scope or character.

**Scope.** Seven inline integrations across Part II (lines 1925–3145) adding canonical learning-science citations to load-bearing pedagogical claims. Bibliography grew 58 → 67 entries (9 new Tier 1 + Tier 2 references from a structured gap analysis). Word count grew 62,619 → 62,855 (+236 words). Page count grew 194 → 196 (+2 pages). All edits are confined to Part II; Parts I and III, the Foreword, and the Appendices are unchanged from v2.9.

**Methodology.** Session 18 followed a multi-step protocol:

1. **Gap analysis** (`Part_II_Citation_Gap_Analysis_2026-05-25.md`): structural audit of Part II's 25 citation events and identification of 8 load-bearing pedagogical claims floating without canonical grounding.
2. **Tiered reference recommendation** (`Part_II_Proposed_References_2026-05-25.bib`): 9 references in Tier 1 (foundational anchors) + Tier 2 (strong specific) prioritized for upload; 2 in Tier 3 (Chi 1989 self-explanation, Felder & Brent 2024 STEM teaching) flagged as discretionary.
3. **Reference upload and verification by Mac**: Mac located the 9 references, converted to Markdown sources, uploaded them with a verified `.bib` file. VES on metadata (DOI, ISBN, author, venue, pages) confirmed all 9 entries publication-ready. VEE on 8 of 9 (source-anchored claim verification) all passed; the 9th (Black & Wiliam 1998) had bib metadata verified but no source file uploaded — accepted on the basis that the proposed integration cites it only for general formative-assessment grounding, not for any source-specific claim that would require VEE.
4. **Integration plan** (`Part_II_Integration_Plan_2026-05-25.md`): drafted contextual additions for each gap with exact line numbers and citation placements, presented for Mac's review before any edits.
5. **Critical-review pass before lock**: surfaced two real issues (described under Quality Pass below) that were fixed in the locked version.
6. **5-pass settle and Mac approval**: clean compile verified, candidate presented, Mac approved.

**The 7 integrations (in line order within Part II):**

**Integration 1 — L2281, AI-tutoring-practices paragraph (+75 words).** After the existing seven-practices list cited to Kestin 2025, added three sentences mapping the practices onto the established learning-science literature. New sentences cite `ambrose2010how` and `nationalacademies2018how` for the general claim that the practices are long established; `freeman2014active` for active engagement specifically, using Freeman et al.'s source-anchored framing (raised exam performance by 0.47 standard deviations; students under traditional lecturing 1.5 times more likely to fail than those under active learning); and `sweller2011cognitive` for the cognitive-load principle.

**Integration 2 — L2285, Plan-Use-Verify structure introduction (+25 words).** Added one sentence after the Plan-Use-Verify pattern is introduced: "The structure operationalizes the principle, well established in the learning sciences, that learners benefit from explicit self-monitoring before and after task engagement \citep{nationalacademies2018how}." Grounds the framework's central pedagogical contribution in metacognitive-monitoring literature (HPL II Conclusion 4-1).

**Integration 3 — L2378, polished-output-vs-demonstrated-learning figure (+30 words).** Added one sentence to the figure's introductory paragraph: "This is the practical face of the long-established \emph{learning versus performance} distinction in cognitive psychology \citep{soderstrom2015learning,bjork2011making}: conditions that improve immediate performance can fail to produce durable learning, and the converse." Activates `bjork2011making` which was already in the bib but uncited.

**Integration 4 — L2362, assessment-validity features list (+45 words).** Added one framing sentence between the introduction and the list: "The pattern these features share is the one articulated by the backward-design approach to assessment \citep{wiggins2005understanding}: working from the learning outcome to the evidence that would demonstrate it, then to the assignment that produces such evidence, rather than from familiar assignment forms outward." Grounds the validity-features list in the canonical UbD framework.

**Integration 5 — L2669, Feedback and grading section opening (+85 words).** Added a short grounding paragraph after the section opening: feedback design as one of the most-studied levers in the learning-science literature, building on Black & Wiliam's foundational case for formative assessment, with effective feedback addressing three questions (where am I going / how am I going / where to next) and working best when directed at task and process rather than at the person (Hattie & Timperley). Attribution was deliberately split between the two citations: `black1998assessment` is cited only for the general foundational role of formative-assessment work, and `hattie2007power` is cited for the specific three-questions framework (which is Hattie & Timperley's contribution, not Black & Wiliam's).

**Integration 6 — L2691, "desirable difficulty" attribution (0 words added).** Inline citation insertion of `bjork2011making` after the phrase "desirable difficulty," properly attributing Bjork's term of art. Second activation of an existing bib entry.

**Integration 7 — L2283, peer-interaction concern (+20 words).** Extended the existing sentence on AI eroding peer interaction with a closing clause naming peer instruction as the documented value being lost: "...the study groups, peer tutoring, and informal collaborative practices through which much undergraduate learning has historically happened, including the peer-instruction methods documented to improve conceptual understanding in undergraduate STEM \citep{mazur1997peer}."

**Bibliography additions (9 entries, all VER:VERIFIED 2026-05-25 by Mac):**

- `ambrose2010how` — Ambrose, Bridges, DiPietro, Lovett & Norman (2010), *How Learning Works: Seven Research-Based Principles for Smart Teaching*, Jossey-Bass. ISBN 9780470484104.
- `freeman2014active` — Freeman et al. (2014), "Active learning increases student performance in science, engineering, and mathematics," *PNAS* 111(23):8410–8415. DOI 10.1073/pnas.1319030111.
- `nationalacademies2018how` — National Academies of Sciences, Engineering, and Medicine (2018), *How People Learn II: Learners, Contexts, and Cultures*, National Academies Press. DOI 10.17226/24783, ISBN 9780309459648.
- `wiggins2005understanding` — Wiggins & McTighe (2005), *Understanding by Design* (2nd ed.), ASCD. ISBN 9781416600350.
- `soderstrom2015learning` — Soderstrom & Bjork (2015), "Learning versus performance: An integrative review," *Perspectives on Psychological Science* 10(2):176–199. DOI 10.1177/1745691615569000.
- `hattie2007power` — Hattie & Timperley (2007), "The power of feedback," *Review of Educational Research* 77(1):81–112. DOI 10.3102/003465430298487.
- `black1998assessment` — Black & Wiliam (1998), "Assessment and classroom learning," *Assessment in Education: Principles, Policy & Practice* 5(1):7–74. DOI 10.1080/0969595980050102.
- `mazur1997peer` — Mazur (1997), *Peer Instruction: A User's Manual*, Prentice Hall. ISBN 9780135654415.
- `sweller2011cognitive` — Sweller, Ayres & Kalyuga (2011), *Cognitive Load Theory*, Springer. DOI 10.1007/978-1-4419-8126-4, ISBN 9781441981257.

**Quality pass — two corrections surfaced by critical review before lock:**

1. *Freeman framing*: an initial draft of Integration 1 said active learning "reduced failure rates by roughly half" — a loose paraphrase that overstated Freeman's actual numbers (21.8% failure under active learning vs. 33.8% under traditional lecturing, which is about a 35% reduction, not "roughly half"). Corrected to use Freeman et al.'s own framing: "students under traditional lecturing 1.5 times more likely to fail than those under active learning."
2. *Integration 5 attribution*: an initial draft co-cited Hattie & Timperley and Black & Wiliam for the three-feedback-questions framework. On re-reading, that framework is Hattie & Timperley's contribution; co-citing both would have implicitly misattributed it. Restructured to attribute the three-questions framework to Hattie alone, with Black & Wiliam cited only for general formative-assessment foundation.

**Compile state.** Clean 5-pass compile: 196 pages (+2 from v2.9), 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references, 0 multiply-defined labels. Bibliography 67 entries, all VER:VERIFIED.

**Lineage.** v2.10 supersedes v2.9 as canonical version on the v2.x lineage. v2.9 files preserved as the round-2 reviewer release (sent to collaborators 2026-05-25); reviewers continue working with v2.9 throughout their cycle. v2.10 integration work is independent of round-2 reviewer feedback; when reviewer feedback arrives, additional changes will layer on top to become v2.11.

**Distribution.** v2.10 distribution packages (CCR, COR, CGR) NOT rebuilt — the v2.9 packages from Session 17 (`hyman2026learning_CCR_2026-05-24.zip`, `LearningWithAI_COR_2026-05-24.zip`, `hyman2026learning_CGR_2026-05-24.zip`) remain valid for the in-flight reviewer cycle. v2.10 packaging deferred to the next release point (likely v2.11 post-reviewer-feedback).

**Deferred items.** Tier 3 references from the Session 18 gap analysis remain available for future integration if Mac chooses: `chi1989self` for Plan-Use-Verify metacognitive depth, `felder2024teaching` for STEM-pedagogy overlay depth. McTighe & Willis (2019) *Upgrade Your Teaching* (uploaded as `mctighe2019upgrade.epub`) was not added to the bib in v2.10; `wiggins2005understanding` serves as the canonical UbD citation. All deferrals are reversible — references can be added in any later cycle.

---

## v2.9 — 2026-05-24 (Session 17: round-2 reviewer release with companion-paper threading + SPRE pass)

**Trigger.** Session 17 expanded the manuscript with the historical-pattern frame and companion-paper references developed collaboratively with Mac, then locked to v2.9 for transmission to round-2 reviewers. Bibliography work cleared the 2 VER:UNVERIFIED entries identified at branch start.

**Note on versioning.** This release was initially produced as v1.0 per the v0.999 → v1.0 standing rule in the project notes and HANDOFF_Session17.md. Mac corrected this on review: the manuscript already had a v1.0 release (May 4, 2026, 141pp, sent to SIAM Publishing) that went through v1.1 → v2.8 (May 13, 2026, 173pp). The v3.x cycle (Sessions 11–16, 173pp → 193pp) operated as internal working state on the v2.x lineage rather than as a fresh start. Today's release continues that lineage as v2.9. The May 4 v1.0 retains its identity as the first canonical SIAM-submission baseline; v2.9 is the round-2 reviewer release that includes Session 17 content additions on top of the v3.x working state.

**Scope.** Four substantive content edits (A, A', B, companion-paper references), bibliography blocker resolution, SPRE pass on new narrative, lock.

**Session 17 changes:**

**Edit 1 — Bibliography blockers resolved (both VER:UNVERIFIED → VERIFIED).**

`pollard2026community` updated: URL changed from stale CCDaily link to verified Inside Higher Ed article (Colleen Flaherty, "Presidents Puzzled on Rebuilding Public Trust in Higher Ed," April 9, 2026); full Pollard quote captured in note field; VER:UNVERIFIED removed.

`levine2026upheaval` updated: Promoted from `@unpublished` to `@book`; co-author Scott Van Pelt confirmed (was "co-author TBC"); ISBN 978-1421454030 added; author field normalized to `{Levine, Arthur and Van Pelt, Scott}`; VER:UNVERIFIED removed.

**Edit 2 — A: Foreword "Why this is not the first time" subsection added.**

New `\subsection*{Why this is not the first time}` inserted in Foreword between the GMIP framework paragraph and "The two-transcript idea" subsection. Six paragraphs introducing the historical-pattern frame through three analogies (photography, calculators, power tools), the "skill relocates" thesis, the disclaimer about uneven costs, and the bridge to the rest of the book. +408 words.

**Edit 3 — A': Pilot/autopilot → calculator replacement in Part I §sec:purpose.**

Single paragraph at line 462 became two paragraphs: closing of the rule statement, plus a calculator-analogy paragraph that delivers the same error-detection point with a more culturally accessible reference. Bastani citation preserved at line 466 (high-school math experiment) where it does the empirical heavy lifting. Net +61 words.

**Edit 4 — B: Calculator-institutional paragraph in Part III §u:sec:purpose.**

New paragraph inserted between ¶1 (problem statement: ban/permission false binary) and ¶2 (framework promise). Connects the calculator touchstone to institutional policy: "schools that simply banned them protected the old form of arithmetic instruction without asking whether that form was still what it was for." +150 words.

**Edit 5 — Companion-paper "in preparation" references added.**

Two new bib entries: `hyman2026next` (AI and the Next Layer of Human Work) and `hyman2026teaching` (Teaching AI Responsibly to Principled Skeptics), both `@unpublished` in-preparation. Two new inline citations: `\citep{hyman2026next}` at start of ¶6 of Foreword historical-pattern subsection (with bridging sentence pair); `\citep{hyman2026teaching}` in new paragraph at Part I §sec:purpose line 484 that acknowledges principled-skepticism position (environmental, labor, economic-concentration, copyright concerns). +171 words.

**SPRE pass on new narrative.**

Mechanical pre-scan on all new content (5 categories): 0 em-dashes, 0 ritual transitions, 0 buzzwords, 0 intensifiers, 0 ritual hedges. Two SPRE-Phase-2 adjustments applied: (1) 50-word sentence in v3.13 principled-skeptics paragraph split into two for better sentence variety (~30+25 words); (2) "arithmetic instruction" repeated within one sentence in B paragraph tightened to "it" in second occurrence. Word count unchanged after SPRE (structural-only changes).

**Compile state.** Clean 5-pass build. 194 pages (was 193 at v3.9; +1 from new Foreword subsection). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references, 0 multiply-defined labels. Clean bibtex run.

**Bibliography state after Session 17:**

| Metric | Count |
|---|---|
| Total entries | 58 (was 56; +2 hyman in-prep entries) |
| Verified | 58 (was 54; +4 today: pollard, levine, hyman2026next, hyman2026teaching) |
| VER:UNVERIFIED | 0 (was 2; both resolved) |
| BKS-conforming keys | 58 of 58 |

**Word count delta v3.9 → v2.9:**

| Stage | Word count | Delta |
|---|---|---|
| v3.9 (Session 16 baseline) | 61,829 | — |
| v3.10 (after A' calculator replacement) | 61,890 | +61 |
| v3.11 (after A Foreword subsection) | 62,298 | +408 |
| v3.12 (after B Part III paragraph) | 62,448 | +150 |
| v3.13 (after companion-paper references) | 62,619 | +171 |
| **v2.9 (after SPRE pass + lock)** | **62,619** | **+0** |
| Cumulative session delta | | **+790** |

**Calculator touchstone now threaded across three audiences:**

- Foreword: high-level introduction ("calculators did not end mathematics; they shifted the level")
- Part I §sec:purpose: student-learning application ("a student who reaches for a calculator before developing number sense...")
- Part III §u:sec:purpose: institutional-policy application ("schools that simply banned them protected the old form of arithmetic instruction...")

Each does different work at a different scale; the recurring touchstone strengthens unity across the book's three audiences. Matches the established pattern with Learning Spiral, CAT framework, and trilemma touchstones.

**Strategic posture.**

v2.9 is the round-2 reviewer release in the v1.0 → v2.x lineage. It supersedes v3.9 (the v3.x internal working-state notation) as the canonical version on the v2.x lineage. The v3.x internal working-state numbering (v3.10 through v3.13) is preserved in `/mnt/user-data/outputs/` as a rollback chain. The May 4 v1.0 remains the original SIAM-submission baseline in the manuscript's history. Mac sends v2.9 to reviewers for round-2 feedback; reviewer feedback shapes any subsequent v2.10+ revisions before the next major-version transition.

**Files updated this session:** `learning_with_ai_v2_9.tex`, `learning_with_ai_v2_9.pdf`, `LearningWithAI.bib`, `MANUSCRIPT_STATUS.yaml`, `CHANGELOG.md`.

**Packaging triad executed at session close (2026-05-24):**

Per CCR v1.1's "packaging triad" cadence, three archives were produced in dependency order (CCR upstream → COR → CGR):

| Archive | Output | Size | Contents |
|---|---|---|---|
| **CCR** (collaboration continuity) | `hyman2026learning_CCR_2026-05-24.zip` | 4.6 MB | 20 files: START_HERE.md, handoff/ (4 files), journal/ (2 files), protocols/ (3 files), source/ (build tree tarball + BUILD_README.md), compiled/ (PDF + COMPILE_STATE.md) |
| **COR** (Overleaf/SIAM submission) | `LearningWithAI_COR_2026-05-24.zip` | 4.7 MB | 8 files (flat-path): manuscript .tex/.pdf/.bib, 2 cartoon PDFs, README.md (rendered from YAML via manuscript-tracking skill), MANUSCRIPT_STATUS.yaml, CHANGELOG.md. Test compile in isolation: PASS (194 pages, 0 errors, 0 warnings) |
| **CGR** (GitHub repo) | `hyman2026learning_CGR_2026-05-24.zip` | 2.8 MB | 9 entries: book/learning_with_ai_v2_9.pdf, LICENSE (MIT), CITATION.cff, README.md (with Development Tools section per CGR v4.0), CHANGELOG.md, companion-papers/ placeholder for hyman2026next and hyman2026teaching. CGR-Audit PASS (Checks 3+4+5+7, all applicable); CGR-FreshExtract PASS (primary artifact book PDF verified at 194 pages, 2,715,485 bytes) |

All three archives are mutually consistent — they share the same source tree and compile state. Distribution block added to MANUSCRIPT_STATUS.yaml recording all three with paths, sizes, and audit states.

**Deferred for post-reviewer cycle:** Pre-final excellence-first check (more authoritatively informed by reviewer feedback than by self-review at this stage). Companion papers go to GitHub repo when Mac completes enhancement; book cross-reference text already in place.

**Cartoon-provenance handoff correction.** HANDOFF_Session17.md Section 5.2 stated that `cartoon_c1.pdf` and `cartoon_c2.pdf` were unreferenced in the manuscript. This is incorrect — both are active `\includegraphics{}` references and required for compile. The HANDOFF record is corrected here for future sessions.

---

## v3.9 — 2026-05-23 (Session 16: Bibliography integration + BKS key renames)

**Trigger.** Mac delivered VER v3.6 session report and updated bibliography (`LearningWithAI_v2.bib`) from the verification thread. The report documented 10 entries verified clean, 8 metadata corrections applied (3 CRITICAL/HIGH for VER-001 through VER-003; 5 LOW), 56 annote fields condensed, and explicitly flagged two BKS-non-conforming keys requiring coordinated manuscript-thread action (rename entry in .bib AND update `\cite{}` calls in .tex). Two entries remain VER:UNVERIFIED: `pollard2026community` (primary IHE URL unconfirmed) and `levine2026upheaval` (forthcoming book pending publication).

**Scope discipline.** Three coordinated tasks: bibliography swap, two BKS key renames (each requiring atomic .bib + .tex updates), tracking-document updates. No new content. No new citations. Bibliography count unchanged at 56 entries. Manuscript word count effectively unchanged (the only .tex changes are 2 cite-key strings in two existing sentences).

**Session 16 changes:**

**Edit 1 — Bibliography file replaced with v2 from verification thread.**

`/mnt/user-data/outputs/LearningWithAI.bib` now contains:
- VER-001 correction: `kings2024disclosure` author corrected from "King's Business School (authors TBD)" to "Gonsalves, Chahna"; volume=50, number=4, pages=592-606 added; DOI 10.1080/02602938.2024.2415654 preserved.
- VER-002 correction: `rees2026agentic` author corrected from "Rees, Geraint and others" to "Rees, Geraint and Wilsdon, James"; volume=652, pages=1119-1121, day=27 added.
- VER-003 correction: `insidehighered2026defense` author corrected from "Inside Higher Ed (author TBD)" to "Manturuk, Kim".
- Minor corrections: `samuel2025retrospective` day=17 added; `hepi2025students` month=feb, day=26 added with Josh Freeman noted in annote.
- 10 entries verified clean (no corrections needed).
- All 56 annote fields condensed from verbose session-log style to compact `VER:YYYY-MM-DD Verified.` notation; longest annote now 273 characters (was >600 before condensation).

**Edit 2 — BKS key rename: `kings2024disclosure` → `gonsalves2024addressing`.**

Coordinated change in two files. In `LearningWithAI.bib`: entry key renamed from `@article{kings2024disclosure,` to `@article{gonsalves2024addressing,` (author Gonsalves, year 2024, first content word "Addressing" — conforms to Mac's standing BKS rule lastname+year+firstword lowercase). In `learning_with_ai_v3_9.tex` line 589: `\citep{kings2024disclosure}` updated to `\citep{gonsalves2024addressing}` in the Student's Trilemma evidence paragraph discussing the King's Business School disclosure study.

**Edit 3 — BKS key rename: `insidehighered2026defense` → `manturuk2026best`.**

Coordinated change in two files. In `LearningWithAI.bib`: entry key renamed from `@misc{insidehighered2026defense,` to `@misc{manturuk2026best,` (author Manturuk, year 2026, first content word "Best" — conforms to BKS). In `learning_with_ai_v3_9.tex` line 2040: `\citep{insidehighered2026defense}` updated to `\citep{manturuk2026best}` in the Instructor's Trilemma honest-risk example discussing faculty reverting to blue books.

**Compile state.** Clean 5-pass build. 193 pages (unchanged from v3.8). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references, 0 multiply-defined labels. Clean bibtex run.

**Bibliography state after Session 16:**

| Metric | Count |
|---|---|
| Total entries | 56 |
| Verified (PASS) | 54 |
| VER:UNVERIFIED | 2 (pollard2026community, levine2026upheaval) |
| BKS-conforming keys | 56 of 56 (was 54 of 56 before Session 16) |
| Annote field format | Compact (was verbose for 12 entries) |

**Outstanding citation work (carried from VER report):**

- `pollard2026community`: PARTIALLY VERIFIED. Primary IHE article URL not independently confirmed; only Community College Daily secondary headline page (ccdaily.com/2026/04/headlines-1154/) was confirmed. Pollard's role as AACC President/CEO and the quoted passage are plausible. Action: retrieve and confirm primary IHE article URL before submission; substitute with established primary-source quote if unresolvable.
- `levine2026upheaval`: UNVERIFIED. Forthcoming book from Johns Hopkins University Press; co-author identity and ISBN cannot be confirmed prior to publication. Source evidence: Inside Higher Ed column (February 3, 2026) quoted Levine as co-author. Action: confirm co-author and ISBN once published; substitute with established source if book does not appear before submission.

**Files updated:** `learning_with_ai_v3_9.tex`, `learning_with_ai_v3_9.pdf`, `LearningWithAI.bib` (replaced with v2 + 2 key renames applied).

**Strategic posture and what's next.**

The companion-repository work plan is complete (Sessions 12-15). The bibliography is now in clean shape with 54 of 56 entries verified, 2 entries flagged with clear resolution paths, and all keys conforming to the BKS protocol.

Remaining manuscript work:
- 2 VER:UNVERIFIED entries pending resolution (pollard2026community URL confirmation; levine2026upheaval publication confirmation)
- v0.999 → v1.0 transition logic still applies: next substantive revision becomes v1.0 per Mac's standing rule for this project
- Real-student-deployment feedback if SPP or DPP surface manuscript-relevant issues
- Other manuscript improvements at Mac's direction
- Or, the v0.999 → v1.0 transition if the manuscript is ready to lock for SIAM submission

---

## v3.8 — 2026-05-23 (Session 15 Priority 2: Four operational cross-references for DPP/SPP/instructor briefings)

**Trigger.** With Priorities 1, 3, and 4 complete (Sessions 12-14), Priority 2 was the only remaining work in the companion-repository plan. Required a scope-confirmation pass before drafting (per the original prompt's design and the precedent set by Priority 1's evaluation pass at the start of Session 12). The fresh-eyes review of the original 6-add/11-skip proposal flipped three decisions: dropped DPP at app:ai-config opening (would compete with the in-book template), dropped companion-checklist and companion-disclosure-templates pointers (standalone-file pointers are repository housekeeping rather than reader benefit, and the frontmatter already establishes that standalone artifacts exist), and added SPP at the Learning Spiral's ask-for-help subsection (the natural first encounter with the practice, missed in the original proposal). Final scope: 4 cross-references at 4 high-value locations.

**Scope discipline.** Per Mac's direction, Locations 1 and 3 consolidated to single sentences. Locations 2 and 4 also single-sentence (the briefings pointer is one long sentence naming the operational difference between the book's category-specific paragraphs and the repository's full-syllabus variants). Each cross-reference earns its place by being at the moment a reader would benefit from the operational tool, not by exhaustively flagging every plausible touchpoint.

**Session 15 Priority 2 changes:**

**Edit 1 — DPP cross-reference appended to §sec:setup remedy paragraph (~30 words).**

Single sentence appended after the existing "ten minutes setting these once" payoff statement: "Students who would prefer to be walked through this setup interactively can use the Define Personal Preferences (DPP) walkthrough in the companion repository (`companion/dpp/`)." Position is at the natural moment of choice: the reader has just learned about persistent preferences and the six categories, been told the full template appears in the appendix, and been given the rationale. The DPP pointer offers the guided alternative to the copy-and-adapt template. First `companion/dpp/` path reference in the manuscript.

**Edit 2 — SPP cross-reference appended to §subsec:ask-for-help (~30 words).**

Single sentence appended after the existing closing "best prompts are not commands to replace your work; they are requests for coaching" statement: "Students who want a tested prompt for converting the AI into a study partner rather than an answer machine can use the Study Partner Protocol (SPP) in the companion repository (`companion/spp/`)." Position is at the natural close of the Learning Spiral subsection that develops the "ask for help" practice. This is the first encounter a linearly-reading student has with the operational SPP tool (frontmatter introduced SPP by name; this is the first body-text pointer in the operational moment).

**Edit 3 — SPP cross-reference inserted in AIT subsection (§subsec:yellow) between the existing v3.5 thread-sharing additions (~22 words).**

Single sentence inserted between "AIT use is common when..." and the existing thread-sharing pointer: "The Study Partner Protocol (SPP) in the companion repository (`companion/spp/`) is designed for exactly this kind of AIT work." Position places SPP as the operational tool for doing the work BEFORE thread sharing as the operational mechanism for disclosing the work, mirroring the natural workflow ordering.

**Edit 4 — Instructor-briefings cross-reference appended to §i:app:syllabus opening (~55 words).**

Single longer sentence appended to the existing "may be adapted to fit a course" framing: "For instructors who prefer to start from a pre-written briefing rather than adapt the language below, the companion repository's `instructors/briefings.md` provides three ready-to-use syllabus paragraphs at different permissiveness levels (restrictive, default, and permissive); each is about 180 words and designed to drop into a syllabus without modification." Length earns its place by naming the operational difference between the book's category-specific paragraphs (NAI/AIT/AIC/AIS each treated separately) and the repository's three full-syllabus variants by permissiveness level (a different conceptual cut). First `instructors/` path reference in the manuscript.

**Compile state.** Clean 5-pass build. 193 pages (+1 from v3.7's 192). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references. Net change: +1 page, +121 words.

**No new citations.** Four cross-references; no academic literature is newly cited. Bibliography unchanged at 56 entries with 12 VER:UNVERIFIED pending verification.

**Companion repository reference inventory in v3.8.** Frontmatter (v3.7) introduces the repository, SPP, and DPP. Body text now contains:
- `companion/dpp/` — 1 reference (sec:setup, v3.8 Edit 1)
- `companion/spp/` — 4 occurrences (frontmatter prose as example pattern; v3.6 sec:learning-loop default-profile paragraph; v3.8 Edit 2 subsec:ask-for-help; v3.8 Edit 3 subsec:yellow AIT)
- `students/sharing-ai-conversations.md` — 1 reference (v3.5 subsec:thread-sharing)
- `students/checklist` — 1 occurrence (frontmatter prose as example pattern)
- `instructors/briefings.md` — 1 reference (v3.8 Edit 4)

Cross-reference distribution by Part: Part I (Student Guide) has 6 companion references (3 from v3.5-v3.6 plus 3 new in v3.8); Part II (Instructor Guide) has 1 companion reference (v3.8 Edit 4); Part III has 0 (deliberately — institutional content is not operationalized by companion tools).

**Companion-repository work plan now COMPLETE.** All four priorities resolved:

| Priority | Status |
|---|---|
| Priority 1 (memo evaluation + four Part I/II items) | ✅ Complete (Sessions 12-13) |
| Priority 2 (operational cross-references) | ✅ Complete (Session 15, v3.8) |
| Priority 3 (thread sharing as named practice) | ✅ Complete (Session 12, v3.5) |
| Priority 4 (frontmatter "About the companion repository") | ✅ Complete (Session 14, v3.7) |

**Files updated:** `learning_with_ai_v3_8.tex`, `learning_with_ai_v3_8.pdf`. All earlier versions retained for rollback (v3.7, v3.6, v3.5, v3.4, v2.15, v2.13).

**Strategic posture and what's next.**

The companion-repository integration work is complete. The book now references the repository at frontmatter (introduction with named tools and URLs) and at 7 body locations spread across Parts I and II. The cross-reference density is calibrated: enough to remind a reader of the apparatus at high-value moments, not so much that the book feels like a thinly-disguised pointer to its own companion.

Remaining manuscript work (pre-existing, not added by the companion-repository plan):
- 12 VER:UNVERIFIED bibliography entries pending Mac's batch verification (carried since 2026-05-22)
- v0.999 → v1.0 transition logic still applies: next substantive revision becomes v1.0 (per Mac's standing rule for the learning book)

Repo-side work for Mac to coordinate with the repo thread:
- Push the scaffold to `github.com/machyman/hyman2026learning`
- Activate GitHub Pages at `machyman.github.io/hyman2026learning`
- Apply the companion-artifact versioning convention to `CONTRIBUTING.md` (Issue logged from Priority 1 evaluation)

The book thread has no further companion-repository-integration work pending. Future sessions can return to other manuscript improvements, real-student-deployment feedback, or whatever Mac directs next.

---

## v3.7 — 2026-05-23 (Session 14 Priority 4: About the companion repository frontmatter section)

**Trigger.** With Priority 1 closed (Session 13) and Priority 3 complete (Session 12), Priority 4 was the next conceptual addition required before Priority 2 (operational cross-references). The rationale: Priority 4 provides the first formal introduction of the companion repository in the manuscript, which then lets Priority 2's cross-references land in a manuscript where the reader already knows the repository exists.

**Scope discipline.** Two-paragraph frontmatter section. The prompt suggested "one or two paragraphs" and two was the natural register: one factual paragraph (where it lives, what it contains, SPP and DPP introduced by name) and one relational paragraph (book-vs-repo relationship, licensing, ERRATA mechanism). No new sections in the body of the book; no new citations.

**Session 14 Priority 4 changes:**

**Edit 1 — New §section* "About the companion repository" inserted in frontmatter between "How to read this book" and "Acknowledgments" (~245 words, two paragraphs).**

The placement keeps the new section among the practical orienting materials at the front of the book, alongside "How to read this book," before the ritual Acknowledgments section, and before the substantive Foreword. A reader getting oriented to the book encounters the companion repository at the natural moment in the front-matter flow.

Paragraph 1 (factual): Names the repository URL (`github.com/machyman/hyman2026learning`) and the Pages site (`machyman.github.io/hyman2026learning`). Introduces the two primary companion tools by name: Study Partner Protocol (SPP) and Define Personal Preferences (DPP). Describes the broader categories of material (instructor materials, student materials) without enumerating every file. Cross-references Part~\ref{part:student} for the pre-submission checklist that appears both in the book and in the repository.

Paragraph 2 (relational): Names the book-versus-repository division of labor ("the book teaches the framework; the repository hosts the operational artifacts"). Names the cross-reference pattern that readers will encounter throughout (`companion/spp/`, `students/checklist`, etc.). States the licensing arrangement: book remains under SIAM copyright; repository materials are MIT-licensed and may be freely used, modified, adapted, translated, and redistributed with attribution. Names the ERRATA mechanism for post-publication corrections.

The section uses the existing frontmatter conventions: `\section*{...}` (unnumbered), `\addcontentsline{toc}{section}{...}` for TOC inclusion, comment-block separator before the section heading. SPP and DPP are now introduced by name in the frontmatter; subsequent body-text references in Priority 2 can use the acronyms without re-introducing them.

**Compile state.** Clean 5-pass build (pdflatex / bibtex / pdflatex / pdflatex / pdflatex). 192 pages (unchanged from v3.6's 192 — the new frontmatter section absorbed into existing front-matter layout without forcing pagination changes; the ideal outcome for a small frontmatter addition). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references. Net change: 0 pages, +234 words.

**No new citations.** Frontmatter section names the companion repository but cites no academic literature. Bibliography unchanged at 56 entries with 12 VER:UNVERIFIED pending verification.

**First formal manuscript introduction of SPP and DPP.** v3.5's `subsec:thread-sharing` referenced `students/sharing-ai-conversations.md` as a file path. v3.6's `sec:learning-loop` default-profile paragraph referenced `companion/spp/` as a path. Neither expanded the acronym or named the tool. v3.7's frontmatter is the first place where SPP and DPP are named explicitly as the Study Partner Protocol and Define Personal Preferences, with brief descriptions. This unlocks Priority 2's body-text cross-references to use the acronyms without re-introducing them.

**Files updated:** `learning_with_ai_v3_7.tex`, `learning_with_ai_v3_7.pdf`. All earlier versions retained for rollback (v3.6, v3.5, v3.4, v2.15, v2.13).

**Strategic posture and what's next.**

Priorities 1, 3, and 4 are all complete. Only Priority 2 remains:

**Priority 2: Operational cross-references for DPP/SPP/checklist/disclosure templates/instructor briefings.**

Locations identified during Session 12's verification work:
- DPP cross-references in `sec:setup` and `app:ai-config` (~11 candidate locations from "persistent preferences / custom instructions / account configuration" grep)
- SPP cross-references at natural Learning Spiral and AIT contexts beyond the existing references already in place (v3.5's `subsec:thread-sharing` for thread-sharing-specific framing; v3.6's `sec:learning-loop` default-profile paragraph for new-student framing; v3.6's `i:sec:integrity` spot-checking paragraph for instructor-side framing)
- Pre-submission checklist cross-references (3 actual locations in v3.7, not 24 as the prompt initially claimed)
- Disclosure template cross-references in `sec:disclosure`
- Instructor briefings cross-references in Part II (1 actual syllabus-template location at `i:app:syllabus`)

Priority 2 work will require a scope-confirmation discussion to decide which candidate locations actually warrant cross-references vs. which would be over-referencing. Some candidate locations may not need cross-references because the v3.7 frontmatter introduction is now sufficient orientation; others will benefit from inline pointers.

The natural next session is Priority 2, but it should begin with a scope-confirmation conversation (which candidate locations get cross-references and which don't) before any drafting. The prompt's original guidance was clear: "For each candidate location, propose to Mac: whether a cross-reference is appropriate (some may not be); draft text for the cross-reference (typically one or two sentences); whether the addition should be inline, a footnote, or a forward-pointer in a 'see also' position."

---

## v3.6 — 2026-05-23 (Session 13: Remaining Priority 1 conceptual items — §5 forward-pointer, default-profile student, instructor spot-checking)

**Trigger.** Session 12 Priority 3 closed the §7 and §13 gates from the Priority 1 evaluation pass (both forward-pointers required thread sharing to be introduced first). Session 13 executes the three remaining Priority 1 conceptual items approved in the evaluation pass: §5 forward-pointer (translation test + cross-thread coordination), Item 1 (default-profile student paragraph), and Item 2 (instructor spot-checking in Part II).

**Scope discipline.** Three tight additions, ~280 words total, +0 pages (new content absorbed into existing page layout). No new sections; each addition lands inside an existing section at the natural position. The work pattern follows Session 10's "tight integration, not expansion" discipline.

**Session 13 changes:**

**Edit 1 — Cross-thread structural claim added to §sec:compact, after the translation test figure and before the five-part compact enumeration (~80 words).**

The §5 forward-pointer from Priority 1's evaluation pass strengthens the translation test's claim to load-bearing status by naming what it catches beyond single-chat overreliance: "The translation test catches more than single-chat overreliance. It also catches AI work produced outside any single, identifiable session, including work whose surface was polished in one chat while the actual content was drafted in another. The test asks what the student can do regardless of which chat produced what." Forward-points to §subsec:thread-sharing for the operational version, completing a symmetric cross-reference pair: §sec:disclosure's §subsec:thread-sharing already pointed BACK to §sec:compact as the structural safeguard; §sec:compact now points FORWARD to §subsec:thread-sharing as the operational treatment.

**Edit 2 — Default-profile student paragraph added to §sec:learning-loop, between the time-scales meta-paragraph and the §subsec:try-first detailed walkthrough (~115 words).**

Acknowledges that the five Learning Spiral steps name skills, not behaviors that come automatically. A first-generation student new to a discipline may not know what trying first looks like for a proof, what verifying means for a citation in a specific field, or what counts as working independently in a programming class versus a literature class. Closes by directing readers who recognize themselves in the paragraph to the companion materials in `companion/spp/` that explicitly support students new to any of this. The paragraph operationalizes the equity dimension of the Student's Trilemma's dimensions-of-variation subsection (Session 9, v3.2) at the Learning Spiral level: the trilemma names the structural pressures different students face; this paragraph names the operational skills not all students arrive with.

**Edit 3 — Instructor spot-checking paragraph added to Part II §i:sec:integrity, between the accountability framing and the Northeastern faculty case (~95 words).**

Names probabilistic deterrence as the operational practice: spot-checking does not require reviewing every student's AI conversation on every assignment; reviewing three or four threads per assignment, chosen at random or based on signal, creates probabilistic deterrence at sustainable cost. Closes with the trilemma-balance argument: the probabilistic version preserves the framework's three-cornered balance because the instructor's trustworthy-judgment corner is honored without making sustainability impossible. References §subsec:thread-sharing as the student-side practice that makes spot-checking operationally efficient. The paragraph deliberately does NOT name SPP by name (that introduction is Priority 2 work scheduled for a later session).

**Compile state.** Clean 5-pass build (pdflatex / bibtex / pdflatex / pdflatex / pdflatex). 192 pages (unchanged from v3.5's 192 — the three new paragraphs absorbed into existing page layout without forcing pagination changes; this is the ideal outcome for small-scope conceptual additions). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references. Net change: 0 pages, +280 words.

**No new citations.** Three conceptual additions building on Priority 1's approved evaluation; no academic literature is newly cited. Bibliography unchanged at 56 entries with 12 VER:UNVERIFIED pending verification.

**Priority 1 evaluation pass: ALL approved items now landed.**

| Priority 1 item | Status | Version |
|---|---|---|
| §5 forward-pointer (translation test + cross-thread) | ✅ Landed | v3.6 (Session 13) |
| §6 forward-pointer (CAT + NASEM mentorship) | Skipped per evaluation | — |
| §7 forward-pointer (Learning Spiral + thread sharing) | ✅ Landed | v3.5 Edit 2 (Session 12) |
| §13 forward-pointer (disclosure + thread sharing) | ✅ Landed | v3.5 Edit 1 (Session 12) |
| Item 1 (default-profile student) | ✅ Landed | v3.6 (Session 13) |
| Item 2 (instructor spot-checking, Part II) | ✅ Landed | v3.6 (Session 13) |
| Item 3 (terminology transition note in frontmatter) | Skipped per evaluation | — |
| Item 4 (companion versioning convention, manuscript) | Skipped per evaluation; listed as Issue for repo thread | — |

**Files updated:** `learning_with_ai_v3_6.tex`, `learning_with_ai_v3_6.pdf`. All earlier versions retained for rollback (v3.5, v3.4, v2.15, v2.13).

**Strategic posture and what's next.**

Priority 1 is now complete. Remaining priorities:

**Priority 2: Operational cross-references for DPP/SPP/checklist/disclosure templates/instructor briefings.**
- DPP cross-reference in §sec:setup and §app:ai-config (7 relevant locations identified)
- SPP cross-references in Learning Spiral and AIT contexts (companion/spp/ already referenced in §sec:learning-loop via Session 13 Edit 2; further SPP references should be added at natural locations)
- Pre-submission checklist cross-references (3 actual locations in v3.6, not 24 as the prompt initially claimed)
- Disclosure template cross-references in §sec:disclosure
- Instructor briefings cross-references in Part II (1 actual syllabus-template location)

**Priority 4: Frontmatter "About the companion repository" section.**
- One or two paragraphs in preface or before Part I
- Where the repository lives (`github.com/machyman/hyman2026learning`)
- What it contains (tools, templates, guides)
- Book vs. repository relationship
- Licensing note

The natural next session executes either Priority 2 (operational cross-references) or Priority 4 (frontmatter). Priority 4 is the cleaner choice for the next session because it provides the first formal introduction of the companion repository in the manuscript; Priority 2's cross-references will then land in a manuscript where the reader has already been told the repository exists.

---

## v3.5 — 2026-05-23 (Session 12 Priority 3: Thread sharing introduced as a named practice)

**Trigger.** Companion repository (`hyman2026learning_repo_scaffold.zip`) and SPP development memo arrived at end of Session 11 with four priorities for the book thread to evaluate. Priority 1 was an evaluation pass that produced approved decisions (4 add items, 4 skip items, 2 items gated on Priority 3). Priority 3 executes one of those gated items: introducing thread sharing as a named practice in the manuscript. v3.4 was silent on thread sharing despite the companion repository formalizing it in three places (SPP wrapper, students/sharing-ai-conversations.md, instructor briefings). Students reading the book did not know what their teachers were likely to ask for. Priority 3 closes this gap.

**Scope discipline.** Per the priority-evaluation decision, the manuscript NAMES AND MOTIVATES the practice; the companion repository carries the operational mechanics (platform-by-platform instructions). The manuscript does not duplicate the companion's platform-specific guidance. Target: one short subsection in `sec:disclosure` plus brief forward-pointers from two related locations.

**Session 12 Priority 3 changes:**

**Edit 1 — New §subsec:thread-sharing in §sec:disclosure, inserted between §subsec:good-disclosure and §sec:privacy.**

Three paragraphs total. Paragraph 1 names the practice: most major platforms (ChatGPT, Claude, Gemini, Copilot, and others) support a share function producing a read-only link; companion repository's `students/sharing-ai-conversations.md` provides operational steps per platform. Paragraph 2 argues thread sharing is the strongest form of disclosure available to a student because it closes the gap between the student's account and the underlying interaction. Paragraph 3 names two honest limits: (a) the cross-thread theater problem (a student running a polished AI session for show while drafting in a separate unshared chat has not solved disclosure, only relocated it; translation test in §sec:compact is the structural safeguard); (b) privacy considerations (the §sec:privacy material applies to anything visible in a shared thread; edit/redact before sharing or ask instructor for an alternative).

This subsection is the primary introduction of thread sharing. Subsequent references in the manuscript point back to it.

**Edit 2 — Forward-pointer added to §subsec:reflect-disclose (Learning Spiral step 5).**

Single sentence appended to the existing "follow the assignment instructions" line: "When an instructor asks to see the AI conversation itself, thread sharing (\cref{subsec:thread-sharing}) is the strongest disclosure available; for most AI-assisted work it makes the written block unnecessary." Lets a student reading the Learning Spiral disclose-and-reflect step know that thread sharing exists as an option above written disclosure.

**Edit 3 — Forward-pointers added to §subsec:yellow (AIT) and §subsec:green (AIC) in Part I §sec:assignment-categories.**

Each subsection received a single sentence noting that thread sharing is the natural disclosure mechanism for that category. AIT addition: "When AIT work produces a tutoring conversation worth showing your instructor, thread sharing (\cref{subsec:thread-sharing}) documents the interaction more cleanly than any written summary." AIC addition: "Because the AI's contribution is part of what is being assessed, thread sharing (\cref{subsec:thread-sharing}) is often the most natural way to disclose how the work was produced." NAI and AIS subsections deliberately not amended: NAI work should produce no thread to share, and AIS work has its own disclosure pattern (the AI output is itself the artifact).

**Compile state.** Clean 5-pass build (pdflatex / bibtex / pdflatex / pdflatex / pdflatex). 192 pages (+1 from v3.4's 191). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references. Net change: +1 page, +341 words.

**No new citations.** Thread sharing is introduced as a practice the companion repository formalizes; no academic literature is cited for the practice itself. Bibliography unchanged at 56 entries with 12 VER:UNVERIFIED pending verification.

**First companion-repository references in manuscript.** v3.5 is the first manuscript version that references the companion repository by file path (`students/sharing-ai-conversations.md`). The repository itself is not yet introduced via frontmatter (that work is deferred to a later session combining Priorities 4 + Item 1d if approved). For v3.5, the path reference suffices because the SPP and DPP framing comes later in the work plan.

**Priority 3 closes the gates on §7 and §13 forward-pointer opportunities from Priority 1.** Both §subsec:reflect-disclose (the §7 opportunity) and §sec:disclosure (the §13 opportunity) received their thread-sharing content in this session. The Priority 1 §5 forward-pointer (translation test + cross-thread coordination) remains pending; the cross-thread theater framing in §subsec:thread-sharing paragraph 3 partly addresses it, but the explicit §5 addition the memo proposed has not yet been made.

**Files updated:** `learning_with_ai_v3_5.tex`, `learning_with_ai_v3_5.pdf`. All earlier versions retained for rollback (v3.4, v2.15, v2.13).

**Strategic posture and what's next.**

Priority 3 complete. Remaining Priority 1 work to execute (per approved decisions):
- §5 forward-pointer: translation test + cross-thread coordination explicit addition (one or two sentences in `sec:compact`)
- Item 1: default-profile student paragraph (in Learning Spiral section)
- Item 2: instructor spot-checking paragraph (Part II)

Remaining Priorities:
- Priority 2: cross-references for DPP (`sec:setup`, `app:ai-config`), pre-submission checklist (3 actual locations), disclosure templates, instructor briefings (Part II). Now informed by Priority 3's thread-sharing introduction.
- Priority 4: frontmatter "About the companion repository" section.

The natural next session executes the remaining Priority 1 items (§5 forward-pointer + Item 1 default-profile + Item 2 Part II spot-checking) since these are conceptual additions that should land before the operational cross-references in Priority 2.

**Issues for repo thread (per coordination rule):**

- Item 4 from memo (companion-artifact versioning convention) — recommend adding to `CONTRIBUTING.md` and each companion artifact's provenance section that companion artifacts should declare which manuscript version they were built against.

---

## v3.4 — 2026-05-22 (Session 11: Phase 3 cycle — class-size signposting in Part II opening, Scott #7)

**Trigger.** With drudgery-vs-payoff complete (Session 10), the only remaining Scott McKinley meeting item was #7: class-size signposting at Part II's opening. Per the Session 3 strategic review's logging: "Scott was emphatic that 30-student, 70-student, and 100+-student classrooms are 'completely different worlds' for assessment design. Part II addresses this 'as you get into it more' but Scott was skimming and may have missed the signposting. v3.0 polish pass should ensure the class-size axis is prominently visible at Part II's opening so a skimming reader sees the framework's class-size sensitivity immediately, not only after reading deeply. Small reorganization, no new substantive content." Mac requested this as a quick win before pausing Phase 3 work to prepare GitHub repository details for the next session (Joshua #3 Blue category expansion).

**Scope discipline.** Scott #7 was explicitly logged as "Small reorganization, no new substantive content." The Session 11 work honored this constraint: a single short paragraph inserted between Part II's four-aims list and the modesty-caveat paragraph, no new sections, no new citations, no structural changes.

**Session 11 changes:**

**Edit 1 — Class-size signposting paragraph added to §i:sec:purpose (Part II Purpose and scope), between the four-aims enumerate and the existing modesty paragraph.**

The original Part II opening mentioned class size only in passing (the fourth aim referenced "small, medium, and large courses") and developed the class-size axis fully in §i:sec:three-axes — but a skimming reader (which Scott was) could miss both the passing mention and the deep section. The Session 11 addition names class size unmissably as the dominant variable: "One variable runs through the rest of this Part more than any other: class size. A thirty-student seminar, a seventy-student lecture, and a three-hundred-student introductory course are completely different worlds for AI-era assessment design."

The paragraph then explains the framework's class-size sensitivity: approaches that work in the seminar don't scale, approaches that scale don't preserve what makes the seminar valuable. It names the three assessment models (Oral-Defense, Evidence-of-Thinking, Hybrid) and points the reader forward to §i:sec:three-axes. Closes with practical guidance for readers whose class size is their dominant constraint: scan §i:sec:three-axes and the three assessment models early.

**Compile state.** Clean 5-pass build (pdflatex / bibtex / pdflatex / pdflatex / pdflatex). 191 pages (unchanged from v3.3's 191). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references. Net change: 0 pages, +127 words. The new paragraph fit into existing page layout without forcing pagination changes — the ideal outcome for small-scope signposting.

**No new citations.** Existing Part II citations (Bastani, Kestin, Dunlosky, OECD, Miao) sufficient for the surrounding prose. Bibliography unchanged at 12 VER:UNVERIFIED entries pending verification.

**Scott McKinley meeting items: complete inventory.** With Session 11, every major Scott meeting item has now landed in the manuscript:

| Scott # | Item | Session landed | Version |
|---|---|---|---|
| #1 | Translation test "say it three ways" | 6 | v2.15 |
| #2 + #4 | Configuration step elevation + friction-wall | 5 | v2.14 |
| #3 | Trilemma framework endorsement | 1 | (confirmation, no new prose) |
| #5 | Part III chairs-to-deans + drudgery-vs-payoff | 10 | v3.3 |
| #6 | Conscientious-objector subsection | 6 | v2.15 |
| #7 | Class-size signposting in Part II | 11 | v3.4 |
| Bonus | Cross-audience Trilemma (all three Parts) | 7, 8, 9 | v3.0, v3.1, v3.2 |

The Scott meeting feedback inventory is now complete. Manuscript v3.4 reflects the full integration of Scott McKinley's 2026-05-22 meeting feedback across the eleven sessions that followed.

**Files updated:** `learning_with_ai_v3_4.tex`, `learning_with_ai_v3_4.pdf`. All earlier versions retained for rollback.

**Strategic posture and what's next.**

Phase 3 paused at Mac's request to prepare GitHub repository details before tackling Joshua #3 (Blue category expansion). Joshua #3 is logged as Mac's "most original idea" worth expanding — possibly new content in Parts I, II, III showing Blue (AIS) assignments at student, instructor, and administrator levels. The repository details Mac will upload will inform how the Blue category expansion integrates with the planned GitHub companion repository structure.

Phase 3 work remaining after pause:
- **Blue category (AIS) expansion across all three Parts** (Joshua #3) — next session after Mac uploads GitHub repository details
- Citation verification batch pass (VER on 12 UNVERIFIED entries from Sessions 7-9)
- Manuscript-wide polish pass: should-reduction, list-density audit, repetition reduction (Joshua #1)
- SPP integration (pending SPP v2.0 from stress-test thread)
- Learning Spiral figure redraw (separate visual-design session)
- Possible compression of Parts I, II, III to manage cumulative page budget

External-input gates active for upcoming sessions:
- **GitHub repository details** (Mac uploading before Joshua #3)
- SPP v2.0 from stress-test thread (gates SPP integration)
- Reader feedback from Scott and others (informational, not blocking)

---

## v3.3 — 2026-05-22 (Session 10: Phase 3 cycle — drudgery-vs-payoff framing + chairs-to-deans rhetorical pivot for Part III)

**Trigger.** With cross-audience trilemma development complete (Sessions 7-9), Phase 3 returns to the original Scott McKinley meeting feedback items that had been deferred until the framework was complete. Scott #5 was the largest of those items: organize Part III around "the argument chairs need to make to the deans" using his "drudgery vs. payoff" distinction as the structural device. Both framings come directly from the 2026-05-22 meeting transcript: drudgery-vs-payoff at lines 2282-2303 (where Scott articulated why coders welcome AI but artists resist it) and chairs-to-deans at line 2534 (where Scott named the rhetorical purpose Part III should serve).

**Approach: tight integration, not expansion.** The Session 3 strategic review explicitly constrained this work: "Part III's current ~40 pages is its CEILING for v3.0, not its floor. The reframe should reorganize existing material around a stronger spine; new framings must be paid for by equal or greater compression of existing material." Session 7's Institution's Trilemma additions already pushed Part III +3pp over the original ceiling, with Mac confirming that the trilemma viewpoint earned the pages. Session 10's drudgery-vs-payoff work needed to be even more disciplined. The strategic review's specific guidance: "One paragraph of well-placed framing using this distinction is worth more than three sections of supporting examples." Other meeting material (post-COVID creativity drop, photography analogy, campfire guitar) was explicitly excluded from the manuscript per that review — reserved for talks and presentations rather than entering the book.

**Session 10 changes:**

**Edit 1 — Operationalize the educational-mission corner of the Institution's Trilemma with drudgery-vs-payoff (~110 words added to existing corner definition).**

The educational-mission corner in v3.2 was defined abstractly: "the deeper commitment to what students gain by attending... varies by institutional type but is always present in the institution's self-understanding." This definition named what the corner referred to without operationalizing what made it load-bearing. Session 10 adds a paragraph that uses Scott's drudgery-vs-payoff distinction to give the corner operational meaning: "What unifies these institution-type-specific articulations is a single claim: that some learning is itself the payoff, not just a means to an end. A coder welcomes AI because for them the drudgery is what they want eliminated and the working program at the end is the payoff. An artist resists AI because for them the drudgery---the patient hours of practice and revision---is the payoff and the finished piece is its trace. The educational-mission corner rests on the same distinction at the institutional scale."

The framing converts the educational-mission corner from a soft mission-language claim into a sharp operational claim: an institution that has accepted that all of its content can be delivered more efficiently by AI has tacitly accepted that nothing it does is itself the point. The framing is presented as the book's own (not attributed to Scott by name in the manuscript, per academic-attribution norms and Scott's status as a non-author reviewer).

**Edit 2 — Add chairs-to-deans argumentative purpose to trilemma-stakes subsection (~140 words inserted before Northeastern transition).**

The trilemma-stakes subsection in v3.2 positioned the trilemma as the conceptual spine for the rest of Part III but did not name Part III's broader rhetorical purpose. Session 10 adds a paragraph that explicitly names that purpose: "There is also a more concrete rhetorical purpose to this Part. Department chairs and program directors increasingly find themselves in conversations with deans, provosts, and boards about whether faculty roles can be replaced by AI tools at substantially lower cost. The Institution's Trilemma supplies the structural answer to that question: the case for human-led education is the case that the educational-mission corner cannot be honored by a system that has hollowed out into pure credentialing. Throughout the rest of this Part, the operational tools developed---assessment models, integrity procedures, faculty change management, implementation phases---can be read as ammunition for the argument chairs need to make to deans when AI-replacement proposals arrive on the agenda."

The paragraph closes with a directive sentence that names the argument's stance: "The argument is not nostalgic and it is not defensive. It is the argument that some of what students pay for, and some of what graduates carry forward, is the very thing that AI-as-replacement is supposed to eliminate."

**Compile state.** Clean 5-pass build (pdflatex / bibtex / pdflatex / pdflatex / pdflatex). 191 pages (+1 from v3.2's 190). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references. Net change: +1 page, +297 words.

**No new citations.** Both framings are conceptual additions building on Scott's meeting feedback rather than empirical claims requiring literature support. The framings themselves are now the book's own, presented without attribution to Scott (who is a colleague and reviewer, not a co-author). Bibliography unchanged.

**Audience-weighted page budget impact.** Part III is now +4pp over its original ~40pp ceiling (Session 7 +3pp from Institution's Trilemma; Session 10 +1pp from drudgery-vs-payoff and chairs-to-deans framings). The drudgery-vs-payoff work was specifically constrained to one paragraph (+1pp total) per the Session 3 strategic review's "tight, not expansion" guidance. The combined Phase 3 Part III expansion (+4pp) reflects substantial conceptual additions that have been disciplined to their minimum effective size. Future v3.x sessions may compress weaker existing Part III material if Mac decides further offsetting is needed.

**Cumulative Phase 3 impact through Session 10:**

| Session | Work | Pages added |
|---|---|---|
| 7 | Institution's Trilemma + institutional-type variation | +3 |
| 8 | Instructor's Trilemma + faculty-type variation | +5 |
| 9 | Student's Trilemma optimization | +5 |
| 10 | Drudgery-vs-payoff + chairs-to-deans | +1 |
| **Phase 3 cumulative** | — | **+14 (177pp → 191pp)** |

Phase 3 has invested heavily in conceptual framework development and rhetorical sharpening across all three Parts. The investment pattern matches the audience-weighted budget: +5pp Part I (75% readers), +5pp Part II (20% readers), +4pp Part III (5% readers).

**Files updated:** `learning_with_ai_v3_3.tex`, `learning_with_ai_v3_3.pdf`. All earlier versions retained for rollback.

**Strategic posture and what's next.**

Session 10 completes the Scott #5 work (drudgery-vs-payoff + chairs-to-deans). Combined with Sessions 7-9 (cross-audience trilemma development) and earlier Sessions 5-6 (configuration elevation, conscientious-objector, faculty AI use, equity expansions, translation test three-modality), the major Scott McKinley meeting items have all landed in the manuscript.

Phase 3 work remaining:
- Blue category (AIS) expansion across all three Parts (Joshua #3)
- Class-size signposting in Part II opening (Scott #7)
- Empirical citations VER pass (12 UNVERIFIED entries from Sessions 7-9)
- Manuscript-wide polish pass: should-reduction, list-density audit, repetition reduction (Joshua #1)
- SPP integration (pending SPP v2.0 from stress-test thread)
- Learning Spiral figure redraw (separate visual-design session)
- Possible compression of Parts I, II, III to manage cumulative page budget if Mac decides current size needs offsetting

The natural next session is **Blue category (AIS) expansion** (Joshua #3) — Joshua called this Mac's "most original idea" worth expanding. Builds on v2.14's framework-rename foundation where AIS (Blue) was established as orthogonal to the NAI/AIT/AIC permission axis — every Blue expansion can be introduced as a question *about* AI rather than a permission level *for* AI. Alternative: a smaller item like class-size signposting (Scott #7) if a quick win is preferred.

---

## v3.2 — 2026-05-22 (Session 9: Phase 3 cycle — Student's Trilemma optimization to same standard as other two trilemmas)

**Trigger.** After Session 8 brought the Instructor's Trilemma up to literature-grounded rigor matching the Institution's, Mac asked whether the Student's Trilemma had been optimized to the same level. Honest audit revealed it had not: while the framework was first developed in Part I, it had not received the literature-first / refinement workflow used for the other two. Side-by-side comparison showed the Student's Trilemma lacked literature citations, a type-variation subsection equivalent, a stakes-for-rest-of-Part subsection, expanded failure modes (compressed to one paragraph), and a structural-feature observation parallel to the other two. Given that Part I serves ~75% of readers per Mac's audience distribution, the asymmetry was exactly backward of the audience-weighted page budget.

**Process and refinement.** Initial Session 9 plan proposed full structural parity with the other two trilemmas (four student types, two-pronged third corner, full literature dive, etc.). Fresh-eyes self-review caught reflex-toward-symmetry pattern and revised the plan: (1) student-type variation does not carve as discretely as faculty employment status or institutional type, so dimensions-of-variation (continuous pressures that compound) rather than discrete types is more honest; (2) the cognitive-development vs. workforce-preparation tension acute for faculty is less acute for students (who navigate assessments rather than design them), so the third corner can stay single-pronged; (3) Part I already has substantial literature elsewhere, so a smaller targeted dive (2-3 sources specifically on student AI experience) plus weaving existing citations is sufficient; (4) the Student's Trilemma's existing strengths (Wendy case, figure, counter-argument) should be preserved, not layered over. Mac confirmed the revised lighter scope before drafting.

**Targeted literature dive surfaced:** HEPI 2025 student AI survey (92% use, up from 66%), Inside Higher Ed Student Voice 2025 survey (1,047 students), King's Business School disclosure non-compliance study (74% fail to declare AI use), WGU Labs first-generation digital divide study, international-student visa-consequence reporting on AI accusations.

**Session 9 changes:**

**Edit 1 — Restructured Part I: promoted Student's Trilemma from embedded section to its own §sec:trilemma between §sec:outcomes and §sec:learning-science.**

The original Trilemma content lived inside §sec:learning-science as an extended opening before the five learning-science findings. The restructure pulls Wendy, the trilemma definition, the figure, and the counter-argument paragraph into a new dedicated §sec:trilemma section, with substantial new subsection content added. §sec:learning-science is refocused on the five learning-science findings (with Wendy's bridge sentence still opening the section to maintain narrative connection). The new section structure parallels Parts II and III, where the trilemma is a standalone section before the operational content.

**Edit 2 — Literature anchor paragraph added after the figure.**

New paragraph anchors the trilemma in three quantitative findings: HEPI's 92% AI-use statistic (up from 66% in 2024), IHE Student Voice survey showing students want proactive integrity addresses, King's Business School study showing 74% fail to declare AI use due to fear of negative perceptions. Names the structural pattern: "AI use is widespread; honest disclosure is widely avoided; the gap between performance and underlying competence is widely felt but rarely acknowledged."

**Edit 3 — New §subsec:trilemma-failures "Three student failure modes".**

Replaces the previous one-paragraph treatment of all three failure modes with a full subsection that gives each mode its own paragraph. Polished hollow paragraph names the structural feature ("invisible from outside and felt from inside"). Strategic compliance paragraph explains why it is the most common mode (the locally rational response to inconsistent expectations). Honest risk paragraph names the competitive price for transparency. Closes with comparative observation: the three modes are not symmetric in their consequences.

**Edit 4 — New §subsec:trilemma-dimensions "How the trilemma manifests differently for different students".**

Four dimensions of variation walked through with continuous-pressure framing rather than discrete-type typology (per Mac's confirmation of dimensions-of-variation approach): (1) **economic stakes around the grade** — first-generation students face structural pressure with citation to WGU Labs digital divide finding; (2) **consequence severity around honest disclosure** — international students on F-1 visas face SEVIS/deportation consequences plus AI-detection false-positive risk; (3) **career stakes around demonstrated understanding** — pre-professional students (pre-med, pre-law, pre-engineering) feel polished-hollow edge most sharply; (4) **time available for honest risk** — working students and non-traditional students face strategic compliance as structural condition rather than choice. Closes with composite-student observation that pressures compound.

**Edit 5 — New §subsec:trilemma-invisibility "What makes the trilemma hard to see".**

Develops the structural-feature observation parallel to "honest risk is a luxury good in the academy" (Instructor's) and the framework-spine claims (Institution's). Names the load-bearing insight: **"the trilemma is invisible to the people best positioned to remove it."** Explains why each failure mode is structured to be unobservable from the instructor's vantage. Connects to Parts II and III by noting that instructors and administrators face their own version of the same predicament. Counter-argument paragraph (Wendy article's "use a car" question) preserved within this subsection as it fits the invisibility theme.

**Edit 6 — New §subsec:trilemma-stakes "Why the Student's Trilemma matters for the rest of Part I".**

Positions the trilemma as the conceptual spine for the rest of Part I: Learning Spiral as the operational response to honest-risk; CAT framework as the alignment of the three corners; translation test as the polished-hollow diagnostic; disclosure templates as the strategic-compliance pressure reducer. Closes with cross-audience pointer strengthened from the v3.1 version: explicitly names that students learn vocabulary they will see again in inverted forms in Parts II and III.

**Edit 7 — §sec:learning-science refactored to start with bridge sentence and five findings.**

The Wendy bridge sentence ("Wendy's predicament has the shape it does because of how durable learning actually happens") now opens the learning-science section, maintaining narrative continuity from the trilemma section to the principles section.

**Compile state.** Clean 5-pass build (pdflatex / bibtex / pdflatex / pdflatex / pdflatex). 190 pages (+5 from v3.1's 185). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references. Net change: +5 pages, +1225 words.

**Citations.** Four new entries added to LearningWithAI.bib, all tagged `VER:UNVERIFIED 2026-05-22` for Mac's batch verification pass: `hepi2025students` (HEPI 92% AI-use statistic), `insidehighered2025studentvoice` (IHE Student Voice survey on integrity preference), `kings2024disclosure` (King's Business School disclosure non-compliance study), `wgulabs2024divide` (WGU Labs first-generation AI digital divide). Bibliography now contains 12 VER:UNVERIFIED entries pending verification (4 from Session 7 + 4 from Session 8 + 4 from Session 9). All three trilemmas now have parallel citation density.

**Audience-weighted page budget impact.** Part I receives ~75% of reader attention per Mac's distribution. The +5 page addition serves the largest audience and is the most cost-effective per-reader investment among the three Phase 3 trilemma expansions. Phase 3 cumulative impact: Session 7 +3 pp in Part III (5% of readers), Session 8 +5 pp in Part II (20% of readers), Session 9 +5 pp in Part I (75% of readers) for a total of +13 pp across the manuscript. The investment pattern now matches the audience-weighted budget rather than inverting it.

**Files updated:** `learning_with_ai_v3_2.tex`, `learning_with_ai_v3_2.pdf`, `LearningWithAI.bib`. All earlier versions retained for rollback.

**Strategic posture and what's next.**

**Cross-audience trilemma development is now complete at the same standard across all three Parts.** Student's (Part I, ~75% of readers), Instructor's (Part II, ~20%), Institution's (Part III, ~5%) all have:
- Literature-anchored corner definitions
- Three full failure-mode paragraphs with parallel naming (polished hollow / strategic compliance / honest risk, with appropriate prefixes)
- Type or dimensions-of-variation subsection
- Structural-feature observation
- Stakes-for-rest-of-Part subsection
- Cross-audience pointer

Phase 3 work remaining beyond Session 9:
- Drudgery-vs-payoff framing for Part III (Scott #5)
- "Argument chairs need to make to deans" rhetorical pivot (Scott #5)
- Blue category (AIS) expansion across all three Parts (Joshua #3)
- Class-size signposting in Part II opening (Scott #7)
- Empirical citations VER pass (12 UNVERIFIED entries from Sessions 7-9)
- Manuscript-wide polish pass (Joshua #1)
- SPP integration (pending SPP v2.0 from stress-test thread)
- Learning Spiral figure redraw (separate visual-design session)
- Possible compression of Parts I, II, III to manage cumulative page budget

The natural next session is **drudgery-vs-payoff framing for Part III** (item 1), now that all three trilemmas are at the same standard and the framework's conceptual machinery is fully built. Drudgery-vs-payoff operationalizes the Institution's educational-mission corner and gives Part III its rhetorical spine for the rest of Phase 3.

---

## v3.1 — 2026-05-22 (Session 8: Phase 3 cycle — Instructor's Trilemma in Part II + faculty-type variation)

**Trigger.** Session 8 launches the second Phase 3 substantive deliverable: the Instructor's Trilemma. After Session 7 established the Institution's Trilemma with literature-grounded rigor in Part III, the Part II analog (which existed only as a one-paragraph placeholder from Session 6) became the framework's weakest link by structural comparison. Per Mac's Session 7 strategic-pause decision, Phase 3 paused on Part III deepening (drudgery-vs-payoff, chairs-to-deans) to bring Part II up to the same standard before continuing.

**Process.** Faculty-AI-pressure literature dive: Elon/AAC&U survey (1,057 faculty, Oct-Nov 2025), AAUP topical report on AI threats to academic professions, Samuel's faculty typology (Hardliners/Redesigners/Resigned/Disengaged), IHE faculty AI surveys and opinion essays, moral-injury research on Canadian lecturers, faculty-typology literature on tenured vs. contingent labor patterns. Seven themes surfaced: (1) student-overreliance worry, (2) cheating-detection cat-and-mouse exhaustion, (3) faculty typology of postures, (4) time pressure and workload, (5) professional identity and role anxiety, (6) workforce-preparation tension, (7) institutional inconsistency as ambient stressor.

**Framework refinement.** Initial three-corner draft was reviewed and refined twice before adoption. Mac correctly pushed back on whether three corners would compromise precision for cross-Part symmetry. First revision proposed four corners (adding workforce preparation as separate). Second revision (after fresh-eyes self-review) recognized that workforce preparation is not structurally separate from real student learning — it is a contested definition within that corner. Final framing: three corners with the third corner richly two-pronged (cognitive development vs. workforce preparation), preserving the trilemma's geometric elegance and cross-audience symmetry while honestly naming the tension faculty actually report.

**Session 8 changes:**

**Edit 1 — New section §i:sec:trilemma "The Instructor's Trilemma" inserted in Part II, between §i:sec:calibration (the instructor-side calibration problem) and §i:sec:three-axes (Three design axes).**

The new section names the structural predicament faculty navigate under AI pressure, parallel to the Student's Trilemma in Part I and the Institution's Trilemma in Part III. The section opens with a deliberately quiet animating paragraph on the vocational-meaning question ("what am I uniquely for, in a classroom where AI can also explain, also tutor, also assess?") — treated as the existential context that makes the trilemma feel weighty, not as a fourth corner. Mac confirmed this treatment after the framework-refinement discussion.

The three corners are: (1) **Professional sustainability**, capturing manageable workload, contract renewal, tenure case, course evaluations, time for genuine student engagement, and protection against burnout; (2) **Trustworthy professional judgment**, defined as what assessments, grades, feedback, recommendations, and other professional acts of vouching actually signify about students; (3) **Real student learning**, two-pronged definition explicitly naming both cognitive development (reasoning, deeper understanding, AI-independent capability) and workforce preparation (capability in AI-saturated professional environments) as competing-yet-related facets of the same corner. The 95%/63% Elon/AAC&U survey finding is named directly to anchor the third corner's within-corner tension.

**Edit 2 — New subsection §i:subsec:trilemma-failures "Three instructor failure modes" within the new section.**

Develops the three failure modes with parallel naming to the other trilemmas: (a) **instructor polished hollow** (sustainability + trustworthy judgment without real learning) — defensive teacher with blue books and over-constrained assignments; (b) **instructor strategic compliance** (sustainability + real learning without trustworthy judgment) — AI-integrated teacher whose grades cannot be defended in conversation; (c) **instructor honest risk** (trustworthy judgment + real learning without sustainability) — exhausted exemplar who burns out holding standards. The AAUP work-intensification framing is invoked as the labor-level description of the honest-risk pattern.

**Edit 3 — New subsection §i:subsec:trilemma-by-type "How the trilemma manifests differently by faculty type".**

Four faculty types walked through, with type-specific trilemma pull strengths: (1) **Tenured faculty with reasonable course loads** — most freedom across all corners; honest-risk is the failure mode they can afford and sometimes consciously choose; (2) **Tenure-track faculty** — sustainability dominates because tenure case is at stake; polished-hollow is the most relevant risk through defensive pedagogy; (3) **Full-time non-tenure-track** (lecturers, clinical faculty, teaching-stream professors) — mixed trilemma; strategic compliance risk when teaching loads exceed verification capacity; (4) **Adjunct and per-course contingent faculty** — sustainability dominant in non-moralizable way; strategic compliance is the failure mode they often inhabit without meaningful choice. Section names a structural feature directly: **"honest risk is a luxury good in the academy."** Closes with brief acknowledgment that the typology is not comprehensive (graduate-student instructors, postdocs, emeriti; discipline matters too).

**Edit 4 — New subsection §i:subsec:trilemma-stakes "Why the Instructor's Trilemma matters for the rest of this Part".**

Positions the trilemma as the conceptual spine for the rest of Part II: the assessment models (Oral-Defense, Evidence-of-Thinking, Hybrid), the CAT framework, and the fair response sequence all become tools for holding the three corners together rather than a list of best practices. Names the rhetorical purpose explicitly: the framework surfaces the structure beneath individual instructor stories.

**Edit 5 — Updated §i:sec:integrity faculty AI use paragraph (replaces Session 6 placeholder).**

The Session 6 sketchy "instructor analog of the Student's Trilemma" paragraph (~110 words) was replaced with a forward-pointer paragraph (~95 words) that references the new §i:sec:trilemma and re-reads the Northeastern case through the trilemma frame as a trustworthy-judgment failure. The substantive trilemma content now lives in one canonical location rather than being duplicated.

**Compile state.** Clean 5-pass build (pdflatex / bibtex / pdflatex / pdflatex / pdflatex). 185 pages (+5 from v3.0's 180). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references. Net change: +5 pages, +1860 words.

**Citations.** Four new entries added to LearningWithAI.bib, all tagged `VER:UNVERIFIED 2026-05-22` for Mac's batch verification pass: `elon2026faculty` (Elon/AAC&U survey for 95% statistic), `aaup2025ai` (AAUP topical report for work intensification framing), `insidehighered2026defense` (IHE opinion essay for blue-books-or-early-retirement pattern), `samuel2025retrospective` (Samuel's faculty typology Substack for the "blind AI use collapses under its own weight" phrase). Bibliography now contains 8 VER:UNVERIFIED entries pending verification (4 from Session 7 Institution's Trilemma + 4 from Session 8 Instructor's Trilemma).

**Audience-weighted page budget impact.** Part II receives ~20% of reader attention per Mac's distribution. The +5 page addition is large for Part II in absolute terms but proportional to the framework's centrality. Combined with Session 7's +3 pages in Part III, Phase 3 has now added +8 pages total to the manuscript across two structural framework additions. Mac confirmed in Session 7 that the Trilemma viewpoint earned the extra Part III pages; similar reasoning applies to Part II. Future v3.x sessions may tighten weaker material in both Parts if desired.

**Files updated:** `learning_with_ai_v3_1.tex`, `learning_with_ai_v3_1.pdf`, `LearningWithAI.bib`. All earlier versions retained for rollback.

**Strategic posture and what's next.**

Phase 3 cross-audience trilemma development is now complete. All three trilemmas (Student's in Part I, Instructor's in Part II, Institution's in Part III) are at the same standard of literature-grounded rigor, with parallel three-corner / three-failure-mode / type-variation structure. Cross-Part symmetry is preserved while each trilemma is appropriately tailored to its audience.

Phase 3 work remaining beyond Session 8:
- Drudgery-vs-payoff framing for Part III (Scott #5) — operationalizes the Institution's educational-mission corner
- "Argument chairs need to make to deans" rhetorical pivot (Scott #5)
- Blue category (AIS) expansion across all three Parts (Joshua #3)
- Class-size signposting in Part II opening (Scott #7)
- Manuscript-wide polish pass: should-reduction, list-density audit, repetition reduction (Joshua #1)
- SPP integration (pending SPP v2.0 from stress-test thread)
- Learning Spiral figure redraw (separate visual-design session)
- Empirical citations for Sessions 7 and 8 prose (VER verification of 8 UNVERIFIED entries)
- Possible compression of Part III and Part II to manage page budget

External-input gates that are NOT blocking Phase 3 work:
- Reader feedback from Scott and others (one input among many; Phase 3 proceeds in parallel)
- SPP v2.0 from stress-test thread (gates SPP integration specifically; does not gate other work)

---

## v3.0 — 2026-05-22 (Session 7: Phase 3 launch — Institution's Trilemma + institutional-type variation)

**Trigger.** Session 7 launches Phase 3 v3.0 work. After Mac confirmed that Scott's Part III feedback is "not a decision point for going forward" (multiple readers expected over coming weeks), Phase 3 begins immediately rather than waiting on any single reader. The session targets the highest-conceptual-leverage v3.0 item: introducing the Institution's Trilemma as the missing structural framework for Part III's analysis.

**Process.** Before drafting, conducted a literature dive into administrator-targeted AI discourse to ground the trilemma's three corners in what administrators actually report worrying about. Sources surveyed: EDUCAUSE 2025 Technology Leadership Workforce report, Inside Higher Ed 2026 Survey of College and University Presidents, EDUCAUSE Review essays (Maksl, "A More Human University"), Arthur Levine's "From Upheaval to Action" framing, the Rees et al. Nature paper on agentic AI threats to grant funding (NIH "Apply Responsibly" directive), AACC commentary on community college trust, and presidents' essays from Tania Tetlow (Fordham), Greg Weiner (Assumption), Daniel Hendrickson (Creighton), and others. The dive surfaced five concerns administrators consistently raise: (1) public trust and legitimacy, (2) enrollment cliff and fiscal sustainability, (3) workforce displacement and faculty role anxiety, (4) academic integrity and the credential's meaning, (5) research integrity and grant funding (research universities only). Mac refined the corner labeling so that "Institutional sustainability" explicitly couples financial viability with public legitimacy (rather than treating these as separate concerns).

**Posture.** This is the first Phase 3 release. v3.0 is the new version label for Phase 3 work, mirroring how v2.x labeled Phase 2 work across multiple sessions. Phase 3 will continue across subsequent sessions (v3.1, v3.2, etc. or remain in v3.0 working state per Mac's preference). The Institution's Trilemma section is the conceptual spine for Phase 3's Part III work; subsequent v3.x sessions will develop the drudgery-vs-payoff framing (Scott #5), the chairs-to-deans argumentative structure (Scott #5), the Instructor's Trilemma (cross-audience symmetry), Blue category development (Joshua #3), class-size signposting (Scott #7), and the manuscript-wide polish pass (Joshua #1).

**Session 7 changes:**

**Edit 1 — New section §u:sec:trilemma "The Institution's Trilemma" inserted in Part III, between §u:sec:outcomes and §u:sec:problem.**

The new section names the structural predicament administrators navigate under AI pressure, parallel to (and explicitly mirroring) the Student's Trilemma introduced in Part I. The three corners are: (1) **Institutional sustainability**, defined to couple financial viability with public legitimacy explicitly so readers cannot separate them (per Mac's framing decision; the corner captures both faces of the same problem since public skepticism erodes enrollment, falling enrollment erodes funding, falling funding erodes the institution's ability to make the case for its own value); (2) **What the credential certifies**, the degree as a meaningful claim about graduates that depends on both the institution's testimony and the underlying evidence; (3) **Educational mission**, the deeper commitment to what students gain by attending, varying by institutional type but always present.

The three failure modes deliberately echo the Student's Trilemma's three failure modes: **institutional polished hollow** (sustainability + credential without mission), **institutional strategic compliance** (sustainability + mission without credential), **institutional honest risk** (credential + mission without sustainability). The naming creates cross-audience symmetry that gives readers who move between Parts a consistent vocabulary.

**Edit 2 — New subsection §u:subsec:trilemma-failures "Three institutional failure modes" within the new section.**

Develops each of the three failure modes as a substantive paragraph, with concrete description of what each looks like in practice. The institutional honest-risk failure mode references the closure pattern of small private tuition-dependent colleges in recent years.

**Edit 3 — New subsection §u:subsec:trilemma-by-type "How the trilemma manifests differently by institutional type".**

Four institutional types walked through, with the same trilemma corners showing different pull strengths at each:

- **R1 private research universities** (Stanford, Duke, Tulane) — credential is the brand; mission is dual research/liberal; institutional polished-hollow is the most relevant failure mode; agentic-AI grant-funding pressure adds an institution-specific complication
- **Wealthy liberal arts colleges** (Williams, Pomona, Kenyon) — credential and mission tightly coupled (the case for the institution IS the case for the human-led residential experience); sustainability is the threatening corner; institutional honest-risk failure mode is the most visible
- **Regional public universities** — sustainability dominates due to enrollment cliff + funding cuts; mission framed in workforce-alignment terms; institutional strategic-compliance failure mode is the most relevant risk
- **Community colleges** — flatter trilemma overall; strong public trust insulates somewhat; mission articulated as access + workforce alignment; credential question is dominated by credit transferability; least vulnerable to honest-risk pattern

Closes with brief acknowledgment that the typology is not comprehensive (HBCUs, religious-affiliated, for-profit, fully online institutions face the same trilemma with type-specific pull strengths).

**Edit 4 — New subsection §u:subsec:trilemma-stakes "Why the Institution's Trilemma matters for the rest of this Part".**

Positions the trilemma as the conceptual spine for the rest of Part III: the assessment models, integrity procedure, faculty change management, and implementation phases are tools for holding the three corners together under AI pressure. Connects forward to the existing §u:sec:problem section by re-reading the Northeastern case as an early signal of the institutional polished-hollow pattern.

**Compile state.** Clean 5-pass build (pdflatex / bibtex / pdflatex / pdflatex / pdflatex for cross-reference settling). 180 pages (+3 from v2.15's 177). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references. Net change: +3 pages, +1413 words.

**Citations and verification posture.** The new section was drafted without footnotes for substantive empirical claims (college closure patterns, grant-funding strain, community college trust). The literature dive surfaced relevant sources (Rees et al. 2026 Nature on agentic AI grant funding, AACC president Pollard on community college trust, Inside Higher Ed 2026 presidents survey, Levine 2026 forthcoming on reform), but these need proper VER verification before being added to LearningWithAI.bib. A future verification session should add these citations to the new prose. The trilemma framework itself is a conceptual contribution that does not require citation; the supporting empirical claims do.

**Audience-weighted page budget impact.** The original Session 3 strategic review set Part III's ceiling at current ~40 pages, with v3.0 work to be REORGANIZATION not accretion. The Session 7 work added ~3 pages of new Trilemma content without compressing existing Part III material. Honest assessment: **Part III is currently +3 pages over the original budget.** Future v3.x sessions should plan compression of weaker Part III material to bring the page count back to the original ceiling, OR Mac may decide the Trilemma's value justifies the larger Part III. The framing decision was Mac's; the budget overrun is flagged here for transparency.

**Files updated:** `learning_with_ai_v3_0.tex`, `learning_with_ai_v3_0.pdf`. v2.15 retained as Phase 2 complete baseline; v2.13 retained as Scott's Monday Part III reading version; v2.12 retained as deep rollback.

**Strategic posture and what's next.**

Phase 3 v3.0 is now in flight. The Institution's Trilemma provides the conceptual spine for the rest of Phase 3's Part III work. The natural next session targets the drudgery-vs-payoff framing (Scott #5) which operationalizes the educational-mission corner: the institution's case for itself rests on the claim that some of the learning is itself the payoff, not a means to an end. After that, the chairs-to-deans argumentative structure becomes the rhetorical pivot for the rest of Part III.

Phase 3 work remaining beyond Session 7:
- Drudgery-vs-payoff framing for Part III (Scott #5)
- "Argument chairs need to make to deans" rhetorical pivot (Scott #5)
- Cross-audience expansion: Instructor's Trilemma in Part II
- Blue category (AIS) expansion across all three Parts (Joshua #3)
- Class-size signposting in Part II opening (Scott #7)
- Manuscript-wide polish pass: should-reduction, list-density audit, repetition reduction (Joshua #1)
- SPP integration (pending SPP v2.0 from stress-test thread)
- Learning Spiral figure redraw (separate visual-design session)
- Empirical citations for Session 7 Trilemma prose (VER verification of Rees, Pollard, Levine, IHE presidents survey)

External-input gates that are NOT blocking Phase 3 work:
- Scott McKinley's Part III feedback (not a decision point per Mac's 2026-05-22 clarification; one valued reader among many expected over coming weeks)
- SPP v2.0 from stress-test thread (gates SPP integration specifically; does not gate other v3.0 work)

---

## v2.15 — 2026-05-22 (Session 6: Phase 2 complete — translation test expansion, conscientious-objector subsection, faculty AI use, equity acknowledgment)

**Trigger.** Session 6 of Phase 2 v2.14 cycle, batching the four remaining substantive prose items (Tiers 2–3 per the two-session execution plan recommended after Session 5). All four items are smaller-scoped than the configuration elevation in Session 5; together they close out Phase 2. v2.15 is the Phase 2 release: framework renames (Session 4-A) + configuration elevation (Session 5) + four prose items (Session 6) integrated into a single coherent vocabulary-tightening and prose-addition release that converts the v2.13 manuscript into the substantially revised v2.15.

**Posture.** Phase 2 v2.14 cycle complete. The four Session 6 items honored their word-cap constraints (per Session 3 audience-weighted strategic review: Faculty AI use ≤250 words; Equity acknowledgment 100–150 words; Conscientious-objector subsection ~200 words; Translation test expansion ~150–250 words). Net Session 6 addition: +675 words. v2.15 total page count: 177 (+1 from v2.14 Session 5's 176, +4 from v2.13's 173). All v3.0 work (Part III reframe, Blue category development, cross-audience Trilemma expansion, polish pass, SPP structural integration) remains pending and is gated on Scott McKinley's Part III feedback (expected after his Monday Part III reading of v2.13).

**Session 6 changes:**

**Edit 1 — Translation test expansion to three-modality framing (Scott #1, Part I §sec:compact line 650).**

The translation test's primary definition was rewritten to introduce the three-modality form (visual, mathematical, plain language) as the broadest version of the test, with notation change positioned as one specific case rather than the test's central form. Scott McKinley's meeting feedback drove this expansion: he challenged the notation-change framing as insufficient ("I don't know that I would say that changing the notation would be sufficient") and proposed the three-modality alternative from his own undergraduate teaching practice ("can you say it three ways. One is visually, one is mathematically, and one is in plain language"). The new definition uses three paragraphs: (1) the three-modality test as the broadest form, with concrete examples for each mode; (2) the notation-change case as a specific instance, with explicit acknowledgment that a student who can rewrite $f(x)$ as $g(t)$ has shown only one form of recognition; (3) the plain-language axis for non-mathematical work, which is how the test usually runs outside mathematics.

The Part I cross-reference at §sec:compact (line 1216) was updated to mention the three-modality form briefly. The Part II reference at line 1912 (the symmetric translation test for instructor AI use) was updated implicitly through the Session 6 Edit 3 (faculty AI use expansion) which now uses "translate AI-assisted course material into their own language, with their own examples, in their own structure" as the standard. Other cross-references (Part III references at lines 3053 and 3297) retain the original concise wording since they are brief mentions, not definitional.

Glossary entry was already updated in Session 4-A with the three-modality framing; the in-text definition now catches up to the glossary.

**Edit 2 — Conscientious-objector subsection added (Scott #6, Part I §subsec:conscientious-objector, inserted in §sec:when-not-to-use).**

A new ~220-word subsection acknowledges the constituency Scott raised in his meeting: students who decline AI use on environmental, labor, or ethical grounds, including the stronger position taken in some fields ("there is no ethical use of AI in their discipline at the present moment"). The subsection is deliberately respectful and does not attempt to convince conscientious objectors to use AI. Instead, it explains how the book's framework still applies to them in a different way: every assignment is implicitly \NAI{} for these students; the Learning Spiral is the practice they were already going to use; the Student's Trilemma is the predicament they are still asked to navigate when peers are using AI freely. The framework gives these students vocabulary for situations they will encounter (grading curves shaped by tools they do not use, group projects where teammates do, courses where the instructor assumes AI use without saying so). Cross-reference to Part III for institutional policy implications.

**Edit 3 — Faculty AI use expanded (Joshua #4, Part II §i:sec:integrity, expanded from 3 paragraphs to 4 paragraphs).**

The existing Northeastern paragraph + symmetric translation test argument (~130 words) was expanded to a ~380-word treatment that develops the symmetric application of the book's standards to instructor AI use, while respecting the ≤250-word cap per audience-weighted strategic review (Part II = ~20% of readers). The expansion adds: (1) the instructor analog of the Student's Trilemma (faculty navigate competing pulls between efficient course-material production, demonstrating the standards they ask of students, and modeling teaching that produces real learning); (2) the translation test as a private check faculty can run on their own AI-assisted course material before placing it in front of students; (3) the analog of the polished hollow as "course material the instructor cannot stand behind in conversation"; (4) a forward-pointer to Part III for the response-sequence question (what response sequence applies when faculty use AI without disclosure or in ways that contradict their own policies). The cross-audience Trilemma expansion (Instructor's Trilemma, Institution's Trilemma as named frameworks) remains deferred to v3.0 per the original plan; this expansion uses "instructor analog" language without claiming a named framework that v3.0 will develop more formally.

**Edit 4 — Equity acknowledgment expanded (Joshua #6, Part II §i:sec:oral-defense-model, complementary follow-on paragraph).**

The existing equity paragraph (~130 words, addressing multilingual students, shy students, neurodivergent students, and students who need a moment to organize their explanation) was complemented with a new ~140-word paragraph addressing two additional considerations: (1) students with documented accommodations through institutional disability services (anxiety disorders, students who use augmentative communication, students who are deaf or hard of hearing) may need formats beyond the spoken-aloud audit, with concrete alternatives (short written explanation, signed conversation, typed exchange, recorded video with subtitles); (2) the right to request alternative formats should extend beyond formal accommodation letters, since some students whose understanding is sound will struggle in live questioning for reasons that do not appear on any accommodation letter. The expansion respects the 100–150 word cap per audience-weighted strategic review.

**Compile state.** Clean 5-pass build (pdflatex / bibtex / pdflatex / pdflatex / pdflatex for cross-reference settling). 177 pages, 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references, 0 multiply-defined labels. Net change from v2.14 Session 5: +1 page, +675 words.

**Word count summary across Phase 2:**

| Source | Words added | Pages |
|---|---|---|
| Session 4-A framework renames + glossary consolidation | +680 | +1 |
| Session 5 configuration elevation + friction-wall | +564 | +2 |
| Session 6 four prose items | +675 | +1 |
| **Phase 2 total (v2.13 → v2.15)** | **+1,919** | **+4** |

The Phase 2 total falls within the projected 1,600–2,500 word v2.14 budget from Session 3 strategic review. Net page change is +4 pages (173 → 177), well below the projected upper bound of 180–185 pages. The audience-weighted page budget held: Part I gained the most prose (configuration elevation, translation test expansion, conscientious-objector subsection); Part II received targeted but capped additions (faculty AI use, equity expansion); Part III gained only one sentence (institutional baseline configuration).

**Files updated:** `learning_with_ai_v2_15.tex`, `learning_with_ai_v2_15.pdf`. v2.14 retained in outputs for rollback; v2.13 retained as Scott's Monday Part III reading version; v2.12 retained as deep rollback.

**Strategic posture and what's next.**

v2.15 represents the completion of Phase 2 v2.14 (the cycle that began with vocabulary tightening and continued through substantive prose). The next strategic gate is Scott McKinley's return of Part III feedback after his Monday reading of v2.13. Until that feedback arrives:

- v2.15 is the canonical working version; no further substantive prose is planned without external input
- The pending v2.14 work that did not land in v2.15 (SPP integration, Learning Spiral figure redraw) is deferred to natural future sessions when its inputs arrive (SPP v2.0 from stress-test thread; visual-design session for the figure)
- Phase 3 v3.0 work (Part III reframe around "argument chairs need to make to deans," cross-audience Trilemma expansion, Blue category development, polish pass, class-size signposting) is gated on Scott's Part III feedback

When Mac wants to send Scott a "your feedback shaped this" followup after Scott returns Part III feedback, three pieces of evidence will be visible: the configuration elevation (Scott's "scripts didn't echo my experience" diagnosis), the translation test expansion (Scott's "say it three ways" framing), and the conscientious-objector subsection (Scott's "no ethical use" observation). Two further pieces—the faculty AI use expansion (Joshua's #4) and the equity expansion (Joshua's #6)—reflect Joshua Agbomola's earlier review and will be visible to him as well.

**What remains tracked but not in v2.15 (pending external input):**

| Task | Source | Gating event |
|---|---|---|
| SPP integration (operational + forward-pointer in §sec:setup) | Session 3 plan | SPP v2.0 from stress-test thread |
| Learning Spiral figure redraw | Session 4-A deferral | Visual-design session |
| v3.0 Part III reframe (drudgery-vs-payoff + Institution's Trilemma + chairs-to-deans framing) | Scott #5 | Scott's Part III feedback |
| v3.0 Blue category development | Joshua #3 | Open (likely after Scott Part III feedback) |
| v3.0 cross-audience Trilemma expansion | Session 3 plan | After Scott Part III feedback |
| v3.0 class-size signposting in Part II | Scott #7 | Open |
| v3.0 polish pass (should-reduction, list-density audit, repetition reduction) | Joshua #1 + audit | After v3.0 substantive work |

---

## v2.14 (Session 5) — 2026-05-22 (Configuration elevation + friction-wall integration)

**Trigger.** Session 5 of Phase 2 v2.14 cycle. Tier 1 substantive prose work: configuration elevation (Scott #2 + Scott #4) consolidated with friction-wall integration (Joshua #2) per Session 3 strategic-review consolidation decision. Single coherent treatment in §sec:setup with unified opening framing, new worked before/after subsection, friction-wall pattern naming, and brief Part III institutional baseline-configuration touchpoint. v2.14 file remains the working state; v2.15 release deferred to end of Session 6 when remaining Phase 2 prose lands.

**Posture.** Highest-leverage remaining v2.14 item executed as dedicated session. Scott explicitly identified this as a critical gap during his 2026-05-22 meeting ("I think that could have... that could increase the impact quite a bit"). The Session 5 work elevates configuration from a brief appendix mention to substantive Part I central content, makes the configuration step's payoff striking and concrete via a worked before/after example, names the friction-wall pattern explicitly (Joshua #2) within the same coherent treatment, and adds a single sentence to Part III about institutional baseline configurations during AI-literacy onboarding.

**Session 5 changes:**

**Edit 1 — Unified opening framing for §sec:setup (Part I, replaces three opening paragraphs).**

The previous opening had four paragraphs introducing configuration as the simplest form of pre-AI preparation. The new opening replaces three of those four paragraphs with a tighter, more strategically framed three-paragraph opening: (a) the two-precondition framing ("Two things matter before you ask AI anything for coursework: that you have configured your AI to behave the way this guide's scripts assume, and that you have made an honest attempt at the problem yourself"); (b) the configuration explanation (defaults are "tuned to be impressive in a demo, not designed for learning"); (c) the friction-wall pattern naming (the second precondition, with the failure pattern explicitly called the "friction-wall failure"). The closing line "When using AI, the prompt matters, but the preparation matters more" was kept and reframed as a standalone sentence that bridges to the practical configuration mechanics in the unchanged subsequent paragraphs.

Rationale: Scott's diagnosis was that the book's scripts don't echo his teaching experience because students without configuration get verbose default AI behavior; without elevating configuration to a foundational concern, the book's operational claims have an implicit footnote. The unified framing also closes Joshua #2 (friction-wall) by consolidating both pre-AI failure modes into one coherent treatment — the consolidation decision from Session 3 strategic review.

**Edit 2 — New subsection §subsec:config-before-after (Part I, "Why this step matters: a before-and-after").**

Inserted between the existing template-pointer paragraph and the existing "The prompt is only the visible part" subsection. Contains a concrete worked example: a calculus student asks "Help me find the limit of $(\sin x)/x$ as $x \to 0$." Two AI responses are shown side-by-side. The default (untuned) AI answers immediately with three proofs the student did not ask for. The configured AI asks back: "What have you tried so far? If you graph $y = \sin(x)/x$ near $x = 0$, what value does the curve appear to approach?" The contrast makes the configuration step's cost (ten minutes) and payoff (every subsequent conversation pitched closer to the student's level) striking and concrete. Added a brief practical note at the end addressing what to do if default-style verbose responses return despite configuration (session-boundary effects, platform updates resetting settings).

Rationale: Scott's feedback was specifically that the scripts "didn't echo my experience." A worked example demonstrates the configuration claim rather than asserting it. The before/after structure makes the diagnosis concrete and the remedy tangible.

**Edit 3 — Friction-wall glossary entry (Part I glossary).**

Added in alphabetical position between "Evidence of thinking" and "Generated citation." Brief definition matching the in-text introduction at line 467: "The failure pattern produced when a student reaches for AI before making a real attempt at the problem. They recognize the AI's solution but cannot generate the analogous one on their own, and often cannot tell the difference. Named for the moment of productive difficulty that AI use can short-circuit." Maintains glossary alphabetical structure established in Session 4-A.

**Edit 4 — Part III institutional baseline-configuration touchpoint (§u:subsec:student-training).**

Appended one sentence to the existing student-training subsection in Part III: "Institutions can reduce friction further by providing a recommended baseline AI configuration---a starter set of personal preferences students can adopt during orientation---since most students do not configure their AI accounts without prompting and benefit substantially from doing so." This is a deliberately small institutional-level touchpoint, not a developed section — consistent with the audience-weighted page budget (Part III serves ~5% of readers; institutional treatments are kept compact).

**SPP forward-pointer NOT added.** SPP integration as substantive subsection requires SPP v2.0 from the stress-test thread (per Session 3 plan). Even a one-sentence forward-pointer was deferred until SPP v2.0 stress-test feedback is available to ensure the pointer's framing aligns with the polished artifact. Will be added when SPP v2.0 arrives.

**Compile state.** Clean 4-pass build (pdflatex / bibtex / pdflatex / pdflatex). 176 pages (+2 from v2.14 Session 4-A's 174). 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references, 0 multiply-defined labels. Net change: +2 pages, +564 words.

**Word count tracking.**

| Source | Words added |
|---|---|
| Unified opening (replaced 3 paragraphs) | +200 |
| Worked before/after subsection | +280 |
| Friction-wall glossary entry | +50 |
| Part III institutional sentence | +50 |
| **Total Session 5 net additions** | **+580 ≈ +564 measured** |

Slightly over the ~400–500 target from Session 3 strategic review; the practical-note paragraph at the end of the worked-example subsection accounts for the ~80-word overrun and provides genuinely useful troubleshooting guidance.

**Files updated:** `learning_with_ai_v2_14.tex`, `learning_with_ai_v2_14.pdf`. v2.14 (Session 4-A baseline) NOT retained separately — Session 5 builds directly on the Session 4-A v2.14 baseline.

**Strategic posture:** v2.13 remains Scott's Monday Part III reading version (unchanged). v2.14 (Session 5) is the working file for remaining Phase 2 prose. When Mac wants to send Scott a "your feedback shaped this" followup after Scott returns Part III feedback, the configuration elevation is the single most visible piece of evidence — Scott will recognize his exact words ("the scripts didn't echo my experience") reflected in the new section's purpose, even though the new prose doesn't quote him.

**What remains for v2.15 release (Session 6):**

| Task | Source | Word target | Part |
|---|---|---|---|
| Translation test expansion (say-it-three-ways) | Scott #1 | ~150–250 | Part I |
| Conscientious-objector subsection | Scott #6 | ~150–200 | Part I |
| Faculty AI use (capped) | Joshua #4 | ~250 | Part II |
| Equity acknowledgment (capped) | Joshua #6 | ~100–150 | Part II |

Total Session 6 projection: ~650–850 added words. Phase 2 v2.14 complete at end of Session 6; release as v2.15.

---

## v2.14 — 2026-05-22 (Session 4-A: four framework renames + glossary consolidation)

**Trigger.** Session 4-A of Phase 2 v2.14 cycle. Mac confirmed Option A: execute the four framework renames as a single coherent vocabulary-tightening release, paired with Joshua #7 glossary consolidation, with the Learning Spiral figure redraw deferred to a separate session. All four renames were workshopped and decided in Session 3 before execution.

**Posture.** Coherent vocabulary tightening. v2.14 announces itself as the release that consolidates the book's distinctive contributions into single precise words. Substantive prose additions (configuration elevation, translation test expansion, conscientious-objector subsection, faculty AI use, equity acknowledgment, SPP integration) remain pending for Session 5+ and will apply to v2.14 as base. Net page change from v2.13: +1 page (173 → 174).

**Framework rename 1 — Assignment categories: Red/Yellow/Green/Blue → \NAI{}/\AIT{}/\AIC{}/\AIS{}.**

The four color-based assignment-category labels were converted to colored mnemonic acronyms. Each acronym is rendered in its category color throughout the manuscript via LaTeX macros (`\NAI`, `\AIT`, `\AIC`, `\AIS`), making the categories more accessible to skimming readers and more screen-reader-friendly than pure color references. Three colors sit on a traffic light (\NAI{} red = stop, \AIT{} yellow = proceed with care, \AIC{} green = go); \AIS{} is blue, deliberately off the traffic light, because the question changes — \AIS{} asks what AI is *doing* rather than how much AI freedom the assignment allows. The first-definition passage in Part I (§sec:assignment-categories) was rewritten to introduce all four with the traffic-light framing and the AIS-as-different-sign framing as a unified explanation rather than separate definitions. Approximately 150 substitution sites across Parts I, II, III, the syllabus table, the assignment-color-tree figure, and the Part I glossary. Color definitions live in the preamble (catNAI/AIT/AIC/AIS RGB values) so future adjustments propagate everywhere from a single edit.

**Framework rename 2 — Umbrella framework: C/A/R → CAT.**

Three substitutions applied throughout the manuscript: C/A/R → CAT (28 sites), AI-Augmented Practice → AI-assisted Practice (25 sites), Responsible Judgment → Trustworthiness (27 sites). The CAT acronym spells a real word (in the same way SMART goals do), is plainer than the previous slash-separated abbreviation, and integrates better in prose. The component changes are also load-bearing: "AI-assisted" is plainer than "AI-Augmented" (which read as marketing-adjacent), and "Trustworthiness" is more concrete and reader-facing than "Responsible Judgment" (which read as administrative-speak). pdfkeywords updated to include "CAT framework." The M/A/E translation table received one careful update: the right-column letter abbreviations now correctly show (T) instead of (R) for Trustworthiness, both in the table and in the M/A/E→CAT bridge figure (fig:car-mae). M/A/E lineage in Appendices A and B preserved intact per the rename plan.

**Framework rename 3 — Five-step practice: AI Learning Loop → Learning Spiral.**

13 sites updated, including section heading, figure caption, glossary entry, all cross-references, and three Part II references. The opening paragraph of the Learning Spiral section gained an explanatory clause: "each pass through them should deepen what you understand rather than return you to the same place---this is why the framework is called a spiral rather than a loop." The figure caption was rewritten to acknowledge the spiral concept while the figure itself remains a closed-cycle drawing (per Mac's explicit confirmation, figure redraw is deferred to a separate session). The figure caption now reads: "The figure shows the five-step structure; the framework is a spiral rather than a closed cycle because each pass should build on the last." "Closes the loop" updated to "closes the pass" in the learning-science cross-reference passage. The figure label (`fig:learning-loop`) was deliberately preserved as an internal-only ID to avoid breaking cross-references; the section label `sec:learning-loop` was likewise preserved.

**Framework rename 4 — Predicament diagnosis: Honest-A Bind → Student's Trilemma.**

Three substitution sites: first-use definition in Part I (§subsec:wendy), figure caption, and Part II translation-test cross-reference. The first-use definition was rewritten to include the horn-metaphor inline gloss: "Call it the Student's Trilemma: a three-way pull, like a dilemma but with one more horn, among earning the grade, being honest about how the work happened, and demonstrating genuine understanding." The figure caption's closing clause "AI sharpens each edge; it did not create the bind" was updated to "it did not create the trilemma" for internal consistency, and the paragraph following the figure ("The bind has three structural failure modes") was updated to "The trilemma has three structural failure modes." The three failure mode names (polished hollow, strategic compliance, honest risk) are unchanged. The figure label `fig:honest-a-bind` was preserved as internal-only. Cross-audience expansion (Instructor's Trilemma in Part II, Institution's Trilemma in Part III) is deferred to v3.0 per the original plan; the line at §sec:trilemma-introduction promising "the same taxonomy applies in inverted forms to instructors and to institutions" remains as the forward-pointer.

**Joshua #7 — Glossary consolidation completed.**

The Part I glossary (§app:glossary, ~21 entries) was reorganized alphabetically and expanded to include all new framework terminology. New entries added: AI-assisted Practice (CAT component), Polished hollow (Trilemma failure mode), Strategic compliance (Trilemma failure mode), Student's Trilemma (with horn-metaphor inline definition), Translation test (with three-modality expansion preview pointing forward to Scott #1 v2.14+ work), Trustworthiness (CAT component). Existing entries updated to match new vocabulary: CAT framework (already updated), Core Competence (clarified as CAT's first component), Learning Spiral (added spiral-vs-loop explanation), Assignment categories (added traffic-light explanation noting AIS as off-spectrum), Verification (linked to Trustworthiness as the act that drives it). Entries remain in alphabetical order throughout. Other glossaries elsewhere in the manuscript (Parts II and III have local glossaries) were not consolidated in this pass — the Part I glossary is the canonical reference; cross-Part glossary unification deferred to v3.0 polish pass.

**LaTeX preamble additions (Session 4-A).**

Four new color definitions for the colored-acronym scheme: `catNAI` (RGB 180,30,30 red), `catAIT` (RGB 180,135,0 amber for print readability), `catAIC` (RGB 30,130,60 green), `catAIS` (RGB 25,70,120 blue). Four macros `\NAI`, `\AIT`, `\AIC`, `\AIS` each render the bold colored acronym from a single point of definition, so any future color adjustment propagates globally. The TikZ figure assignment-color-tree leaf nodes use `\textcolor{catNAI/AIT/AIC/AIS}{\textbf{...}}` directly to maintain visual consistency with the inline macros.

**M/A/E preservation verification.**

The M/A/E lineage in Appendices A (Graduate Mathematical Intelligence Profile) and B (AI-Integrated Graduate Mathematics Assessment Framework) is intact: Mathematical Understanding (M) appears 4 times, AI-Augmented Mathematical Skill (A) 2 times, Epistemic and Ethical Responsibility (E) 3 times, M/A/E (as abbreviation) 8 times. The M/A/E → CAT translation table in the Foreword/Introduction reflects the new right-column vocabulary with corrected letter abbreviations.

**Compile state.** Clean 5-pass build (pdflatex / bibtex / pdflatex / pdflatex / pdflatex for cross-reference settling). 174 pages, 0 errors, 0 LaTeX warnings, 0 undefined citations, 0 undefined references, 0 multiply-defined labels. Net change from v2.13: +1 page, +36 lines, +680 words.

**What remains for v2.14 (Session 5+).**

Substantive prose additions awaiting future sessions:
- Translation test expansion: "say it three ways" three-modality reformulation (Scott #1) — ~150–250 added words in §sec:translation-test
- Configuration elevation + friction-wall integration (Scott #2+#4 consolidated with Joshua #2) — ~400–500 added words in §sec:setup
- Conscientious-objector subsection (Scott #6) — ~150–200 words in Part I
- Faculty AI use (Joshua #4) — capped at ~250 words in Part II
- Equity acknowledgment (Joshua #6) — capped at ~100–150 words in Part II
- SPP integration (pending SPP v2.0 from stress-test thread)
- Learning Spiral figure redraw — deferred to a separate visual-design session

**Files updated:** `learning_with_ai_v2_14.tex`, `learning_with_ai_v2_14.pdf`. v2.13 source retained in outputs for rollback.

**Strategic posture:** Scott will read Part III from v2.13 starting Monday. v2.14's vocabulary changes do NOT affect his reading; he is reading the v2.13 release which keeps Honest-A Bind, AI Learning Loop, C/A/R, and Red/Yellow/Green/Blue. The framework renames in v2.14 will become visible to him only after he completes his Part III feedback and a future release incorporates that feedback. This sequencing was deliberate (decided Session 3) to keep Scott's reading vocabulary consistent.

---

## v2.13 — 2026-05-22 (Phase 1 complete: pre-Scott edits + empirical audit + acknowledgments)

**Trigger.** Session 3 Phase 1 v2.13 cycle: four prose edits across two sub-phases. The first sub-phase (two targeted edits to v2.12 — Hamming quotation and mathematics hypothesis prompt) was completed earlier in Session 3 before the Scott McKinley meeting. The second sub-phase (empirical-claim audit, Bastani Turkey clarification, restructured acknowledgments) was completed after the meeting. All four edits land in v2.13 as a single release; the manuscript is now ready for Scott's Monday Part III reading.

**Posture.** All edits are surgical prose changes; no structural changes. The framework renames (NAI/AIT/AIC/AIS, CAT, Learning Spiral, Student's Trilemma), translation test expansion, configuration elevation, and other major v2.14 work remain pending and will apply to v2.13 as base. (Whole-version increment per Mac's standing preference: this is v2.13, not v2.12.4.)

**v2.13 changes (4 prose edits, listed in source-order):**

**Edit 1 — Acknowledgments restructured for scalability (page following copyright).**

*Before:* Single dense paragraph naming Tulane University and Los Alamos National Laboratory affiliations explicitly, with a detailed Yuwei Bao sentence describing her contribution at length.

*After:* Two paragraphs. The opening paragraph drops explicit institutional affiliations ("friends and colleagues" without affiliation), retaining the SIAM community and graduate-student attributions. The second paragraph is a compact alphabetical list of detailed-manuscript readers: Joshua Agbomola, Yuwei Bao, Scott McKinley. A LaTeX comment marks where additional reviewers will be added as feedback is received.

Rationale: Mac expects 10–20 named contributors before publication across 5–8 institutions. The previous detailed-contribution-per-person format does not scale; the previous Tulane/LANL-specific naming creates implicit hierarchy. The new alphabetical list treats all contributors with equal honor and accommodates the growing list without prose restructuring at each addition. Joshua's seven-recommendation review and Scott's substantive contributions to the translation test, configuration step, and Part III framing receive their structural credit through the v2.14 work they shaped, not through length of acknowledgment.

**Edit 2 — Hamming quotation (Chapter 12, §sec:verification, line 1149).** *Before:* "do the back-of-the-envelope calculation before you build the cathedral of computation" → *After:* "do the back-of-the-envelope calculation before you build the cathedral." Tighter quotation; removes the qualifier that pinned the metaphor to computation specifically.

**Edit 3 — Mathematics hypothesis prompt (Chapter 7, line 1429).** *Before:* "For each hypothesis in the theorem, tell me whether my proof uses it. If I did not use one, ask whether the theorem might be misstated or the proof incomplete." → *After:* "Identify whether each hypothesis in the theorem is actually used in the proof. If any hypothesis is unused, ask whether the theorem can be strengthened by removing or weakening that assumption." Reframes from defensive ("something is wrong with my work") to generative ("the theorem may be stronger than I realized"). Trains a mathematically more sophisticated habit.

**Edit 4 — Bastani Turkey clarification (Chapter 4, line 381).** *Before:* "The Bastani study examined a single secondary-mathematics intervention period; replication across other subjects, age ranges, and tool generations is still accumulating..." → *After:* "The Bastani study examined a single secondary-mathematics intervention period at a Turkish high school; replication across other subjects, age ranges, and tool generations is still accumulating..." Six-word addition sharpens an already-careful limitation note by acknowledging the study's geographic context explicitly. No change in argument.

**Empirical-claim audit findings (Joshua #5, completed 2026-05-22):**

Audited every quantitative claim in the manuscript that cites Bastani et al. 2025 or Kestin et al. 2025 against the primary sources (`/mnt/user-data/uploads/bastani2025generative.md` and `kestin2025ai.md`). **All claims verified accurate.** Specifically:

- Bastani 48% (GPT Base practice improvement), 127% (GPT Tutor practice improvement), 17% (GPT Base exam reduction) — all three figures verified exactly against primary source abstract and Main Results section
- Bastani "nearly a thousand high-school mathematics students" — verified (primary source: "approximately 1,000")
- Kestin "learning gains over double those of in-class active learning" — verified (primary source phrase: "over double")
- Kestin seven pedagogical practices (active engagement, cognitive-load management, growth mindset, scaffolding, feedback accuracy, timely targeted feedback, self-pacing) — all seven verified verbatim
- Kestin claim about which AI components handle which practices — verified against primary source design description
- Kestin N=194 Harvard introductory physics — verified
- FAA autopilot analogy attributed to Bastani — verified (Bastani primary source includes the same FAA framing)

No factual edits required beyond the optional Turkey clarification (Edit 4). The manuscript's prior verification work (VER v3.5 protocol) was thorough. Mac's habit of caveat-laden prose ("the specific effect sizes should be read as evidence for the qualitative pattern rather than as parameters that will reproduce exactly in every setting") protected the manuscript from any overclaiming risk the empirical citations might have introduced. No separate audit report generated per Mac's decision (the clean result needs no standalone document).

**Compile state.** Clean 4-pass build (pdflatex / bibtex / pdflatex / pdflatex). 173 pages, 0 errors, 0 undefined citations, 0 undefined references, 0 multiply-defined labels. Same page count as v2.12 — the Hamming and acknowledgment edits removed slightly more text than the Turkey and hypothesis edits added; net page change zero.

**Files updated:** `learning_with_ai_v2_13.tex`, `learning_with_ai_v2_13.pdf`. v2.12 source retained in outputs for rollback.

**Status for Scott's Monday reading:** v2.13 is the release Scott will read Part III against. The vocabulary is unchanged from v2.12 (Honest-A Bind, AI Learning Loop, C/A/R, Red/Yellow/Green/Blue all preserved) so Scott's reading is consistent with his Part I reading from the earlier version. The framework renames are deliberately deferred to v2.14 so Scott's Part III feedback applies to current vocabulary, not changed vocabulary.

---

## v2.12 — 2026-05-16 (Bastani repetition de-duplication — small preview edit)

**Trigger.** Mac flagged that the v2.11 manuscript contains two near-parallel passages reporting the Bastani et al. 2025 finding — a formal evidence-base treatment in §5 (~line 378) and an experiential treatment in §3 (~line 434). Both passages used the same 17% figure with similar clause structure, creating audible repetition. The second passage's job is to make an experiential point about unreliable self-assessment; the data lives in service of that point rather than carrying it.

**Posture.** Localized prose rewrite, executed as a small v2.12 preview before the post-Friday phase plan begins. This is the kind of edit the Phase 3 repetition-reduction pass would do across the whole manuscript; doing one in advance both improves a sore spot and demonstrates the rewrite pattern for the larger pass.

**Note on version numbering.** v2.12 was originally projected for the empirical-claim audit (Phase 1 of the post-Joshua/Scott plan). That work is now expected to land at v2.13. The phase plan adjusts accordingly: v2.12 (this preview), v2.13 (empirical audit + Joshua/Scott foreword acknowledgments), v2.14 (four focused additions), v3.0 (Blue development + polish pass including should-reduction and full repetition pass).

**v2.12 change (1 prose rewrite):**

**Section:** Part I §3 `subsec:illusion`, line 434

**Before:**

> This is also why your own sense of how much you have learned can be misleading. A pre-registered randomized trial of nearly a thousand high-school mathematics students found that students who used unrestricted AI on practice problems scored 17\% lower on the closed-book exam that followed than students who never had AI access, and they did not notice that they had learned less. The work felt successful because the AI produced correct-looking answers \citep{bastani2025generative}. The guide's emphasis on verification, explanation, and honest self-checks is meant to bridge this gap between what a polished AI artifact looks like and what you actually understand.

**After:**

> This is also why your own sense of how much you have learned can be misleading. In a pre-registered trial with nearly a thousand high-school mathematics students, those who practiced with unrestricted AI did not notice that they had learned less than students who worked without AI---but the closed-book exam afterward made the gap visible \citep{bastani2025generative}. The work felt successful because the AI produced correct-looking answers. This guide's emphasis on verification, explanation, and honest self-checks is meant to bridge that gap between what a polished AI artifact looks like and what you actually understand.

**Specific changes:**

- **Removed the explicit 17% figure.** The exact number lives in §5's formal Bastani treatment where it earns its space. The §3 passage's experiential point ("the gap is visible afterward") works without the specific number competing for the reader's attention.
- **Inverted clause structure.** §5's formal treatment leads with the objective score gap, then notes the metacognitive gap. The rewritten §3 passage leads with the metacognitive gap ("did not notice"), then notes the objective gap ("made the gap visible"). Same study, different emphasis — matches the experiential framing the §3 passage is built around.
- **"This guide's" instead of "The guide's"** — minor sharpening.
- **"that gap" instead of "this gap"** — minor; refers to the just-named gap.

**Compile state.** Clean 4-pass cycle. **173 pages unchanged from v2.11.** Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 4 overfull and 32 underfull hboxes (unchanged from v2.7 baseline).

**Bibliography:** unchanged from v2.11 (44 entries, all Mac-VER verified, 6 reportage entries WBM-stamped).

**Graffiti count unchanged** at 15/14.

**Packaging triad refreshed:** `hyman2026learning_COR_2026-05-13.zip`, `hyman2026learning_CGR_2026-05-13.zip`, `hyman2026learning_CCR_2026-05-13.zip` updated to reference v2.12.

**Session 2 status.** This v2.12 preview was a single authorized edit. Session 2 returns to its waiting state pending Scott McKinley's feedback on Friday. After that, the multi-phase plan (now starting at v2.13) proceeds.

---

## v2.11 — 2026-05-14 (Citation-as-claim Mac-voice graffiti from Lean Curated draft; +1 over CVE budget)

**Trigger.** Mac uploaded `Macs_Rules_Lean_Curated_May2026.md` — a 98-rule consolidation of the prior expansion with duplicates merged and the rule set distilled to submission-quality sidebar-ready content. Main-thread review of the lean draft surfaced one graffiti-strength candidate that addresses a real gap in the existing marginalia: the AI-citation-fabrication failure mode.

**Posture.** Single graffiti addition, accepting +1 over the CVE protocol's 14-graffiti budget ceiling. The justification: the existing 14 graffiti have no Mac-voice entry addressing AI's most common high-stakes failure mode in academic work — fabricated citations. G7 in §38 names the detection-side failure (false positives on student writing); the new rule names the production-side failure (sources that do not exist) and pairs with G7 to frame §38's central topic.

**v2.11 change (1 graffiti addition, total now 15):**

- **`\graffiti{A citation is a claim, not a decoration. Verify it.}`** added at Part II §38 `i:sec:integrity`, immediately after the existing G7 ed.-voice graffiti.

**Paired graffiti effect in §38.** §38 now hosts two graffiti in sequence:

> *Six in ten non-native English essays were flagged as AI-generated. The detector was wrong.* ---ed.
>
> A citation is a claim, not a decoration. Verify it.

The first names what AI detectors get wrong on the surveillance side; the second names what students must do on the production side. Together they frame §38's argument that the academic-integrity question cannot be outsourced — neither to detection software nor to AI tools. The reader carries the responsibility either way.

**Voice attribution.** The new rule is Mac-voice unattributed per the v2.2 author-default convention. The rule is in Mac's-Rules lineage with no Pólya/Hamming/Krantz fingerprint per the lean draft's source map (the citation-claim formulation is Mac's own).

**Voice scheme after v2.11 (15 graffiti total):**

| Section | Graffiti | Voice |
|---|---|---|
| Part I §1 sec:purpose | G4 Thirty years | Mac |
| Part I §3 sec:learning-outcomes | Clock builder | Mac |
| Part I §4 subsec:illusion | G1 AI proof | Student |
| Part I §4 subsec:illusion | Smoother the prose | Mac |
| Part I §5 sec:compact | Verify-verify-verify | Mac |
| Part I §7 sec:learning-loop | G5 Five-step loop | Annotator |
| Part I §9 sec:good-uses | Magic-more-information | Mac |
| Part I §11 sec:dangerous-uses | Easiest-to-fool | Mac |
| Part I §12 sec:verification | G2 Verify-looks-right | Mac |
| Part I §12 sec:verification | Draft-not-witness | Mac |
| Part II §2 i:sec:instructor-outcomes | Fill-a-bucket | Mac |
| Part II §27 i:sec:central-problem | G6 Harder-to-see | Mac |
| Part II §38 i:sec:integrity | G7 Six-in-ten | Annotator |
| **Part II §38 i:sec:integrity** | **Citation-as-claim (v2.11)** | **Mac** |
| Part III §61 u:sec:change-management | G8 One-page-compact | Mac |

Total: 15 graffiti, **1 over CVE budget of 14**. Mac-voice: 12; Student: 1; Annotator: 2. Distribution: 10 in Part I, 4 in Part II (Part II now hosts two graffiti pairs — §27 single + §38 pair), 1 in Part III.

**Compile state.** Clean 4-pass cycle. **173 pages unchanged from v2.10.** Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 4 overfull and 32 underfull hboxes (unchanged from v2.7 baseline).

**Bibliography:** unchanged (44 entries, all Mac-VER verified, 6 reportage entries WBM-stamped).

**v3.0 sidebar candidate inventory updated.** From the lean curated draft, the following rules are documented as candidates for a future Mac's-Rules sidebar (the lean draft itself is essentially submission-quality sidebar source text and can be used largely as-is in v3.0):

- *Do not use competence as a mask. Honesty lasts longer.* (Life Rule; direct conceptual link to competence costume; held from v2.11 because of competition risk with existing §54 prose)
- *The answer is not finished until you can defend it without the machine.* (AI Rule; overlaps with translation test which is already a `\keyterm{...}` doing this work; better in sidebar where it amplifies rather than competes)
- *Teach the mistake before the method. The method makes more sense after the trap is visible.* (Teaching Rule; strong Part II candidate if a future pass lightens Part II's graffiti scarcity)
- *Discovery may begin in fog. Publication should not.* (Research Rule; strong but no obvious home)
- *Students remember the moment the fog lifted. Build toward that moment.* (Teaching Rule; strong Part II candidate)
- *Research is less footrace than barn raising.* (Collaboration Rule; strong but off main theme)

**Packaging triad refreshed:** `hyman2026learning_COR_2026-05-13.zip`, `hyman2026learning_CGR_2026-05-13.zip`, `hyman2026learning_CCR_2026-05-13.zip` updated to reference v2.11.

---

## v2.10 — 2026-05-14 (Hamming personal-source attribution in §12 verification)

**Trigger.** Mac surfaced that Dick Hamming was a personal friend whose Los Alamos visits produced long conversations, and that the "back-of-the-envelope" discipline should appear in the book with attribution to Hamming and a brief reference to their friendship.

**Posture.** Prose addition rather than graffiti. The graffiti format is too compressed to carry both the principle and the friendship; a short prose paragraph honors the personal connection, attributes the principle cleanly, and integrates with the book's existing personal-history register (Mac's pre-AI memories in §1 already establish that personal-academic-history prose belongs in the book). This is the book's first **attributed personal-source mention** — a third category alongside journalism attributions (Walsh, Hill, McMurtrie) and Mac's own anonymous-colleague memories.

**v2.10 change:**

- **Hamming-attributed paragraph** inserted in Part I §12 `sec:verification`, between the opening framing paragraph (self-explanation + dunlosky2013improving) and the verification questions list (Meaning / Accuracy / Method / Evidence / Assumptions / Ownership). Approximately 65 words. Text:

  > Sage advice from Dick Hamming, whom I knew during his visits to Los Alamos: do the back-of-the-envelope calculation before you build the cathedral of computation. The principle scales. In an AI-assisted setting, a rough check on the answer's shape and order of magnitude is worth more than a precise validation of the wrong thing. Verification starts with what you would expect to see, not with what the AI gave you.

**Why this placement.** The paragraph bridges the conceptual framing (verification as self-explanation) and the practical machinery (the six-question checklist). The "back-of-the-envelope before cathedral of computation" framing establishes the rough-check-first discipline at the section's opening; the verification questions then operationalize it. The closing sentence ("Verification starts with what you would expect to see, not with what the AI gave you") rhymes with the existing G2 graffiti's emphasis on explaining-why over looking-right.

**Attribution choice.** The phrasing "Dick Hamming, whom I knew during his visits to Los Alamos" honors the friendship modestly — factual, no inflation, matches the understated register Mac uses elsewhere for personal references. The Hamming source is acknowledged cleanly (the back-of-envelope discipline is widely associated with him); the cathedral-of-computation image is Mac's own and now appears in published form.

**Pattern established.** This is the first attributed personal-source mention in the book. The convention going forward — *"X, whom I knew during [context]"* — is suggested for any future named-colleague attributions in a v3.0 medium pass. Candidates that could use this convention: the Dr. Xiang Ji "explain to your parents" line (pending Yuwei's introduction and Dr. Ji's permission); any other colleague Mac would want to credit by name.

**Compile state.** Clean 4-pass cycle. **173 pages unchanged from v2.9.** Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 4 overfull and 32 underfull hboxes (unchanged from v2.7 baseline).

**Bibliography:** unchanged from v2.7 (44 entries, all Mac-VER verified, 6 reportage entries WBM-stamped). The Hamming attribution does not require a bibliography entry — the source is identified by name in the prose itself, in the personal-anecdote register, which is the appropriate citation form for a friend-quoted-from-conversation rather than a published-work citation.

**Graffiti count unchanged.** v2.10 adds prose, not marginalia. The CVE protocol's 14-graffiti budget remains at 14/14 after this version. Future graffiti additions still need to either swap an existing one or formally raise the budget.

**Packaging triad refreshed:** `hyman2026learning_COR_2026-05-13.zip`, `hyman2026learning_CGR_2026-05-13.zip`, `hyman2026learning_CCR_2026-05-13.zip` all updated to reference v2.10.

---

## v2.9 — 2026-05-13 (Two AI-Era graffiti from Mac's Rules expansion)

**Trigger.** Mac uploaded `Macs_Rules_Expansion_First_Pass.md` containing ~100 expanded maxims across nine categories with a private source map showing Pólya / Hamming / Krantz lineage where applicable. Main-thread review identified the AI-Era Rules section as the strongest fit for *Learning with AI* (Mac's-original lineage per the source map; directly thematic). Five strong candidates were narrowed to two via minimum-effective-dose discipline; the third candidate ("alternatives, not absolution") was held in reserve for the prospective v3.0 Mac's-Rules sidebar where it can operate alongside related rules without competing.

**Posture.** Two graffiti additions at the CVE protocol's 14-budget ceiling. Both rules are clearly Mac-voice (no Pólya/Hamming/Krantz fingerprint per source map) and earn their placement by doing work the existing book cannot deliver in the same form.

**v2.9 changes (2 graffiti additions):**

| Rule | Section | Placement | Why |
|---|---|---|---|
| *The smoother the prose, the more carefully you should check the facts.* | Part I §4 `subsec:illusion` | Immediately after existing G1 student-voice graffiti | Creates a voice exchange in §4: G1 names the lived experience of being fooled by fluency; this Mac-voice rule names the principle that explains why fluency is the danger. Diversifies §4's voice (previously student-only) and sharpens the illusion-of-competence material. |
| *The AI answer is a draft, not a witness.* | Part I §12 `sec:verification` | Immediately after existing G2 Mac-voice graffiti | Creates a Mac-voice exchange in §12: G2 names the failure mode (verifying that AI looks right); this rule names the correct posture (treating AI as draft, not testimony). Introduces a conceptual frame — the *epistemic status* of AI output — that the book's prose does not currently name. |

**Voice scheme after v2.9 (14 graffiti total):**

| Section | Graffiti | Voice |
|---|---|---|
| Part I §1 sec:purpose | G4 Thirty years | Mac |
| Part I §3 sec:learning-outcomes | Clock builder (v2.6) | Mac |
| Part I §4 subsec:illusion | G1 AI proof | Student (`---student`) |
| Part I §4 subsec:illusion | **Smoother the prose (v2.9)** | **Mac** |
| Part I §5 sec:compact | Verify-verify-verify (v2.6) | Mac |
| Part I §7 sec:learning-loop | G5 Five-step loop | Annotator (`---ed.`) |
| Part I §9 sec:good-uses | Magic-more-information (v2.6) | Mac |
| Part I §11 sec:dangerous-uses | Easiest-to-fool (v2.6) | Mac |
| Part I §12 sec:verification | G2 Verify-looks-right | Mac |
| Part I §12 sec:verification | **Draft-not-witness (v2.9)** | **Mac** |
| Part II §2 i:sec:instructor-outcomes | Fill-a-bucket (v2.6) | Mac |
| Part II §27 i:sec:central-problem | G6 Harder-to-see | Mac |
| Part II §38 i:sec:integrity | G7 Six-in-ten | Annotator (`---ed.`) |
| Part III §61 u:sec:change-management | G8 One-page-compact | Mac |

Total: 14 graffiti at the CVE protocol budget ceiling. Eleven Mac-voice (unattributed, author default); one Student (`---student`); two Annotator (`---ed.`). Distribution: ten in Part I (with §4 and §12 now hosting two graffiti each for the voice-exchange effect), three in Part II, one in Part III. The density gradient (heavier in Part I) is preserved.

**Attribution status.** Both new rules are in Mac's-Rules lineage per the source map's AI-Era Rules category. Neither has a recognizable Pólya/Hamming/Krantz fingerprint. Both land unattributed as Mac voice in the existing graffiti scheme.

**Held for v3.0 Mac's-Rules sidebar.** Per main-thread review of the expansion, the following candidates are strong but their placements in this book would duplicate existing Mac-voice without distinctive payoff; they are documented for a possible v3.0 sidebar treatment:

- *Ask AI for alternatives, not absolution.* (AI-Era; strong wordplay; no clean home in current sections)
- *Do not let AI make you sound smarter than you are. Honesty lasts longer than polish.* (AI-Era; close thematic relative to the existing easiest-to-fool graffiti)
- *AI can help you move faster in the wrong direction. Check the compass.* (AI-Era; strong image)
- *Use AI to sharpen your thinking, not to replace your judgment.* (AI-Era; close thematic relative to fill-a-bucket)
- *A student who finds the question owns more than a student who copies the answer.* (Teaching/Mentoring; Mac-original; strong but lands at translation-test conceptual level)

**Held entirely (attribution concern).** A few rules in the expansion are strong but carry recognizable Pólya/Hamming fingerprints that would require footnote attribution to use honestly: *Name the unknown before you chase it* (Pólya How to Solve It); *Find the baby problem* (Pólya auxiliary problem); *Do the back-of-the-envelope calculation before building the cathedral of computation* (Hamming back-of-envelope). The cathedral image is Mac's own, but the first half carries Hamming's signature. These belong either in a sidebar with attribution, or in a separate document, not as unattributed graffiti in a book about academic integrity.

**Compile state.** Clean 4-pass cycle. **173 pages unchanged from v2.8.** Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 4 overfull and 32 underfull hboxes (unchanged from v2.7 baseline).

**Bibliography:** unchanged from v2.7 (44 entries, all Mac-VER verified, 6 reportage entries WBM-stamped).

**Packaging triad regenerated:** `hyman2026learning_COR_2026-05-13.zip`, `hyman2026learning_CGR_2026-05-13.zip`, `hyman2026learning_CCR_2026-05-13.zip` all refreshed to reference v2.9.

---

## v2.8 — 2026-05-13 (Yuwei Bao deferred suggestions integrated: voice-input footnote and continuous-loop paragraph)

**Trigger.** Two small additions from Yuwei Bao's v1.7 reflection that had been deferred from v2.5 integration (where only her strongest contribution, the teach-AI pattern, was integrated as a new §9 subsection). With submission readiness substantively complete after v2.7, integrating these two small remaining items closes the Yuwei integration arc.

**v2.8 changes:**

- **Voice-input accessibility footnote** added in Part I §2 subsec:prompt-and-setup, attached to the sentence "The prompt is one piece of the request. The deeper act is setting up the conditions for good thinking." Footnote text: *"Composing prompts in writing is not the only option. Most AI platforms accept voice input or transcribed dictation, which can help students whose spoken expression is more fluent than their written expression --- for example, students whose first language is not English. Speak the question, let the platform transcribe it, then refine the wording in writing before sending. The underlying skill (setting up the situation, naming what kind of help would help) does not change with the input modality."* Approximately 70 words. Yuwei's accessibility insight made platform-agnostic; her specific reference to non-native English speakers preserved in spirit without naming her contribution explicitly (which is acknowledged generally in the foreword).

- **Continuous-loop paragraph** added in Part I §7 sec:learning-loop, after the steps summary table and before subsec:try-first. Paragraph text: *"The loop runs at multiple time scales. Within a single task, the five steps are a sequence. Across an assignment, a unit, or a semester, the same loop repeats: what you learned from verification in one pass becomes part of the try-first in the next; what you reflected on becomes the setup for the next round of questions. The local cycle on each task supports a longer cycle on the work as a whole."* Approximately 65 words. Yuwei's longitudinal-loop observation made concrete with the assignment/unit/semester time scales relevant to a student reader.

**Compile state.** Clean 4-pass cycle. **173 pages unchanged from v2.7.** Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 4 overfull and 32 underfull hboxes (unchanged from v2.7 baseline; the v2.8 additions absorbed cleanly into existing whitespace).

**Bibliography:** unchanged from v2.7 (44 entries, all Mac-VER verified, 6 reportage entries WBM-stamped).

**Yuwei Bao integration arc summary** (now complete):

| Version | Yuwei contribution integrated |
|---|---|
| v2.4 | Named acknowledgment in foreword |
| v2.5 | Teach-AI pattern as new §9 subsection ("Use AI to test your explanations") with audience role-play folded in |
| v2.8 | Voice-input footnote in §2; continuous-loop paragraph in §7 |
| Deferred to v3.0 | Dr. Xiang Ji quote candidate ("if you explain your research to your parents and they can't understand it, that is a failure") for Mac's-notebook interlude treatment |
| Not integrated | Cross-tool verification (technically weak; correlated training data); job-seeking (out of scope); visualization/checklist conversion (would be mechanical list extension) |

**COR package:** regenerated as `LearningWithAI_v2.8_2026-05-13.zip`.

**SIAM cover letter draft:** produced this session as a companion deliverable, referencing v2.8 as the submission state. Not bundled in the COR ZIP; provided as a separate item for Mac's editorial customization (addressee name, signature details).

---

## v2.7 — 2026-05-13 (Wayback Machine durability pass: wildcard archive URLs added to 6 reportage entries)

**Trigger.** Wayback Machine snapshot pass deferred since v1.7 — the seven v1.7 reportage entries cite live journalism URLs vulnerable to link rot. After main-thread investigation confirmed that web_fetch cannot directly access the archive.org availability API and that specific Wayback URLs do not reliably surface via web search even when snapshots are known to exist, the approach selected was wildcard pointer URLs (`web.archive.org/web/*/{original_url}`) added to each entry's note field. The wildcard format resolves on the reader's end to the Wayback Machine calendar page listing all available snapshots for the URL, providing stable durability without requiring per-entry verification of a specific timestamp.

**Posture.** Bibliography-only update; no manuscript prose changes. The .bib file is the shared canonical resource across all manuscript versions, so the v2.7 manuscript .tex content is identical to v2.6 with only the bibliography content differing in rendered output.

**Scope.** Six of the seven v1.7-era reportage entries received Wayback wildcard URLs:

1. **walsh2025everyone** (New York Magazine, paywalled): new `note` field added
2. **hill2025professors** (New York Times, paywalled): new `note` field added
3. **mcmurtrie2024professors** (Chronicle of Higher Education, paywalled): existing print-version `note` extended
4. **silva2025university** (The Conversation, open access): existing co-investigator `note` extended
5. **klee2023falsely** (Rolling Stone): new `note` field added
6. **kingkade2026avoid** (NBC News): new `note` field added

The seventh originally-categorized "reportage" entry, **hou2025roads**, is actually an ACM peer-reviewed conference proceedings paper with DOI (10.1145/3724363.3729024), ISBN, and arXiv preprint (2504.09779) — already durable via stable academic identifiers, no Wayback needed.

**Format added to each entry.** A note-field clause of the form: *Wayback Machine snapshots: \url{https://web.archive.org/web/*/[original URL]}.* The asterisk wildcard pattern is correct Wayback Machine syntax for "show all snapshots." Each entry's `annote` field also received a `WBM:2026-05-13` stamp documenting the addition for protocol traceability.

**Verification approach selection rationale (documented for protocol traceability).** Approach 2 (per-entry search-and-verify with specific Wayback timestamps) was considered but rejected on token-cost grounds: each URL would have required at least one web_search to locate Wayback snapshots, with no guarantee of success for paywalled articles where archive coverage is spotty in search results. Approach 4 (defer entirely for interactive Save Page Now use by Mac) was offered but Mac elected approach 1 (wildcard) to complete the durability pass in this session. The wildcard format is honest — it admits the bibliography points to "whatever the archive has" rather than claiming a specific verified snapshot — and is the format most academic style guides actually recommend for archive-supplemented references where specific snapshot URLs would be impractical to maintain.

**Compile state.** Clean 4-pass cycle. **173 pages unchanged from v2.6.** Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, **4 overfull and 32 underfull hboxes (regressed from 3/25 baseline)** — the long archive URLs in the new note fields produce 1 additional overfull and 7 additional underfull warnings from URL line-breaks. These are cosmetic only (no compile errors); the cost is acceptable for the durability gain. If line-break tightness becomes a concern at production typesetting, the long URLs in the note fields can be shortened to the wildcard prefix only or moved to a separate URL-only appendix.

**Bibliography status after v2.7.**

| Metric | Before v2.7 | After v2.7 |
|---|---|---|
| Total entries | 44 | 44 |
| Mac-VER verified | 44/44 | 44/44 |
| VER:pending | 0 | 0 |
| Wayback Machine wildcard URL (reportage entries) | 0/6 | 6/6 |
| Bibliography durability completeness | partial | complete-as-feasible |

**COR package:** regenerated as `LearningWithAI_v2.7_2026-05-13.zip`.

---

## v2.6 — 2026-05-11 (Five Mac-voice graffiti from Mac's Rules: synthesized main-thread + parallel-thread placements)

**Trigger.** Mac uploaded `Macs_Rules_Draft_May2026.docx` containing his accumulated teaching/research/coding/communication/life rules and asked whether some could be woven into the book in a way his former students would recognize. The main thread (this conversation) proposed three high-fit placements with detailed reasoning; a parallel conversation independently proposed four placements with different reasoning, including two life-rule placements at outcomes sections that the main thread had initially excluded as off-topic. Mac asked to merge the two sets.

**Posture.** Synthesis: accept the parallel thread's four placements (its life-rule-at-outcomes-section moves were stronger than the main thread's initial exclusion judgment) and add the main thread's strongest unique candidate (the explicit AI rule at the basic compact). Five total graffiti additions. All Mac-voice using `\graffiti{}` syntax (unattributed, per the v2.2 author-default convention).

**v2.6 changes (5 graffiti additions):**

| Rule | Section | Placement | Source thread |
|---|---|---|---|
| *Be a clock builder, not a time teller.* | Part I §3 `sec:learning-outcomes` | Between the five-item enumerated list and the closing paragraph "These outcomes are modest by design..." | parallel |
| *With AI tools: verify, verify, verify, then trust.* | Part I §5 `sec:compact` | At section close, after "The responsibility belongs to you." | main |
| *When it seems like magic, you need more information.* | Part I §9 `sec:good-uses` | After the section's final line "This is a strong use of AI because it prepares you to think without AI." | parallel |
| *The easiest person for you to fool is yourself.* | Part I §11 `sec:dangerous-uses` | After the opening paragraph, before `subsec:outsource-first-contact` | parallel |
| *You are not there to fill a bucket. Your goal is to launch a career.* | Part II §2 `i:sec:instructor-outcomes` | After the closing line "It is now part of pedagogy.", before `i:subsec:instructor-unesco` | parallel |

**Placement reasoning summary.** Outcomes sections (Part I §3, Part II §2) are about purpose — what students should achieve, what instructors should achieve. Mac's life-rule graffiti at those points reframe outcomes from delivery-of-knowledge to building-capability and from content-filling to career-launching. The basic compact (§5) is the book's commitments section, where the explicit AI rule belongs. The §9 close ("prepares you to think without AI") and the magic-rule are ironic counterpoints: when AI stops preparing you to think, that's exactly when more information is needed. The §11 opening describes the deceptive-comfort pattern; the easiest-to-fool rule is the thesis of the entire dangerous-uses section, not just one subsection.

**Voice scheme after v2.6:**

| Graffiti | Section | Voice | Source |
|---|---|---|---|
| Clock builder | Part I §3 sec:learning-outcomes | Mac | Mac's Rules (Life Rules) |
| G4 Thirty years | Part I §1 sec:purpose | Mac | original v2.0 |
| G1 AI proof | Part I §4 subsec:illusion | Student (`[student]`) | original v2.0 |
| Verify-verify-verify | Part I §5 sec:compact | Mac | Mac's Rules (Research Guidelines) |
| G5 Five-step loop | Part I §7 sec:learning-loop | Annotator (`[ed.]`) | original v2.0 |
| G2 Verify-looks-right | Part I §12 sec:verification | Mac | original v2.0 |
| Magic-more-information | Part I §9 sec:good-uses | Mac | Mac's Rules (Research Guidelines) |
| Easiest-to-fool | Part I §11 sec:dangerous-uses | Mac | Mac's Rules (Research Guidelines) |
| Fill-a-bucket | Part II §2 i:sec:instructor-outcomes | Mac | Mac's Rules (Life Rules) |
| G6 Harder-to-see | Part II §27 i:sec:central-problem | Mac | original v2.0 |
| G7 Six-in-ten | Part II §38 i:sec:integrity | Annotator (`[ed.]`) | original v2.0 |
| G8 One-page-compact | Part III §61 u:sec:change-management | Mac | original v2.0 |

Twelve total graffiti: nine Mac-voice (unattributed), one Student (`---student`), two Annotator (`---ed.`). Distribution: eight in Part I, three in Part II, one in Part III. The density gradient is preserved.

**Why these five and not others from the Rules document.** The Rules document contains roughly 50 items across Research Guidelines, Coding Rules, Communication Rules, the four-step research style, and Life Rules. The main-thread review classified each for fit with the book's themes: direct AI/learning fit (~5 candidates), tangential fit (~3 candidates), and off-topic for this book (~10 candidates including career, networking, and life-passion guidance). The parallel thread independently identified the same off-topic Life Rules but found that *two* of them ("clock builder" and "fill a bucket") earn their place when anchored to outcomes sections, because outcomes sections are about purpose — the natural home for purpose-reframing rules. That insight changed the main thread's judgment on those two. The remaining 45 items in the Rules document are documented as candidates for a possible future "Mac's Rules" sidebar in a v3.0 medium pass, or for use in other documents (talks, essays, separate appendix).

**Compile state.** Clean 4-pass cycle. **173 pages** (+1 from v2.5). Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 3 overfull and 25 underfull hboxes (unchanged baseline metrics).

**Bibliography:** unchanged (44 entries, all Mac-VER verified).

**COR package:** regenerated as `LearningWithAI_v2.6_2026-05-11.zip`.

---

## v2.5 — 2026-05-11 (Yuwei Bao contribution integration: new §9 subsection on teach-the-AI pattern + audience role-play)

**Trigger.** Mac asked to review the v2.4 recommendations for integrating Yuwei Bao's substantive suggestions and to optimize the proposed changes before execution. Of the seven suggestions catalogued in the v2.4 changelog, an Excellence-First review found that only the strongest deserved space in the manuscript; the others were either superficially appealing but technically weak (#2 cross-tool verification — AI tools share training data and often produce correlated errors, so cross-AI agreement does not establish correctness and would weaken the book's existing standard of verifying against authoritative sources), out of scope (#4 job-seeking — the book is about learning and teaching, not careers), tool-specific in a way the book has consciously avoided (#3 voice input), implicit in the existing Learning Loop structure (#6 continuous re-feeding), or generic utility uses that would extend §9 mechanically without adding insight (#7 visualization/checklist). Suggestion #5 (audience role-play) was folded into #1 rather than given its own subsection.

**Posture.** One disciplined integration: a single new subsection in Part I §9 that develops Yuwei's strongest contribution (the teach-AI pattern) with her supporting insight (audience role-play) woven into the same unit. The integration earns its space by closing a real gap — §9 previously had no subsection capturing the production-by-teaching pattern, which is one of the book's most useful applications of the production-over-recognition principle.

**v2.5 change:**

- **New subsection `subsec:teach-ai` ("Use AI to test your explanations")** inserted in Part I §9 between the existing `subsec:retrieval` (Use AI to practice retrieval) and `subsec:weak-points` (Use AI to find weak points). The placement is pedagogically natural: retrieval is "produce the answer yourself"; teach-AI is "produce your explanation and submit it for judgment"; find-weak-points is "submit your finished work for critique." All three center on active production, in increasing structure. The new subsection follows the established §9 register: short opening that names the principle, three `\studentprompt{...}` examples that span the pattern's variations, closing sentence stating the underlying logic. Approximately 210 words.

**The three prompts:**

1. *"I'll explain this concept to you. Tell me which parts are unclear and which parts are incomplete."* — the base teach-AI pattern.
2. *"Act as someone outside this field. Listen to my explanation and ask the questions a non-expert would ask."* — the audience role-play variant (Yuwei's contribution #5 folded in).
3. *"Here is my answer to this problem. Critique it as if I were teaching you the topic. Where would a student be confused?"* — a hybrid: user produces, AI evaluates from a learner's perspective.

**Closing principle of the new subsection:** *"When you ask AI to solve a problem, AI does the producing and you evaluate. When you ask AI to evaluate your explanation, you do the producing and AI evaluates. The second form keeps the cognitive work where it needs to be. The same shift lets you rehearse for different audiences, which is one of the more useful side benefits of teaching yourself by teaching AI."*

**Acknowledgment relationship.** The v2.4 acknowledgment of Yuwei Bao ("a detailed reading reflection on a draft version whose practical suggestions from a current graduate-student perspective are gratefully acknowledged") remains unchanged in v2.5. The wording is forward-compatible: "are gratefully acknowledged" does not commit to a specific level of integration. v2.5 substantively realizes that gratitude by integrating one of her contributions; the acknowledgment itself stays at the same level of specificity.

**Suggestions deferred from Yuwei's reflection** (documented for future revision cycles if Mac elects):

- Voice input as accessibility note in §2 — small enough to be a future footnote.
- Continuous re-feeding in §7 — most useful for longitudinal research; could land in Part II or III rather than Part I if pursued.
- The Dr. Xiang Ji quote ("if you explain your research to your parents and they can't understand it, that is a failure") remains a candidate for a v3.0 Mac's-notebook interlude.

**Compile state.** Clean 4-pass cycle. **172 pages unchanged from v2.4** (the new subsection absorbed without page increase; layout flowed within existing whitespace). Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 3 overfull and 25 underfull hboxes (unchanged baseline metrics).

**Bibliography:** unchanged from v2.3 (44 entries, all Mac-VER verified).

**COR package:** regenerated as `LearningWithAI_v2.5_2026-05-11.zip`.

---

## v2.4 — 2026-05-11 (Acknowledgment of student reviewer Yuwei Bao)

**Trigger.** Mac received a detailed v1.7 reading reflection from his student Yuwei Bao on 2026-05-11 — a substantive review (approximately 10 specific suggestions plus four favorite-element callouts) drawing on her experience as a current graduate-student user of AI, including her infectious-disease research context, her work with prompt engineering courses, and her perspective as a non-native English speaker. Mac asked to acknowledge her contribution in the book.

**Posture.** Single-sentence addition to the existing acknowledgments paragraph; no integration of her substantive suggestions in this pass (those are documented separately for elective consideration in a future revision). The acknowledgment is placed within the existing categorical mention of graduate students who tested the framework, with Yuwei named as a particular instance.

**v2.4 change:**

- **Acknowledgments section** (Foreword, `\section*{Acknowledgments}`): one sentence added to the end of the existing first paragraph: *"Among these, Yuwei Bao provided a detailed reading reflection on a draft version whose practical suggestions from a current graduate-student perspective are gratefully acknowledged."* Word choice notes: "a draft version" rather than naming v1.7 specifically (the acknowledgment should age well past version-specific labels); "current graduate-student perspective" characterizes the perspective without specifying her institution or research field (consistent with the existing paragraph's level of detail about other named groups); "gratefully acknowledged" is the standard academic-acknowledgment register.

**Yuwei Bao's substantive contributions** (documented for elective future integration, not implemented in v2.4):

1. **"Explain to AI" / "teach AI" framing.** Her highest-value contribution. Connects directly to the book's existing production-over-recognition theme (Dunlosky retrieval research; the translation test). She frames the user-as-teacher approach as: explain a topic or proposed answer to AI, let AI judge or correct, with two specific benefits — (a) intention-driven engagement (the user's mental model is the starting point, not the AI's), and (b) AI as a second pair of eyes that catches what one person's perspective misses. Candidate for integration in Part I §9.3 or earlier in Part I where the C/A/R framework or Learning Loop is introduced.

2. **Cross-tool verification.** Use of multiple AI systems (different models or vendors) to cross-check AI output. Candidate for a brief addition to Part I §12 (verification) or Part I §7.4 (the Verify step of the Loop).

3. **Voice input for non-native speakers.** Speaking questions and using transcription as AI input, then letting AI restate the question before answering, helps refine question quality and supports learners whose written English is less fluent than their spoken. Candidate for a brief mention in Part I §2 (setup) or Part I §5 (compact).

4. **Job-seeking with AI.** Practical pattern for graduate students transitioning to industry: feed job descriptions, LinkedIn profiles of advanced-career people in target roles, and one's own CV to AI, then identify gaps and prepare interview questions. Candidate for a new section in Part I or a worked example.

5. **AI as audience-shifter / role-player.** Use AI's flexibility to assign different audience identities — expert in the field, lay reader, parent without technical background — to practice research communication. Connects to her advisor Dr. Xiang Ji's instruction that "if you explain your research to your parents and they can't understand it, that is a failure." The Dr. Xiang Ji quote itself is the kind of vivid teacher-anecdote the book uses elsewhere (Wendy, Wilson, Stapleton) and could become a Mac's-notebook-style interlude in a future medium pass.

6. **Continuous-loop with re-fed updated information.** The AI Learning Loop does not end when the user gets a satisfying answer; new information can be fed back to AI to generate better suggestions over time. Particularly resonant in longitudinal-data domains like infectious-disease research. Candidate for a brief extension in Part I §7 (the Loop) or as a Mac's-notebook interlude.

7. **AI for visualization and structure.** Two specific patterns Yuwei identified: ask AI to turn abstract ideas into simple examples or illustrations, and ask AI to convert messy information into actionable bullet checklists. Candidate for additions to Part I §2 or §9.

**Yuwei's parts-I-like callouts:** the Dunlosky-cited claim about retrieval over passive exposure; the "ten seconds, passive reading → active hypothesis testing" framing; the AI account configuration template (described as concrete and easy to adopt); the overall checklist-plus-specific-questions structure described as intuitive.

**Compile state.** Clean 4-pass cycle. **172 pages** (+1 from v2.3; the additional sentence in the acknowledgments paragraph shifted page layout slightly). Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 3 overfull and 25 underfull hboxes (unchanged baseline metrics).

**Bibliography:** unchanged from v2.3 (44 entries, all Mac-VER verified).

**COR package:** regenerated as `LearningWithAI_v2.4_2026-05-11.zip`.

---

## v2.3 — 2026-05-11 (Bibliography verification: VER v3.5 pass — 4 author corrections + 1 DOI added; all 44 entries now verified)

**Trigger.** Mac executed the VER v3.5 verification protocol on the 5 legacy VER:pending entries plus a spot-check of representative prior-pass entries. Results delivered as `LearningWithAI_VER.bib` plus `VER_FINAL_REPORT.md`. The pass resolved all outstanding VER:pending annotations, corrected three author name errors across two entries, added one missing DOI, and confirmed the remaining three previously-pending entries clean.

**Posture.** Bibliography-only update; no manuscript prose changes. Replacing the canonical `LearningWithAI.bib` with the verified version produces rendered-bibliography changes in two entries (Beresnitzky first name; Xiang and Zhou first names in chen2025unpacking). No inline citations are affected since `\citep{...}` produces "Beresnitzky et al." and "Chen et al." regardless of first names.

**v2.3 changes (bibliography corrections from VER v3.5):**

- **kosmyna2025brain (HIGH severity correction):** Author name corrected from `Beresnitzky, Anastasiia V.` to `Beresnitzky, Ashly Vivian` per arXiv preprint 2506.08872 abstract, MIT Media Lab project page, and ResearchGate full author list — four independent sources agree on "Ashly Vivian Beresnitzky"; the original "Anastasiia V." appears nowhere in any official source. DOI `10.48550/arXiv.2506.08872` added per v3.5 identifier-completeness requirement (was missing). Annote updated with VER:2026-05-11 verification stamp documenting both corrections.

- **chen2025unpacking (HIGH severity correction):** Two author names corrected — `Xiang, Mengqi` to `Xiang, Mengtong` and `Zhou, Junlin` to `Zhou, Junyi` — per ScienceDirect article page and Monash Research repository. "Mengtong Xiang" and "Junyi Zhou" are consistent across all sources; the original "Mengqi" and "Junlin" appear nowhere. Annote updated with VER:2026-05-11 verification stamp documenting both corrections.

- **kosar2024computer:** Spot-check confirmed all metadata correct (authors Kosar/Ostojić/Liu/Mernik; journal Mathematics, vol 12 no 5 article 629, 2024; DOI 10.3390/math12050629 resolves cleanly). Annote updated with VER:2026-05-11 verification stamp.

- **wang2024tutor:** Spot-check confirmed all metadata correct (authors Wang/Ribeiro/Robinson/Loeb/Demszky; Annenberg Institute at Brown University techreport; DOI 10.26300/81nh-8262). One transparency note documented: the edworkingpapers.com official suggested citation uses EdWorkingPaper 24-1056 (which the BibTeX `number` field correctly retains); the ERIC record ED661562 uses 24-1054, which appears to be an ERIC-assigned accession number distinct from the EdWorkingPaper series number. No change required; flagged in annote for transparency. Annote updated with VER:2026-05-11 stamp.

- **fan2025beware:** Spot-check confirmed all metadata correct (full 9-author list Fan/Tang/Le/Shen/Tan/Zhao/Shen/Li/Gašević; British Journal of Educational Technology vol 56 no 2 pp 489–530, 2025; DOI 10.1111/bjet.13544). Published online December 2024; collected in print vol 56(2), 2025. Annote updated with VER:2026-05-11 stamp.

**Spot-check of representative prior-pass entries.** bastani2025generative, dunlosky2013improving, hou2025roads, roediger2006test, bjork2011making each confirmed correct under VER v3.5 standards. The prior-pass annotes remain authoritative for these and the other 34 entries verified before this pass.

**Incidental finding (no action required).** A PNAS correction notice (doi: 10.1073/pnas.2518204122, August 20, 2025) corrected an affiliation error for Osbert Bastani in the bastani2025generative paper (CIS department, not OID department). This is a production error in the journal; the BibTeX entry does not record affiliations, so no change to the entry is required. Flagged in the VER report for completeness.

**Verification status summary after v2.3:**

| Metric | Before v2.3 | After v2.3 |
|---|---|---|
| Total entries | 44 | 44 |
| VER:pending | 5 | 0 |
| Mac-VER verified | 28 | 44 |
| Web-verified (no Mac sign-off) | 11 | 0 |
| Author errors corrected (cumulative) | 0 | 3 (in 2 entries) |
| DOIs added (cumulative) | 0 | 1 (kosmyna2025brain) |
| BibTeX compile | clean | clean |

**Compile state.** Clean 4-pass cycle. **171 pages** (unchanged from v2.2; bibliography entries change in detail but not in length). Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 3 overfull and 25 underfull hboxes (unchanged from v2.2 baseline).

**Inline citation impact: none.** All four corrected names are within author lists rendered as "X et al." in inline `\citep{...}` calls. The first author surname is unchanged in both entries (Kosmyna; Chen), so the rendered text in the body of the manuscript is identical to v2.2. Only the bibliography section's rendered output changes.

**COR package:** regenerated as `LearningWithAI_v2.3_2026-05-11.zip` with the verified bibliography, cartoon PDF assets, and updated README.

**Documentation archived.** `VER_v3_5_FINAL_REPORT_2026-05-11.md` saved in outputs as the audit trail for this verification pass.

---

## v2.2 — 2026-05-11 (Graffiti refinement: voice attribution markers added; G4 repositioned; G5 rephrased to dual audience)

**Trigger.** Main-thread review of the seven v2.0 graffiti pullquotes surfaced three design issues: (a) the CVE protocol's four-voice scheme (Mac/Student/Annotator/Skeptic) was invisible to readers because the `\graffiti{}` rendering carried no attribution marker — all graffiti looked identical regardless of voice; (b) G4 (Mac voice, Part I §1) sat immediately after "The technology has changed. The ache has not." and competed with that compression line as a parallel second compression; (c) G5 (Annotator voice, Part I §7) directly addressed "Instructors:" mid–Student Guide, breaking Part I's voice register.

**Posture.** Three small focused edits per main-thread recommendations: minimum-touch voice attribution (Mac voice stays unattributed as the author default; only Student and Annotator voices get small marker tags); single relocation of G4 within §1; single wording change to G5 that preserves the forward pointer while removing the explicit register break.

**v2.2 changes (5 edits in 2 files):**

- **Preamble `\graffiti{}` command extended** to accept an optional attribution argument. Mac-voice graffiti continue to use `\graffiti{text}` syntax (no attribution rendered); other voices use `\graffiti[student]{text}` or `\graffiti[ed.]{text}` which render a small `---student` or `---ed.` marker at the end of the pullquote in upright (non-italic) footnotesize text. The marker is visually subordinate to the graffiti text itself but clearly present.
- **G1 graffiti (Part I §4 subsec:illusion) attribution added:** `\graffiti[student]{I read an AI proof, nodded along, then couldn't reproduce step two.}`. The first-person student voice is now distinguished from the surrounding Mac-voice graffiti and from the analytical prose.
- **G4 graffiti (Part I §1 sec:purpose) relocated:** moved from after "The technology has changed. The ache has not." to between the wrong-answer memory paragraph and that compression sentence. The graffiti now reads as the third element in the §1 memory sequence (notation memory → wrong-answer memory → graffiti naming the conversation that follows → compression bridge), rather than as a parallel compression competing with "The ache has not."
- **G5 graffiti (Part I §7 sec:learning-loop) rephrased + attribution added:** old text `\graffiti{Instructors: the same loop, read from the front of the room, becomes a rubric for what AI-assisted work should show. See~\cref{i:sec:car-framework}.}`; new text `\graffiti[ed.]{The same five-step loop, read as a rubric, becomes what AI-assisted work should show. See~\cref{i:sec:car-framework}.}`. The explicit `Instructors:` address is dropped (eliminating the Part I voice-register break); the graffiti now reads as a general observation about the loop's reach that serves both student and instructor readers. The `---ed.` attribution marks this as the Annotator-voice forward-pointer rather than authorial commentary.
- **G7 graffiti (Part II §38 i:sec:integrity) attribution added:** `\graffiti[ed.]{Six in ten non-native English essays were flagged as AI-generated. The detector was wrong.}`. The Annotator-voice data-restatement is now marked.

**Voice attribution scheme summary after v2.2:**

| Graffiti | Section | Voice | Rendering |
|---|---|---|---|
| G4 | Part I §1 sec:purpose | Mac | unattributed (author default) |
| G1 | Part I §4 subsec:illusion | Student | ---student |
| G5 | Part I §7 sec:learning-loop | Annotator | ---ed. |
| G2 | Part I §12 sec:verification | Mac | unattributed (author default) |
| G6 | Part II §27 i:sec:central-problem | Mac | unattributed (author default) |
| G7 | Part II §38 i:sec:integrity | Annotator | ---ed. |
| G8 | Part III §61 u:sec:change-management | Mac | unattributed (author default) |

Four Mac-voice graffiti remain unattributed (the book's default authorial voice). Two `---ed.` attributions (G5, G7) mark the Annotator role. One `---student` attribution (G1) marks the first-person student voice. The Knuth *Concrete Mathematics* model is now functional at the reader level.

**Compile state.** Clean 4-pass cycle. **171 pages** (unchanged from v2.1; the attribution markers and the G4 relocation are absorbed into existing whitespace). Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 3 overfull and 25 underfull hboxes (unchanged from v2.1).

**Bibliography:** unchanged (44 entries).

**COR package:** regenerated as `LearningWithAI_v2.2_2026-05-11.zip` with cartoon PDF assets bundled.

---

## CVE protocol v1.1 → v1.2 — 2026-05-11 (Process improvement; no manuscript content change)

**Trigger.** The v2.0 → v2.1 work showed that the v1.1 figure earning test could pass a figure while the figure silently introduced or redefined vocabulary inconsistent with the surrounding manuscript. The `fig:honest-a-bind` triangle was the worked example: all five v1.1 questions answered yes, but one edge label collided with the existing competence-costume definition in Part III §54 and two edge labels introduced unsupported analytical terms. Resolution required ~140 words of new prose plus two short cross-references in v2.1, all of which would have been prevented by an explicit consistency check at the protocol level.

**Change.** A sixth question added to the Figure Earning Test in §3.2 of the CVE protocol: **Consistent? Does the figure use only vocabulary the surrounding prose develops, and preserve the meaning of any named concepts it invokes?** The change includes a four-step application checklist (enumerate term-of-art words; check whether each is already defined in the .tex source; confirm prose support before committing to TikZ; treat configuration descriptors as descriptors rather than as named concepts). Audit thresholds updated to the new 6-yes scale (Strong = 6 yes; Acceptable = 5; Revisit = ≤4). The §6.3 figure checklist line updated from "all 5 yes" to "all 6 yes."

**Scope.** Protocol artifact only. The manuscript itself is unchanged. The v1.2 protocol is archived in outputs as `CVE_Content_Visual_Enhancement_Protocol_v1_2.md`, alongside the v1.1 artifact (`CVE_Content_Visual_Enhancement_Protocol_v1_1_1_.md`) which is retained for historical reference. If the parallel visual-enhancement thread reconvenes for future visual work, the v1.2 protocol should be the version loaded.

**Pending follow-up.** Main-thread review of the seven v2.0 graffiti pullquotes surfaced three design questions requiring Mac's input before any v2.2 graffiti refinement (voice attribution scheme; G4 placement in Part I §1; G5 cross-audience break in Part I §7). These are documented in `MANUSCRIPT_STATUS.yaml` under `next_session` and await Mac's decisions.

---

## v2.1 — 2026-05-11 (Honest-A Bind triangle taxonomy refinement: polished hollow rename + three-mode prose support + Part II/III cross-references)

**Trigger.** The v2.0 manuscript produced by the parallel CVE thread introduced a Honest-A Bind triangle figure (`fig:honest-a-bind`) with three edge labels: *competence costume*, *strategic compliance*, *honest risk*. Review in the main thread identified two consistency issues: (a) the v2.0 figure used *competence costume* in a sense incompatible with its v1.7 definition anchored to the Stapleton case in Part III §54 (where competence costume names AI-polished material projecting more confident engagement than the underlying work supports, with non-disclosure as the defining feature); (b) the triangle introduced two new analytical sub-terms (*strategic compliance*, *honest risk*) without prose support in the surrounding manuscript.

**Posture.** Resolve the consistency issue by renaming the left edge of the triangle and adding prose support for the three-mode taxonomy. The taxonomy and competence costume become complementary rather than competing: the taxonomy (now: *polished hollow* / *strategic compliance* / *honest risk*) names internal configurations the bind-bearer occupies; competence costume names what is projected outward. Stapleton's case (Part III §54) stays anchored as competence costume projected via strategic compliance.

**v2.1 changes (5 edits in 3 sections):**

- **Part I §4 (`sec:learning-science`) figure label:** TikZ left-edge label changed from *competence costume* to *polished hollow*. The new term avoids vocabulary collision with §54's competence costume, preserves parallel adjective-noun structure with *strategic compliance* and *honest risk*, and signals coined-term status grammatically (hollow as noun) similar to competence costume itself.
- **Part I §4 figure caption:** rewritten to be lighter. Old caption defined all three modes; new caption defers definitions to the new taxonomy paragraph. Now reads: *"The Honest-A Bind. Three goals in genuine tension. Each edge labels the failure mode that arises when the two adjacent goals are satisfied at the cost of the third. The text develops the modes. AI sharpens each edge; it did not create the bind."*
- **Part I §4 prose insertion:** ~140-word taxonomy paragraph added immediately after the figure environment and before the existing "go from A to B" counter-argument paragraph. Names and defines the three modes in student-facing language (polished hollow = grade + honesty satisfied, understanding sacrificed; strategic compliance = grade + understanding satisfied, honesty sacrificed; honest risk = honesty + understanding satisfied, grade sacrificed). Each mode introduced with `\keyterm{...}`. Forward-references the taxonomy's appearance in Parts II and III.
- **Part II §38 (`i:sec:integrity`) cross-reference:** ~45-word addition after the existing "translation test offers a positive frame" paragraph. Establishes that the translation test catches polished hollow directly (the student cannot translate); strategic compliance and honest risk require different instructor responses developed later in Part II.
- **Part III §54 (`u:sec:problem`) cross-reference:** ~45-word clarification added after the existing competence costume definition paragraph. Connects the taxonomy and the costume: the Northeastern professor's costume was projected through strategic compliance (he understood his own course but hedged on disclosure); competence costume names the outward projection while the taxonomy names the configuration that produces it.

**Compile state.** Clean 4-pass cycle. **171 pages** (true page count with cartoon PDFs rendering at actual size; the parallel thread's v2.0 reported 166 pages but that figure appears to have been compiled before the actual cartoon assets were available at full resolution). Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 3 overfull and 25 underfull hboxes (unchanged from v1.9 baseline metrics; cartoon and figure additions did not introduce new hbox issues).

**Bibliography:** unchanged from v1.9 (44 entries). All new prose uses existing bibliography references or no citations.

**COR package:** regenerated as `LearningWithAI_v2.1_2026-05-11.zip` to include the cartoon PDF assets (`cartoon_c1.pdf`, `cartoon_c2.pdf`) alongside the manuscript and bibliography.

**Three named concepts now consistently developed across all three Parts:** Honest-A Bind (Part I §4 introduction; Part II §27 callback; Part III §54 callback), translation test (Part I §5 introduction; six recurrences across Parts I-III), and competence costume (Part III §54 anchored to Stapleton case; foreword implicit reference). The v2.1 work adds three sub-terms within the Honest-A Bind taxonomy (polished hollow, strategic compliance, honest risk) developed at lower prominence than the three primary named concepts. They appear once per their definition in §4, once in §38, and once in §54.

---

## v2.0 — 2026-05-11 (Parallel-thread visual enhancement: CVE protocol applied, 2 figures + 7 graffiti + 2 cartoons + 1 table conversion)

**Trigger.** Following Michael Forbes's reviewer feedback (2026-05-11) on the absence of visual material in v1.9, the figures/cartoons/graffiti effort was structured as a parallel conversation per `PARALLEL_SETUP_RECOMMENDATIONS.md`. The parallel thread executed the Content Visual Enhancement Protocol (CVE v1.1) and delivered v2.0 with twelve changes.

**Posture.** No structural restructuring of the manuscript. All visual elements anchored to section labels per the section-label inventory in `FIGURES_STATE.yaml`. Three element types governed by the CVE protocol: TikZ figures (minimum spatial-earning test), graffiti pullquotes (Knuth Concrete-Mathematics model; four voices: Mac/Student/Annotator/Skeptic; seven placement triggers; five-criterion quality filter), and AI-generated cartoons (pen-and-ink Sumi-e style via Gemini Nano Banana; LaTeX captions only; fixed Master Style Prompt for visual consistency).

**v2.0 changes (12 total):**

- **Two new TikZ figures:** `fig:honest-a-bind` (equilateral triangle showing three-way pull with edge labels; located Part I §4) and `fig:translation-test` (before/after worked example showing translation by notation change; located Part I §5).
- **One TikZ-to-table conversion:** `fig:three-models` (three-column model comparison) converted to `tab:three-models` (booktabs tabularx). The audit found the content was tabular, not spatial; 48 lines of TikZ reduced to 14 lines of clean LaTeX. Four `\cref{fig:three-models}` cross-references updated to `\cref{tab:three-models}`.
- **Seven graffiti pullquotes** added via custom `\graffiti{}` LaTeX command in a right-aligned 0.43-textwidth minipage. Distribution: G4 (Mac voice, `sec:purpose`); C2 cartoon at `subsec:prompt-and-setup`; G1 (Student, `subsec:illusion`); G5 (Annotator, `sec:learning-loop`); G2 (Mac, `sec:verification`); G6 (Mac, `i:sec:central-problem`); G7 (Annotator, `i:sec:integrity`); G8 (Mac, `u:sec:change-management`). Each note matches exactly one of seven placement triggers and passes a five-criterion quality filter.
- **Two AI-generated cartoons:** C1 (`u:sec:problem`, the competence-costume cartoon — three panels showing academic regalia + pajama trousers, the recognition humor inviting reader inference); C2 (`subsec:prompt-and-setup`, the tutoring-session cartoon — two panels contrasting "drop book and leave" vs "seated with prepared notes"). Both rendered in pen-and-ink Sumi-e style via Gemini. PDF assets shipped alongside the .tex source (`cartoon_c1.pdf`, `cartoon_c2.pdf`).

**Stress-test results from the parallel thread.** Null-test pass rates: 24% Part I, 10% Part II, 7% Part III. The density gradient correctly tracks the book's three-audience register (student-facing Part I tolerates more visual material than administrator-facing Part III). The aggregate 13% pass rate confirmed the minimum-effective-dose principle held throughout the enhancement effort.

**v2.0 known issue resolved in v2.1.** The Honest-A Bind triangle introduced edge labels (*competence costume*, *strategic compliance*, *honest risk*) that conflicted with v1.7's existing definition of competence costume anchored to the Stapleton case. Resolution: see v2.1 entry above.

**Files added to outputs:** `learning_with_ai_v2_0.tex`, `cartoon_c1.pdf`, `cartoon_c2.pdf`, `CVE_Content_Visual_Enhancement_Protocol_v1_1_1_.md` (parallel-thread protocol artifact).

---

## v1.9 — 2026-05-10 (Part I §2 for-further-reading footnote added to the prompt-vs-setup subsection)

**Trigger.** Mac requested guidance for students who want to learn the craft of AI account setup, prompt design, and conversation protocols. The book is deliberately not a tool guide, but some pointer to external resources is appropriate. Mac's constraints: keep it short (not a long discussion to the reader); use the existing Mollick citation; do not commit to specific URLs that require maintenance to keep current.

**Posture.** Single footnote added at the end of the new §2 subsection (`The prompt is only the visible part`). Body text unchanged. The footnote names four categories of resources that age well (platform-provider documentation, university-produced AI-use guidance, accessible books on AI literacy, open educational resources), cites `\citep{mollick2024cointelligence}` (already in bibliography) as a specific book pointer, and explicitly states the deliberate non-endorsement of specific commercial products or prompt-engineering courses.

**v1.9 insertion:**

- **Part I §2 (`The prompt is only the visible part` subsection):** ~85-word footnote attached to the closing sentence of the tutoring-session analogy paragraph. The footnote names four durable resource categories, cites Mollick's *Co-Intelligence* as the book-level pointer matching the manuscript's orientation, and reiterates the tool-agnostic stance.

**Compile state.** Clean 4-pass cycle. **166 pages (unchanged from v1.8; footnote absorbed without page increase).** Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 3 overfull and 25 underfull hboxes (both unchanged from v1.8).

**Bibliography:** unchanged from v1.7 and v1.8 (44 entries). The Mollick citation in the new footnote was already in the manuscript from earlier versions.

**COR package:** regenerated as `LearningWithAI_v1.9_2026-05-10.zip`.

---

## v1.8 — 2026-05-10 (Part I §2 prompt-vs-setup subsection added)

**Trigger.** Mac requested an addition to Part I §2 (`Setting up your AI for learning`) emphasizing that the prompt matters less than the preparation. The point distinguishes per-conversation context-setting (a new contribution) from persistent account preferences (the existing §2 content). The new material makes explicit a principle that the rest of Part I has been implicitly assuming.

**Posture.** Single focused subsection added inside the existing §2 boundary. No structural restructuring; no impact on Parts II, III, or appendices; no new bibliography entries. The v1.7 humanity-pass voice register (occasional first-person, conversational analogies, named principles set in display quotes) extends naturally into this addition.

**v1.8 insertion:**

- **Part I §2 (`Setting up your AI for learning`):** new subsection `subsec:prompt-and-setup` titled *The prompt is only the visible part* inserted after the existing closing paragraph about the persistent-preferences template. ~380 words. The subsection (a) names the distinction between persistent preferences (existing §2 content) and per-conversation setup (the new content); (b) contrasts a weak setup (``Explain this topic'') with a stronger one (a mathematical-modeling worked example demonstrating role, audience, purpose, and standard of success); (c) names the broader principle that AI users are best understood as *designers of context* rather than as prompters; (d) gives a learning-specific homework example (`Do my homework problem' vs. `Here is my attempt, I think the error is in the second step, please ask one question at a time'); (e) sets the central aphorism in a display quote: *A good prompt asks a question. A good setup teaches the AI what kind of answer matters.*; (f) closes with a short tutoring-session analogy that makes the principle stick.

**Compile state.** Clean 4-pass cycle. **166 pages (+1 from v1.7, +5 cumulative from v1.6).** Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 3 overfull hboxes and 25 underfull hboxes (both unchanged from v1.7; the new subsection introduces no new tabular or float content).

**Bibliography:** unchanged from v1.7 (44 entries).

**COR package:** regenerated as `LearningWithAI_v1.8_2026-05-10.zip` with the v1.7 README updated to reflect the v1.8 addition.

**Relationship to v1.7 named concepts.** The new subsection does not introduce a new key term that recurs across Parts II and III; "designers of context" is a phrase that appears once locally in §2 rather than a load-bearing concept threaded through the book. The principle aligns with and reinforces the translation test threaded across all three Parts, in the sense that good setup before a conversation is part of what builds the understanding that the translation test can then verify.

---

## v1.7 — 2026-05-10 (Light humanity pass: voice, three vignettes, named concepts, mixed-citation strategy)

### Sub-entry — 2026-05-10 (COR v1.7 Overleaf submission package generated)

**Trigger.** Light humanity pass executed in three sessions (B, C, D per `MULTISESSION_PLAN_v1_7.md`). Mac approved the plan on 2026-05-10 with three confirmations resolved before Session B: (1) BKS key for Hou et al. = `hou2025roads`; (2) archive URLs deferred to a later VER pass; (3) §57 keeps three citations in the natural mixed registers (Liang inline, Klee and Kingkade as footnotes).

**Posture.** No structural restructuring. All insertions land inside existing sections. Three Parts gain emotional anchors via Wendy (§4), Wilson (§27), and Stapleton (§54). Two named concepts threaded across Parts: the Honest-A Bind (introduced in §4) and the translation test (introduced in §5, recurring in §10, §27, §38, §54, §61). One cross-role phrase introduced: competence costume (§54). Author voice anchored at the opening of Part I §1 (notation memory) and in the foreword's expanded AI-assistance disclosure.

**v1.7 insertions, all silent-mode edits applied via `str_replace`:**

- **Foreword** (`Acknowledgments and AI assistance` subsection): existing 50-word AI-assistance paragraph replaced with 200-word expanded meta-disclosure naming the specific temptation (polished AI output making the author appear more confident, more current, more sure-footed than the underlying thinking). First-person register; closing sentence preserved verbatim. The pointer to "more detailed disclosure in front matter" removed since the expanded aside is now the detailed disclosure.
- **Part I §1 (`Why this guide exists`):** 145-word pre-AI memory opening added before the existing first paragraph. Mac's two pre-AI detection memories (notation mismatch on copied proofs; copying-with-wrong-answer pairs in homework) anchor the narrator. Closing bridge sentence: "The technology has changed. The ache has not."
- **Part I §4 (`How learning happens, and how AI changes it`):** opening paragraph replaced with a 365-word four-paragraph expansion — Wendy paraphrased from `walsh2025everyone` (footnoted), Honest-A Bind named as a key term, "go from A to B" counter-argument addressed, transition into existing science-of-learning content. The original opening paragraph is preserved as the fourth paragraph of the new opening.
- **Part I §5 (`The basic compact`):** 110-word translation test introduction inserted between the "If you cannot explain the work, the work has not yet become part of your understanding" sentence and the "compact has five parts" enumeration. Names the translation test as a key term and gives both math and non-math instantiations.
- **Part I §10 (`How to verify AI-assisted work`):** 70-word translation test reference inserted after the six-item ownership-question list. Cross-references back to §5.
- **Part II §27 (`The instructor-side calibration problem`):** opening replaced with a 290-word four-paragraph expansion — brief callback to the Part I notation memory ("the same diagnostic I once used to catch a copied proof"); Wilson "fake papers instead of playing with my own kids" line from `mcmurtrie2024professors` (footnoted); "ChatGPT won't judge you" finding from `silva2025university` Pittsburgh focus groups (footnoted); cross-reference to §38 for translation test as teaching tool. Original first paragraph preserved as the fifth paragraph of the new opening.
- **Part II §32 (`Designing assignments that preserve thinking`):** 85-word peer-isolation paragraph added between the existing pedagogical-foundations paragraph and the plan-use-verify pattern. Cites `hou2025roads` inline as `\citep`.
- **Part II §38 (`Academic integrity without detector dependence`):** 140-word two-paragraph addition after the "goal is not to avoid accountability" sentence. Stapleton case briefly pointed to (footnote with cross-reference to §54 for full case); translation test developed as a teaching tool with the symmetry argument.
- **Part III §54 (`The institutional problem`):** opening replaced with a 250-word four-paragraph expansion — Stapleton case told in full (footnoted via `hill2025professors`); competence costume named as a key term; translation test as institutional policy standard. Original first paragraph preserved as the fifth paragraph.
- **Part III §57 (`Academic integrity procedure`):** 150-word footnoted paragraph added after the existing Liang detector-bias paragraph. Klee/Stivers human-stakes case (footnoted), humanizer arms race line attributed to Erin Ramirez via `kingkade2026avoid` (footnoted). Liang remains inline per mixed-citation strategy.
- **Part III §61 (`Faculty use of AI`):** 80-word translation test as faculty self-standard inserted between the first and second existing paragraphs. Brief cross-reference back to the §54 Stapleton case.

**Bibliography expansion: 7 new entries (37 → 44 entries):**

- `walsh2025everyone` — James D. Walsh, *New York Magazine*, May 7, 2025. Source for Wendy paraphrase and "go from A to B" counter.
- `hill2025professors` — Kashmir Hill, *New York Times*, May 14, 2025. Source for Stapleton/Northeastern case.
- `mcmurtrie2024professors` — Beth McMurtrie, *Chronicle of Higher Education*, June 2024. Source for Wilson "fake papers" line.
- `hou2025roads` — Hou et al., ITiCSE 2025 (peer-reviewed). Source for peer-isolation finding. BKS key locked as `roads` per Mac's preference.
- `silva2025university` — Elise Silva, *The Conversation*, July 16, 2025. Source for Pittsburgh focus groups and "won't judge you" line.
- `klee2023falsely` — Miles Klee, *Rolling Stone*, June 6, 2023. Source for Stivers/UC Davis false-positive case.
- `kingkade2026avoid` — Tyler Kingkade, NBC News, January 28, 2026. Source for humanizer arms race line.

All seven entries VER:2026-05-10 Verified via web search (multiple cross-source byline and date verification). Archive URLs deferred per Mac's preference; one archive.is mirror included for `walsh2025everyone` since it was already snapshot-confirmed during the verification pass.

**Mixed-citation strategy implemented.** Peer-reviewed studies (Liang for detector bias; Hou et al. for peer isolation) cited inline as `\citep{...}` consistent with the existing manuscript convention. Reportage and named individuals from journalism (Walsh, Hill, McMurtrie, Silva, Klee, Kingkade) cited via `\footnote{\citet{...}}` so the human stories carry traceable attribution without breaking the prose flow with parenthetical author-year cites.

**Compile state.** Clean 4-pass cycle. **165 pages (+4 from v1.6).** Diagnostics: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 3 overfull hboxes (+1 from v1.6, cosmetic), 25 underfull hboxes (+4 from v1.6, cosmetic). All v1.7 cross-references (`\cref{sec:compact}`, `\cref{u:sec:problem}`, `\cref{i:sec:integrity}`, etc.) resolve. All seven new bibliography entries cite cleanly with no `Citation undefined` warnings.

**Net new content.** ~1,735 words added across 11 silent-mode edits, distributed: ~770 words in Part I (across §1, §4, §5, §10), ~515 words in Part II (across §27, §32, §38), ~480 words in Part III (across §54, §57, §61), plus the 200-word foreword expansion replacing the prior 50-word version. The light-pass envelope predicted +5 pages; actual growth is +4 pages, with the slight efficiency from prose flowing into existing whitespace.

**Items deliberately deferred to v2.0** (per multisession plan):
- New section explicitly for the Honest-A Bind and translation test in Part I (light pass introduces both inside existing sections; v2.0 would give them their own section).
- Four-character temptation arc as structural spine (student / teacher / administrator / author woven together).
- Eight to twelve "Mac's notebook" interludes throughout the body.
- Full subtext-per-audience framing.

---

## v1.6 — 2026-05-09 (MREP v5.0.5+ Cycle 4: adversarial review and edit pass on Appendices A-D + XCR Phase C — closes four-cycle review)

### Sub-entry — 2026-05-09 (COR v1.6 Overleaf submission package generated)

**Trigger.** Mac requested COR (Consolidated Overleaf Repository) package update following completion of the four-cycle MREP review at v1.6.

**Output.** `LearningWithAI_v1.6_2026-05-09.zip` (≈932 KB) saved to `/mnt/user-data/outputs/`.

**Package structure** (per LEGACY_COR_CGR_AID_v4.0_Protocol.md):

```
LearningWithAI/
├── learning_with_ai_v1_6.tex       380 KB    Source manuscript (single file)
├── learning_with_ai_v1_6.pdf       845 KB    Compiled PDF (161 pages)
├── LearningWithAI.bib              22.9 KB   Shared bibliography (37 entries)
└── README.md                       9.3 KB    Generated v4.0 README
```

**Generation steps executed:**

- **Phase 0** — Compilation verification: 4-pass clean (0 errors, 0 undefined citations, 0 undefined references).
- **Phase 1** — Dependency analysis: single-file source (no `\input` files), TikZ-only (no external image files), shared bibliography file (`LearningWithAI.bib`).
- **Phase 2** — File collection: staged `.tex`, `.pdf`, `.bib` into `LearningWithAI/` subdirectory.
- **Phase 3** — README generation: v4.0 template populated with paper title, version, target journal (SIAM Books on Education), AI disclosure note, recent-changes summary covering all four MREP cycles, file-structure listing, compilation instructions, required LaTeX packages list (extracted from `\usepackage` commands), bibliography stats, version audit trail, and submission checklist.
- **Phase 4** — Package creation: ZIP built, integrity verified (`unzip -l` listing matches expected structure; round-trip extraction confirmed all three file md5 hashes match the original outputs).
- **Phase 5** — Cover-Letter Cross-Reference Audit: skipped (no cover letter; not applicable to monograph submission).

**AID re-run:** skipped for this package generation (the manuscript's existing front-matter AI disclosure remains accurate; the v1.6 changes were content edits within Parts and Appendices that don't affect the AI disclosure language). If SIAM Books on Education publishes a series-specific AI policy before submission, the front-matter disclosure should be reviewed against it; see README submission checklist.

**Prior COR packages preserved** (for reference): `LearningWithAI_v1.0_2026-05-04.zip`, `LearningWithAI_v1.0_CGR_2026-05-04.zip`, `LearningWithAI_v1.1_2026-05-04.zip`, `LearningWithAI_v1.2_2026-05-09.zip`, `LearningWithAI_v1.2_CGR_2026-05-09.zip`. The v1.6 package supersedes all prior COR packages for any forward submission action.

---

### (Original v1.6 entry below)

**Trigger.** MREP Cycle 4 of the four-cycle adversarial review initiated on v1.2. Cycle 4 covers Appendices A-D (GMIP, M/A/E framework, Scientific Writing, Math Quick Reference) plus XCR Phase C (final coherence pass across the full v1.5 manuscript: Parts I, II, III, and all four appendices). **v1.6 closes the four-cycle MREP review.** v1.0, v1.1, v1.2, v1.3, v1.4, v1.5 audit baselines preserved unchanged.

**Posture.** Independent review of each appendix (no consultation of prior reviewer materials, AI persona baseline, or v1.2 Plan during the Cycle 4 review proper). Cycles 1, 2, and 3 findings used as anchor for the XCR Phase C coherence check. Findings document: `Cycle4_Appendices_Findings.md` (5 findings: 0 HIGH, 1 MEDIUM, 4 LOW, plus 16 of 17 XCR-C coherence checks pass; 21 calibration-OK observations). The four appendices independently confirmed as well-constructed graduate-technical references. Citation discipline strong: 4 of 5 unique appendix citations VER:Verified.

**Targeted findings addressed.**

- **M1-IV** — Walters fabrication-rate claim in Appendix C §C.4 hedged. Previous wording ("Empirical work documents fabrication rates of roughly 15-50%") attributed a specific quantitative range to a single citation; new wording ("Empirical work documents substantial fabrication rates in AI-generated bibliographies, often in the range of tens of percent") preserves the citation's load-bearing role without overstating the source. Symmetric to the citation-discipline pattern set in v1.3 Cycle 1 H3 (Kosmyna preprint disclosure) and v1.4 Cycle 2 H2-II (Wang working-paper disclosure).
- **L1-IV** — "Recent surveys" → "A recent survey" in Appendix A §A.6 (singular form to match singular `\citep{ahn2024large}` citation).
- **L2-IV** — Appendix C §C.2 cross-reference updated. Previously pointed to `\cref{sec:setup}` only (the brief overview after v1.3 Cycle 1 S2 fix split the setup section); now points to both `\cref{sec:setup}` and `\cref{app:ai-config}` (full template).
- **L3-IV** — Appendix C scope-clarification sentence added to intro. The new sentence makes the appendix's STEM-graduate-research scope explicit ("The emphasis is on STEM and computational research where equations, code, and numerical results dominate verification practice") and provides a cross-reference to Part II §15 (`\cref{i:sec:discipline-overlays}`) for humanities and qualitative-research writers. **This edit explicitly resolves the v1.2-deferred AI-persona finding about humanities thinning**, which Cycles 1-3 independent review had not confirmed and which Cycle 4 located in App C as the only remaining venue. The resolution is not "humanities thinning was a real problem" but rather "the appendix's STEM-graduate scope is now legible to non-STEM readers who jump directly to App C."

**XCR Phase C coherence.**

- **XCR-C9** — AI Learning Loop figure cross-reference added to Part III §18.1 *Student training*. Now reads "Student orientation should teach the AI Learning Loop (`\cref{fig:learning-loop}`)..." matching the parallel treatment in Part II §12 Dialogue 8 annotation. Helps Part III readers who haven't read Part I.

**XCR Phase C summary (full-manuscript final coherence pass).** 16 of 17 cross-Part coherence checks pass cleanly across Parts I, II, III, and Appendices A-D. After v1.6 implementation, the manuscript has **complete cross-Part coherence**: C/A/R definitions consistent everywhere; Red/Yellow/Green/Blue assignment categories consistent; UNESCO crosswalks parallel across all three Parts (Tab `tab:car-unesco`, Tab `tab:instructor-unesco`, Part III §5.1 prose); three-models references consistent; Plan-Use-Verify pattern consistently invoked; Liang detector-bias citations appropriate; all GMIP/M/A/E lineage references resolve; disclosure block templates consistent with audience-appropriate adaptation; section-ending pattern consistent (evidence → reference materials in all three Parts).

**Compile state.** Clean 4-pass cycle. **161 pages (unchanged from v1.5)** — all five edits are short text substitutions or additions; net page count is stable. Diagnostics identical: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 2 overfull hboxes, 21 underfull hboxes.

**Audit trail preserved.** All seven versions retained unchanged in outputs:
- v1.0 — SIAM submission baseline (141pp)
- v1.1 — sent to four human reviewers (141pp)
- v1.2 — substantive enhancement based on round-1 reviewer feedback (153pp)
- v1.3 — MREP Cycle 1 on Part I (155pp)
- v1.4 — MREP Cycle 2 on Part II + XCR Phase A (161pp)
- v1.5 — MREP Cycle 3 on Part III + XCR Phase B (161pp)
- v1.6 — MREP Cycle 4 on Appendices + XCR Phase C; **closes four-cycle review** (161pp)

**Pending items resolved across the four-cycle review.**

- *Hybrid Model under-development* (v1.2 deferral, AI-persona finding, no human reviewer raised in round 1): **resolved** by v1.4 H1-II — Part II §10 expanded from 6 paragraphs to 5 subsections matching Oral-Defense and Evidence-of-Thinking depth. Independently confirmed in Cycle 2 review.
- *Humanities thinning* (v1.2 deferral, AI-persona finding, no human reviewer raised in round 1): **resolved as not-confirmed-independently** across all four cycles, with optional scope-signaling improvement applied in v1.6 L3-IV.
- *Within-category variation* (v1.2 deferral, AI-persona finding): **not surfaced in any of the four cycles' independent reviews**. May be a v2.0 consideration but not a v1.6 concern.

**MREP Cycle counts.**

| Cycle | Findings | Severity breakdown | Edit move |
|---|---|---|---|
| Cycle 1 (Part I) | 16 | 4 H, 7 M, 4 L, 1 95-gap | v1.2 → v1.3 |
| Cycle 2 (Part II + XCR-A) | 9 + 2 XCR-A | 2 H, 3 M, 2 L, 2 XCR-A | v1.3 → v1.4 |
| Cycle 3 (Part III + XCR-B) | 4 | 0 H, 2 M, 2 L | v1.4 → v1.5 |
| Cycle 4 (Appendices + XCR-C) | 5 | 0 H, 1 M, 3 L, 1 XCR-C | v1.5 → v1.6 |

The decreasing severity profile across cycles (4-2-0-0 HIGH findings, 7-3-2-1 MEDIUM findings) reflects the manuscript's strengthening as MREP work progressed.

**Pending.** Single consolidated MREP reflection (`ai_learning_book_MREP_Reflection_v1.1.yaml`) — deferred to a separate session per token-budget posture and to allow systematic per-protocol commentary without competing context. Handoff document `HANDOFF_PostV1.6.md` to be created listing reflection-session inputs.

**MREP review work complete with v1.6.** Mac may now decide whether to (a) submit v1.6 as the next round to human reviewers; (b) use v1.6 as the basis for an updated SIAM submission package; (c) continue to a v2.0 with additional substantive expansions; or (d) keep v1.6 as the final review-ready manuscript. These decisions are outside the MREP scope.

---

## v1.5 — 2026-05-09 (MREP v5.0.5+ Cycle 3: adversarial review and edit pass on Part III + XCR Phase B)

**Trigger.** MREP Cycle 3 of the four-cycle adversarial review initiated on v1.2. Cycle 3 covers Part III (Departmental and Institutional Guide) plus XCR Phase B (Part I ↔ Part II ↔ Part III coherence across all three Parts). Cycle 4 (appendices + final XCR + consolidated reflection) remains pending. v1.0, v1.1, v1.2, v1.3, v1.4 audit baselines preserved unchanged.

**Posture.** Independent review of Part III (no consultation of prior reviewer materials, AI persona baseline, or v1.2 Plan during the Part III review proper). Cycle 1 and Cycle 2 findings used as anchor for the XCR Phase B coherence check. Findings document: `Cycle3_Part3_Findings.md` (4 findings: 0 HIGH, 2 MEDIUM, 2 LOW, plus 16 of 18 XCR-B coherence checks pass; 19 calibration-OK observations). Part III independently confirmed as the strongest of the three Parts at v1.4 baseline — zero VER:pending citations, exceptional change-management treatment, dual-audience framing honored throughout.

**Substantive structural improvement (95-gap Excellence-mode lever for Part III).**

- **New §5.1 *Alignment with UNESCO learning outcomes*** (M1-III) — UNESCO learning-outcomes mapping (the four-category typology of values, foundational knowledge and skills, higher-order thinking skills, vocational skills) **moved from §22.4 *What is likely to stay the same* to a new §5.1 subsection** immediately after the C/A/R framework definition. Now parallel to the UNESCO crosswalks in Parts I (Tab `tab:car-unesco`, student framework) and Part II (Tab `tab:instructor-unesco`, teacher framework). Department chairs and deans aligning with international policy frameworks for accreditation reporting and curriculum-revision proposals can find the mapping where they expect it (at the framework definition) rather than buried 25 pages later. Cross-references to the new label `u:subsec:unesco-outcomes` updated accordingly.

**Targeted findings addressed.**

- **L1-III** — Forward-pointers added from Part III §8.1, §8.2, §8.3 (the brief institutional-level treatments of the three assessment models) to the operational treatments in Part II §8, §9, §10. The Hybrid Model forward-pointer is especially valuable because v1.4 substantially expanded Part II §10 (recommended structure with mapping table, sampling strategy, worked example, suggested weighting, two empirical anchors). Institutional readers who decide on a model now have a clear path to operational depth.
- **M2-III** — Auto-resolved by M1-III placement. The line-3242 reference at §19.5 (*Cost and resource considerations*) previously included a forward reference to `\cref{u:subsec:will-stay}` (which was at §22.4) framed as "established earlier in this volume." With UNESCO mapping now at §5.1 (genuinely earlier), the reference updates to `\cref{u:subsec:unesco-outcomes}` and is now accurate as written.

**Polish.**

- **L2-III** — Part III ending reordered: §evidence-limits → §reference-materials → §*{acknowledgment} → §*{publication-note}. Now matches the pattern in Parts I and II (evidence base before reference materials). The Part-III-specific *Acknowledgment of source framework* section retains its position near the end as a framework-lineage acknowledgment.

**XCR Phase B coherence summary.** 16 of 18 cross-Part coherence checks passed cleanly. Two observations not actioned: (a) Liang detector-bias specific numbers cited in both Part II §13 and Part III §13 — appropriate redundancy for stand-alone Parts; (b) label prefix conventions inconsistent across Parts (Part I no prefix, Part II `i:`, Part III `u:`) — inherited convention; cost-benefit of changing now is poor; compile is clean.

**Compile state.** Clean 4-pass cycle. **161 pages (unchanged from v1.4)** — UNESCO content moved positions but its size is unchanged; forward-pointers add ~3 lines net. Diagnostics identical to v1.4: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 2 overfull hboxes, 21 underfull hboxes — the structural reorganization introduced no new layout issues.

**Audit trail preserved.** v1.0 (SIAM submission baseline, 141pp), v1.1 (sent to four human reviewers, 141pp), v1.2 (substantive enhancement based on round-1 reviewer feedback, 153pp), v1.3 (MREP Cycle 1 on Part I, 155pp), and v1.4 (MREP Cycle 2 on Part II + XCR Phase A, 161pp) all retained unchanged in outputs.

**Pending.** MREP Cycle 4 (appendices A-D + final XCR across full v1.5 manuscript) on v1.5. Single consolidated reflection (`ai_learning_book_MREP_Reflection_v1.1.yaml`) follows Cycle 4. The remaining venue for the v1.2-deferred *humanities thinning* concern is Appendix C *Best Practices for Ethical AI-Assisted Scientific Writing*, which Cycle 4 will address.

---

## v1.4 — 2026-05-09 (MREP v5.0.5+ Cycle 2: adversarial review and edit pass on Part II + XCR Phase A)

**Trigger.** MREP Cycle 2 of the four-cycle adversarial review initiated on v1.2. Cycle 2 covers Part II (Instructor Guide) plus XCR Phase A (Part I ↔ Part II coherence). Cycles 3 (Part III + XCR Phase B) and 4 (appendices + final XCR) remain pending. v1.0, v1.1, v1.2, v1.3 audit baselines preserved unchanged.

**Posture.** Independent review of Part II (no consultation of prior reviewer materials, AI persona baseline, or v1.2 Plan during the Part II review proper). Cycle 1 Part I findings used as anchor for the XCR Phase A coherence check. Findings document: `Cycle2_Part2_Findings.md` (9 findings: 2 HIGH, 3 MEDIUM, 2 LOW, plus 2 XCR-A coherence findings; 17 calibration-OK observations; 11 of 13 XCR-A coherence checks pass).

**Substantive expansion (95-gap Excellence-mode lever for Part II).**

- **§10 The Hybrid Model expanded** from 6 paragraphs (no subsections) to 5 subsections matching the depth of §8 Oral-Defense and §9 Evidence-of-Thinking. New subsections: §10.1 Recommended structure (with Tab `hybrid-mapping` showing live-element ↔ process-element pairings for four common course types); §10.2 Sampling strategy for live audits (random / stratified / threshold sampling, with trade-offs for each); §10.3 Worked example (15-week narrative of a 60-student intermediate course allocating effort across the term); §10.4 Suggested weighting (component weights table matching the format of §8.4 and §9.2); §10.5 Two empirical anchors (Kestin AI-tutor flipped-classroom finding + Kosar course-redesign convergence finding, woven into the subsection structure rather than tacked on).

**Substantive additions.**

- **New §7.0 Plan-Use-Verify in practice subsection** (~1 page). Three discipline-specific examples of what each artifact looks like (humanities essay, programming problem set, mathematics problem). Three "works when" patterns (artifacts short, gradable at glance, treated as thinking aid) and three "breaks when" patterns (graded on length, written retroactively, demanded as verbatim transcripts). Pattern scaling note (same shape from 1-page homework to semester project).
- **§14 Privacy, access, and equity expanded** from 5 paragraphs to 4 subsections (~14 paragraphs total). §14.1 Privacy (now includes course-design responsibility for third-party data exposures). §14.2 Access (three layers: tool, device, internet; baseline-plus design pattern). §14.3 Equity in assessment design (NEW; treats assessment-modality fairness explicitly: process-evidence favors documenters, in-class no-AI favors uninterrupted-focus students, oral favors verbal comfort; hybrid as mitigation). §14.4 Multilingual students and accessibility (preserves prior content; ties to Part I configuration template).

**Targeted findings addressed.**

- **H2-II** — Wang 2024 (Tutor CoPilot) cited at line 2237 with new disclosure: "currently circulating as an Annenberg working paper pending journal publication, and the specific effect sizes should be read with that status in mind." Symmetric to v1.3 Cycle 1 H3 fix (Kosmyna).
- **M1-II** — GMIP D2 reference in Part II Dialogue 8 annotation now includes Appendix A cross-reference: "(proof construction *and repair*; see Appendix~\ref{app:gmip})" — matching the v1.3 Cycle 1 L3 fix to the parallel Part I Dialogue 2 annotation.

**XCR Phase A (Part I ↔ Part II coherence).**

- **XCR-A9** — Bridge sentence added in Part II §7 (Designing assignments) about Kestin's specific implementation: "In Kestin's specific implementation (described in more detail in Part I §evidence-limits), the AI tutor's system prompt handled the first three practices, the platform's structured walkthrough handled scaffolding, and the remaining three are properties of AI as a medium." This harmonizes Part I §23 (after v1.3 M1 fix) and Part II §7 framings of the same paper.
- **XCR-A10** — Hybrid Model mention added to Part I §16 (Large classes / Evidence-of-Thinking Model). Two new sentences acknowledging the in-between case and forward-pointing to Part II §10. Especially valuable now that v1.4 develops Part II §10 fully.

**Polish.**

- **L1-II** — Part II §19 Reference materials and §20 Evidence base swapped in ordering, so Evidence base now precedes Reference materials (matching Part I's pattern). The §*{Publication note} stays after Reference materials in both Parts.
- **L2-II** — Forward-pointer added at the start of Part II §6 (Four assignment categories) to the Part I configuration template (`\cref{app:ai-config}`): instructors may want to recommend that students complete the configuration as a no-credit first assignment.

**Compile state.** Clean 4-pass cycle. **161 pages (+6 over v1.3's 155).** Diagnostics identical to v1.3: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 2 overfull hboxes, 21 underfull hboxes — i.e., the substantial expansion of §10 Hybrid Model, §7.0 Plan-Use-Verify, and §14 Privacy/access/equity introduced no new layout issues.

**Audit trail preserved.** v1.0 (SIAM submission baseline, 141pp), v1.1 (sent to four human reviewers, 141pp), v1.2 (substantive enhancement based on round-1 reviewer feedback, 153pp), and v1.3 (MREP Cycle 1 on Part I, 155pp) all retained unchanged in outputs.

**Pending.** MREP Cycles 3 (Part III + XCR Phase B across all three Parts) and 4 (appendices + final XCR) on v1.4. Single consolidated reflection (`ai_learning_book_MREP_Reflection_v1.1.yaml`) follows Cycle 4. COR/CGR regeneration deferred until after Cycle 4 closes.

---

## v1.3 — 2026-05-09 (MREP v5.0.5+ Cycle 1: adversarial review and edit pass on Part I)

**Trigger.** Adversarial four-cycle MREP review initiated on v1.2 between distribution rounds. Cycle 1 covers Part I (Student Guide). Cycles 2 (Part II + XCR Phase A), 3 (Part III + XCR Phase B), and 4 (appendices + final XCR) remain pending. v1.2 audit baseline preserved unchanged.

**Posture.** Independent review (no consultation of prior reviewer materials, AI persona baseline, or v1.2 plan/implementation reports during the review proper). Findings document: `Cycle1_Part1_Findings.md` (16 findings: 4 HIGH, 7 MEDIUM, 4 LOW, 1 95-gap; 17 calibration-OK observations).

**Structural changes.**

- **§6 Foundations moved earlier** — now sits between §3 Outcomes and §4 Compact, so the cognitive-science principles ground the Compact and the C/A/R framework rather than following them. Resolves the v1.2-introduced internal contradiction in §6's framing sentence ("the rest of Part I reads as application rather than assertion") which was at odds with the section's previous placement after the framework.
- **§2 Setting up your AI shortened** — body reduced from full six-category template to one-page motivation plus a list of the six categories; full template moved to §25 Reference materials as new subsection *Template: AI account configuration* (label `app:ai-config`). Procedural detail no longer front-loads Part I.
- **§17 retitled and trimmed** — "How to ask better AI questions" → "Asking better questions in mathematics." Removed ~40 lines that duplicated §7.2 (Ask for help, not replacement); kept the proof-based-mathematics extension and the closing study-technique-amplification meta-paragraph that are not in §7.2.
- **§20 Discipline examples reframed** — each vignette now walks through the whole AI Learning Loop (try-first → ask → work → verify → reflect) rather than only the verification step. Differentiates §20 (process narrative) from §12 (verification toolkit).

**Substantive addition (95-gap Excellence-mode lever).**

- **New §6.2 *Calibration checks in the moment*** (~1pp). Five moment-by-moment calibration moves: predict before reading, forced unassisted gap, blank-page rehearsal, self-quiz on the next day, explanation aloud. Each moves the calibration framework from concept to operational habit. Closing paragraph maps each move to the specific point in the AI Learning Loop where it runs.

**Targeted findings addressed.**

- **H1** — Dialogue renumbering 5→8 jump removed: Part I now has Dialogues 1–5 (strong) plus 6 (borderline); Part II has 7 (weak undergraduate calculus) and 8 (weak graduate proof). Cross-references updated.
- **H3** — Kosmyna 2025 cited with preprint disclosure; specific 12%/89% numerical claim softened to qualitative "dramatically reduced ability to recall content," consistent with the bib entry's stated VER:pending status.
- **H4** — FAA autopilot analogy now cited (Bastani 2025 raises the analogy in the source paper); previously presented as bare fact.
- **M1** — Kestin claim about "system prompt explicitly built in seven pedagogical practices" reworded to accurately describe which practices the prompt handled (i–iii) versus which the platform structure or AI medium handled (iv–vii).
- **M4** — Glossary expanded from 7 to 18 terms covering cognitive-science vocabulary (calibration error, retrieval practice, spacing, interleaving, generation effect, desirable difficulties, illusion of competence) and framework vocabulary (AI Learning Loop, C/A/R framework, AI-Augmented Practice, Responsible Judgment, Try first, Assignment categories, Distributed practice).
- **M6** — Two-sentence acknowledgment in §10 dialogues introduction noting STEM/research-heavy distribution and inviting cross-disciplinary readers to translate.
- **M7** — Five cognitive-science principles in §6 converted from `\emph{...}` to `\keyterm{...}` for consistent term-of-art tagging (Practice testing, Distributed practice, Interleaving, Generation effect, Desirable difficulties).

**Polish (L-tier).**

- **L1** — "field study" harmonized to "pre-registered randomized trial" (line 403; matches usage in §23).
- **L3** — GMIP D2 reference in Dialogue 2 annotation now points to Appendix A inline.
- **L4** — MathSciNet given inline gloss "(the AMS bibliographic database)" in Dialogue 3.
- **L2** — AI Learning Loop figure node label retained as-is (caption disambiguates).

**Compile state.** Clean 4-pass cycle. 155 pages (+2 over v1.2's 153). Diagnostics identical to v1.2: 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings, 2 overfull hboxes, 21 underfull hboxes — i.e., the edits introduced no new layout issues.

**Audit trail preserved.** v1.0 (SIAM submission baseline, 141pp), v1.1 (sent to four human reviewers, 141pp), and v1.2 (substantive enhancement based on round-1 reviewer feedback, 153pp) all retained unchanged in outputs.

**Pending.** MREP Cycles 2 (Part II + XCR Phase A), 3 (Part III + XCR Phase B), and 4 (appendices + final XCR) on v1.3. Single consolidated reflection (`ai_learning_book_MREP_Reflection_v1.1.yaml`) follows Cycle 4. COR/CGR regeneration deferred until after Cycle 4 closes.

---

## v1.2 — 2026-05-09 (substantive enhancement based on first-round human reviewer feedback)

**Trigger:** Four human reviews of Parts I and II returned during the SIAM review period. The reviewers converged on a coherent enhancement program: weave the cognitive-science principles already operationalized in the AI Learning Loop into the prose more visibly, particularly around retrieval practice, spacing, interleaving, blank-page reconstruction, metacognitive anchoring, and calibration. Three-session implementation followed `v1.2_Plan_2026-05-09.md`.

**Page change:** v1.1 was 141 pages; v1.2 is 153 pages (+12). Bibliography: 33 → 37 entries (+4 cognitive-science references).

**Session 1 (conceptual foundation):**
- Added §6 *How learning happens, and how AI changes it* — new section in Part I (~2 pages) naming five recurring findings from the science of learning: practice testing, distributed practice, interleaving, generation effect, desirable difficulties. Cites Roediger & Karpicke (2006), Bjork & Bjork (2011), Rohrer & Taylor (2007).
- Added §6.1 *The illusion of competence* — new subsection (~1 page) naming calibration error as the central concept and identifying the four illusions AI use widens: recognition–production gap, mastery illusion on transfer, effort illusion, authorship illusion. Cites Bjork & Bjork (2011), Dunlosky & Metcalfe (2009).
- Renamed Part II §"The instructor's central problem" → §"The instructor-side calibration problem" with three new opening paragraphs framing the assessment models as calibration-restoring designs.
- Added front-matter pointer in *How to read this book* directing readers to the new Foundations section.

**Session 2 (Tier-1 operational additions, fourteen items):**
- *Try first* step: metacognitive anchoring (write down where reasoning failed), errorful-generation framing (counterintuitive value of effortful unsuccessful attempts), productive-struggle threshold (10–15 min rule for routine homework).
- *Verify* step: spaced and interleaved retrieval as a follow-up move.
- *Reflect and disclose* step: two reflection prompts ("Why does each step work?" / "What changes if assumption weakened?") plus a weekly interleaved-retrieval habit.
- §11.1 STEM verification: compact 5-bullet math verification kit (special case, limiting case, units, known formula, independent route).
- Prompt library: bad/better prompt examples for proof-based mathematics (5 paired examples).
- §17 Practical study routine: when-then plan templates (implementation intentions).
- Student checklist: blank-page reconstruction item plus framing as the strongest single calibration check.
- §19 STEM example: proof-vs-computational mathematics distinction (student side).
- §31.2 Yellow assignments: help-ladder paragraph (concept → analogous example → hint → critique → ungraded full solution).
- §39.1 STEM overlay: proof-vs-computational paragraph (instructor side).
- §42 Implementation workflow: prepended three high-leverage moves for instructors under time constraints.

**Session 3 (Tier-3 polish, appendix, cross-references, tone sweep):**
- §33.3 *Equity in oral assessment* — new subsection in Oral-Defense Model with anxiety-reducing and inclusion guidance.
- Process-theater warning added to Evidence-of-Thinking Model (§33.1): process documentation should not be rewarded for length.
- Scaffolded-feedback boundary added to §35.1 Safe uses of AI for feedback: instructor AI prompts should produce hints not complete corrections.
- Tone-softening: two specific sentence-level revisions per Review 1 ("no longer mixed at the macro level" → "still heterogeneous, but a clear pattern is emerging"; "reduces it substantially" → "may help, but does not remove the need to verify"). Bounded sweep for similar overclaiming patterns found no other cases requiring modification.
- **Appendix D — Math-Specific Quick Reference** (new appendix, ~5 pages): consolidates math-specific patterns into a one-stop reference. Student-side proof-based and computational workflows; strong AI prompt patterns table (6 patterns); instructor-side course types × category mix table (6 course types); assessment artifacts list; fast design rules. Adapted from a reviewer-suggested draft.
- Cross-reference threading: brief calibration tags added at Verify subsection (Part I) and Hybrid Model section (Part II); the rest of the threading is already implicit in the Foundations section, the calibration subsection, the Part II opener, the blank-page-redo framing, the process-theater warning, and the equity subsection.

**Compile state:** 4-pass cycle clean — 0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings. 2 cosmetic overfull hboxes (same as v1.1: Python code line in Dialogue 4, TikZ figure in Appendix A). 21 cosmetic underfull hboxes (11 pre-existing in tabularx cells + 10 new in Appendix D's two tables). All cosmetic; SIAM production typesetting will handle.

**Bibliography additions (4):**
- `roediger2006test` — Roediger & Karpicke 2006, *Test-enhanced learning*, *Psychological Science*, DOI 10.1111/j.1467-9280.2006.01693.x. Web-verified.
- `bjork2011making` — Bjork & Bjork 2011, *Making things hard on yourself, but in a good way*, in Gernsbacher et al. (eds.) *Psychology and the Real World*, Worth Publishers, ISBN 9781429230438. Web-verified.
- `rohrer2007shuffling` — Rohrer & Taylor 2007, *The shuffling of mathematics problems improves learning*, *Instructional Science*, DOI 10.1007/s11251-007-9015-8. Web-verified.
- `dunlosky2009metacognition` — Dunlosky & Metcalfe 2009, *Metacognition*, SAGE Publications, ISBN 9781412939720. Web-verified.

**Packages produced (book convention, dated 2026-05-09):**
- `LearningWithAI_v1.2_2026-05-09.zip` — current COR, 5 files (tex, pdf, bib, README), 1.2 MB.
- `LearningWithAI_v1.2_CGR_2026-05-09.zip` — current CGR, 7 files (tex, pdf, bib, README, CITATION.cff, LICENSE), 1.2 MB.

**No structural breakage:** all chapter and section labels preserved; cross-references unchanged; existing appendices A, B, C unchanged. Three appendices become four (D added).

---

## Erratum (2026-05-04, post-cleanup discovery)

During session cleanup and pre-handoff sync, a fresh independent compile of v1.0 and v1.1 was run with corrected diagnostic grep patterns. The historical entries below for v0.998, v0.999, v1.0, and v1.1 reported "zero overfull/underfull hboxes" and "zero warnings of any kind." Those reports were based on a buggy grep pattern in the diagnostic check (over-escaped backslashes in the bash subshell that never matched the actual log lines).

The actual counts have been **2 overfull and 11 underfull hboxes** throughout v0.998 through v1.1. Severity:

- **2 overfull hboxes:** Line 883 (Dialogue 4, Python code line ~84pt past margin); line 3496 (Appendix A TikZ figure ~135pt past natural width). Minor; not blocking SIAM submission. SIAM production will handle in their layout pass.
- **11 underfull hboxes:** All inside `tabularx` table cells where text doesn't fill column width. Entirely cosmetic; not visible in rendered PDF.

The historical CHANGELOG entries below are preserved as written (honest audit trail of what was reported at the time, even though the measurement was wrong). The corrected understanding is reflected in:
- HANDOFF_ReviewPeriod.md §5 (Known Issues)
- MANUSCRIPT_STATUS.yaml (`compile_status` field)

The other diagnostics (0 errors, 0 undefined citations, 0 undefined references, 0 hyperref warnings) are correctly reported and verified.

---

## v1.1 — May 4, 2026 (post-v1.0 maintenance: NTA narrative audit + epigraph line-splits)

Post-v1.0 maintenance update. v1.0 remains the SIAM submission baseline (already attached to the Elizabeth Greenspan / Tammy Kolda email). v1.1 is the working version for continued editing during the SIAM review period.

**NTA (Narrative Thread Audit) on V1A/V1B/V1C content:**

Audited all newly-added prose from the three v1.0 enhancement sessions for drift relative to the manuscript's central thesis (students will use AI; the question is how to use it without surrendering one's own thinking; framework separates Core Competence, AI-Augmented Practice, and Responsible Judgment; supports varying practice across class size, level, and discipline; departmental adoption is the primary actionable level).

| Section audited | Paragraphs | Word count | Drift findings |
|---|---:|---:|---|
| Part I §Setting up your AI for learning (V1A) | 8 | 1,148 | 0 — all 6 starter-template elements operationalize specific framework practices (calibration, verification, integrity boundary). Living-document closing matches modest-tone ethic. |
| Part III §From department to institution bridge (V1B) | 6 | 708 | 0 — bridge section is a high-fidelity articulation of the rebalance argument. Each subsection cross-references existing book content appropriately. |
| Foreword abstract updates (V1C) | 2 textual edits | — | 0 — both changes are corrective alignments to V1B's Part III rename, not new content. |

**Result: 0 drift findings.** Light VES on factual claims also clean — no invented citations, all new empirical claims observational or supported by existing book citations.

**Epigraph review and line-split formatting:**

Surveyed all 7 epigraphs (Foreword + 3 Parts + 3 Appendices). Each was already strong on theme fit; no content rewrites warranted. Per Mac's request, applied line-split formatting to the 6 multi-sentence epigraphs:

| # | Location | New format | Lines |
|---|---|---|---:|
| 1 | Foreword | "AI changed how proofs are written. / It did not change what it means to understand one." | 2 |
| 2 | Part I | "A polished answer is not understanding. / AI can produce one and leave the other behind." | 2 |
| 3 | Part II | "The question is not whether a student used AI. / It is what the work still shows." | 2 |
| 4 | Part III | "A workable policy is not one rule for every course. / It is a vocabulary every course can use." | 2 |
| 5 | Appendix A | "Two transcripts. / One records what the student can prove. / The other records what they can responsibly verify." | 3 |
| 6 | Appendix B | "Three orthogonal axes. / A weak score on one cannot be paid off by a strong score on another." | 2 |
| 7 | Appendix C | "If a reviewer asks, the author should have an answer that does not begin with the tool." | 1 (kept) |

Implementation: `\\` inside the `\bookepigraph{}` argument. The macro's centered-italic minipage propagates centering and italics through line breaks naturally.

**Manuscript:**
- Page count: **141** (unchanged from v1.0; line splits add minimal vertical space within centered minipage)
- File size: .tex 325,595 bytes; .pdf 780,217 bytes
- Compile: clean 4-pass cycle. Zero errors, zero undefined citations, zero undefined references, zero hyperref warnings, zero overfull/underfull hboxes
- Bibliography: 33 entries unchanged

**v1.0 vs v1.1 distinction:**
- v1.0 = SIAM submission baseline, the version attached to Mac's email to Elizabeth and Tammy
- v1.1 = working version during the review period, continues to evolve as further edits accumulate
- Future significant updates increment as v1.2, v1.3, etc.

---

## v1.0 — May 4, 2026 (Session V1C: final v1.0 release production)

**v1.0 release complete.** Third and final session of the v1.0 enhancement pass (V1A → V1B → V1C). Manuscript is ready to send to Elizabeth Greenspan (SIAM Publishing Office) and Tammy Kolda (SIAM Vice President for Publications).

**XCR-equivalent integrity audit applied to V1B's Part III rename:**

The Part III rename from "An Institutional Guide" to "A Departmental and Institutional Guide" had two cascade effects in the Foreword abstract that V1C identified and corrected:

1. **Abstract third-audience description.** Was "universities developing coherent policy and practice"; now "academic departments and institutions developing coherent policy and practice." Matches Part III's new audience framing.
2. **Abstract Part III title reference.** Was "Part III, the Institutional Guide, gives departments and universities..."; now "Part III, the Departmental and Institutional Guide, gives departments and universities..." with the addition "...that work at the level where most decisions are actually made" to make the rebalance explicit.

The Foreword §"Who this book is for" subsection already correctly framed the third audience as "Departments and institutions" (had been written that way originally), so no change was needed there.

**Subtitle adjustment:**
- Primary subtitle preserved unchanged: "A Framework for Students, Instructors, and Universities"
- Secondary subtitle updated from "From Graduate Mathematics to Undergraduate Education and Institutional Policy" to "From Graduate Mathematics to Undergraduate Education, Departmental Practice, and Institutional Policy" across all three locations (preamble version comment, title-block author block, standalone titlepage)

This minimizes branding disruption (primary title stable for AID cover-letter and existing references) while making the departmental practice explicit in the secondary line.

**SPRE chapter-scope audit on new V1A and V1B prose:**
- AI-signature word audit: 0 violations on §setup; 0 violations on §From department to institution. (1 grep hit on "leverage" was a false positive — "highest-leverage" is normal English usage; the SPRE concern is about "leverage" used as buzzword verb, not as compound adjective.)
- Em-dash discipline check: 0 unicode em-dashes in new prose
- Modest-tone audit: 0 violations on "groundbreaking", "novel", "first to", "we prove", "pioneered" in new prose

**VLC/FRC final readiness check:**
- 0 TODO/FIXME/XXX markers in source
- Clean 4-pass compile from cleared aux files
- Version-comment match (preamble v1.0 ↔ MANUSCRIPT_STATUS v1.0)
- All critical artifacts present in outputs

**Updated AID document:**
Cover-letter draft to Elizabeth and Tammy now includes a paragraph noting that v1.0 incorporates feedback from initial reviewers — specifically the Part I §setup user-context-setup subsection (per first-reviewer feedback that students need to configure AI account preferences before using AI for coursework) and the Part III rebalance from "An Institutional Guide" to "A Departmental and Institutional Guide" (per second-reviewer feedback that the book overreaches by claiming whole-university scope when its primary readers operate at departmental level).

**Regenerated submission packages:**
- `LearningWithAI_v1.0_2026-05-04.zip` (COR — Overleaf submission package)
- `LearningWithAI_v1.0_CGR_2026-05-04.zip` (CGR — GitHub publication repository)

CITATION.cff in CGR package updated with version field set to 1.0.

**Updated MREP_FINAL_Project_Report.md** reflects v1.0 final state and post-feedback enhancements.

**Manuscript:**
- Page count: 141 (unchanged from v1.0_sessionB; V1C additions were cosmetic-textual rather than additive-paragraph)
- File size: .tex 325696 bytes; .pdf 780195 bytes
- Compile: clean 4-pass cycle. Zero errors, zero undefined citations, zero undefined references, zero hyperref warnings, zero overfull/underfull hboxes
- Bibliography: 33 entries unchanged

**Total cumulative growth from v0.999 → v1.0:** +5 pages (+3.7%), 0 new bibliography entries, 1 new Part I subsection, 1 new Part III bridge section, 4 new bridge subsections, abstract update, secondary subtitle adjustment.

**v1.0 is the source baseline for SIAM submission.** Future post-feedback updates from Elizabeth, Tammy, or subsequent reviewers will increment to v1.1, v1.2, etc.

---

## v1.0_sessionB — May 4, 2026 (Session V1B: Part III restructuring Phase 1)

Working state for v1.0 release. Second of three sessions (V1A → V1B → V1C) producing the v1.0 post-feedback substantive revision.

**Trigger:** Second-reviewer feedback that the book overreaches by claiming whole-university scope when its primary readers (math/science/engineering faculty and graduate students) have departmental influence rather than institutional influence. Reviewer recommended refocusing Part III entirely on department-level. Mac and Claude agreed on a rebalance rather than refocus to preserve both audiences without diluting either.

**Approach taken:**
The original Session V1B plan called for inserting an explicit §Departmental framework block-divider, demoting the existing 12+ sections to subsections within it, and then inserting a separate §Institutional framework block. An attempt at this surfaced a structural problem: the existing Part III section ordering interleaves topics that span the department/institution boundary (Privacy and Equity sit between department-actionable topics like Disclosure standard and department-actionable topics like Faculty use of AI), which would have required substantial cut-and-paste reorganization with high risk of breaking the carefully-developed prose. Instead, V1B took a lighter-touch approach: the rebalance is communicated through Part III's title, intro framing, and a new bridge section that explicitly addresses how departmental practice can shape institutional policy. The existing section structure is preserved.

**Three changes applied:**

1. **Part III renamed.** "An Institutional Guide" → "A Departmental and Institutional Guide". Title cascade affects the part heading on the part-divider page; existing label `part:institutional` preserved so all forward-references from main text resolve unchanged.

2. **Part III intro rewritten with three-movement framing.** New 4-paragraph intro explicitly addresses primary readers (math/science/engineering faculty/graduate students with departmental influence) and secondary readers (deans/provosts/central administrators with institutional influence). Explains the three-movement organization: shared foundations (Purpose-and-scope through Disclosure-standard); predominantly institutional topics (Privacy through Risk-register); shared forward-looking and reference material (Looking-forward through Reference-materials). Calibration commitment: prose throughout speaks to whichever level the section is primarily addressing, while shared topics address both audiences.

3. **New §From department to institution bridge section** added between §Faculty change management and §Looking forward (label `u:sec:dept-to-institution`). Four subsections:
   - §The pattern in practice — how departmental practice typically becomes the seed for institutional policy in mathematics, science, and engineering settings
   - §What departmental faculty can do to support the bridge — four concrete actions (document; participate in working groups; share with adjacent departments; name needed institutional support)
   - §What departments should ask of their institution — list of five things institutions are usually willing to provide once asked specifically (privacy/data-governance policy; centrally supported tool licenses; integrity procedure compatible with department-level evidence; merit-review recognition of redesign time; teaching-center workshop services). Cross-references existing Cost-and-resource-considerations from v0.998 and existing §integrity from v0.994.
   - §The honest limit — explicit acknowledgment that some institutional decisions are out of departmental hands and that departmental practice is valuable regardless of institutional adoption

**Compile correction:** First v1.0_sessionB compile produced one undefined-reference warning (used `u:sec:academic-integrity` when actual label is `u:sec:integrity`). Fixed; final compile fully clean.

**Manuscript:**
- Page count: 138 → **141** (+3)
- File size: .tex 325488 bytes; .pdf 780051 bytes
- Compile: clean 4-pass cycle. Zero errors, zero undefined citations, zero undefined references, zero hyperref warnings, zero overfull/underfull hboxes.
- Bibliography: 33 entries unchanged

**Preserved from v1.0_sessionA:**
- §Setting up your AI for learning subsection in Part I
- Forward-references from §AI Learning Loop and Appendix C §C.2
- All 5 figure labels (Session 8a updates)
- All HR consensus enhancements from v0.998 (Bastani temporal caveat, Liang temporal caveat, Cost-and-resource-considerations, persistent-skeptic subsection, STEM-tilt acknowledgment)
- All earlier-session work (UNESCO crosswalks, three-axis design frame, Part III §implementation UNESCO usage paragraph, Appendix B §B.9 Kosar paragraph, Appendix C §C.3 Liang fairness paragraph, Appendix C §C.4 Fan metacognitive paragraph)

**Next:** Session V1C — Part III restructuring Phase 2: XCR-equivalent integrity audit on monograph-scale cross-references that may have been affected by Part III renaming, SPRE chapter-scope on new V1A and V1B prose, subtitle/title decision, final v1.0 packaging with COR/CGR regeneration and updated AID document. v1.0_sessionB is the input baseline for Session V1C.

---

## v1.0_sessionA — May 4, 2026 (Session V1A: Part I user-context-setup subsection)

Working state for v1.0 release. First of three sessions (V1A → V1B → V1C) producing the v1.0 post-feedback substantive revision.

**New subsection added:** `\section{Setting up your AI for learning}` (label `sec:setup`) inserted at the front of Part I, between §Why this guide exists and §Learning outcomes. The subsection addresses a real gap identified by the first reviewer: students opening fresh AI conversations don't realize the AI cannot tell whether they are a kindergarten student or a Nobel laureate, and the framework's later practices (C/A/R, the AI Learning Loop, verification) implicitly assume calibration that account-level preferences make possible.

**Structure of the new subsection:**

1. Opening paragraph framing the calibration problem and the day-one cost of skipping setup.
2. Six-element starter template, presented as a numbered list with inset starter quotes the student can adapt:
   - **Element 1** Who you are and what you are studying — tells AI to calibrate to year/department/courses
   - **Element 2** How you want explanations pitched — includes the "ask me what I already know rather than assuming" instruction
   - **Element 3** How you want uncertainty handled — flags AI hallucination concerns and asks AI to mark its own uncertainty
   - **Element 4** Writing style preferences — includes explicit English-as-second-language clause that cross-references the Liang detector-bias treatment in Part III and Appendix C, providing ESL students with a self-protection mechanism
   - **Element 5** Scope of use and integrity boundary — reminds student that account-level preferences do NOT override assignment-level rules; cross-references the four assignment categories
   - **Element 6** Optional technical-work accuracy guard — for STEM students specifically, asks AI to label confidence claims and show work
3. "Living document" framing paragraph — preferences are something that grow over two-to-three semesters of use, not something to perfect on day one.
4. Pointer to platform documentation — deliberately NOT screenshotted (UIs change too fast); pointer is to ChatGPT, Claude, Gemini, Copilot documentation pages and to institutional library/IT/teaching-center guides.

**Forward-references added:**

- §The AI Learning Loop intro: "The loop assumes you have already configured your AI account so it knows who you are and how you want it to respond. If you have not done that yet, do it now using the starter template in \cref{sec:setup}; the loop's calibration depends on that configuration."
- Appendix C §C.2 verification cornerstone: paragraph noting that researchers benefit from the same configuration practice; the student-facing version transfers directly to research use, particularly the technical-work accuracy guard for research-grade writing.

**Two minor label-name typos corrected:**

The first compile pass surfaced two undefined-reference warnings (`sec:four-categories` should have been `sec:assignment-categories`; `sec:loop` should have been `sec:learning-loop`). Both fixed; final compile clean.

**Manuscript:**
- Page count: 136 → **138** (+2)
- File size: .tex 317607 bytes (was 309029); .pdf 771151 bytes (was 762203)
- Compile: clean 4-pass cycle. Zero errors, zero undefined citations, zero undefined references, zero hyperref warnings, zero overfull/underfull hboxes.
- Bibliography: 33 entries unchanged.

**Next:** Session V1B — Part III restructuring Phase 1 (rebalance from "An Institutional Guide" to "A Departmental and Institutional Guide" per second-reviewer feedback). v1.0_sessionA is the input baseline for Session V1B.

---

## v0.999 — May 4, 2026 (MREP Session 8b: title page + acknowledgments cleanup + TOC newpage)

Pre-COR/CGR-packaging adjustments per Mac's request before producing the SIAM submission package.

**Three changes applied:**

1. **Standalone title page** — replaced `\maketitle` (which produced an article-style title block flowing into the abstract) with a `titlepage` environment. The title page now occupies page 1 alone, with the title centered vertically using `\vfill`, the "Preliminary version" note moved to the bottom, and `\setcounter{page}{0}` inside the titlepage to ensure the abstract starts cleanly on page 1 without a hyperref page-anchor collision.

2. **Acknowledgments section rewritten:**
   - Removed all `[colleague names to be inserted]` and `[institutional contacts]` placeholders that had been awaiting Mac's name list
   - Removed the `[Optional: dedication to be added if Mac wishes]` line per Mac's request
   - Rewrote the opening paragraph to thank friends and colleagues at Tulane University and Los Alamos National Laboratory for the critical feedback and discussion on AI-assisted learning that shaped the framework, per Mac's instruction
   - Preserved the second paragraph (about the AI-assistance disclosure model) and the third paragraph (about transparent disclosure as a recommended practice)

3. **Table of Contents starts on its own page** — added explicit `\newpage` before `\tableofcontents` (in addition to the existing `\newpage` after) so the TOC is preceded and followed by clean page breaks rather than continuing from the prior content.

**Manuscript:**
- Page count: 135 → 136 (+1 from standalone title page)
- File size: .tex 309029 bytes (was 308628); .pdf 762203 bytes (was 734885)
- Compile: clean 4-pass cycle. Zero errors, zero undefined citations/references, **zero hyperref warnings** (the `page.1` duplicate-anchor warning that briefly appeared in initial v0.999 compile was eliminated by the `\setcounter{page}{0}` fix), zero overfull/underfull hboxes
- Bibliography: 33 entries unchanged

**v0.999 is now the source baseline for COR (Overleaf submission) and CGR (GitHub publication) packaging.**

---

## v0.998 — May 4, 2026 (MREP Session 8a Terminal Phase 1: XCR + HR + LRV + 5 updated figures + consensus fixes)

Terminal-phase consolidated production pass. XCR (Cross-Chapter Review) Phases 1-7 passed with 2 minor consistency findings; HR (Harsh Review) book-panel returned CONDITIONAL ACCEPT with 3 HIGH + 1 MEDIUM consensus issues; LRV terminal bibliography review passed (after correcting an earlier grep bug that had falsely flagged 4 entries as orphans — all 33 entries are validly cited inline). Mac uploaded 5 updated TikZ figures during this session. All approved fixes applied in a single coordinated pass.

**5 TikZ figures updated** (from Mac's revised source):
- `fig:two-transcripts` (figureA) — Foreword two-transcript design diagram
- `fig:car-mae` (figureB) — Foreword C/A/R-as-generalization-of-M/A/E diagram
- `fig:learning-loop` (figureC) — Part I AI Learning Loop five-step cycle
- `fig:verification-disciplines` (figureD) — Part I verification-by-discipline diagram
- `fig:plan-use-verify` (figureE) — Part II Plan-Use-Verify assignment-structure diagram

A stray `\end{document}` in figureE.tex's source was removed during integration to prevent premature manuscript termination.

**XCR mechanical fixes (2):**
- Foreword line 319: converted two unicode em-dashes to `---` (LaTeX convention)
- 6 bare `\cite{}` calls normalized to `\citep{}` for plainnat-style consistency (47 → 52 \citep total)

**HR consensus content additions (4):**
- **C-1 in Part III §implementation:** New subsection §"Cost and resource considerations" addressing implementation-cost dimensions (faculty time, TA support, calibration scheduling), low-cost adoption path for resource-constrained departments, and explicit guidance on UNESCO-crosswalk usage during institutional adoption. Connects the C/A/R↔UNESCO mappings to practical accreditation/curriculum-revision use. ~½ page.
- **C-2 Foreword + Part II:** Brief temporal/scope caveats added to the Bastani Foreword anchor ("examined a single secondary-mathematics intervention period; replication... still accumulating") and the Liang Part II §academic-integrity treatment ("specific rates above were measured on the detector tools available in 2023; subsequent detector generations may reduce the false-positive rate, but the structural concern... is intrinsic to the detection method"). Preserves modesty about generalizing specific empirical numbers.
- **C-3 in Part III §faculty-change-management:** New subsection §"When the standard playbook is not enough" addressing persistent-skeptic scenarios beyond the four-adopter-category model. Includes guidance on department-governance approaches, course-assignment strategies, and the important distinction between obstruction and substantive dissent. ~¼ page.
- **C-4 in Foreword §"What this book is not":** Added paragraph acknowledging the discipline coverage tilt to STEM and explicitly noting that humanities, qualitative social sciences, and arts adoption will require disciplinary expert adaptation. Strengthens scope honesty.

**LRV terminal correction:**
The earlier LRV report (XCR_Report_v0_997.md companion) flagged 4 entries (bertramgallant2008academic, mollick2023assigning, usde2023artificial, ma2025meta) as orphans. Re-checking with corrected grep (multi-key citations like `\citep{a,b}` were not being counted by the original pattern) confirmed all 4 entries are validly cited inline. **No bibliography changes were needed.**

**Bibliography:** 33 entries, no changes (the new C-1 paragraph adds a second citation point for usde2023artificial, which strengthens its placement).

**Manuscript:**
- Page count: 133 → 135 (+2 from C-1 + C-3 + C-4 prose additions)
- File size: .tex 308628 bytes (was 302409); .pdf 734885 bytes (was 728214)
- Compile: clean 4-pass cycle. Zero errors. Zero undefined citations/references. Zero hyperref warnings. Zero overfull/underfull hboxes. **Same exceptional quality bar as v0.997 maintained**.

**EVP (Excellence Verification Protocol) assessment:** Not triggered. XCR/HR/LRV findings were all addressable through the consolidated v0.998 production pass; no element scored below the implicit Excellence-First threshold requiring re-enhancement. Manuscript is at target quality for SIAM monograph submission.

**ARP (Audience Reachability Protocol) for Foreword assessment:** PASS after C-4 addition. Foreword now reaches all four declared audiences (graduate-mathematics researchers via the GMIP lineage; undergraduate instructors via C/A/R generalization; institutional administrators via Part III preview; international/UNESCO-aligned readers via the crosswalk references). The C-4 STEM-tilt acknowledgment also addresses the implicit fifth audience of humanities/qualitative-social-science readers by setting expectation appropriately.

---

## v0.997 — May 4, 2026 (MREP Session 7: Appendix C Sci writing MCR + SIA + Tier C Liang ICLR + Fan)

Multi-Chapter Review (MCR) of Chapter 6 (Appendix C — Best Practices for Ethical AI-Assisted Scientific Writing). Applied SIA `--mode=monograph-appendix` per MREP v5.0.4 protocol, plus two Tier C opportunistic enhancements including the Liang ICLR-research-context citation deferred since Session 5.

**SIA `--mode=monograph-appendix` Phase 0 assessment: MINIMAL.**
Appendix C is principles/practices/checklists/disclosure templates for ethical AI-assisted scientific writing — no formal theorems with proofs deferred from main chapters; no simulations; no data tables.

**SIA Phase 6 cross-reference integrity: PASS.**
- 7 forward references from main text to Appendix C verified accurate (Foreword acknowledgment-disclosure-model reference; Part I's verification-and-disclosure dialogue at lines 782, 788, 833 anchors; Part I §verification line 891 mentioning "fuller verification protocol... addresses research-grade work specifically"; Part I line 1003 graduate research raises the verification bar; Part III §"What is likely to stay the same" line 2977 disclosure-norms reference).
- 2 backward references from Appendix C verified (Part~\ref{part:student} + Appendix~\ref{app:gmip} on line 3665; Appendices~\ref{app:gmip} and~\ref{app:mae} on line 3782).
- 1 internal label (app:sciwriting) used 7× from elsewhere ✓.
- No drift between main-text claims about Appendix C and the appendix's actual content.

**Appendix C §C.3 Disclosure guidelines — Tier C primary (deferred from Session 5):**
Added new \paragraph{Fairness considerations in detector-based screening.} after the existing closing paragraph on under/over-disclosure tradeoffs. The new paragraph addresses journal-side use of AI-text detectors and the documented unfairness for non-native-English authors. Anchors with Liang 2023's ICLR 2023 finding (papers by first authors from non-English-native countries showed systematically lower text perplexity than papers by English-native first authors) and the same study's 61.3% average false-positive rate on TOEFL essays. Explains the perplexity-mechanism cause (lower lexical/syntactic variability misread as AI-generation), provides practical guidance (be prepared to provide process evidence: drafts, revision history, prompt logs), and connects back to Appendix C's detailed-disclosure standards as the evidence-based response. Closes with broader implication: research-publishing community should treat detector output as one signal among several, not as a basis for editorial decisions.

**Appendix C §C.4 Common pitfalls — Tier C secondary:**
Modified existing "Accepting unverified analysis" pitfall paragraph. Added one sentence introducing Fan 2025's metacognitive-laziness mechanism as the empirical anchor for the cognitive-offloading pattern that the pitfall describes. Brief contextualization (educational research literature, focus on student learning, mechanism applies to research writing as well) preserves modest tone and scope honesty.

**Bibliography:** 33 entries, no changes. Both new citations (`liang2023gpt`, `fan2025beware`) were already added to the bibliography in earlier sessions (Sessions 2 and 3 respectively).

**Manuscript:**
- Page count: 132 → 133 (+1; the §C.3 fairness paragraph is the larger of the two additions).
- Compile: clean 4-pass cycle. Zero errors. Zero undefined citations.
- Liang citation count in main + appendices: 6 (Foreword, Part II detector-bias, Part III academic-integrity-procedure, Part III What-is-likely-to-change, Part III stable-finding, Appendix C fairness).
- Fan citation count: 2 (Part II central-problem, Appendix C accepting-unverified-analysis).

---

## v0.996 — May 4, 2026 (MREP Session 6: Appendix B M/A/E policy framework MCR + SIA + Tier C Kosar)

Multi-Chapter Review (MCR) of Chapter 5 (Appendix B — AI-Integrated Graduate Mathematics Assessment Framework). Applied SIA `--mode=monograph-appendix` per MREP v5.0.4 protocol, plus one Tier C opportunistic enhancement.

**SIA `--mode=monograph-appendix` Phase 0 assessment: MINIMAL.**
Appendix B is policy/operational reference material (purpose, core principles, M/A/E competency model, assessment structure, instruments, oral exam framework, documentation requirements, grading rubrics, safeguards, implementation phases, expected outcomes) — no formal theorems with proofs deferred from main chapters; no simulations; no data tables. Standard MCR coverage suffices for this content type.

**SIA Phase 6 cross-reference integrity: PASS.**
- 6 forward references from main text to Appendix B verified to describe what Appendix B actually contains (Foreword, Foreword again on M/A/E preservation, Part II §C/A/R framework, Part III §C/A/R framework cross-references, Appendix A companion-document mention, Appendix C verification-habits cross-reference).
- 1 reference from Appendix B to main text verified (line 3490 → Appendix~\ref{app:gmip}).
- 1 label defined within Appendix B (app:mae) verified active and used 6× from elsewhere.
- No drift between main-text claims about Appendix B and the appendix's actual content.

**MCR Phases 0-5:**
- Phase 0 (thread verify): PASS. Appendix B's stated purpose ("department-level policy formulation that complements the GMIP technical reference") and content unchanged by Sessions 2-5 main-text changes.
- Phase 1 (VEE + VES): PASS. No mathematical or factual claims requiring verification; appendix has no external citations until this session.
- Phase 2 (GSR chapter-scope): PASS. Eleven subsections (B.1-B.11) preserved; logical flow sound.
- Phase 3 (SMR chapter-scope, opportunistic Tier C check): ONE ENHANCEMENT APPLIED. Added Kosar 2024 paragraph in §B.9 "Safeguards against AI substitution" as cross-discipline empirical validation. Kosar's CS course redesign (paper-and-pencil mid-terms, oral defenses in lab time, GenAI-resistant home assignments) operationalizes three of the four safeguards Appendix B recommends, with reported equivalent learning outcomes for with-AI and without-AI cohorts. Citation includes appropriate scope caveat (CS course, not graduate mathematics; broadly consistent rather than direct evidence).
- Phase 4 (SPRE chapter-scope): clean. New prose uses modest tone with explicit caveat ("Although direct empirical evidence on graduate-mathematics adoption of these specific safeguards is not yet available").
- Phase 5 (FTQ chapter-scope): clean 4-pass compile.

**Bibliography:** 33 entries, no changes (kosar2024computer was already added in Session 3).

**Manuscript:**
- Page count: 132 (unchanged from v0.995; new paragraph absorbed within existing layout).
- File size: 300384 bytes (.tex), up from 299344 bytes — the diff captures the new Kosar paragraph + version comment.
- Compile: clean 4-pass cycle. Zero errors. Zero undefined citations.

---

## v0.995 — May 4, 2026 (MREP Session 5: Appendix A GMIP MCR + SIA monograph-appendix mode)

Multi-Chapter Review (MCR) of Chapter 4 (Appendix A — Graduate Mathematical Intelligence Profile). Applied SIA `--mode=monograph-appendix` per MREP v5.0.4 protocol.

**SIA `--mode=monograph-appendix` Phase 0 assessment: MINIMAL.**
GMIP appendix contains framework descriptions, eight competency domains, two-transcript design, assessment architecture, grading scheme, future-proofing stress tests, operational policy, and templates. No formal theorems with proofs deferred from main chapters; no simulations; no data tables. Standard MCR VEE coverage suffices for this content type. SIA Phase 6 (cross-reference integrity) is the only sub-phase warranted.

**SIA Phase 6 cross-reference integrity: PASS.**
- 8 forward references from main text to Appendix A verified to describe what GMIP actually contains (Foreword, Part I §C/A/R, Part II §C/A/R, Part II §STEM example, Part III §C/A/R, two cross-Appendix references).
- 4 references from Appendix A to main text verified to resolve correctly (\cref{fig:gmip-domains}, Part I, Part II, Appendix B).
- 2 labels defined within Appendix A (app:gmip, fig:gmip-domains) verified active.
- No drift between main-text claims about Appendix A and the appendix's actual content.

**MCR Phases 0-5:**
- Phase 0 (thread verify): PASS. Appendix A's stated purpose and content unchanged by Sessions 2-3.5-4 main-text changes.
- Phase 1 (VEE + VES): PASS. No mathematical or factual claims to verify; appendix content was carefully verified pre-MREP.
- Phase 2 (GSR chapter-scope): PASS. Eight subsections (A.1-A.8) preserved; logical flow sound.
- Phase 3 (SMR chapter-scope, opportunistic Tier C check): No Tier C enhancements applied. Evaluated four candidates (Liang ICLR-research-context, Kestin STEM, Bastani metacognitive, Kosmyna neuroscience); none fit naturally in graduate-mathematics-assessment context. Per HANDOFF guidance: default to no enhancement when placement is not clearly improving.
- Phase 4 (SPRE chapter-scope): No prose changes. Existing prose uses modest tone.
- Phase 5 (FTQ chapter-scope): clean 4-pass compile.

**Bibliography:** 33 entries, no changes.

**Manuscript:**
- Page count: 132 (unchanged from v0.994).
- Compile: clean 4-pass cycle. Zero errors. Zero undefined citations.
- Version-comment-only change to .tex; the v0.995 bump captures the verification work documented in MREP_Session5_Report.md and the SIA monograph-appendix Phase 0/6 assessment.

---

## v0.994 — May 4, 2026 (MREP Session 4: Part III Institutional Guide content enhancement)

Multi-Chapter Review (MCR) of Chapter 3 (Part III — Institutional Guide). Implemented Tier A + Tier B + Tier C enhancements scoped to Part III per the Tier-1 source content analysis.

**Part III §"Academic integrity procedure" — Tier A:**
- Liang 2023 substantially expanded: anchored 61.3% non-native FPR, 19.8% unanimous misclassification, 97.8% flagged-by-at-least-one-detector specific bias rates.
- Added text-perplexity mechanism explanation (why detectors fail).
- Added two-direction failure framing (false positives concentrate on multilingual writers; false negatives accrue to students with prompt-refinement skill).
- Added "presumption of guilt" institutional-trust framing with reputational-consequence note.

**Part III §"What is likely to change" — Tier A:**
- Strengthened the existing one-sentence reference to Liang's detector-bias finding into a fuller two-direction-failure paragraph: detectors are already failing in two directions, with both directions projected to worsen as detector vendors tune for false-positive control and as student prompting skill becomes ubiquitous.

**Part III §"Implementation plan" — Tier B:**
- Added opening paragraph citing UNESCO's 7-step regulatory framework for GenAI in education (data protection; whole-of-government AI strategies; ethics regulations; copyright; GenAI-specific frameworks; capacity building; long-term implications). Positions the four-phase institutional plan that follows as the institutional-level operationalization within whatever national regulatory environment applies.

**Part III §"What is likely to stay the same" — Tier B:**
- Added paragraph on UNESCO's 4 categories of AI-era learning outcomes (Values; Foundational knowledge and skills; Higher-order thinking skills; Vocational skills). Maps the four categories explicitly onto C/A/R: Core Competence ↔ Foundational; Responsible Judgment ↔ Values + critical-evaluation portion of Higher-order thinking; AI-Augmented Practice ↔ Vocational skills + human-AI-collaboration portion of Higher-order thinking.

**Part III §"Evidence base and limits" — Tier C:**
- Added performance-versus-learning gap as a third stable institutional-level finding alongside detector unreliability and privacy/equity concerns. Frames OECD's central evidentiary distinction (apparent quality vs. durable learning) as the institutional-evaluation lens that keeps AI policies honest.

**Bibliography:**
- 33 → 33 entries (no changes; all Session 4 citations use existing bibliography entries).
- Compile: clean 4-pass cycle. Zero errors. Zero undefined citations.
- Page count: 131 → 132 (+1 from enhancement paragraphs; the Part III enhancements were predominantly sentence-level and additive-paragraph rather than new structural sections).

---

## v0.993 — May 4, 2026 (MREP Session 3.5: Three-axis design frame)

A coordinated mini-pass addressing a structural ambiguity raised by Mac: was the manuscript's primary instructor-design distinction "undergraduate vs graduate," "small vs large class," or some combination? Implemented a three-axis frame (class size, course level, discipline) and propagated the clearer framing through the bound volume.

**Phase A — New Part II section: \ref{i:sec:three-axes} "Three design axes: class size, level, and discipline":**
- New \ref{tab:three-axes} mapping each axis to what it drives and where in Part II it is treated.
- One paragraph each for class size (drives assessment-model selection), course level (drives Core Competence definition + category mix + AI autonomy), and discipline (drives verification specifics).
- Closing paragraph noting the three axes are largely independent (a small graduate seminar and a small first-year writing class share assessment-model options but differ in category mix; a large intro course and a large advanced course share model constraints but differ in verification specifics).
- Section placed between §central-problem and §C/A/R framework, where it naturally sits as a navigational aid for the rest of Part II.

**Phase C — New Part II subsection: \ref{i:subsec:category-by-level} "Category mix shifts with course level":**
- Added at end of §Four assignment categories.
- Explains that introductory courses lean Red/Yellow (because verification capacity is being built); intermediate courses use a balanced mix; advanced and graduate courses lean Green/Blue (because verification capacity is established).
- Explicitly notes the shift is not driven by class size — a 200-student intro lecture and a 12-student intro seminar share the typical Red/Yellow weighting; small and large graduate-equivalent courses share Green/Blue weighting.

**Phase B — Whole-volume audit and prose cleanup:**
- Foreword §"What to expect" §"A note on multiple audiences": rewrote the previous "undergraduate vs graduate as distinct populations" framing to use the three-axis frame explicitly. Cross-references new Part II §Three design axes section.
- Part I §"Small classes and the Oral-Defense Model" opening: clarified that the model's defining feature is class size, not course level.
- Part I §"Large classes and the Evidence-of-Thinking Model" opening: same clarification — class-size-driven, not level-driven.
- Part II §"The Oral-Defense Model" opening: revised list ("small classes of any level") and added cross-reference to the category-by-level subsection.
- Part II §"The Evidence-of-Thinking Model" opening: same parallel revision.
- Part III §Purpose-and-scope closing: replaced "designed for undergraduate education... can be adapted for graduate" with three-axis framing pointing to Part II §Three design axes.

**Bibliography:**
- 33 → 33 entries (no changes).
- Compile: clean 4-pass cycle. Zero errors. Zero undefined citations.
- All forward references in new content (\cref{i:sec:oral-defense-model}, \cref{i:sec:evidence-model}, \cref{i:sec:hybrid-model}, \cref{i:sec:assignment-categories}, \cref{i:sec:rubrics}, \cref{i:sec:discipline-overlays}) verified to resolve correctly.
- Page count: 128 → 131 (+3 from new section, new subsection, and revised passages).

---

## v0.992 — May 4, 2026 (MREP Session 3: Part II Instructor Guide content enhancement)

Multi-Chapter Review (MCR) of Chapter 2 (Part II — Instructor Guide). Implemented Tier A + Tier B + Tier C enhancements scoped to Part II per the Tier-1 source content analysis.

**Part II §"Instructor outcomes" — new subsection:**
- Added \ref{i:subsec:instructor-unesco} "Relation to international AI competency frameworks for teachers" with \ref{tab:instructor-unesco} mapping instructor outcomes to UNESCO's 5-aspect / 15-block teacher framework (Miao 2024b). Mirrors the C/A/R↔UNESCO student-framework crosswalk added to Part I in Session 2.

**Part II §"The instructor's central problem":**
- Added Fan 2025 ("metacognitive laziness") and Chen 2025 ("cognitive offloading") mechanism naming. These two new citations make explicit the mechanisms by which a polished AI-assisted artifact can hide reduced learning.

**Part II §"Designing assignments that preserve thinking":**
- Added Kestin 2025 paragraph on the seven research-based pedagogical practices identified in the Harvard physics RCT (active engagement, cognitive load, growth mindset, scaffolding, accuracy, timely feedback, self-pacing).
- Added Bastani 2025 paragraph contrasting the unrestricted-AI vs guardrailed-tutor design choice, framing this as direct empirical validation of the Yellow assignment category (AI as hint-giver, not solver).

**Part II §"The Hybrid Model":**
- Added Kestin 2025 flipped-classroom integration recommendation (AI tutor for first contact with material; class time for higher-order tasks).
- Added Kosar 2024 paragraph as direct empirical validation of the Oral-Defense and Evidence-of-Thinking models (CS course redesign with paper-and-pencil mid-terms, lab-time oral defenses, and GenAI-resistant home assignments achieved similar learning outcomes for with-AI and without-AI cohorts).

**Part II §"Feedback and grading with AI" / §safe-feedback subsection:**
- Added Wang 2024 (Tutor CoPilot) paragraph documenting the +4% pass rate / +9% gain for less-experienced tutors, illustrating constructive AI-supports-human design.

**Part II §"Academic integrity without detector dependence":**
- Liang 2023 substantially expanded: anchored 61.3% non-native FPR, 19.8% unanimous misclassification, 97.8% flagged-by-at-least-one-detector specific bias rates.
- Added text-perplexity mechanism explanation (why detectors fail).
- Added "presumption of guilt" institutional-trust framing.
- Added two-direction failure framing (false-positives against multilingual writers + false-negatives via prompted literary language).

**Part II §"Academic integrity" — new subsection:**
- Added \ref{i:subsec:detector-self-check} "A constructive role for detectors" — Liang 2023's Yellow-category use case for detectors as student-facing self-check aids.

**Bibliography:**
- 29 → 33 entries (+4 new entries, all VER:pending sourced via OECD 2026 reference list):
  - `kosar2024computer` — Mathematics 12(5):629, doi:10.3390/math12050629
  - `wang2024tutor` — Annenberg Inst EdWP 24-1056, doi:10.26300/81nh-8262
  - `fan2025beware` — BJET 56(2):489-530, doi:10.1111/bjet.13544
  - `chen2025unpacking` — Computers & Education 226:105198, doi:10.1016/j.compedu.2024.105198
- Compile: clean 4-pass cycle. Zero errors. Zero undefined citations.
- Page count: 124 → 128 (+4 from enhancements; the UNESCO teacher-framework crosswalk subsection + table is the largest single addition).

---

## v0.991 — May 4, 2026 (MREP Session 2: Part I + Foreword content enhancement)

Multi-Chapter Review (MCR) of Chapter 1 (Part I — Student Guide) plus the Foreword. Implemented Tier A + Tier B + selective Tier C enhancements identified by the Tier-1 source content analysis (8 sources analyzed in depth; europeancommission2022ethical content unavailable).

**Foreword enhancements:**
- §"What this book is not": Bastani et al.\ findings anchored in specific quantitative results (+48% / +127% practice gains; -17% exam loss with unrestricted AI; metacognitive blindness — students do not perceive their own learning loss).

**Part I §"Why this guide exists" enhancements:**
- Added FAA / autopilot analogy (pilots minimize autopilot to maintain skills).
- Added Bastani metacognitive blindness finding as foundation for objective Core Competence assessment.
- Added OECD performance-vs-learning framing.

**Part I §"Dangerous uses of AI" enhancement:**
- Added UNESCO "writing without thinking" framing (Miao 2023) to §"Do not outsource first contact".

**Part I §C/A/R framework — new subsection \ref{subsec:car-unesco}:**
- Added "Relation to international AI competency frameworks" subsection.
- New table \ref{tab:car-unesco} maps C/A/R to UNESCO's 4-aspect / 12-block student framework (Miao 2024a).
- Positions C/A/R as a focused subset of UNESCO's broader competency map applied to assessment of academic work.

**Part I §"The AI Learning Loop" / Try-First step:**
- Added Kosmyna 2025 neuroscientific evidence (12% LLM-group recall vs 89% no-AI; lower neural activation; "writing alone first preserves recall" finding).
- Note: kosmyna2025brain VER:pending (cited via OECD 2026; full Mac VER deferred).

**Part I §"How to ask better AI questions":**
- Added utility-amplifier reframing (Dunlosky 2013): AI amplifies whichever study technique is requested; high-utility techniques (practice testing, distributed practice, elaborative interrogation, self-explanation) yield strong amplification, low-utility techniques (highlighting, rereading, unread-content summarization) yield weak amplification.

**Part I §"How to verify AI-assisted work":**
- Added Dunlosky self-explanation framing as cognitive habit underneath verification.

**Part I §"Evidence base and limits of the guide":**
- Substantially strengthened. Reframed "evidence is mixed" → "results converge on a single conclusion: design determines outcome".
- Anchored in specific Bastani 2025 numbers (1000 students, 48%/127%/-17%).
- Strengthened Kestin 2025 claim (RCT, learning gains over double in-class active learning, p < 10^-8) with appropriate scope caveat.
- Added convergent-mechanisms naming: cognitive offloading, metacognitive laziness, crutch pattern, neuroimaging evidence.

**Bibliography:**
- 28 → 29 entries (added kosmyna2025brain VER:pending).
- Compile: clean 4-pass cycle (pdflatex + bibtex + 3× pdflatex). Zero errors. Zero undefined citations.
- Page count: 121 → 124 (+3 from enhancements; primarily from new C/A/R↔UNESCO crosswalk subsection and the strengthened evidence-base section).

---

## v0.99 — May 4, 2026 (Session 8 TIP pass)

**Type:** Term-inference protocol pass — 1 Major + 2 Note findings resolved

**Summary:** Applied TIP v2.0 (Term Inference Protocol) to v0.98. Audited all Tier 1 universal terms, all Tier 2 frequently-misused terms, and 16 manuscript-specific Tier 3 terms. Tier 1 / Tier 2 sweep was clean — every potentially-flagged term turned out to be in colloquial use with no inference risk, because this is a pedagogical/policy book rather than a quantitative-modeling text. Three findings were raised, all in book-defined terms; all three resolved per Mac's approval.

**Changes:**

- **TIP Finding 1 (Major) — Appendix C §C.2 verification cornerstone.** Replaced "the author's validated scientific contribution" with "a contribution the author can defend before peer review and disciplinary critique." Verification (the book's defined sense: checking AI output against sources/methods/reasoning) is necessary but not sufficient for scientific validation in the formal sense (peer review + replication + disciplinary critique). The previous wording invited the inference *verified = validated*, which would have led junior researchers to submit AI-assisted manuscripts on the assumption that author-side verification suffices. The new wording preserves rhetorical force, removes the false equivalence, and pedagogically primes the reader for the downstream filters that §C.4 then names.

- **TIP Finding 2 (Note) — assessment validity glossary anchor.** Added a one-sentence "Assessment validity" entry to the Part II shared glossary (alphabetically between AI-assisted work and Core Competence) and to the Part III shared vocabulary (between AI-generated output and Disclosure). The term was used 8+ times across Parts II and III as a load-bearing concept but never defined. STEM-faculty readers outside educational measurement could conflate it with reliability or fairness. Glossary text: "The degree to which an assessment measures the competence it claims to measure. Distinct from reliability (consistency of measurement) and fairness (procedural justice in the assessment process)."

- **TIP Finding 3 (Note) — Foreword anchor for "independent competence."** Inserted a parenthetical sentence at the first use of "independent competence" in the Foreword (line 258 of v0.98): "(In the C/A/R framework introduced in Part~\ref{part:student}, independent competence is named *Core Competence*; the two phrases refer to the same idea.)" Resolves the ambiguity for ~30 downstream uses of "independent competence" without renaming or restructuring.

**Verification:** Four-pass compile clean. 0 errors, 0 cross-reference warnings, 0 undefined references, 0 undefined citations, 0 BibTeX warnings. Page count: 121 (+1 from the Foreword anchor sentence; expected). All 7 EAP epigraphs re-checked against TIP and pass Q1 + Q2.

**Files updated:**
- `learning_with_ai_v0_99.tex` (current manuscript source)
- `learning_with_ai_v0_99.pdf` (compiled output, 121 pages)
- `MANUSCRIPT_STATUS.yaml`, `CHANGELOG.md`, `README.md`

**v1.0 FINAL still deferred** per Mac's standing instruction (awaiting colleague names for Acknowledgments).

---

## v0.98 — May 4, 2026 (Session 8 EAP pass)

**Type:** Epigraph audit and placement protocol — 7 part-level epigraphs added; in-section principle highlights unified

**Summary:** Applied EAP v1.0 (Epigraph Audit and Placement Protocol) to v0.97. Audit found zero formal epigraphs at the seven major openings (Foreword + 3 Parts + 3 Appendices) and six in-section aphoristic highlights with format inconsistency (H1 bolded, H2–H6 unbolded). Per Mac's approval, added all seven primary-form epigraph candidates and unified bolding across H1–H6.

**Changes:**

- **Preamble:** Added `\bookepigraph{}` macro (centered italic, 0.78\\textwidth, 0.6em vspace below). No attribution by design — all epigraphs in this volume are authored maxims.

- **Foreword epigraph (C-1):** "AI changed how proofs are written. It did not change what it means to understand one." (16 words; Q3 misconception fix: framework is recovered practice, not new rules.)

- **Part I epigraph (C-2):** "A polished answer is not understanding. AI can produce one and leave the other behind." (15 words; Q2 distinction: production cost vs. understanding cost.)

- **Part II epigraph (C-3):** "The question is not whether a student used AI. It is what the work still shows." (16 words; Q3 misconception fix: pivot from detection to design.)

- **Part III epigraph (C-4):** "A workable policy is not one rule for every course. It is a vocabulary every course can use." (18 words; Q3 misconception fix: policy as vocabulary, not policy as rule.)

- **Appendix A epigraph (C-5):** "Two transcripts. One records what the student can prove. The other records what they can responsibly verify." (17 words; Q1 unexpected structure: two-transcript design.)

- **Appendix B epigraph (C-6):** "Three orthogonal axes. A weak score on one cannot be paid off by a strong score on another." (17 words; Q1+Q3: orthogonality refuses substitution.)

- **Appendix C epigraph (C-7):** "If a reviewer asks, the author should have an answer that does not begin with the tool." (17 words; Q3 misconception fix: defensibility test.)

- **In-section highlights H2–H6 bolded** to match the previously-bolded H1, treating the six principle markers as a deliberate visual device. The H1/H6 structural parallel ("AI may [verb], cannot/must not [verb]" — student-facing mirror of instructor-facing) was kept as deliberate cross-Part rhetorical mirroring per Mac's Decision 2a.

**EAP Five-Question Final Check:** All 7 candidates pass Q1 (parseable before reading), Q2 (richer after reading), Q3 (not trite), Q4 (unique within book), Q5 (chapter earns it).

**EAP Step 5 Placement:** All seven epigraphs are at major opening positions, separated by >10 pages, no doubling, no external attribution.

**Verification:** Four-pass compile clean. 0 errors, 0 warnings, **120 pages** (unchanged — epigraphs absorbed into existing pagination).

---

## Branch closure — May 5, 2026 (cleanup + handoff)

**Type:** Project housekeeping — no manuscript content changes

**Summary:** Closed the v0.5 → v0.97 development branch. Removed one stale file from outputs (`BKS_Change_Report.md`, pre-Session-1 housekeeping never referenced by Sessions 1-7c). Created `HANDOFF_Session8.md` to support resumption in a new conversation branch. Manuscript content (v0.97 source and PDF) unchanged. Bibliography unchanged. Compile remains clean (120 pages, zero errors).

**Outputs state at branch closure:** 21 files, ~1.96 MB total, including: current manuscript (v0.97 `.tex` and `.pdf`), bibliography (`LearningWithAI.bib` and the Mac-VER archive), tracking files (`MANUSCRIPT_STATUS.yaml`, `CHANGELOG.md`, `README.md`), 8 session reports (Session1 through Session7c), `GSR_SMR_Score_v095.md`, `SIAM_Package_Enhancement_Plan_v2.md`, three v0.4 source PDFs (provenance), and `HANDOFF_Session8.md`.

**Pending for next branch:** v1.0 FINAL transition deferred per Mac's standing instruction. When Mac sends "begin FINAL session" with colleague names for the four Acknowledgments placeholder slots and a dedication decision, the next branch will execute: title-page transition, version increment to v1.0 FINAL, COR + CGR submission packages, cover letter to SIAM Publishing, and submission checklist.

---

## v0.97 — May 4, 2026 (Session 7c polish)

**Type:** Targeted polish — SMR finding (b), evidence-base section duplication

**Summary:** Polished the per-Part evidence-base section openings to remove duplicated learning-science boilerplate without restructuring. Part I §evidence-limits is now the canonical/foundational evidence section. Parts II and III open with a one-sentence cross-reference to Part I, then go directly to audience-specific findings. SMR findings (c) and (d), on closer inspection, turned out to be misidentified during the Session 6 GSR review and are recorded as resolved-on-inspection rather than deferred.

**Changes:**

- **Part II §evidence-limits:** Opening paragraph rewritten. Now opens with `\cref{sec:evidence-limits} of Part~\ref{part:student}` cross-reference, followed by "Two findings matter most for course design": (1) mixed AI-tutoring evidence framed for instructional design, (2) meta-analytic heterogeneity that the discipline overlays in Part II address. Removed the duplicated foundation paragraph about active retrieval / spaced practice / self-explanation / feedback. Citations unchanged: liu2025effects, ma2025meta. Word count: 95 → 84.

- **Part III §evidence-limits:** Opening paragraph rewritten. Now opens with cross-reference to Part I establishing "the learning-science foundation that AI-aware policy must preserve", followed by "two additional findings are stable enough to guide practice for institutions specifically": detector unreliability and privacy/access/equity concerns. Removed the duplicated phrase about students learning more when they retrieve, explain, test, and revise. Word count: 95 → 69.

- **Part I §evidence-limits:** Unchanged. Now serves as the canonical evidence section that Parts II and III cross-reference. This asymmetry is intentional: students need the most evidentiary context, while professionals reading Parts II and III can be pointed to Part I.

**SMR findings (c) and (d) — resolved on inspection:**

- **(c) Terminology consistency.** Audit confirmed that "AI literacy" (12 instances) is consistently used for learner capability, "AI-aware teaching" (4 + 11 broader uses) is consistently used for pedagogical practice, and "responsible AI use" (4 instances) is consistently used for ethical conduct. Three distinct concepts; three distinct names. No unification needed.

- **(d) Verification framing repetition.** Audit confirmed that verification is explained once in Part I §verification (canonical), applied to research-grade work in Appendix C (different audience, different practical content), and referenced (not re-explained) in the change-management chapter via cross-references to `\cref{fig:verification-disciplines}`. The "repetition" concern in the original SMR was based on a surface-level scan and overstated the issue.

**Honest note:** Two of the four Session 6 SMR findings turned out to be wrong on closer inspection. Recording this transparently rather than treating them as deferred.

**Compile status:** clean (120 pages, zero errors, zero unresolved cross-references, zero BibTeX warnings, all 28 entries still cited inline).

---

## v0.96 — May 4, 2026 (Session 7 polish)

**Type:** Minor polish — Foreword preview + Acknowledgments section

**Summary:** Two targeted additions Mac approved at Session 7 startup. The Foreword now includes a "What to expect" subsection previewing the 8 annotated dialogues and the change-management + looking-forward chapters. The front matter now includes an Acknowledgments section between "How to read this book" and the Table of Contents, with bracketed placeholders for colleague names that Mac will fill in. The manuscript explicitly remains in **preliminary** status; Mac stated "we are not ready for the final version yet" and asked to retain the "Preliminary version --- for review only" subtitle.

**Changes:**

- **Foreword:** new subsection `\subsection*{What to expect}` inserted between "Who this book is for" and "What this book is not". One paragraph naming the dialogue disciplines (calculus, real analysis, percolation theory, programming, history, writing), framing dialogues as pedagogical illustrations (not transcripts of real students), previewing the change-management chapter and looking-forward section.

- **Acknowledgments:** new `\section*{Acknowledgments}` in front matter (between "How to read this book" and "Table of Contents"). Four-paragraph structure: thanks to colleagues with bracketed name placeholders; AI-assistance disclosure naming Anthropic ("tool user, not a sponsorship"); meta-comment framing the acknowledgment as a model of disclosure-and-verification practice; optional dedication slot. Cross-references Appendix C.

- **Compile status:** clean (120 pages, zero errors, zero warnings).

---

## v0.95 — May 4, 2026 (Session 6)

**Type:** Quality assurance — bibliography expansion, appendix consolidation, GSR/SMR review, SPRE polish

**Mac VER addendum (May 4, 2026, post-Session-6):** Mac independently verified the original 21 bibliography entries via a parallel VER protocol pass and uploaded `LearningWithAI_VER.bib`. His verification caught three substantive errors in the working bib: (1) `bastani2025generative` was missing its subtitle "Evidence from high school mathematics" and its issue number; (2) `kestin2025ai` had a digit-transposition in pages (21958 → corrected to 17458); (3) `usde2023artificial` had a missing article ("and Future" → "and the Future"). His VER pass also added DOIs to 4 entries (europeancommission2022ethical, miao2024aib, miao2024aia, mollick2023assigning) and ISBNs to 5 entries (europeancommission2022ethical, miao2023guidance, miao2024aib, oecd2026digital, bender2021dangers). Every entry now carries a `VER:2026-05-04` annotation. Mac's verified bib was adopted as authoritative for the 21 originals; the 7 Session 6 additions were preserved with matching VER annotations. Final count remains 28.

**Summary:** Bibliography expanded from 21 to 28 verified entries. Inline appendix material in each Part consolidated under a single `\section{Reference materials}` (24 sections demoted to subsections). GSR review scored 92/100 overall; threshold met. SPRE polish removed 2 em-dashes from prose. Compile clean: 120 pages.

---

## v0.9 — May 4, 2026 (Session 5)

Faculty change management chapter (~10 pages, 7 subsections) and Looking forward section (~5 pages, 4 subsections) added to Part III. Compile clean: 119 pages.

## v0.8 — May 4, 2026 (Session 4)

Eight annotated student-AI dialogues; disciplinary depth strengthened in Parts I-II. Compile clean: 111 pages.

## v0.7 — May 4, 2026 (Session 3)

Eleven TikZ figures across Foreword, three Parts, and Appendix A. Compile clean: 102 pages.

## v0.6 — May 4, 2026 (Session 2)

Foreword written, three global appendices added, all 21 bib entries cited inline. Compile clean: 97 pages.

## v0.5 — May 4, 2026 (Session 1)

Three v0.4 volumes merged into single bound volume. Compile clean: 77 pages.

## v0.4 — May 4, 2026 (Pre-session admin)

Author updated, AI-disclosure inserted, bibliography file created.

## v0.3 — April 2026 (pre-existing draft)

Three separate volumes drafted by Mac with AI assistance.
