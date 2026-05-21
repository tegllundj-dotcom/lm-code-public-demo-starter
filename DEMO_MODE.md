# Demo Mode Contract

Demo mode is the public safety boundary for LM Code demo releases.

## Required flags

```text
DEMO_MODE=true
FILE_WRITES=false
PROJECT_SCANNING=false
PATCH_APPLY=false
TELEMETRY=false
NETWORK_MODE=local-or-mock
```

## Allowed behavior

A demo build may:

- render the desktop UI
- show mock LM Studio model discovery
- show mock streaming responses
- show sample project context
- render read-only patch previews
- demonstrate task modes
- demonstrate history and undo UI states
- open bundled sample files
- run as a static browser demo with bundled mock data

## Forbidden behavior

A demo build must not:

- write files
- apply patches
- scan user directories
- send project contents over the network
- include secrets or private URLs
- include customer or personal code
- mutate Git repositories
- collect telemetry by default

## UI copy requirement

The demo UI should clearly state:

```text
Public Demo Mode: read-only, sample data, no file writes, no patch apply.
```

## Release naming

Use pre-release naming until the public demo has been tested independently.

```text
LM Code Public Demo v1.0.0-preview
```
