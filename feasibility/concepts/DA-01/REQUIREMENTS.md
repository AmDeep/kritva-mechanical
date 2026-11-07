# DA-01 — Preliminary Requirements (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-DA-01-REQ |
| Concept | DA-01 Fixed Tabletop Dual-Arm |
| Status | PROPOSED — Week 1 extraction |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |
| Authority | Paper feasibility only; not approved requirements |

## 1. Source of Values

All numeric values below are taken from the concept sheet and cross-section sheet (evidence type C, maturity L0, PROPOSED). They are tagged CONCEPT_TARGET. They are not approved requirements. Requirements-register entries remain UNKNOWN or TBD until owner decision.

## 2. Configuration Requirements (from artwork)

| ID | Statement | Value / Notes | Tag | Source |
|---|---|---|---|---|
| R-DA01-001 | Robot type | Dual-arm, fixed tabletop base | CONCEPT_TARGET | Both sheets |
| R-DA01-002 | Number of arms | 2 (symmetric left/right) | CONCEPT_TARGET | Both sheets |
| R-DA01-003 | DOF per arm | 3 (shoulder, elbow, wrist) | CONCEPT_TARGET | Both sheets |
| R-DA01-004 | Total arm actuators | 6 | CONCEPT_TARGET | Both sheets |
| R-DA01-005 | Gripper | 2-finger parallel; optional servo or BLDC; may be passive | CONCEPT_TARGET | Both sheets |
| R-DA01-006 | Base | Fixed base plate; no mobility | CONCEPT_TARGET | Both sheets |
| R-DA01-007 | Overall width (arm-to-arm) | 700 mm | CONCEPT_TARGET | Both sheets (agreed after regeneration) |
| R-DA01-008 | Overall height | 400 mm | CONCEPT_TARGET | Both sheets |
| R-DA01-009 | Base footprint | 300 mm × 250 mm | CONCEPT_TARGET | Both sheets |
| R-DA01-010 | Arm reach (shoulder to gripper) | 350 mm | CONCEPT_TARGET | Both sheets |
| R-DA01-011 | Target mass | 5 – 8 kg (est.) | CONCEPT_TARGET | Concept sheet |
| R-DA01-012 | Target payload | 0.1 – 0.2 kg | CONCEPT_TARGET | Concept sheet |
| R-DA01-013 | Supply indication | 24 V DC | CONCEPT_TARGET | Both sheets |
| R-DA01-014 | Primary use | Pick-and-place, object transfer, Kritva platform demonstration | CONCEPT_TARGET | Concept sheet |

## 3. Items Explicitly Unknown or TBD

| Item | Status | Reason |
|---|---|---|
| Confirmed payload requirement | UNKNOWN | Printed value is CONCEPT_TARGET only |
| Confirmed reach / workspace requirement | UNKNOWN | Printed 350 mm is CONCEPT_TARGET only |
| Joint continuous / peak torque | TBD | No calculation yet; no actuator data package |
| Joint speed / duty cycle | TBD | Not printed |
| Wrist axis type (rotation vs pitch) | OWNER_DECISION | Discrepancy still open |
| Torso / mast width 300 mm | OWNER_DECISION | Appears on cross-section only |
| Adjustable camera mast | NOT VERIFIABLE FROM CURRENT ARTWORK | Shown on cross-section; not on concept sheet |
| Cable bend-radius limits | TBD | Not specified |
| Material grades | TBD | Artwork shows aluminium / CNC / 3D-print options only |
| Gripper actuation method | TBD | Optional on sheets |

## 4. Derived / Study Requirements (Week 1)

These are study tasks, not product requirements:

- Produce kinematic sketch with joint axes and coordinate frame (evidence C).
- Estimate workspace and dual-arm overlap by calculation (evidence C) — deferred to Week 2.
- Record all assumptions with tags.
- Keep D-003 compliance: paper methods only.
