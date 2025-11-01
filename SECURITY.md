# Security & Vulnerability Disclosure

## How to report a vulnerability
1. Send a private email (PGP/age key if available) to: `security@yourdomain` (or a private contact in ORGANIZATION settings).
2. Include: repo, steps to reproduce, PoC, severity, suggested mitigation.

## Policy
- Keep disclosure private until patch is available (coordinated disclosure).
- Reward: no official bounty program yet; case-by-case.

## Keys & Secrets
- Never commit secrets/keys.
- Use GitHub Secrets + OIDC for CI when possible.
