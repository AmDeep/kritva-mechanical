# QR-02 — Architecture Notes (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-QR-02-ARCH |
| Concept | QR-02 Standard Quadruped |
| Status | PROPOSED — Week 1 reference study |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |
| Authority | Paper feasibility only |

## 1. Configuration Summary

- Family: Legged (quadruped)
- Complexity: Medium
- Legs: Four, symmetric
- DOF per leg: 3
- Total actuators (baseline): 12
- Body: Rigid central chassis with electronics bay
- Primary demonstration role: Reference-geometry quadruped for walking and basic terrain work

## 2. Degrees of Freedom

| Joint (per leg) | Function | Notes | Status |
|---|---|---|---|
| Hip abduction / adduction | Lateral | 1 DOF | CONCEPT_TARGET |
| Hip / thigh flexion / extension | Sagittal | 1 DOF | CONCEPT_TARGET |
| Knee flexion / extension | Sagittal | 1 DOF | CONCEPT_TARGET |

Total leg DOF / actuators: 12. No additional body DOF shown.

## 3. Envelope and Packaging (printed)

| Dimension | Value | Tag |
|---|---|---|
| Body length | 350 mm | CONCEPT_TARGET |
| Body width | 260 mm | CONCEPT_TARGET |
| Body height | 250 mm | CONCEPT_TARGET |
| Overall length (legs extended) | 520 mm | CONCEPT_TARGET |
| Overall width (legs extended) | 480 mm | CONCEPT_TARGET |
| Target mass | 4 – 6 kg (est.) | CONCEPT_TARGET |
| Target payload | 0.5 – 1.0 kg (est.) | CONCEPT_TARGET |

## 4. Mechanical Architecture (from sheets)

| Element | Description on artwork | Status |
|---|---|---|
| Body | Rigid central chassis (aluminium or carbon); electronics bay for Kritva Edge and power | Illustrative |
| Legs | Four symmetric three-joint legs ending in foot pads | Illustrative |
| Joint assemblies | Housing with BLDC/PMSM, gearbox, encoder | Illustrative |
| Links | Hip, thigh, lower-leg; aluminium CNC or 3D-print / composite options | Illustrative |
| Feet | Replaceable rubber / TPU; optional force sensor | CONCEPT_TARGET |
| Sensors | Optional top sensor module (IMU, LiDAR named on concept sheet) | OWNER_DECISION |
| Cable routing | Through leg links and body channels | Illustrative |

## 5. Interfaces Visible on Sheets

- Body mounting / sensor module: optional top mount.
- Power: 24 V indication; internal 5 V / 12 V rails shown on cross-section.
- Compute: space for Kritva Edge.
- No mobility base (legged locomotion only).

## 6. Week 1 Observations

- Both sheets agree on body dimensions, DOF and actuator count after 31 Oct regeneration.
- Artwork status: REVIEWED / REVIEWED — no open defects.
- Optional sensors remain an owner decision.
- Suitable as the medium-complexity quadruped reference against QR-04.
