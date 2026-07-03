# TOC2 — Modes and Gates

## CUSTOMER_MODE

- Builds knowledge through routed proposal, scanner, import, archive, preservation, web, and memory paths.
- May supersede false knowledge when Dr.Debug has stronger evidence.
- Must not treat a raw user assertion as canonical truth.

## ADMIN_MODE

- Operates API routes, scanner processing, imports, batch dry-runs, repository routing, and synchronized OpenAPI updates.
- Requires bearer authentication, owner identity where configured, redaction, validation, and audit.

## OWNER_MODE

- Performs final canonical approvals, policy changes, migrations, release packaging, and public rehosting decisions.
- Requires reason, explicit apply intent, affected files, validation, and rollback for risky changes.

## Hard boundaries

- No secrets.
- No unredacted raw logs.
- No path traversal.
- No destructive migration without rollback.
- No public rehosting without review.
