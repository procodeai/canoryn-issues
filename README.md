# Canoryn Issues Repository Starter

Use this starter when creating a public issues-only repository under `procodeai` (recommended name: `canoryn-issues`).

## Suggested Repository Setup

1. Create a public repo with no source code.
2. Keep only:
   - `README.md`
   - `.github/ISSUE_TEMPLATE/*`
3. Disable Discussions initially unless you explicitly want community forums.
4. Enable Issues and Projects.

## Example README for the Issues Repo

```md
# Canoryn Issues & Feedback

This repository is for tracking bugs, feature requests, and product feedback for **Canoryn**.

The application source code is not hosted here.

## Before filing

1. Search existing issues first.
2. Include app version + macOS version.
3. Add steps to reproduce and expected vs actual behavior.
4. If possible, include logs/screenshots.

## Quick links

- Report a bug: `issues/new?template=bug_report.yml`
- Request a feature: `issues/new?template=feature_request.yml`
```

## In-App Link Targets

If using app menu links:

1. `https://github.com/procodeai/canoryn-issues/issues/new?template=bug_report.yml`
2. `https://github.com/procodeai/canoryn-issues/issues/new?template=feature_request.yml`
3. `https://github.com/procodeai/canoryn-issues/issues`

## Notes

- The app currently reads `AppIssueTrackerRepo` from Info.plist via `AppBranding`.
- If this key is missing, default fallback is `procodeai/aura-issues`.
