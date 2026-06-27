# hestiaos-templates

Templates for HestiaOS repositories and agent work.

```
This repo contains templates for HestiaOS repos and agent work.
It contains NO product source.
It is NOT a runtime repo.
It is NOT a secrets / config repo.
Its purpose: create new repos consistently, governance-compatible, and clean-room-capable.
```

## Contents

```
repo-skeletons/green-skeleton/   canonical skeleton copied into new GREEN repos
templates/                       reusable document templates (ADR, backlog, runbook, evidence, ...)
docs/                            template-usage.md, skeleton-policy.md
README/SCOPE/GOVERNANCE/AGENT_RULES/BACKLOG/PROVENANCE/SECURITY/LICENSE/.gitignore
```

## How to use (summary)

Copy `repo-skeletons/green-skeleton/` into a new clean-room candidate, fill the placeholders
(`{{REPO_NAME}}`, `{{OWNER}}`, ...), then follow the push-gate in the Extraction Ledger. See
`docs/template-usage.md` and `docs/skeleton-policy.md`. Templates **prepare** repos; they never push or
publish automatically.
