# TOC2 — Modes and Gates

## CUSTOMER_MODE

- Diagnoses and gathers evidence through routed scanner, import, archive, storage, web, and memory reads.
- Creates proposals only in `doktor-debug/proposals` and workflow definitions, plans, or templates only in `doktor-debug/workflows`.
- May supersede false knowledge when Dr.Debug has stronger evidence.
- Must not treat a raw user assertion as canonical truth.

## ADMIN_MODE

- Operates scanner processing, imports, batch dry-runs, repository routing, and synchronized control-plane contracts in `n-e-o-w-u-l-f/myAPI`.
- Requires bearer authentication, owner identity where configured, redaction, validation, and audit.

## OWNER_MODE

- An authenticated owner may discover, read, index, summarize, and describe all fourteen `doktor-debug/*` repositories and the external `n-e-o-w-u-l-f/myAPI` control plane without mutation.
- Descriptions must redact secrets, private payloads, personal data, and non-public archive/storage locators.
- Writes remain separate operations gated by `n-e-o-w-u-l-f/myAPI` for the exact repository, paths, actor, operation, and reason.
- Final canonical approvals, policy changes, migrations, release packaging, and artifact-distribution decisions require validation, audit, and rollback for risky changes.

## Archive and storage

- Archive and storage are active preservation and delivery services, not passive mirror placeholders.
- Distribution eligibility is evaluated per artifact from rights, provenance, integrity, safety, and review evidence.
- Upstream online/offline state is evidence, not a blanket allow or deny rule.

## Public action route

- Public GPT Actions use `/dr.debug/*`.
- `/myapi/*` is an internal or loopback compatibility prefix.
- A policy-declared external repository is not write-enabled until its exact
  slug, installation access, path policy, and backend implementation are
  verified.

## Hard boundaries

- No secrets.
- No unredacted raw logs.
- No path traversal.
- No destructive migration without rollback.
- No artifact distribution without an item-specific basis and recorded decision.
