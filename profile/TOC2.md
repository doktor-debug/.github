# TOC2 — Modes and Gates

Permission mode and diagnostic phase are separate dimensions. Authority does not prove a diagnosis.

## CUSTOMER_MODE

- Supports safe additive `INTAKE`, `TRIAGE`, evidence collection, reproduction guidance, and non-destructive isolation.
- Unresolved hypotheses, correction/fix candidates, and review requests go only to `doktor-debug/.proposals`.
- Workflow definitions, repair playbooks, validation sequences, automation, migrations, and rollback plans go only to `doktor-debug/.workflows`.
- Must not promote an unverified hypothesis or claim a repair succeeded without validation of the original failure condition.

## ADMIN_MODE

- Supports authenticated inspection, reproduction, isolation, dry-runs, validation, repair-plan preparation, and reversible staging.
- May establish a verified root cause only when evidence supports it; authority is not an evidence grade.
- Protected mutation still requires the applicable owner/gateway gate.

## OWNER_MODE

- An authenticated owner may discover, read, index, summarize, and describe all 16 `doktor-debug` repositories plus the external shared `n-e-o-w-u-l-f/myAPI` dependency without gaining mutation authority from that read capability.
- Controlled repair application, canonical promotion, migrations, publication, agent-policy changes, and API/control-plane changes remain separately gated.
- A repair is successful only after the original failure condition has been retested and acceptance criteria are met.

## API ownership

- `doktor-debug/.api` owns Dr.Debug-specific routes/contracts under `/doktor-debug/**`.
- `n-e-o-w-u-l-f/myAPI` owns shared `/`, health/system information, cross-project discovery, authentication/owner resolution, audit, dispatch, and common gateway enforcement.
- Neither layer may silently duplicate or weaken the other.

## Archive and storage

- Archive and storage are active preservation and delivery services, not passive mirror placeholders.
- Distribution eligibility is evaluated per artifact from rights, provenance, integrity, scan/safety evidence, sensitivity, and review/approval state.
- Upstream online/offline state is evidence, not a blanket allow or deny rule.

## Hard boundaries

- No secrets or private credentials.
- No unredacted private logs or private storage locators in public output.
- No path traversal or implicit scope widening.
- No destructive migration/repair without the required recovery/rollback plan.
- No successful-fix claim without verification against the original failure.
- No artifact distribution without an item-specific basis and recorded decision.
