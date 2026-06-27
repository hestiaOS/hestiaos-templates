# Agent Rules — hestiaos-templates

## Agents MAY

```
- Read templates.
- Copy skeletons into NEW clean-room candidates (under dev/_cleanroom_* work area).
- Draft backlog items, ADRs, runbooks from the templates.
- Fill non-secret placeholders ({{REPO_NAME}}, {{OWNER}}, {{STATUS}}, {{SOURCE}}, {{PROVENANCE}},
  {{RISK_LEVEL}}, {{ACCEPTANCE_CRITERIA}}).
```

## Agents MUST NOT

```
- Fill in secrets / tokens / keys / credentials.
- Push repos or create GitHub repos.
- Create tags.
- Copy source from legacy repos into a skeleton.
- Change production infrastructure or any of 20/50/51/60, the Command Center, or the kernel freeze.
```

## Default mode

```
Plan/docs-first. Any code or publish step needs an explicit human Go and passes the push-gate.
```
