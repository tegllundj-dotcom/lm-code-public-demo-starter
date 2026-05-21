# LM Code Public Demo Starter

This folder is a clean starter kit for a future public repository such as `tegllundj-dotcom/lm-code-demo`.

It is safe-by-default and includes a small runnable demo app. It must not be treated as the commercial LM Code source tree.

## Positioning

LM Code is a local-first AI coding workbench for Windows and LM Studio. It helps developers review, reason about, and prepare code changes while keeping the workflow visible, reviewable, and non-destructive.

## Public demo goal

The public demo should show the LM Code workflow without exposing private product code, private repository history, secrets, customer code, or unsafe file operations.

The demo may show:

- premium desktop UI direction
- LM Studio connection concept
- mock model discovery
- mock streaming chat
- task modes
- sample project context
- read-only patch preview
- Monaco-style editor preview
- history and undo concepts

The demo must not include:

- real project scanning
- file writes
- patch apply
- secrets, tokens, or private URLs
- private repository history
- customer or personal code
- telemetry by default
- cloud model calls by default

## Recommended public repository contents

```text
README.md
SECURITY.md
PRIVACY.md
DEMO_MODE.md
RELEASE_CHECKLIST.md
SAMPLE_RELEASE_NOTES.md
LICENSE.md
demo-app/
  index.html
assets/
  screenshots/
  demo-video-link.md
sample-project/
  README.md
```

## Run the local public demo

Open this file directly in a browser:

```text
demo-app/index.html
```

The demo is static and self-contained. It uses mock data only and does not call LM Studio, scan files, write files, apply patches, or collect telemetry.

## Recommended first public release

```text
LM Code Public Demo v1.0.0-preview
```

Mark it as a pre-release and attach only safe demo assets:

```text
LM-Code-Demo-v1.0.0-preview-win-x64.zip
SHA256SUMS.txt
sample-project.zip
```

## Non-goal

This starter kit is not the product source code. The commercial LM Code workbench, licensing system, updater, team/admin features, safe patch apply engine, and private deployment tooling should remain private unless explicitly separated and reviewed later.

## Core rule

Open-source trust. Sell workflow.
