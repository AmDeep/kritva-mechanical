# DA-04 — Architecture Notes (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-DA-04-ARCH |
| Concept | DA-04 Humanoid Mobile Dual-Arm |
| Status | PROPOSED — Week 1 reference study |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |
| Authority | Paper feasibility only |

## 1. Configuration Summary

- Family: Dual-arm (mobile humanoid)
- Complexity: High
- Arms: Two 4-DOF arms
- Base: Four-wheel differential drive (2 actuators)
- Total actuators (baseline): 10
- Head: Fixed (no pan) — owner baseline 31 Oct 2026
- Primary demonstration role: Mobile dual-arm humanoid-form platform demonstrator

## 2. Degrees of Freedom

| Joint / Drive | Count | Notes | Status |
|---|---|---|---|
| Shoulder yaw (per arm) | 1 | — | CONCEPT_TARGET |
| Shoulder pitch (per arm) | 1 | — | CONCEPT_TARGET |
| Elbow (per arm) | 1 | — | CONCEPT_TARGET |
| Wrist (per arm) | 1 | — | CONCEPT_TARGET |
| Differential drive (left / right) | 2 | Base mobility | CONCEPT_TARGET |
| Head pan | 0 | Explicitly excluded from baseline | OWNER baseline |

Total actuators: 10.

## 3. Envelope and Packaging (printed)

| Dimension | Value | Tag |
|---|---|---|
| Overall width (arm to arm) | 1200 mm | CONCEPT_TARGET |
| Overall width (shoulder to shoulder) | 600 mm | CONCEPT_TARGET |
| Total reach (left to right) | 1200 mm | CONCEPT_TARGET |
| Torso width | 400 mm | CONCEPT_TARGET |
| Base (W × L) | 500 mm × 600 mm | CONCEPT_TARGET |
| Overall height (with head) | 1200 mm | CONCEPT_TARGET |
| Arm reach (each side) | 450 mm | CONCEPT_TARGET |
| Target mass | 25 – 35 kg (est.) | CONCEPT_TARGET |
| Target payload (each arm) | 0.5 – 1.0 kg (est.) | CONCEPT_TARGET |

## 4. Mechanical Architecture (from sheets)

| Element | Description on artwork | Status |
|---|---|---|
| Torso | Humanoid form with head; space for compute and power | Illustrative |
| Arms | 4-DOF each; joint housings with BLDC/PMSM + gearbox + encoder | Illustrative |
| Mobile base | Four-wheel differential drive; two driven wheels implied | Illustrative |
| Electronics | Central / torso bay for Kritva Edge and power distribution | Illustrative |
| Head | Fixed; camera / sensor mount implied | Illustrative (no pan) |
| Battery | Not drawn on either sheet | NOT DRAWN |
| Gripper | 2-finger options shown | CONCEPT_TARGET |

## 5. Interfaces Visible on Sheets

- Mobile base to torso mechanical interface.
- Power: 24 V indication; internal 5 V / 12 V rails shown on cross-section.
- Compute: space reservation for Kritva Edge.
- Sensor: head-mounted (details TBD).
- No battery interface shown.

## 6. Shared assumptions (common to all interns)

- Actuator family: BLDC/PMSM modular rotary, Option C mechanical direction, S/M/L size classes.
- Electronics: Kritva Edge reservation; 24 V investigation direction.
- Cable routing, safety and serviceability: to be assessed consistently.
- Cost: INR 2,00,000 planning ceiling only.

## 7. Week 1 Observations

- Artwork status: REVIEWED / REVIEWED — no open defects.
- Owner baseline (31 Oct): 10 actuators, head pan excluded, head drawn fixed.
- Battery absence is a packaging gap that must stay visible.
- High-complexity dual-arm reference for comparison with DA-01.
