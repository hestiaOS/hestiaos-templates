# Skeleton Policy

## GREEN Skeleton Policy

GREEN repositories may receive a fresh-root skeleton when the scope is clear and no legacy source is required. Skeletons must include README, scope, governance, agent rules, backlog, provenance, security, and ignore rules. GREEN skeleton work is local until a separate push gate approves publication.

## YELLOW Clean-Room Scan Policy

YELLOW repositories need clean-room analysis before migration or publication. Agents may inspect documentation and planning material, but must not copy product source, preserve old git history, or publish content until scope, provenance, risk, and scan results are documented.

## RED Migration Hold Policy

RED repositories are on hold. No skeleton publication, source migration, push, tag, release, or infrastructure action is allowed without explicit hardening approval. Work is limited to planning notes that do not expose secrets, private infrastructure details, customer data, or product source.

## DONE Remote Truth Policy

DONE repositories already have an accepted remote truth. New work must respect the established remote, branch, provenance, and gate rules. Do not recreate, overwrite, mirror-push, or tag without explicit approval.

## `dev/` vs `projects/` storage rule

`<dev-root>/` is the extraction, planning, and clean-room candidate area. It may contain unfinished local candidates such as `_cleanroom_*`.

`<projects-root>/` is the intended stable local home after a repository has passed its gate and has a confirmed remote truth. Moving from `dev/` to `projects/` requires a separate approved step.
