# Single Admin Marketplace

This directory is the hosted marketplace acceptance source for the
`novusai-admin` single-admin split.

The default backend marketplace source points to:

`https://raw.githubusercontent.com/eric134679/novusai-admin-marketplace/main/marketplace`

Acceptance files:

- `registry.json`: hosted marketplace registry.
- `plugins/audit-logger.json`: hosted package detail.
- `artifacts/audit-logger/audit-logger-1.1.0.zip`: hosted compatible ZIP.
- `artifacts/audit-logger/audit-logger-1.1.0.zip.sha256.json`: checksum evidence.

The marketplace P0 can only be treated as closed after this directory is pushed
to GitHub and the backend validator returns `accepted=true` against the raw
GitHub URLs.
