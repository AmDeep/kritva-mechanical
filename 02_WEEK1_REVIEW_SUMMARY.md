# 02 — Week 1 Review Summary (Action 5)

End-of-Week-1 short review: what is understood, what is unknown, what needs owner input.

## What is understood

### DA-01 Fixed Tabletop Dual-Arm (Low)
- Fixed base, two symmetric 3-DOF arms, 6 actuators.
- Printed envelope after regeneration: overall width 700 mm, height 400 mm, base 300 × 250 mm, reach 350 mm.
- Printed mass 5–8 kg (est.), payload 0.1–0.2 kg (est.) — both CONCEPT_TARGET only.
- Suitable low-complexity dual-arm reference for comparison with DA-04.

### QR-02 Standard Quadruped (Medium)
- Four legs, 3 DOF per leg, 12 actuators.
- Body 350 × 260 × 250 mm; overall with legs extended ~520 × 480 mm.
- Artwork fully REVIEWED / REVIEWED; no open defects.
- Optional IMU / LiDAR named on concept sheet only.
- Suitable medium-complexity quadruped reference for comparison with QR-04.

### DA-04 Humanoid Mobile Dual-Arm (High)
- Two 4-DOF arms + differential-drive base = 10 actuators (owner baseline 31 Oct).
- Head pan explicitly excluded; head drawn fixed.
- Overall width 1200 mm, height 1200 mm, base ~500 × 600 mm, arm reach ~450 mm.
- Target mass 25–35 kg (est.), payload 0.5–1.0 kg per arm (est.) — CONCEPT_TARGET only.
- Battery not drawn on either sheet.
- High-complexity mobile dual-arm reference.

### QR-04 Agile Long-Leg Quadruped (High)
- Four long legs, 3 DOF per leg, 12 actuators.
- Body 450 × 280 × 320 mm.
- Cross-section shows indicative body mounting interface (4 × M5, 2 × Ø5) and adjustable sensor module — both OWNER_DECISION.
- Longer legs imply higher joint moments than QR-02 for the same payload (to be quantified in Week 3).

### Shared understanding
- All work remains paper-only under HOLD D-003.
- Printed numbers are CONCEPT_TARGET, not requirements.
- Actuator S/M/L compatibility cannot be assessed until capability data is supplied.
- Mass and cost models require subsystem breakdowns that do not yet exist.

## What is unknown / TBD

| Item | Affects | Tag |
|---|---|---|
| Confirmed payload (all four) | Torque, structure, stability, cost | UNKNOWN |
| Confirmed reach / workspace requirements | Kinematics, packaging | UNKNOWN |
| Joint continuous and peak torque targets | Actuator mapping | TBD |
| Actuator S/M/L continuous/peak tables | Week 3 feasibility | UNKNOWN (to this study) |
| Battery mass, volume, placement (especially DA-04) | Mass budget, CG, mobile stability | NOT DRAWN / TBD |
| Cable bend-radius and twist limits through joints | Serviceability, routing | TBD |
| Material grades and manufacturing process | Cost, mass | TBD |
| Ground clearance / stance parameters (QR-02, QR-04) | Stability, locomotion | TBD |
| Wheel size / drive torque (DA-04) | Base mobility | TBD |

## What needs owner input (before or during Week 2)

1. **DA-01 wrist label** — rotation vs pitch (discrepancy D4).
2. **DA-01 torso width 300 mm and adjustable mast** — present on cross-section only.
3. **QR-02 optional sensors** — are IMU / LiDAR part of the study baseline?
4. **QR-04 body mounting interface** — is the indicative 4 × M5 + 2 × Ø5 baseline?
5. **QR-04 adjustable sensor module** — is it baseline?
6. **Treatment of printed payload / reach ranges** — may they be used as labelled working scenarios, or must they remain strictly UNKNOWN?
7. **S/M/L actuator capability summary** — continuous and peak torque (and any speed / duty data) so Week 3 mapping can proceed.
8. **Battery representation for DA-04** — should a conceptual battery volume/mass be assumed for study purposes, or left strictly NOT DRAWN?

## Week 1 deliverable status

| Deliverable | Status |
|---|---|
| Four concept descriptions (architecture, DOF, envelope) | COMPLETE |
| Preliminary requirements extraction | COMPLETE |
| Initial risk / open-question entries | COMPLETE |
| Artwork discrepancy log with owner-decision flags | COMPLETE |
| Week 1 short review (this document) | COMPLETE |
| Formal dimensioned kinematic sketches | INCOMPLETE (textual notes only) |
| Torque / mass / cost calculations | NOT STARTED (correct for Week 1) |

## D-003 compliance

No CAD, final BOM, quotations, procurement, fabrication, assembly or physical testing was initiated.
