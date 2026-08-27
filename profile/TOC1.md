# TOC1 — Repository Map

| Repository | Role | Canonical entry |
|---|---|---|
| `.agents` | Global agent instructions, modes, diagnostic lifecycle, routing, gates | `.agents/AGENTS.md` |
| `.api` | Dr.Debug-specific `/doktor-debug/**` API contract and domain layer | `.api/AGENTS.md` |
| `.memory` | Accepted textual diagnostic observations and knowledge | `.memory/MEMORY/INDEX.md` |
| `.canonical` | Reviewed root causes, facts, methods, conflicts, supersede lineage | `.canonical/CANONICAL/` |
| `.research` | Sources, claims, contradictions, reproducibility and rights review | `.research/` |
| `.taxonomy` | Device/software/dependency classification and relations | `.taxonomy/TAXONOMY/` |
| `.scanner` | Untrusted artifact intake and triage | `.scanner/to_process/` |
| `.import` | Controlled extraction/import staging | `.import/` |
| `.proposals` | Unresolved correction, repair and structural proposals | `.proposals/PROPOSALS/` |
| `.workflows` | Repair playbooks, validation sequences, batches, migrations and rollback | `.workflows/WORKFLOWS/` |
| `.archive` | Active provenance, preservation, snapshots and distribution decisions | `.archive/ARCHIVE/` |
| `.storage` | Artifact integrity, retention, restore and controlled delivery | `.storage/STORAGE/` |
| `.web` | Private sanitized renderer/web source | `.web/` |
| `.github` | Public organization profile and navigation | `.github/profile/README.md` |
| `wiki` | Public human-readable documentation portal | `wiki/index.md` |
| `doktor-debug.github.io` | Deliberate generated/sanitized Pages release target | `doktor-debug.github.io/` |

## External shared gateway/control plane

`n-e-o-w-u-l-f/myAPI` is a separate shared dependency. It owns `/`, shared health/system information, cross-project API discovery, shared authentication/owner resolution, audit, dispatch, and other cross-project gateway concerns.

Dr.Debug-specific routes and contracts under `/doktor-debug/**` belong to `doktor-debug/.api`. Neither layer should duplicate the other.

## Source/publication rule

Leading-dot repositories are private source/governance/build locations unless GitHub special behavior requires otherwise. Public Wiki/Pages output must be deliberately selected, sanitized, traceable, and validated; it is not an automatic mirror of private source repositories.
