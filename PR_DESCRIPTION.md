## Summary

Comprehensive Week 1 reference-study package for INTERN-01 (Amardeep).

Assigned concepts (fixed by INTERN_ASSIGNMENTS.md):
- DA-01 Fixed Tabletop Dual-Arm (Low)
- QR-02 Standard Quadruped (Medium)
- DA-04 Humanoid Mobile Dual-Arm (High) — 10-actuator baseline and fixed-head decision respected
- QR-04 Agile Long-Leg Quadruped (High)

This package implements every Week 1 action from the Mechanical Intern Orientation Plan (p.25) and the corresponding requirements in STUDY_PLAN.md §8, AGENTS.md, DESIGN_GUIDELINES.md and the existing concept READMEs (v0.3.0).

## Week 1 actions completed

1. Setup / access / branch / PR workflow confirmation checklist (`00_SETUP_AND_ACCESS.md`)
2. Reading confirmation of all governing documents (`00_READING_CONFIRMATION.md`)
3. Artwork walk-through of the 24 sheets with focus on the four assigned concepts; all discrepancies recorded (`01_ARTWORK_WALKTHROUGH.md` + per-concept OPEN_QUESTIONS)
4. Started the four concept READMEs (sections 11 and 13–16) from the existing drafts; full REQUIREMENTS / ARCHITECTURE / OPEN_QUESTIONS created
5. End-of-week short review: what is understood, what is unknown, what needs owner input (`02_WEEK1_REVIEW_SUMMARY.md` + WEEKLY_STATUS.md)

## Deliverables in this PR

- Updated `feasibility/interns/INTERN-01/WEEKLY_STATUS.md` (Week 1)
- For each of the four concepts:
  - REQUIREMENTS.md (preliminary, fully tagged)
  - ARCHITECTURE.md (DOF, envelope, packaging, shared assumptions)
  - OPEN_QUESTIONS.md (discrepancies + initial risks)
  - README_WEEK1_UPDATES.md (sections 11, 13–16 ready to merge into existing README.md)
  - sketches/README.md (textual notes; formal sketches still incomplete)
  - calculations/, references/, reviews/ placeholders

## Explicitly not done (correct for Week 1)

- Formal dimensioned kinematic sketches (textual notes only)
- Torque / speed calculations
- Mass budgets
- Actuator S/M/L mapping
- Cost modelling
- Any CAD, BOM, quotations, procurement, fabrication or testing

## D-003 compliance

All work is paper feasibility only. HOLD D-003 remains in effect.

## Owner decisions requested

See OPEN_QUESTIONS.md files and 02_WEEK1_REVIEW_SUMMARY.md. Highest priority:

1. DA-01 wrist axis (rotation vs pitch)
2. DA-01 torso width 300 mm / adjustable mast
3. QR-02 optional IMU / LiDAR baseline
4. QR-04 body mounting interface (4×M5, 2×Ø5) and adjustable sensor module
5. Treatment of printed payload / reach ranges across all four concepts
6. Supply of current S/M/L actuator capability data for later weeks
7. Battery representation treatment for DA-04

## Test plan

- [ ] Local links in new Markdown files resolve
- [ ] Only assigned concept folders and INTERN-01 weekly status are modified
- [ ] Commit messages follow `type(scope): summary` + single `Task:` / `Tasks:` footer
- [ ] No secrets or personal data
- [ ] PR template completed
- [ ] Every assumption tagged CONCEPT_TARGET / ESTIMATE / TBD / UNKNOWN / OWNER_DECISION
