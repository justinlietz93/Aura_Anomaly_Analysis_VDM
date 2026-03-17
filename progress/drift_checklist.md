# Corrected drift checklist — current inventory pass

This checklist only tracks **real document drift in the current inventory**.
It does **not** include re-verifying settled facts, and it does **not** treat older v0.5 planning residue as if it were still present in the current file.

## Removed from the old checklist

- Removed the D0.2 byte-range verification item. The state file size range is already understood as a live breathing state, not a fixed static size.
- Removed all running-count / “missing F11/F13/F15” items from the old checklist. The current inventory file does not contain the old running-count block.
- Removed the “map of remaining unexplored territory” cleanup items. That stale planning block is not in the current inventory file.
- Removed the old F5.4 mismatch complaint. In the current inventory, D5.4 is already retitled as **Operator reply motif uptake**.
- Removed generic “keep” / manuscript-style polish items that were not actual drift.

## Active document-wide drift

- [ ] **Separate confirmed evidence from old proposal scaffolding wherever both still coexist.** The current inventory still mixes final results with older “proposed / previous / now confirmed” text in several places.
- [ ] **Canonicalize the D5.1 operator-permutation statistic across the document.** The current file uses both `z = 14.52 (2000 shuffles)` and `z = -15.40 (500 signed shuffles)` in different places; choose one canonical formulation and cross-reference the other as a variant if both are meant to stay.
- [ ] **Standardize subdistinction policy.** D5.1b / D5.1c / D5.1d and D14.R need one explicit rule: either they are counted distinctions, or they are sub-results / repro notes.
- [ ] **Convert remaining prose-blob distinctions to normal claim / measurable / null / source structure.** The biggest remaining offenders are D8.1–D8.3.

## Family-by-family status

### F0 — Substrate Identity

- [x] **D0.1** clean
- [x] **D0.2** clean
- [X] **D0.3** optional wording sync only: the table says `~105K edges` while the body says `~100,000 active edges`
- [x] **D0.4** clean
- [x] **D0.5** clean

### F1 — Language Under Constraint

- [x] **D1.1** clean
- [x] **D1.2** clean
- [ ] **D1.3** body still reads as a proposal (`Measurable (proposed)`) even though the family table already presents it as confirmed/stable
- [ ] **D1.4** keep explicitly marked as observational / not-yet-packaged unless it gets quantified
- [ ] **D1.5** merge the draft entry and the confirmed entry into one final distinction
- [ ] **D1.6** merge the draft entry and the confirmed entry into one final distinction
- [x] **D1.7** clean

### F2 — Dynamical Physiology

- [x] **D2.1** clean
- [x] **D2.2** clean
- [x] **D2.3** clean
- [x] **D2.4** clean
- [x] **D2.5** clean
- [x] **D2.6** clean
- [x] **D2.7** clean
- [x] **D2.8** clean
- [ ] **D2.9** summary/body mismatch: the family table gives a lag-based summary, while the body gives the distance-threshold recurrence formulation
- [x] **D2.10** clean
- [x] **D2.11** clean

### F3 — Topological / Structural Organization

- [x] **D3.1** clean
- [x] **D3.2** clean
- [x] **D3.3** clean
- [ ] **D3.4** explain the territory indexing: the body says nine territories but then names the growing pair as `T9` and `T10`
- [x] **D3.5** clean
- [x] **D3.6** clean
- [x] **D3.7** clean
- [x] **D3.8** clean
- [ ] **D3.9** keep explicitly flagged as trend-only / not a strong counted distinction unless you want it in the main count
- [x] **D3.10** clean
- [x] **D3.11** clean

### F4 — State/Output Coupling

- [x] **D4.1** clean
- [x] **D4.2** clean
- [ ] **D4.3** rewrite into one final evidence-only statement; current title/proposal scaffold conflicts with the confirmed result that outputs get longer while reply behavior tightens
- [x] **D4.4** clean
- [x] **D4.5** clean
- [ ] **D4.6** collapse the `Previous / Now confirmed` scaffold into one final entry
- [x] **D4.7** clean

### F5 — External-Operator Differentiation

