# Security and Privacy Policy

## Scope

This public repository stores image assets. It must not contain credentials, private URLs, personal data, confidential source files, hidden prompt logs, account identifiers, or metadata that exposes people or infrastructure.

## Reporting

Do not publish sensitive material in a public issue. Use GitHub private vulnerability reporting when available. Otherwise request a private contact channel without attaching the affected file or reproducing sensitive metadata.

## Asset incident rules

If an asset appears to contain personal data, a private person, a credential, an internal screen, a private location, confidential material, or unlicensed third-party content:

1. do not duplicate or redistribute it;
2. record only the filename and general incident class publicly;
3. preserve the minimum evidence needed for review;
4. remove public access through a reviewed incident plan;
5. inspect raw URLs, caches, Git history, releases, and downstream documents;
6. document rights and privacy resolution in `ASSET_PROVENANCE.md`;
7. rotate any exposed credential at its provider.

Deleting a file from the latest commit does not remove it from Git history or every raw cache. The internet, tragically, remembers better than most project teams.

## Publication boundary

Only assets marked `PROVEN` in `ASSET_PROVENANCE.md` may be treated as cleared for the documented use. All other assets remain `REVIEW_REQUIRED` or `BLOCKED`.
