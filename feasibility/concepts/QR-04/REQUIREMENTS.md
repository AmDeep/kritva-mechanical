# QR-04 — Preliminary Requirements (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-QR-04-REQ |
| Concept | QR-04 Agile Long-Leg Quadruped |
| Status | PROPOSED — Week 1 extraction |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |
| Authority | Paper feasibility only; not approved requirements |

## 1. Source of Values

All numeric values are taken from the concept sheet and cross-section sheet (evidence type C, maturity L0, PROPOSED). Tagged CONCEPT_TARGET. Not approved requirements.

## 2. Configuration Requirements (from artwork)

| ID | Statement | Value / Notes | Tag | Source |
|---|---|---|---|---|
| R-QR04-001 | Robot type | Agile long-leg quadruped | CONCEPT_TARGET | Both sheets |
| R-QR04-002 | DOF per leg | 3 | CONCEPT_TARGET | Both sheets |
| R-QR04-003 | Total leg actuators | 12 | CONCEPT_TARGET | Both sheets |
| R-QR04-004 | Body length (L) | 450 mm | CONCEPT_TARGET | Both sheets |
| R-QR04-005 | Body width (W) | 280 mm | CONCEPT_TARGET | Both sheets |
| R-QR04-006 | Body height (H) | 320 mm | CONCEPT_TARGET | Both sheets |
| R-QR04-007 | Target mass | printed range on sheets | CONCEPT_TARGET | Concept sheet |
| R-QR04-008 | Target payload | printed range on sheets | CONCEPT_TARGET | Concept sheet |
| R-QR04-009 | Supply indication | 24 V DC | CONCEPT_TARGET | Both sheets |
| R-QR04-010 | Primary use | Agile locomotion, rough terrain, R&D, Kritva platform demonstration | CONCEPT_TARGET | Concept sheet |
| R-QR04-011 | Body mounting interface | 4 × M5, 2 × Ø5 dowels (indicative) | CONCEPT_TARGET / OWNER_DECISION | Cross-section only |
| R-QR04-012 | Adjustable sensor module | Shown on cross-section | OWNER_DECISION | Cross-section only |

## 3. Items Explicitly Unknown or TBD

| Item | Status | Reason |
|---|---|---|
| Confirmed payload | UNKNOWN | Printed value is CONCEPT_TARGET only |
| Joint continuous / peak torque | TBD | No calculation yet; long-leg loading may be higher |
| Body mounting interface details | OWNER_DECISION | Present on cross-section only |
| Adjustable sensor module | OWNER_DECISION | Present on cross-section only |
| Battery capacity and placement | TBD | Not detailed |
| Actuator S/M/L tables | UNKNOWN (to this study) | Needed for Week 3 |
| Ground clearance / leg length ratios | TBD | Derivable later from artwork |

## 4. Derived / Study Requirements (Week 1)

- Record long-leg geometry and 3-DOF sequence.
- Flag mounting-interface and sensor-module items for owner decision.
- Keep all work paper-only under HOLD D-003.