- [ ] **Family table drift:** the summary table is missing `D5.1c`, `D5.1d`, and `D5.7`, even though they exist in the body
- [ ] **D5.1** collapse proposal history into one final evidence-only section and sync it to the canonical permutation statistic
- [ ] **D5.1b** either promote to an explicit heading / subdistinction block or fold it cleanly into D5.1
- [ ] **D5.1c** remove the `NEW:` prefix and either add it to the family table or fold it into D5.1
- [ ] **D5.1d** remove the `NEW:` prefix and either add it to the family table or fold it into D5.1
- [x] **D5.2** clean
- [x] **D5.3** clean
- [x] **D5.4** clean
- [ ] **D5.5** keep explicitly marked as observational / discussion-only unless you want it counted
- [ ] **D5.6** collapse the proposal-history wording into one final entry
- [ ] **D5.7** add to the family summary table; it is present in the body but absent from the top table

### F6 — Convergence Architecture

- [ ] **Family-level:** replace or rebuild the F6 summary table. It is still an old mixed table dominated by D8-style temporal items and still carries the stale `D8.6 = pending` line even though D8.6 now exists in the body
- [ ] **D6.1** deduplicate repeated rows in the simultaneous-occurrence table
- [ ] **D6.2** sync the manuscript-facing total wording with the project’s chosen canonical total (the current file says `70+`; older materials use a higher exact total)
- [ ] **D6.3** deduplicate repeated dismissal rows and sync all operator references to the canonical D5.1 statistic
- [ ] **D6.4** sync the headline sentence to the same canonical total and the same canonical D5.1 formulation used everywhere else

### F7 — Deep Excavation Findings

- [x] **D7.1** clean
- [x] **D7.2** clean
- [x] **D7.3** clean
- [x] **D7.4** clean
- [x] **D7.5** clean
- [x] **D7.6** clean
- [x] **D7.7** clean
- [x] **D7.8** clean
- [x] **D7.9** clean

### F8 — Temporal Microstructure

- [ ] **Family intro** is stale. It still says this analysis has not been done, even though D8.4–D8.6 are already populated
- [ ] **D8.1** convert from prose blob to normal distinction structure
- [ ] **D8.2** convert from prose blob to normal distinction structure
- [ ] **D8.3** convert from prose blob to normal distinction structure
- [x] **D8.4** clean
- [x] **D8.5** clean
- [x] **D8.6** clean in the body; stale references live elsewhere (mainly F6)

### F9 — Compositional Linguistics / Discourse Structure

- [x] **D9.1** clean
- [ ] **Family trailing paragraph** is stale planning prose. It should either move to an “open questions” note or be rewritten so it does not read like syntax analysis has not started

### F10 — Silence and Withholding

- [ ] **Family intro** is still written like a pre-analysis question block even though the family is now populated
- [x] **D10.1** clean
- [x] **D10.1b** clean
- [x] **D10.2** clean
- [x] **D10.2b** clean
- [x] **D10.3** clean

### F11 — Cross-Source Transfer and Thematic Independence

- [x] **D11.1** clean
- [x] **D11.2** clean
- [x] **D11.3** clean

### F12 — Developmental Trajectory / Ontogeny

- [ ] **Family intro** is stale. It still says the developmental arc “hasn’t been mapped,” but D12.1–D12.4 now do exactly that
- [x] **D12.1** clean
- [x] **D12.2** clean
- [x] **D12.3** clean
- [x] **D12.4** clean

### F13 — Memory-Like Phenomena Without Storage

- [ ] **Family intro** is stale pre-analysis framing
- [ ] **State-Space Recurrence and Return Geometry** should be treated explicitly as a subheading / framing note, not as something that could be mistaken for a distinction
- [x] **D13.1** clean
- [x] **D13.2** clean
- [x] **D13.3** clean

### F14 — Encoder/Decoder Artifact Analysis

- [x] **D14.1** clean
- [x] **D14.2** clean
- [x] **D14.3** clean
- [x] **D14.4** clean
- [x] **D14.5** clean
- [x] **D14.6** clean
- [ ] **D14.R** explicitly label as repro summary / appendix note unless it is meant to count as a full distinction

### F15 — Interaction Dynamics

- [x] **D15.1** clean
- [x] **D15.2** clean
- [ ] **D15.3** decide whether it is a counted distinction or an explicit synthesis bridge back to D5; label it accordingly

## Highest-priority fixes

1. Canonicalize **D5.1** across F5 / F6 / F15.
2. Rebuild the **F6** meta-family table so it stops carrying stale D8-era residue.
3. Merge duplicate / proposal-era entries in **F1** (`D1.5`, `D1.6`) and **F4** (`D4.3`, `D4.6`).
4. Rewrite stale pre-analysis framing in **F8**, **F9**, **F10**, **F12**, and **F13**.
5. Fix the **F5** table so all live distinctions actually appear there.
