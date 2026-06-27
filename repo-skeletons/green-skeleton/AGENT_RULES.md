# Agent Rules — {{REPO_NAME}}

## Mode

```
agent_work_allowed_now : {{AGENT_WORK_ALLOWED_NOW}}   # yes (docs) / yes (read-only) / no
default                : plan/docs-first
```

## Agents MAY

```
- {{AGENT_MAY_1}}
- read repo docs, draft backlog/ADR/runbook entries
```

## Agents MUST NOT

```
- fill secrets/tokens/keys
- push / tag / create repos
- copy source from legacy repos (unless an approved clean-room extraction)
- change production infra or 20/50/51/60 / Command Center / kernel freeze
```
