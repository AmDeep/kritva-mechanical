# DA-04 README — Week 1 Updates (sections 11, 13–16)

Paste or merge these sections into the existing concept README.md (v0.3.0). Do not overwrite sections 1–10 or 17 unless recording a new discrepancy.

---

## 11. Feasibility Activity and Evidence (Week 1 progress)

- [x] Read both artwork sheets and cross-check against README sections 1–10
- [x] Record 10-actuator baseline and fixed-head decision (owner 31 Oct)
- [x] Record architecture, DOF table, envelope and packaging notes (see ARCHITECTURE.md)
- [x] Extract preliminary requirements and tag every value (see REQUIREMENTS.md)
- [x] List open questions and initial risks (see OPEN_QUESTIONS.md)
- [ ] Draw 4-DOF arm kinematic sketch with joint axes and coordinate frame (evidence C) — textual notes only; formal sketch still INCOMPLETE
- [ ] Note mobile-base envelope and qualitative stability under extended arms (evidence C) — Week 2
- [ ] Derive static torque once payload is clarified (evidence C) — blocked
- [ ] Estimate mass by subsystem; explicitly treat battery as TBD because it is not drawn (evidence C) — Week 2–3
- [ ] List cable paths through torso and arms (evidence C) — Week 2

Evidence type for all Week 1 work: C.

---

## 13. Folder Contents

- README.md (this file)
- REQUIREMENTS.md (Week 1)
- ARCHITECTURE.md (Week 1)
- OPEN_QUESTIONS.md (Week 1)
- sketches/ (textual notes; formal sketches still INCOMPLETE)
- calculations/ (empty — Week 1)
- references/ (empty — Week 1)
- reviews/ (empty — Week 1)
- Remaining analysis files — not started (Week 2–3)

---

## 14. Current Assessment

- Overall status: PROPOSED — Week 1 reference study complete
- Requirements completeness: Preliminary extraction done; payload, reach and battery still open
- Architecture assessment: Configuration, DOF (10 actuators), envelope recorded; artwork REVIEWED / REVIEWED
- Engineering assessment: NOT STARTED
- Actuator compatibility: NOT STARTED
- Cost assessment: NOT STARTED
- Major risks: Missing battery representation; missing payload; printed mass without breakdown
- Evidence gaps: Formal sketches, torque work, mass budget (including battery), actuator data

---

## 15. Checkpoint Progress

| Checkpoint | Status | Review reference |
|---|---|---|
| Week 1 internal | COMPLETE (description + initial risks) | This package + WEEKLY_STATUS.md |
| CP2 Architecture Review | NOT STARTED | `feasibility/reviews/CP2_ARCHITECTURE_REVIEW.md` |
| CP3 Engineering Review | NOT STARTED | `feasibility/reviews/CP3_ENGINEERING_REVIEW.md` |
| CP4 Final Review | NOT STARTED | `feasibility/reviews/CP4_FINAL_REVIEW.md` |

---

## 16. Open Decisions

See OPEN_QUESTIONS.md. Highest priority:

1. Confirm treatment of missing battery representation for study purposes.
2. Supply S/M/L actuator capability data.
3. Decide treatment of printed payload / reach ranges.
