# Contributing — Technical Guide

Thank you for wanting to contribute! Here is the standard contribution flow.

## 1) Select task
- See `good-first-issue` label if you are new.

- Or search for `help-wanted` / `onboarding` issues.

## 2) Workflow
1. Fork repo → create branch `feat/<short-desc>` or `fix/<issue-number>`.
2. Run unit tests locally, following coding style.
3. Write clear commits (imperative tense, have issue ref).
4. Create PR from your fork branch → choose PR template.
5. Attach appropriate reviewers.

## 3) PR checklist (automated + manual)
- [ ] Have relevant issue or clear description.
- [ ] Pass CI (lint, tests).
- [ ] Have a changelog entry if public API changes.

- [ ] If protocol/interface changes: update spec in `specs/`.

## 4) Code review
- Respect reviewer comments.
- Rebase/merge according to policy (squash merge preferred / or depending on repo).
