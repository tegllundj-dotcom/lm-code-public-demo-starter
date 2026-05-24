# LM Code Public Demo

[![Status](https://img.shields.io/badge/status-public%20demo-46dcd2)](#)
[![Mode](https://img.shields.io/badge/mode-mock--only-12343A)](#)
[![Safety](https://img.shields.io/badge/file%20writes-disabled-ddac5c)](#)
[![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)](#)

LM Code is a local-first AI coding workbench for Windows and LM Studio.

It is built for developers and teams who want AI assistance without surrendering control of their codebase.

This repository is the public demo and download surface for LM Code. It is not the commercial product source tree.

## Try it

- Live demo: https://tegllundj-dotcom.github.io/lm-code-public-demo-starter/
- Windows installer: https://github.com/tegllundj-dotcom/lm-code-public-demo-starter/releases/latest

## Why this exists

AI coding assistants are useful, but many developers and organizations still need control over source code exposure, project context, file mutation and review workflows.

LM Code explores a controlled local workflow:

```text
Developer -> task mode -> visible context -> local/model response -> read-only patch preview -> human review
```

The public demo exists as a trust layer. It shows the workflow direction without exposing private product source code or enabling destructive behavior.

## Safety boundaries

The public demo is intentionally constrained:

- no file writes
- no real project scanning
- no patch apply
- no telemetry by default
- mock/sample data only
- no private product source code
- no private repository history
- no customer or personal code

## What the demo shows

- desktop-oriented LM Code UI direction
- task modes for common coding workflows
- mock LM Studio model behavior
- mock streaming assistant responses
- bundled sample project context
- read-only patch preview concept
- safety/status boundaries in the UI

## What this is not

This public repository is not the full commercial LM Code application.

The private product core, licensing system, updater, future team controls, future safe apply engine, private deployment tooling and paid expansion features remain separate unless explicitly released later.

## Best-fit feedback

Feedback is especially useful from:

- Windows-heavy developers
- .NET / WPF / internal tools teams
- LM Studio users
- local LLM users
- software agencies
- internal IT teams
- public-sector or privacy-conscious technical teams
- teams working with sensitive or client-owned code

## Feedback links

Use GitHub Issues for structured feedback:

- installer experience
- public demo clarity
- workflow usefulness
- safety/privacy expectations
- Windows and LM Studio workflow needs

For open-ended discussion, use the starter text in `docs/DISCUSSION_STARTER.md`.

## Run the local public demo

Open this file directly in a browser:

```text
demo-app/index.html
```

The demo is static and self-contained. It uses mock data only and does not call LM Studio, scan files, write files, apply patches or collect telemetry.

## Public release pattern

Public release assets should stay limited to compiled distribution files and verification material such as:

```text
LM-Code-<version>-windows-x64-setup.exe
SHA256SUMS.txt
```

Do not publish private source code, signing keys, private repository history, customer code, local paths, environment files or secrets.

## Core rule

Open-source trust. Sell workflow.
