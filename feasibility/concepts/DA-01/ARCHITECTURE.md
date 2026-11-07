# DA-01 — Architecture Notes (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-DA-01-ARCH |
| Concept | DA-01 Fixed Tabletop Dual-Arm |
| Status | PROPOSED — Week 1 reference study |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |
| Authority | Paper feasibility only |

## 1. Configuration Summary

- Family: Dual-arm
- Complexity: Low
- Base: Fixed tabletop plate with central electronics bay
- Arms: Two symmetric 3-DOF arms
- Total actuators (baseline): 6
- Mobility: None
- Primary demonstration role: Compact, low-cost dual-arm platform demonstrator

## 2. Degrees of Freedom

| Joint | Axis (as printed) | Notes | Status |
|---|---|---|---|
| Shoulder (per arm) | Yaw (both sheets after regeneration) | 1 DOF | CONCEPT_TARGET |
| Elbow (per arm) | Pitch | 1 DOF | CONCEPT_TARGET |
| Wrist (per arm) | Rotation / pitch (concept) vs pitch (cross-section) | 1 DOF counted on both sheets | DISCREPANCY — OWNER REVIEW |
| Gripper | Optional open/close | Not counted in the 6 arm actuators | CONCEPT_TARGET |

Total arm DOF: 6. No base DOF.

## 3. Envelope and Packaging (printed)

| Dimension | Value | Tag |
|---|---|---|
| Overall width (arm-to-arm) | 700 mm | CONCEPT_TARGET |
| Overall height | 400 mm | CONCEPT_TARGET |
| Base width × depth | 300 mm × 250 mm | CONCEPT_TARGET |
| Arm reach (shoulder → gripper) | 350 mm | CONCEPT_TARGET |
| Target mass | 5 – 8 kg (est.) | CONCEPT_TARGET |

## 4. Mechanical Architecture (from sheets)

| Element | Description on artwork | Status |
|---|---|---|
| Base structure | Compact fixed base plate; central electronics volume | Illustrative |
| Arm links | Shoulder, upper arm, forearm, wrist; aluminium CNC or 3D-print options named | Illustrative |
| Joint housings | BLDC/PMSM + harmonic or planetary gearbox + encoder implied | Illustrative |
| Electronics | Central bay for Kritva Edge / power distribution; cable routing through arms | Illustrative |
| Sensors | Optional camera on mast; adjustable height shown on cross-section only | NOT VERIFIABLE FROM CURRENT ARTWORK / OWNER_DECISION |
| Gripper | 2-finger parallel; optional servo or BLDC | CONCEPT_TARGET |

## 5. Interfaces Visible on Sheets

- Base mounting: fixed tabletop (no mobility interface).
- Power: 24 V indication.
- Compute: space reservation for Kritva Edge (conceptual).
- Sensor: camera mast (details incomplete).
- Cable paths: through arm links and joints (exact routing TBD).

## 6. Shared assumptions (common to all interns)

- Actuator family: BLDC/PMSM modular rotary, Option C mechanical direction, S/M/L size classes.
- Electronics: Kritva Edge reservation; 24 V investigation direction; internal rails as shown.
- Cable routing, safety and serviceability: to be assessed consistently across concepts.
- Cost: INR 2,00,000 is a planning ceiling, not an approved budget or procurement authorisation.

## 7. Week 1 Observations

- After 31 Oct regeneration the two sheets agree on overall width 700 mm, height 400 mm, base 300×250 mm, reach 350 mm, 3 DOF per arm and 6 actuators.
- Remaining open items are text-level (wrist label) and items present on only one sheet (torso width 300 mm, adjustable mast).
- No CAD exists. All geometry is CONCEPT_TARGET.
- Suitable as the low-complexity dual-arm reference for comparison with DA-04.
