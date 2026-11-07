# DA-04 — Open Questions and Initial Risks (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-DA-04-OQ |
| Concept | DA-04 Humanoid Mobile Dual-Arm |
| Status | PROPOSED — Week 1 |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |

## 1. Artwork Status

No open artwork defects. Concept sheet and cross-section both REVIEWED (31 Oct audit). REVIEWED is not design approval.

Baseline decisions already recorded:
- 10 actuators total.
- Head pan excluded; head drawn fixed.

## 2. Unknowns Blocking Further Work

| Item | Tag | Needed for |
|---|---|---|
| Confirmed payload | UNKNOWN | Arm torque, structure, stability |
| Confirmed reach | UNKNOWN | Workspace and packaging |
| Battery mass, volume and placement | NOT VERIFIABLE FROM CURRENT ARTWORK | Mass budget, CG, mobile stability |
| Wheel diameter / drive torque | TBD | Base mobility assessment |
| Joint continuous / peak torque | TBD | Actuator S/M/L mapping |
| Actuator S/M/L capability tables | UNKNOWN (to this study) | Week 3 feasibility |

## 3. Initial Risk Entries (Week 1)

| Risk | Impact | Likelihood | Mitigation |
|---|---|---|---|
| Missing battery representation understates mass and affects CG | High | High | Explicitly list battery as TBD in mass budget; do not invent values |
| Printed mass/payload figures lack breakdown | High | Med | Build traceable subsystem mass budget in Week 2–3 |
| 4-DOF arm + mobile base may exceed S/M/L capability or budget | High | Med | Derive loads in Week 3; compare with S/M/L and INR 2,00,000 ceiling |
| Differential-drive stability under extended arm poses | Med | Med | Qualitative note in Week 2; quantitative later |

## 4. Owner Decisions Requested

1. Confirm whether any battery / power-pack representation should be added to the concept baseline for study purposes.
2. Supply or point to current S/M/L actuator capability data.
3. Decide whether printed payload / reach ranges may be used as working scenarios.
