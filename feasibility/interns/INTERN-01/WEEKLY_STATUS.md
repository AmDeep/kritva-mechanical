# INTERN-01 — Weekly Feasibility Status

| Property | Value |
|---|---|
| Document ID | KMECH-WEEKLY-INTERN-01 |
| Repository | `KritvaOS/kritva-mechanical` |
| Document Type | Intern Weekly Status |
| Status | PROPOSED |
| Owner | Dinesh |
| Assigned Intern | INTERN-01 (Amardeep) |
| Version | 0.3.0 |
| Last Updated | 2026-11-07 |
| Authority | Weekly progress report; subject to owner review |
| Related Documents | `feasibility/STUDY_PLAN.md`, `feasibility/INTERN_ASSIGNMENTS.md` |

## 1. Reporting Period

- Intern: INTERN-01 (Amardeep)
- Week: 1
- Reporting dates: 2026-11-03 to 2026-11-07 (planning baseline 31 Oct 2026)
- Branch: `feasibility/intern-01`
- Commit references: TBD (to be filled after first commit on branch)

## 2. Concepts Worked

Assigned concepts (fixed by INTERN_ASSIGNMENTS.md): DA-01 (Low), QR-02 (Medium), DA-04 (High), QR-04 (High).

| Concept ID | Planned activity (Week 1) | Actual activity | Status |
|---|---|---|---|
| DA-01 | Reference study, architecture, DOF, preliminary requirements, sketches | Full sheet walk-through; architecture, DOF, envelope recorded; REQUIREMENTS / ARCHITECTURE / OPEN_QUESTIONS created; discrepancies logged; textual sketch notes | Week 1 description + initial risks COMPLETE |
| QR-02 | Same | Same; artwork REVIEWED / REVIEWED; optional sensors flagged for owner | Week 1 description + initial risks COMPLETE |
| DA-04 | Same | Same; 10-actuator baseline and fixed-head decision recorded; battery absence flagged | Week 1 description + initial risks COMPLETE |
| QR-04 | Same | Same; mounting interface and sensor module on cross-section only flagged | Week 1 description + initial risks COMPLETE |

## 3. Deliverables vs Plan

| Planned deliverable (STUDY_PLAN §8 + orientation p.25) | Actual result / evidence | Status |
|---|---|---|
| Four concept descriptions (architecture, DOF, envelope) | ARCHITECTURE.md for each concept; README sections 11/13–16 updates prepared | COMPLETE |
| Preliminary requirements extraction | REQUIREMENTS.md for each concept; every value tagged | COMPLETE |
| Initial risk / open-question entries | OPEN_QUESTIONS.md for each concept + risks in this status file | COMPLETE |
| Artwork mismatch and clarification log with owner-decision flags | Recorded in OPEN_QUESTIONS.md and 01_ARTWORK_WALKTHROUGH.md | COMPLETE |
| Week 1 short review (understood / unknown / owner input) | 02_WEEK1_REVIEW_SUMMARY.md + this file §5 | COMPLETE |
| Formal kinematic / free-body sketches | Textual notes under sketches/; formal dimensioned sketches still missing | INCOMPLETE |
| Reading confirmation of governing documents | 00_READING_CONFIRMATION.md | COMPLETE (checklist provided) |
| Setup / access / branch confirmation | 00_SETUP_AND_ACCESS.md | COMPLETE (checklist provided) |

## 4. Blocked and Incomplete Items

| Item | Status | Reason | Dependency / action |
|---|---|---|---|
| Formal kinematic sketches with joint axes and coordinate frames | INCOMPLETE | Only textual notes exist | Intern produces simple paper sketches in Week 2; no CAD |
| Payload and reach values for torque estimates | BLOCKED | Values remain UNKNOWN / CONCEPT_TARGET only | Owner decision on treatment of printed ranges |
| Actuator S/M/L continuous and peak data | BLOCKED | No current capability tables supplied to this study | Owner to supply or point to kritva-actuator reference |
| Wrist axis terminology on DA-01 | BLOCKED | Discrepancy between concept sheet and cross-section | Owner review |
| Body mounting interface and sensor module on QR-04 | BLOCKED | Present on cross-section only | Owner decision |
| Battery representation on DA-04 | BLOCKED | Not drawn on either sheet | Owner decision on study treatment |

