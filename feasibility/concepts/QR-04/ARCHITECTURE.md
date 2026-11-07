# QR-04 — Architecture Notes (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-QR-04-ARCH |
| Concept | QR-04 Agile Long-Leg Quadruped |
| Status | PROPOSED — Week 1 reference study |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |
| Authority | Paper feasibility only |

## 1. Configuration Summary

- Family: Legged (quadruped)
- Complexity: High
- Legs: Four, long-leg geometry for agility
- DOF per leg: 3
- Total actuators (baseline): 12
- Body: Central chassis with electronics bay and optional top sensor module
- Primary demonstration role: Agile / rough-terrain quadruped platform demonstrator

## 2. Degrees of Freedom

| Joint (per leg) | Function | Notes | Status |
|---|---|---|---|
| Hip abduction / adduction | Lateral | 1 DOF | CONCEPT_TARGET |
| Hip / thigh flexion / extension | Sagittal | 1 DOF | CONCEPT_TARGET |
| Knee flexion / extension | Sagittal | 1 DOF | CONCEPT_TARGET |

Total leg DOF / actuators: 12.

## 3. Envelope and Packaging (printed)

| Dimension | Value | Tag |
|---|---|---|
| Body length | 450 mm | CONCEPT_TARGET |
| Body width | 280 mm | CONCEPT_TARGET |
| Body height | 320 mm | CONCEPT_TARGET |
| Target mass | printed range | CONCEPT_TARGET |
| Target payload | printed range | CONCEPT_TARGET |

## 4. Mechanical Architecture (from sheets)

| Element | Description on artwork | Status |
|---|---|---|
| Body | Central chassis; electronics bay; mounting interface on top | Illustrative |
| Legs | Four long-leg 3-DOF assemblies | Illustrative |
| Joint assemblies | Housing with BLDC/PMSM, gearbox, encoder | Illustrative |
| Links | Longer thigh / lower-leg members relative to QR-02 | Illustrative |
| Feet | Replaceable pads; optional force sensing | CONCEPT_TARGET |
| Sensor module | Adjustable module shown on cross-section | OWNER_DECISION |
| Body mounting interface | 4 × M5, 2 × Ø5 dowels (indicative) on cross-section | OWNER_DECISION |

## 5. Interfaces Visible on Sheets

- Top body mounting interface (details only on cross-section).
- Optional adjustable sensor module (cross-section only).
- Power: 24 V indication.
- Compute: space for Kritva Edge.

## 6. Shared assumptions (common to all interns)

- Actuator family: BLDC/PMSM modular rotary, Option C mechanical direction, S/M/L size classes.
- Electronics: Kritva Edge reservation; 24 V investigation direction.
- Cable routing, safety and serviceability: to be assessed consistently.
- Cost: INR 2,00,000 planning ceiling only.

## 7. Week 1 Observations

- Artwork status: Concept sheet REVIEWED; cross-section REVIEWED_WITH_ISSUES (mounting interface + sensor module).
- Longer legs imply higher joint moments than QR-02 for the same payload — flag for Week 3 torque work.
- High-complexity quadruped reference for comparison with QR-02.
