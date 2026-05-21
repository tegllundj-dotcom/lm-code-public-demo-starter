# LM Code Public Demo Starter

This repository is the safe public demo and download surface for LM Code.

It is safe-by-default and includes a small runnable demo app. It must not be treated as the commercial LM Code source tree.

Live demo: https://tegllundj-dotcom.github.io/lm-code-public-demo-starter/

Windows installer: https://github.com/tegllundj-dotcom/lm-code-public-demo-starter/releases/latest

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

## Public installer

The Windows installer is published through GitHub Releases in this public repository. The private LM Code source repository remains private.

Public release assets should stay limited to compiled distribution files and verification material such as:

- Windows installer `.exe`
- `SHA256SUMS.txt`

## Public release pattern

```text
LM Code Windows Installer v<version>
```

Attach only safe public distribution assets:

```text
LM-Code-<version>-windows-x64-setup.exe
SHA256SUMS.txt
```

## Non-goal

This starter kit is not the product source code. The commercial LM Code workbench, licensing system, updater, team/admin features, safe patch apply engine, and private deployment tooling should remain private unless explicitly separated and reviewed later.

## Core rule

Open-source trust. Sell workflow.
