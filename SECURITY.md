# Security Policy

## Scope

This public demo is designed to be safe-by-default and non-destructive.

The demo build must not:

- write to user project files
- apply patches
- scan real project directories
- upload source code
- include telemetry by default
- include secrets, tokens, private URLs, or customer code
- include private repository history

## Demo mode requirement

Any executable public demo must run with demo protections enabled.

```text
DEMO_MODE=true
FILE_WRITES=false
PROJECT_SCANNING=false
PATCH_APPLY=false
TELEMETRY=false
```

## Safe workflow principle

LM Code should keep important steps visible and reviewable before any destructive action can occur.

For the public demo, every workflow must remain read-only or mock-only.

## Reporting security issues

For now, do not disclose security issues publicly. Contact the maintainer privately through the GitHub profile or the contact channel provided in the future public repository.

## Commercial product note

The public demo does not represent the full commercial product surface. Commercial builds may include additional features such as licensing, update flow, project workflows, team policy, or private deployment controls.
