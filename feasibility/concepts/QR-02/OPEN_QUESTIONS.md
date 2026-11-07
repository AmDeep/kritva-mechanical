# QR-02 — Open Questions and Initial Risks (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-QR-02-OQ |
| Concept | QR-02 Standard Quadruped |
| Status | PROPOSED — Week 1 |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |

## 1. Artwork Status

No open artwork defects. Concept sheet and cross-section both REVIEWED (31 Oct audit). REVIEWED is not design approval.

## 2. Unknowns Blocking Further Work

| Item | Tag | Needed for |
|---|---|---|
| Confirmed payload | UNKNOWN | Joint loading, stability, structure |
| Joint continuous / peak torque | TBD | Actuator S/M/L mapping |
| Whether IMU / LiDAR are baseline | OWNER_DECISION | Mass, power, packaging, cost |
| Battery capacity and placement | TBD | Mass budget and CG |
| Ground clearance / stance parameters | TBD | Stability and locomotion notes |
| Actuator S/M/L capability tables | UNKNOWN (to this study) | Week 3 feasibility |

## 3. Initial Risk Entries (Week 1)

| Risk | Impact | Likelihood | Mitigation |
|---|---|---|---|
| Printed mass 4–6 kg lacks subsystem breakdown | High | Med | Build traceable mass budget in Week 2–3 |
| Missing payload prevents load cases | High | High | Keep UNKNOWN; scenario tables only with owner permission |
| Optional sensors may be assumed into baseline | Med | Med | Explicit OWNER_DECISION flag |
| 3-DOF leg may still be torque-limited for desired gait | Med | Med | Derive loads in Week 3; compare with S/M/L |

## 4. Owner Decisions Requested

1. Confirm whether optional IMU / LiDAR (named on concept sheet) form part of the study baseline.
2. Supply or point to current S/M/L actuator capability data.
3. Decide whether printed payload range may be used as a working scenario.
