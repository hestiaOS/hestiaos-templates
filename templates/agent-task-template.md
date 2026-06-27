# Agent Task: {{TASK}}

## Task

{{TASK}}

## Mode

{{MODE}}

## Allowed actions

- {{ALLOWED_ACTION_1}}
- {{ALLOWED_ACTION_2}}

## Forbidden actions

- Do not push, tag, release, clone, move, or create remotes unless explicitly approved.
- Do not copy product source or legacy repository history.
- Do not add secrets, credentials, private hostnames, private IPs, or runtime artifacts.
- Do not change production infrastructure.

## Inputs

- Repository: {{REPO_NAME}}
- Owner: {{OWNER}}
- Status: {{STATUS}}
- Source: {{SOURCE}}
- Provenance: {{PROVENANCE}}

## Outputs

{{OUTPUTS}}

## Acceptance criteria

{{ACCEPTANCE_CRITERIA}}

## Stop condition

Stop immediately if the task requires secrets, product source, external writes, private infrastructure changes, or migration decisions outside the approved scope.

## Report format

- Path: {{PATH}}
- Status: {{STATUS}}
- Evidence: {{EVIDENCE}}
- Risk level: {{RISK_LEVEL}}
- Next action: {{NEXT_ACTION}}