## 5. Unknowns and Assumptions

See 02_WEEK1_REVIEW_SUMMARY.md for the full consolidated list.

New or unresolved unknowns include: confirmed payload, confirmed reach, joint torque targets, S/M/L tables, battery mass/placement, cable bend limits, material grades, ground clearance, wheel size.

Assumptions that remain visible:
- Printed dimensions are CONCEPT_TARGET only.
- 24 V DC is investigation direction only.
- Head on DA-04 remains fixed (no pan) per 31 Oct baseline.
- Optional sensors / grippers / camera masts are not baseline until owner decides.

## 6. Risks Raised (Week 1)

| Risk ID | Description | Impact | Proposed mitigation |
|---|---|---|---|
| IRISK-01-W1 | Wrist-axis label inconsistency on DA-01 may lead to incorrect DOF interpretation | Med | Keep discrepancy visible; wait for owner |
| IRISK-02-W1 | Missing payload and reach values prevent meaningful static-torque estimates | High | Keep UNKNOWN; scenario tables only if owner permits |
| IRISK-03-W1 | QR-04 body mounting interface and sensor module appear on cross-section only | Med | Flag OWNER_DECISION; do not treat indicative hardware as approved |
| IRISK-04-W1 | Concept mass estimates have no subsystem breakdown | High | Build traceable mass budget in Week 2–3; treat printed figures as CONCEPT_TARGET only |
| IRISK-05-W1 | Actuator S/M/L compatibility cannot be assessed without capability data | High | Request data package from owner / kritva-actuator |
| IRISK-06-W1 | Battery absence on DA-04 understates mass and affects CG / stability | High | Explicitly list battery as TBD; do not invent values |
| IRISK-07-W1 | Long-leg geometry of QR-04 may produce higher joint moments than QR-02 | Med–High | Derive loads in Week 3; compare with S/M/L early |
| IRISK-08-W1 | Parallel intern branches may create merge conflicts on shared files | Med | Strictly limit edits to assigned folders and this status file |

These are proposed for later insertion into the shared RISK_REGISTER.md by the owner; they are not edited into that file by the intern.

## 7. Next Actions

| Action | Concept | Owner | Target |
|---|---|---|---|
| Produce simple kinematic sketches (joint axes + coordinate frame) | All four | INTERN-01 | Week 2 |
| Extract preliminary joint ranges and link lengths from artwork for workspace notes | DA-01, DA-04 | INTERN-01 | Week 2 |
| Draft preliminary mass-budget structure (empty cells OK; battery explicit TBD on DA-04) | All four | INTERN-01 | Week 2 |
| Raise wrist-label, mounting-interface, sensor and battery questions for owner decision | DA-01, QR-02, DA-04, QR-04 | INTERN-01 / Dinesh | Before CP2 |
| Request current S/M/L actuator capability summary | All | Dinesh | Before Week 3 torque work |
| Confirm treatment of printed payload / reach ranges | All | Dinesh | Before Week 2 calculations |

## 8. Repository Evidence

- Branch: `feasibility/intern-01`
- Commit references: TBD
- Relevant file paths:
  - `feasibility/concepts/DA-01/` (REQUIREMENTS, ARCHITECTURE, OPEN_QUESTIONS, sketches, README updates)
  - `feasibility/concepts/QR-02/` (same set)
  - `feasibility/concepts/DA-04/` (same set)
  - `feasibility/concepts/QR-04/` (same set)
  - `feasibility/interns/INTERN-01/WEEKLY_STATUS.md`
- Supporting package documents (optional to commit or keep local): 00_SETUP_AND_ACCESS.md, 00_READING_CONFIRMATION.md, 01_ARTWORK_WALKTHROUGH.md, 02_WEEK1_REVIEW_SUMMARY.md, PR_DESCRIPTION.md
- Review / pull request references: TBD

## 9. D-003 Compliance

I confirm that this week's work remained within paper feasibility scope. No CAD, final BOM, quotations, procurement, fabrication, assembly or physical testing was initiated.

- Intern confirmation: Amardeep (INTERN-01)
- Date: 2026-11-07
- Exceptions, if any: NONE

Mechanical HOLD D-003 remains in effect. Any exception requires explicit owner review.
