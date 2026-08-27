# Dr.Debug-GPT instructions for `doktor-debug/.github`

Version: 2.4.0  
Date: 2026-08-27  
Status: ACTIVE  
Repository role: public organization profile and repository navigation

## Read order

1. This `AGENTS.md`.
2. `README.md`.
3. `profile/README.md`.
4. `profile/TOC1.md`, `profile/TOC2.md`, and `profile/TOC3.md` as relevant.
5. The canonical global policy in `doktor-debug/.agents` when repository architecture, routing, modes, or API ownership are involved.
6. Only the task-relevant profile asset or validation file.

## Mission boundary

Public organization material must describe Dr.Debug as a software/hardware fault-analysis and repair system: intake, evidence, reproduction, isolation, root-cause analysis, mitigation, controlled repair, verification, regression prevention, preservation, and reusable diagnostic knowledge.

Do not present Dr.Debug as a general prompt-authoring, prompt-management, persona-design, or generic agent-memory project.

## Repository registry

The current organization registry contains 16 repositories:

- `doktor-debug/.github`
- `doktor-debug/.agents`
- `doktor-debug/.api`
- `doktor-debug/.archive`
- `doktor-debug/.canonical`
- `doktor-debug/.import`
- `doktor-debug/.memory`
- `doktor-debug/.proposals`
- `doktor-debug/.research`
- `doktor-debug/.scanner`
- `doktor-debug/.storage`
- `doktor-debug/.taxonomy`
- `doktor-debug/.web`
- `doktor-debug/.workflows`
- `doktor-debug/wiki`
- `doktor-debug/doktor-debug.github.io`

An authenticated owner may describe these repositories and the external shared `n-e-o-w-u-l-f/myAPI` dependency without gaining mutation authority. Public descriptions must redact secrets, credentials, private payloads, personal data, raw private logs, and non-public storage locators.

## Repository boundary

This repository may contain only organization-profile text, repository maps, public operating-model summaries, navigation, profile assets, and their validation documentation. It is a presentation/routing surface, not a second technical source of truth.

Canonical routing:

- global agent policy and diagnostic lifecycle -> `doktor-debug/.agents`;
- Dr.Debug-specific `/doktor-debug/**` API -> `doktor-debug/.api`;
- proposals -> `doktor-debug/.proposals`;
- workflows/repair playbooks/validation/rollback -> `doktor-debug/.workflows`;
- shared `/`, health/system information, cross-project discovery, authentication, owner resolution, audit, and dispatch -> `n-e-o-w-u-l-f/myAPI`;
- private render/source layer -> `doktor-debug/.web`;
- deliberate public Pages output -> `doktor-debug/doktor-debug.github.io`.

A thin repository-local GitHub Actions caller is allowed only when GitHub technically requires `.github/workflows/**`; reusable workflow logic remains in `doktor-debug/.workflows` whenever feasible.

## Public/private source rule

Leading-dot repositories are private source/governance/build locations unless GitHub special behavior requires otherwise. An unprefixed public repository is not an automatic mirror. Public material must be deliberately selected, sanitized, traceable, and validated before publication.

Archive and storage are active preservation and delivery services. Distribution remains item-specific and evidence-based.

## Writes

All writes require the applicable authentication, exact repository/path selection, redaction, diff/review, validation, audit, and rollback rules. `OWNER_MODE` does not bypass them.

Allowed local write classes after the gate passes:

- organization-profile text and repository descriptions;
- TOC and navigation maintenance;
- local profile assets;
- repository-local validation and agent instructions.

Do not claim a write, commit, push, merge, publication, or successful validation without tool output.

## Validation

Before reporting success:

1. confirm `profile/README.md` remains the rendered GitHub organization-profile entry;
2. verify the 16-repository registry and current dot-prefixed names;
3. verify `.api` owns `/doktor-debug/**` and `myAPI` owns shared gateway/root concerns;
4. ensure `doktor-debug.github.io` is described as a public-release/Pages target rather than canonical private source;
5. check Markdown links, Mermaid syntax, relative asset paths, and table consistency;
6. confirm proposal/workflow links point to their canonical dot-prefixed repositories;
7. run a secret/private-locator review and inspect the final diff.
