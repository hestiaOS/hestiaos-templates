# Governance — hestiaos-templates

```
- Templates may PREPARE new repos but must NOT publish them automatically.
- No source-copy migration via templates (skeletons are empty shells with placeholders).
- No secret values in templates or instantiated repos.
- Clean-room-first: every new repo is fresh-root (no legacy git history).
- Every target repo must have: SCOPE, PROVENANCE, SECURITY, and BACKLOG.
- Push only via the Extraction Ledger push-gate (repo exists + empty + private; main only; no --tags/--all/--mirror).
- Canonical local location for clean repos: <projects-root>/<repo>.
  dev/ is the work/extraction area only.
```
