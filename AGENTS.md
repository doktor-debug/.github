# Dr.Debug-GPT instructions for `doktor-debug/.github`

Version: 2.3.0
Date: 2026-07-19
Status: ACTIVE
Repository role: public organization profile and repository navigation

## Read order

1. This `AGENTS.md`.
2. `README.md`.
3. `profile/README.md`.
4. `profile/TOC1.md`, `profile/TOC2.md`, and `profile/TOC3.md` as relevant.
5. Only the task-relevant profile asset or validation file.

## Dr.Debug-GPT discovery and description

An authenticated `OWNER_MODE` session may discover, read, index, summarize, and describe, without mutation, every repository in this allowlist:

- `doktor-debug/.github`
- `doktor-debug/agents`
- `doktor-debug/archive`
- `doktor-debug/canonical`
- `doktor-debug/import`
- `doktor-debug/memory`
- `doktor-debug/proposals`
- `doktor-debug/research`
- `doktor-debug/scanner`
- `doktor-debug/storage`
- `doktor-debug/taxonomy`
- `doktor-debug/web`
- `doktor-debug/wiki`
- `doktor-debug/workflows`

It may also describe the external private control plane `n-e-o-w-u-l-f/myAPI`. Read/describe authority does not imply write authority.

Public descriptions and reports must redact secrets, credentials, private payloads, personal data, and non-public archive/storage locators. Do not expose a private object key, filesystem path, bucket name, signed URL, or equivalent delivery locator.

## Repository boundary

This repository may contain only the organization profile, repository map, public operating-model summaries, navigation, profile assets, and their validation documentation. It is a presentation and routing surface, not a second source of technical truth.

- Create every proposal only in `doktor-debug/proposals`.
- Create every workflow definition, plan, or template only in `doktor-debug/workflows`.
- A thin repository-local GitHub Actions caller is allowed only when GitHub technically requires `.github/workflows/**`; the reusable workflow definition remains in `doktor-debug/workflows` whenever feasible.
- Gate implementation and write enforcement belong to `n-e-o-w-u-l-f/myAPI`.

`doktor-debug/archive` and `doktor-debug/storage` are active preservation and delivery services. Archive records provenance, preservation state, hashes, and reviewed snapshots. Storage manages large/offline artifact placement, integrity, retention, restore, and controlled delivery. Distribution is decided per item from rights, provenance, integrity, safety, and review evidence; it is not globally allowed or denied merely because an upstream source is online or offline.

## Writes

All writes require a separate successful `n-e-o-w-u-l-f/myAPI` gate for the exact repository, operation, paths, actor, and reason. `OWNER_MODE` does not bypass path policy, redaction, validation, audit, or destructive-operation safeguards.

Allowed local write classes after the gate passes:

- organization-profile text and repository descriptions;
- TOC and navigation maintenance;
- local profile assets;
- repository-local validation and agent instructions.

Do not claim a write, commit, push, merge, publication, or successful validation without tool output.

## Validation

Before reporting success:

1. Confirm `profile/README.md` remains the rendered GitHub organization-profile entry.
2. Verify the active fourteen-repository list and the separate `n-e-o-w-u-l-f/myAPI` control-plane reference.
3. Confirm the content allowlist contains exactly the fourteen repositories listed above and no legacy control-plane content repository.
4. Check Markdown links, Mermaid syntax, relative asset paths, and table consistency.
5. Confirm proposal and workflow links point to their dedicated repositories.
6. Run a secret/private-locator review and inspect the final diff.
