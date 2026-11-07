# Week 1 Comprehensive Package — INTERN-01 (Amardeep)

**Branch target:** `feasibility/intern-01`  
**Repository:** https://github.com/KritvaOS/kritva-mechanical  
**Planning baseline:** 31 October 2026  
**HOLD:** D-003 remains active (paper methods only)

This package implements every Week 1 action listed on page 25 of the Mechanical Intern Orientation Plan and the corresponding requirements in STUDY_PLAN.md §8, INTERN_ASSIGNMENTS.md, AGENTS.md, DESIGN_GUIDELINES.md and the existing concept READMEs (v0.3.0).

## Week 1 actions covered

| # | Action (from orientation plan p.25) | How it is covered in this package |
|---|---|---|
| 1 | Confirm intern accounts, repository access, branch and PR workflow, mentor and reviewer | `00_SETUP_AND_ACCESS.md` |
| 2 | Read AGENTS.md, README.md, STUDY_PLAN.md, INTERN_ASSIGNMENTS.md, DESIGN_GUIDELINES.md and HOLD D-003 notes | `00_READING_CONFIRMATION.md` (checklist + confirmation) |
| 3 | Walk through all 24 sheets with ARTWORK_INDEX.md; record corrections, never edit specifications by assumption | `01_ARTWORK_WALKTHROUGH.md` + per-concept OPEN_QUESTIONS.md and discrepancy tables |
| 4 | Start the four assigned concept READMEs from the existing drafts (sections 11 and 13–16) | `README_WEEK1_UPDATES.md` for each concept + full REQUIREMENTS / ARCHITECTURE / OPEN_QUESTIONS |
| 5 | End week 1 with a short review: what is understood, what is unknown, what needs owner input | `WEEKLY_STATUS.md` §5 + `02_WEEK1_REVIEW_SUMMARY.md` + per-concept open-decision lists |

## Additional coverage from the orientation plan and repository

- Purpose of the internship (understand options, assess feasibility, produce traceable evidence) → reflected in the structure of REQUIREMENTS / ARCHITECTURE / OPEN_QUESTIONS
- Scope boundary and non-negotiable rules (HOLD D-003, branch + PR, never push to main, tag every assumption) → enforced in every file and in the commit/PR guidance
- Three-intern work distribution (Amardeep = DA-01, QR-02, DA-04, QR-04) → exact assignment followed
- How to study each concept (Read → Cross-check → Decompose → Estimate → Challenge → Recommend) → Week 1 completes Read, Cross-check and start of Decompose; Estimate/Challenge deferred with explicit blockers
- Repository folder structure and concept README 17-section model → folders and section ownership respected
- Artwork rules (CONCEPT_TARGET, DISCREPANCY — OWNER REVIEW, never edit sheets) → applied everywhere
- Naming and versioning (do not reuse P0–P8, A0–A2, S/M/L for concepts) → respected
- Deliverables, reviews and acceptance (traceable source, no invented requirements, explicit assumptions) → acceptance checklist included
- Shared assumptions (actuator, electronics, cable-routing, safety, serviceability, cost) → noted in ARCHITECTURE and OPEN_QUESTIONS
- Initial risk entries → in OPEN_QUESTIONS.md and WEEKLY_STATUS.md (ready for later insertion into RISK_REGISTER.md by owner)

## How to apply

1. Create branch `feasibility/intern-01` from current `main`.
2. Copy the `feasibility/` tree into the repository root (merges with existing folders).
3. For each concept, open the existing `README.md` and merge the content from `README_WEEK1_UPDATES.md` into sections 11, 13–16. Keep sections 1–10 and 17 unchanged except for any new discrepancy notes.
4. Commit using the format required by AGENTS.md / GIT_COMMIT_STEP.md (example in `00_SETUP_AND_ACCESS.md`).
5. Open PR from `feasibility/intern-01` → `main` and paste the body from `PR_DESCRIPTION.md`.

## Files that must not be edited by the intern

- Any file outside the four concept folders and `feasibility/interns/INTERN-01/WEEKLY_STATUS.md`
- Shared registers (RISK_REGISTER, REQUIREMENTS_REGISTER, STUDY_PLAN, DESIGN_GUIDELINES, ARTWORK_MANIFEST, etc.)
- Governance files (AGENTS.md, CONTRIBUTING.md, .github/, etc.)
- Artwork PNGs

Propose changes to shared documents via the PR description and WEEKLY_STATUS; do not edit them directly.
