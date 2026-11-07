# QR-02 — Preliminary Requirements (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-QR-02-REQ |
| Concept | QR-02 Standard Quadruped |
| Status | PROPOSED — Week 1 extraction |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |
| Authority | Paper feasibility only; not approved requirements |

## 1. Source of Values

All numeric values are taken from the concept sheet and cross-section sheet (evidence type C, maturity L0, PROPOSED). Tagged CONCEPT_TARGET. Not approved requirements.

## 2. Configuration Requirements (from artwork)

| ID | Statement | Value / Notes | Tag | Source |
|---|---|---|---|---|
| R-QR02-001 | Robot type | Standard quadruped, four legs | CONCEPT_TARGET | Both sheets |
| R-QR02-002 | DOF per leg | 3 (hip abduction/adduction, hip/thigh flexion, knee flexion) | CONCEPT_TARGET | Both sheets |
| R-QR02-003 | Total leg actuators | 12 | CONCEPT_TARGET | Both sheets |
| R-QR02-004 | Body length (L) | 350 mm | CONCEPT_TARGET | Both sheets |
| R-QR02-005 | Body width (W) | 260 mm | CONCEPT_TARGET | Both sheets |
| R-QR02-006 | Body height (H) | 250 mm | CONCEPT_TARGET | Both sheets |
| R-QR02-007 | Overall length (legs extended) | 520 mm | CONCEPT_TARGET | Concept sheet |
| R-QR02-008 | Overall width (legs extended) | 480 mm | CONCEPT_TARGET | Both sheets |
| R-QR02-009 | Target mass | 4 – 6 kg (est.) | CONCEPT_TARGET | Concept sheet |
| R-QR02-010 | Target payload | 0.5 – 1.0 kg (est.) | CONCEPT_TARGET | Concept sheet |
| R-QR02-011 | Supply indication | 24 V DC | CONCEPT_TARGET | Both sheets |
| R-QR02-012 | Primary use | Walking, turning, basic terrain adaptation, R&D, Kritva platform demonstration | CONCEPT_TARGET | Concept sheet |
| R-QR02-013 | Feet | Replaceable rubber / TPU pad; optional spike or force sensor | CONCEPT_TARGET | Both sheets |
| R-QR02-014 | Optional sensors | IMU, LiDAR named on concept sheet | CONCEPT_TARGET / OWNER_DECISION | Concept sheet only |

## 3. Items Explicitly Unknown or TBD

| Item | Status | Reason |
|---|---|---|
| Confirmed payload | UNKNOWN | Printed value is CONCEPT_TARGET only |
| Joint continuous / peak torque | TBD | No calculation yet |
| Joint speed / stride parameters | TBD | Not printed |
| Whether optional IMU / LiDAR are baseline | OWNER_DECISION | Named on concept sheet only |
| Battery capacity and placement | TBD | Not shown in detail |
| Material grades | TBD | Aluminium / CNC / composite options only |
| Ground clearance under body | TBD | Derivable later from leg geometry |

## 4. Derived / Study Requirements (Week 1)

- Record leg joint sequence and DOF table.
- Note body envelope and overall stance dimensions.
- Flag optional sensors for owner decision.
- Keep all work paper-only under HOLD D-003.
