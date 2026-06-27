# Template Usage

## Purpose

`hestiaos-templates` provides reusable clean-room templates for HestiaOS repositories and agent work. Templates prepare repositories and documents; they do not approve publication, pushes, tags, releases, or production changes.

## How to use templates

1. Select the smallest matching template from `repo-skeletons/` or `templates/`.
2. Copy it into a new clean-room candidate or planning document.
3. Replace placeholders such as `{{REPO_NAME}}`, `{{OWNER}}`, `{{STATUS}}`, `{{SOURCE}}`, `{{PROVENANCE}}`, `{{RISK_LEVEL}}`, `{{ACCEPTANCE_CRITERIA}}`, `{{DECISION}}`, `{{EVIDENCE}}`, and `{{NEXT_ACTION}}`.
4. Keep all content clean-room-safe: no product source, secrets, private infrastructure details, runtime artifacts, or legacy git history.
5. Capture provenance and evidence before any later gate decision.

## Required files for GREEN skeleton repositories

Every GREEN skeleton repository must include:

- `README.md`
- `SCOPE.md`
- `GOVERNANCE.md`
- `AGENT_RULES.md`
- `BACKLOG.md`
- `PROVENANCE.md`
- `SECURITY.md`
- `.gitignore`

`LICENSE` is added when the repository ownership and licensing decision is clear.

## Agent usage

Agents may read templates, copy skeletons into new clean-room candidates, and draft ADRs, backlog items, runbooks, evidence records, provenance notes, security reviews, and agent tasks.

Agents must not fill secrets, copy legacy source, push repositories, create tags, create remotes, or modify production infrastructure unless a separate explicit gate allows it.

## Not a release gate

Using a template is not approval to publish. Push, release, remote creation, and tag creation require a separate human-approved gate and a clean scan result.
