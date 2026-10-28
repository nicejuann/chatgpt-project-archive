# Project Backup Status

Last checked: 2026-10-28

This repository is **public**. It is a *catalog*, **not yet a complete source-code backup**. Do not infer that a project is backed up merely because a README is present.

## Source archives located in the owner's private ChatGPT Library

| Project | Available source archive | GitHub source status |
| --- | --- | --- |
| Daily Masculinity | `Daily_Masculinity_Source.zip` (1.1.0) | Not yet uploaded |
| Tervalen | `Tervalen-Source.zip` (1.0.0-rc1) | Not yet uploaded |
| Project 100 | `PROJECT_100_Source.zip` | Not yet uploaded |
| Earlier consolidated source | `ChatGPT_Projects_Source_GitHub_Ready.zip` (prepared 2026-10-24; not necessarily the latest code) | Not yet uploaded |

Other materials (compiled APKs, original children's-book assets, personal manuscripts, and some automation exports) require separate backup/review. Automation workflow source is **not** verified as recovered.

## Why source is withheld from this public repository

The source-backup instructions expressly require a **private** repository. The collections can contain unpublished work, internal test-signing identity material, or content that needs licensing and privacy review. A public branch is not private.

No archive, APK, signing key, unreleased manuscript, private journal, personal data, or confidential police/government document was uploaded during this status update.

## Safe next action

1. Change this repository's visibility to **Private** in GitHub repository **Settings → General → Danger Zone → Change repository visibility**, or create a new private repository.
2. Review the original source archive and exclude keystores, signing keys, tokens, `.env`, `local.properties`, personal data, restricted assets and build artifacts. The 2026-10-24 consolidated zip has a `SECURITY_AND_RESTORE.md` checklist.
3. Commit **extracted source files**, not a ZIP-only dump, into separate project directories. Preserve relevant existing source versions and label release candidates accurately.
4. Re-check the repository privacy and verify the actual committed tree after upload.

**Security reminder:** Git history persists. Deleting an exposed secret file does not make the secret safe again; rotate any accidentally exposed credentials.
