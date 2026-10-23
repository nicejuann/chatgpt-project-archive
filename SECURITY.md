# Security and publication policy

This is a **public** GitHub repository.

## Must not be committed
- Passwords, service API keys, OAuth tokens, certificates, signing keys, `.env` files with secrets, keystores, and credentials.
- Personal journals, health information, financial information, private correspondence, and app user data.
- PNP documents, intelligence reports, investigative material, personnel lists, government records, or other confidential operational content.
- Materials whose redistribution terms or copyright status have not been verified.

## Before publishing any recovered source archive
1. Examine each file and its embedded archives.
2. Verify no private credentials, personal data, or sensitive material.
3. Check third-party asset and translation licenses.
4. Exclude build caches and temporary binary artifacts.
5. Commit reviewed individual source files with a meaningful history.

**Important:** Secrets committed to GitHub may remain in history even after the file is deleted. Rotate exposed keys rather than relying on file deletion alone.
