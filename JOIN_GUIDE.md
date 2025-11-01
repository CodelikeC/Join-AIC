# Join Guide

There are three ways to connect to AIC:

## 1) Follower → Contributor (start small)
1. Fork the repo you want to contribute to (e.g. `AdaptiveAI-/` or `IBCS/`).
2. Read the `CONTRIBUTING.md` of that repo.
3. Create an issue: choose the `feature-request` or `help-wanted` template.
4. Start with a small task: docs, tests, examples, bugfix.
5. Create a PR according to the template, tag `onboarding` if you are a new contributor.

## 2) Contributor → Core Collaborator
- After 2–3 quality PRs: the maintainer will invite you to the corresponding `team` (not required to join the Organization yet).

- Participate in review, write small RFC (file `rfcs/xxxx.md`), participate in discussion.

## 3) Independent Node / Satellite Project (do not join org directly)
- If you want to maintain your own project but connect to AIC:
1. Fork or create your own repo.
2. Implement `NODE_REGISTER.md` template (sample below) and submit PR to `join-aic/nodes/`.
3. Node will be listed in `nodes/README.md` after review.

### Node registration template
Send PR with file `nodes/<node-name>.md` including:
```yaml
name: "Node name"
maintainers: 
- github: "username"
domain: "security / infra / simulation / dataset / ui / docs"
short_description: "1 sentence description"
license: "Apache-2.0 / MIT / (specify)"
interop: "endpoint/protocol/api spec"
trust_model: "how the node handles keys & governance"
contact: "email or matrix/discord/..."
