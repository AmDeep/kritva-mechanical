# DA-01 — Open Questions and Initial Risks (Week 1)

| Property | Value |
|---|---|
| Document ID | KMECH-DA-01-OQ |
| Concept | DA-01 Fixed Tabletop Dual-Arm |
| Status | PROPOSED — Week 1 |
| Assigned Intern | INTERN-01 |
| Last Updated | 2026-11-07 |

## 1. Artwork Discrepancies (carried from README §10 + 31 Oct audit)

| ID | Issue | Status | Action |
|---|---|---|---|
| D3 | Torso width 300 mm printed on cross-section only | OPEN — OWNER REVIEW | Do not use as input until owner decides |
| D4 | Wrist label: rotation / pitch (concept) vs pitch (cross-section) | OPEN | Do not assume axis type |
| D5 | Camera mast height adjustable on cross-section only | NOT VERIFIABLE FROM CURRENT ARTWORK | Flag for owner |

## 2. Unknowns Blocking Further Work

| Item | Tag | Needed for |
|---|---|---|
| Confirmed payload | UNKNOWN | Static torque, structure, stability |
| Confirmed reach / workspace | UNKNOWN | Kinematic and packaging studies |
| Wrist axis type | OWNER_DECISION | Joint mapping and actuator assessment |
| Actuator S/M/L continuous & peak torque tables | UNKNOWN (to this study) | Week 3 actuator feasibility |
| Cable bend / twist limits through joints | TBD | Serviceability and routing |
| Subsystem mass breakdown | TBD | Mass budget and cost model |

## 3. Initial Risk Entries (Week 1)

| Risk | Impact | Likelihood | Mitigation |
|---|---|---|---|
| Incorrect wrist-axis assumption propagates into DOF and torque work | Med | Med | Keep discrepancy visible; wait for owner |
| Printed mass 5–8 kg has no supporting breakdown | High | Med | Build traceable mass budget in Week 2–3; treat printed figure as CONCEPT_TARGET only |
| Missing payload prevents meaningful torque estimates | High | High | Use scenario tables only if owner permits; otherwise remain TBD |
| Cable routing through three joints per arm may be constrained | Med | Med | List path and bend concerns in Week 2 |

## 4. Owner Decisions Requested

1. Resolve wrist label (rotation vs pitch) on DA-01.
2. Confirm whether torso width 300 mm and adjustable mast are part of the concept baseline.
3. Supply or point to current S/M/L actuator capability data for later mapping.
4. Decide whether the printed payload range may be used as a working scenario or must remain UNKNOWN.
