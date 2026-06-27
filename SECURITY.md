# Security Policy — hestiaos-templates

## Scope

Private template repository. Contains only documentation templates and repo skeletons. No runtime, no network
calls, no secrets.

## Status

Not yet public-ready. A final security reporting channel will be defined before any public release. No
published public disclosure channel until then.

## Rules

```
- No secrets, tokens, keys, .env, internal hostnames, or private IPs in templates or instantiated repos.
- Placeholders ({{...}}) must never be filled with real credentials.
- Report security-relevant issues via the private development workflow (pre-public).
```
