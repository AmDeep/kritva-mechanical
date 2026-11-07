# 00 — Setup, Access, Branch and PR Workflow (Week 1 Action 1)

## Confirmations required before substantive work

| Item | Status | Notes |
|---|---|---|
| Intern account (GitHub) | TBD — confirm with owner | Must be able to push to a feature branch and open PRs |
| Repository access (`KritvaOS/kritva-mechanical`) | TBD — confirm with owner | Write access to branches; no direct push to `main` |
| Branch name | `feasibility/intern-01` | Fixed by INTERN_ASSIGNMENTS.md §5 |
| Mentor / reviewer | Dinesh (owner) | Single owner; author cannot self-approve |
| Pull-request template | `.github/PULL_REQUEST_TEMPLATE.md` | Must be used |
| Commit-message check | Workflow present | Format: `type(scope): summary` (≤90 chars) + exactly one `Task:` or `Tasks:` footer |
| Secret scan | Workflow present (gitleaks) | Never commit credentials or personal data |
| CODEOWNERS | Present | Owner reviews |

## Branch and commit rules (from AGENTS.md + GIT_COMMIT_STEP.md)

- Work only on `feasibility/intern-01`.
- Never push to `main`.
- Never force-push shared branches without explicit owner approval.
- Commit message example for this package:

```
docs(feasibility): Week 1 reference study for DA-01 QR-02 DA-04 QR-04

Tasks: None (Week 1 paper study package for INTERN-01)
```

- Or, once a task ID exists in `planning/TASKS.md`:

```
docs(feasibility): Week 1 reference study for DA-01 QR-02 DA-04 QR-04

Task: ROB-MECH-XXX
```

- One focused commit is preferred for the initial Week 1 package; subsequent small commits are fine if they stay within the assigned folders.
- No AI-session or AI-attribution trailers. `Co-Authored-By` is allowed.
- Merge method is merge commit.

## Folder edit boundary (non-negotiable)

Edit only:

- `feasibility/concepts/DA-01/`
- `feasibility/concepts/QR-02/`
- `feasibility/concepts/DA-04/`
- `feasibility/concepts/QR-04/`
- `feasibility/interns/INTERN-01/WEEKLY_STATUS.md`

Do not edit common documents, shared registers, evaluation criteria, study plans, review records or program baseline files. Raise proposed changes for owner review.

## HOLD D-003 reminder

CAD, final BOM, supplier quotations, procurement, fabrication, assembly, physical testing and design freeze remain NOT STARTED and require explicit owner decision. This package contains none of those activities.
