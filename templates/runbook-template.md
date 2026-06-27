# Runbook: {{TITLE}}

## Purpose

{{PURPOSE}}

## Preconditions

- Repository: {{REPO_NAME}}
- Owner: {{OWNER}}
- Status: {{STATUS}}
- Provenance confirmed: {{PROVENANCE}}

## Steps

1. {{STEP_1}}
2. {{STEP_2}}
3. {{STEP_3}}

## Expected outputs

{{EXPECTED_OUTPUTS}}

## Rollback / stop condition

Stop if secrets, product source, legacy history, runtime artifacts, private infrastructure details, or unapproved external writes are encountered.

Rollback action: {{ROLLBACK_ACTION}}

## Evidence to capture

{{EVIDENCE}}

## What not to do

- Do not push, tag, release, or create remotes unless explicitly approved.
- Do not copy source from legacy repositories.
- Do not fill placeholders with secrets, credentials, private hostnames, or private IPs.
