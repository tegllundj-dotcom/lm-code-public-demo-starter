# LM Code Public Demo v1.0.0-preview

This is a safe public demo build of LM Code.

LM Code is a local-first AI coding workbench for Windows and LM Studio. This public demo shows the product direction without exposing private product code or enabling unsafe file operations.

## What this preview demonstrates

- Desktop-oriented LM Code UI direction
- LM Studio connection concept
- Task-mode based coding workflow
- Mock streaming assistant responses
- Sample project context
- Read-only patch preview concept
- History and undo workflow concepts

## Safety boundaries

This public demo runs in demo mode:

```text
DEMO_MODE=true
FILE_WRITES=false
PROJECT_SCANNING=false
PATCH_APPLY=false
TELEMETRY=false
```

The demo does not:

- scan real projects
- write files
- apply patches
- upload source code
- collect telemetry by default
- include private product source code
- include private repository history

The preview includes a static browser demo at `demo-app/index.html` with bundled sample data only.

## Suggested assets

Attach these files to the GitHub release:

```text
LM-Code-Demo-v1.0.0-preview-win-x64.zip
SHA256SUMS.txt
sample-project.zip
```

## Known limitations

This is not the full commercial product. Licensing, updater, team administration, private deployment, and paid expansion features are not included in this public demo.

## Feedback

Use GitHub Issues in the future public demo repository for demo feedback only. Security reports should be sent privately according to `SECURITY.md`.
