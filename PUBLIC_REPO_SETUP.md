# Public Repository Setup

Use this process to create the future public demo repository safely.

## Target repository

```text
tegllundj-dotcom/lm-code-demo
```

Recommended visibility:

```text
public
```

Recommended description:

```text
Safe public demo starter for LM Code — a local-first AI coding workbench for Windows and LM Studio.
```

## Safe setup process

1. Create a brand-new empty public GitHub repository.
2. Do not clone or expose the private `lm-code` repository history.
3. Copy only the reviewed files from `public-demo-starter/` into the new repository root.
4. Add only safe screenshots, sample data, and demo assets.
5. Run the release checklist before creating any release.
6. Mark the first release as a pre-release.

## Suggested first commit in public repo

```text
docs: add LM Code public demo starter
```

## Suggested public repo structure

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

## Do not copy

Do not copy these from the private product repository unless separately reviewed:

- `.git/`
- `.github/workflows/` from private product repo
- private source tree
- product package lock files
- Tauri signing configuration
- license key tooling
- release signing keys
- private docs
- customer or personal project files

## First public release checklist

Before publishing `v1.0.0-preview`, confirm:

- public demo is read-only
- no file writes
- no project scanning
- no patch apply
- no telemetry by default
- no secrets
- no private code history
- no commercial source code unless intentionally released
