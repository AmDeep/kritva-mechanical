# DA-01 README — Week 1 Updates (sections 11, 13–16)

Paste or merge these sections into the existing concept README.md (v0.3.0). Do not overwrite sections 1–10 or 17 unless recording a new discrepancy.

---

## 11. Feasibility Activity and Evidence (Week 1 progress)

What the assigned intern investigates, using paper methods only (calculations, comparison tables, sketches and cited datasheets):

- [x] Read both artwork sheets and cross-check against README sections 1–10
- [x] Record architecture, DOF table, envelope and packaging notes (see ARCHITECTURE.md)
- [x] Extract preliminary requirements and tag every value (see REQUIREMENTS.md)
- [x] List open questions, discrepancies and initial risks (see OPEN_QUESTIONS.md)
- [ ] Fix the shoulder axis and the arm pose behind each printed reach and width, then draw a kinematic sketch with joint axes and a coordinate frame (evidence C) — textual notes only in sketches/; formal sketch still INCOMPLETE
- [ ] Estimate the arm workspace and the overlap of the two workspaces by calculation (evidence C) — deferred to Week 2
- [ ] Derive static torque at shoulder, elbow and wrist for a stated payload and arm pose, then compare with S/M/L data once the owner supplies it (evidence C) — blocked on payload and actuator data
- [ ] Check tabletop stability and base loading for the extended-arm case (evidence C) — Week 2+
- [ ] Estimate mass by subsystem with stated assumptions, separately from the printed 5 – 8 kg (evidence C) — Week 2–3
- [ ] List the cable path through each joint with bend and twist concerns (evidence C) — Week 2

Evidence type for all Week 1 work: C (concept interpretation / paper study).

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
- MECHANICAL_ANALYSIS.md, ACTUATOR_ANALYSIS.md, INTERFACES.md, MASS_BUDGET.md, COST_MODEL.md — not started (Week 2–3)

---

## 14. Current Assessment

- Overall status: PROPOSED — Week 1 reference study complete
- Requirements completeness: Preliminary extraction done; many values remain UNKNOWN / TBD / OWNER_DECISION
- Architecture assessment: Configuration, DOF, envelope and packaging recorded from artwork
- Engineering assessment: NOT STARTED (Week 2–3)
- Actuator compatibility: NOT STARTED (blocked on S/M/L data)
- Cost assessment: NOT STARTED
- Major risks: Wrist-axis discrepancy; missing payload; printed mass without breakdown
- Evidence gaps: Formal kinematic sketches, torque calculations, mass budget, actuator data

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

See OPEN_QUESTIONS.md for full list. Highest priority for owner:

1. Resolve wrist label (rotation vs pitch).
2. Confirm torso width 300 mm and adjustable mast.
3. Supply S/M/L actuator capability data.
4. Decide treatment of printed payload range.
