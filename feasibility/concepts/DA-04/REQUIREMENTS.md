# DA-04 — Preliminary Requirements (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-DA-04-REQ |
| Concept | DA-04 Humanoid Mobile Dual-Arm |
| Status | PROPOSED — Week 1 extraction |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |
| Authority | Paper feasibility only; not approved requirements |

## 1. Source of Values

All numeric values are taken from the concept sheet and cross-section sheet (evidence type C, maturity L0, PROPOSED). Tagged CONCEPT_TARGET. Owner approved DA-04 definition as study baseline on 31 Oct 2026 (10 actuators, head pan excluded).

## 2. Configuration Requirements (from artwork + baseline decision)

| ID | Statement | Value / Notes | Tag | Source |
|---|---|---|---|---|
| R-DA04-001 | Robot type | Humanoid torso dual-arm on differential-drive mobile base | CONCEPT_TARGET | Both sheets |
| R-DA04-002 | DOF per arm | 4 (shoulder yaw, shoulder pitch, elbow, wrist) | CONCEPT_TARGET | Both sheets |
| R-DA04-003 | Base DOF | 2 (differential drive) | CONCEPT_TARGET | Both sheets |
| R-DA04-004 | Total actuators (baseline) | 10 (8 arm + 2 base); head pan excluded | OWNER baseline 31 Oct | Both sheets + decision |
| R-DA04-005 | Overall width (arm to arm) | 1200 mm | CONCEPT_TARGET | Both sheets |
| R-DA04-006 | Overall width (shoulder to shoulder) | 600 mm | CONCEPT_TARGET | Concept sheet |
| R-DA04-007 | Total reach (left to right) | 1200 mm | CONCEPT_TARGET | Concept sheet |
| R-DA04-008 | Torso width | 400 mm | CONCEPT_TARGET | Concept sheet |
| R-DA04-009 | Base dimensions (W × L) | 500 mm × 600 mm | CONCEPT_TARGET | Both sheets |
| R-DA04-010 | Overall height (with head) | 1200 mm | CONCEPT_TARGET | Both sheets |
| R-DA04-011 | Arm reach (each side) | 450 mm (shoulder to gripper) | CONCEPT_TARGET | Concept sheet |
| R-DA04-012 | Target payload (each arm) | 0.5 – 1.0 kg (est.) | CONCEPT_TARGET | Concept sheet |
| R-DA04-013 | Target weight | 25 – 35 kg (est.) | CONCEPT_TARGET | Concept sheet |
| R-DA04-014 | Supply indication | 24 V DC | CONCEPT_TARGET | Both sheets |
| R-DA04-015 | Battery | Not drawn or labelled on either sheet | NOT VERIFIABLE FROM CURRENT ARTWORK | — |
| R-DA04-016 | Head | Fixed (no pan) per baseline decision | OWNER_DECISION | 31 Oct baseline |
| R-DA04-017 | Primary use | Mobile manipulation, pick-and-place, inspection, teleoperation, Kritva platform demonstration | CONCEPT_TARGET | Concept sheet |

## 3. Items Explicitly Unknown or TBD

| Item | Status | Reason |
|---|---|---|
| Confirmed payload | UNKNOWN | Printed value is CONCEPT_TARGET only |
| Confirmed reach | UNKNOWN | Printed values are CONCEPT_TARGET only |
| Joint continuous / peak torque | TBD | No calculation yet |
| Battery mass, volume and placement | NOT VERIFIABLE FROM CURRENT ARTWORK | Not drawn |
| Wheel size / drive torque | TBD | Not detailed |
| Head sensor suite | TBD | Fixed head; details not specified |
| Actuator S/M/L tables | UNKNOWN (to this study) | Needed for Week 3 |

## 4. Derived / Study Requirements (Week 1)

- Record 10-actuator baseline and fixed-head decision.
- Capture envelope and mobile-base architecture.
- Flag missing battery representation.
- Keep all work paper-only under HOLD D-003.
