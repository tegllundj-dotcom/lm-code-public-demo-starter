# Public Demo Release Checklist

Use this checklist before publishing any public LM Code demo repository or release.

## Repository safety

- [ ] Use a new public repository, not the private product repository.
- [ ] Do not copy `.git` history from the private repository.
- [ ] Do not make the private product repository public.
- [ ] Do not publish private branches, tags, Actions logs, or release artifacts.
- [ ] Do not include customer code or personal project files.

## Secret scan

- [ ] No `.env` files.
- [ ] No API keys.
- [ ] No license signing keys.
- [ ] No GitHub tokens.
- [ ] No private URLs.
- [ ] No hardcoded local absolute paths.

## Demo behavior

- [ ] `DEMO_MODE=true`.
- [ ] File writes disabled.
- [ ] Patch apply disabled.
- [ ] Real project scanning disabled.
- [ ] Telemetry disabled by default.
- [ ] Network behavior is local-only or mocked.
- [ ] UI clearly labels the build as public demo mode.
- [ ] Static demo opens locally from `demo-app/index.html`.
- [ ] Demo content uses bundled sample data only.

## Release assets

- [ ] Demo zip or installer built from safe demo source only.
- [ ] SHA256 checksums generated.
- [ ] Release marked as pre-release.
- [ ] Release notes state demo limitations clearly.
- [ ] Screenshots contain no private file names, paths, prompts, code, or keys.
- [ ] Demo video contains no private notifications, usernames, local paths, or repository names beyond intended public names.

## Final release note wording

Use this safety wording in the public release:

```text
This is a safe public demo build. It runs in demo mode with sample data. It does not scan real projects, does not write files, does not apply patches, does not collect telemetry by default, and does not include private product source code.
```
