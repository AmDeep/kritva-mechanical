# 01 — Artwork Walk-through (Week 1 Action 3)

Rules applied (DESIGN_GUIDELINES.md §8.1 and orientation plan p.8):

- Sheets are illustrative concept artwork (evidence type C, maturity L0, PROPOSED).
- Not CAD, not to scale, not engineering evidence.
- Any printed number is CONCEPT_TARGET with its source sheet named.
- When sheets disagree: record DISCREPANCY — OWNER REVIEW and use neither value as an input without owner direction.
- If something cannot be read or checked: NOT VERIFIABLE FROM CURRENT ARTWORK.
- Never edit a sheet. Corrections replace the file, change the manifest SHA-256, return status to PENDING_REVIEW and add a CHANGELOG entry. Send artwork issues to the owner.

Source of truth for status: `docs/images/ARTWORK_INDEX.md` and `docs/images/ARTWORK_MANIFEST.json` (audit of 31 Oct 2026). REVIEWED is not design approval.

## Assigned concepts (focus)

| ID | Concept | Concept sheet | Cross-section | Open item (from 31 Oct audit) |
|---|---|---|---|---|
| DA-01 | Fixed Tabletop Dual-Arm | REVIEWED_WITH_ISSUES | REVIEWED_WITH_ISSUES | Wrist label (rotation / pitch); torso width 300 mm and adjustable mast on cross-section only (owner) |
| QR-02 | Standard Quadruped | REVIEWED | REVIEWED | No artwork defect. Optional sensors (IMU, LiDAR) named on concept sheet only → owner decision if required |
| DA-04 | Humanoid Mobile Dual-Arm | REVIEWED | REVIEWED | No open artwork issue. Baseline decided: 10 actuators, head pan excluded, head drawn fixed. Battery not drawn |
| QR-04 | Agile Long-Leg Quadruped | REVIEWED | REVIEWED_WITH_ISSUES | Body mounting interface (4 × M5, 2 × Ø5 dowels, indicative) and adjustable sensor module on cross-section only (owner) |

## Other 20 sheets (awareness only)

Intern-01 is not responsible for producing analysis on the other eight concepts, but must be aware of the overall set so that later comparison matrices remain consistent. Full list and status live in ARTWORK_INDEX.md. Do not edit other concept folders.

## Recording method used in this package

For each assigned concept the following files record the walk-through results:

- `ARCHITECTURE.md` — configuration, DOF, envelope, packaging observed on the sheets
- `REQUIREMENTS.md` — every printed CONCEPT_TARGET extracted and tagged
- `OPEN_QUESTIONS.md` — every discrepancy, NOT VERIFIABLE item and owner decision needed
- `README_WEEK1_UPDATES.md` — updates to sections 11 and 13–16 of the concept README

No specification was edited by assumption. Where a value appears on only one sheet it is flagged. Where the two sheets previously disagreed and were later regenerated, the agreed value is used and the history is left visible in the existing README §10.

## Shared observations that apply to all four concepts

- 24 V DC is an investigation direction only, not an approved system voltage.
- S/M/L are actuator size classes owned by the actuator workstream; they are not concept labels.
- Optional sensors, grippers and camera masts are CONCEPT_TARGET or OWNER_DECISION until the owner decides.
- Cable routing, thermal management, serviceability and safety are shared concerns for all interns; initial notes are captured per concept and will be consolidated later.
