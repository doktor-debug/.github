# TOC1 — Repository Map

| Repository | Role | Canonical entry |
|---|---|---|
| `agents` | Global instructions for all repositories | `agents/AGENTS.md` |
| `memory` | Textual debug knowledge | `memory/MEMORY/INDEX.md` |
| `web` | Visual/manual/media GitHub Pages memory | `web/index.md` |
| `.github` | Organization profile visible on GitHub | `.github/profile/README.md` |
| `wiki` | Standalone documentation portal | `wiki/index.md` |
| `archive` | Active provenance, preservation, reviewed snapshots, and distribution decisions | `archive/ARCHIVE/` |
| `scanner` | File triage lifecycle | `scanner/to_process/` |
| `proposals` | Staged knowledge proposals | `proposals/PROPOSALS/` |
| `import` | PDF/code/dependency extraction | `import/IMPORTS/` |
| `canonical` | Reviewed canonical knowledge | `canonical/CANONICAL/` |
| `workflows` | Batch/migration orchestration | `workflows/BATCHES/` |
| `storage` | Active large/offline artifact storage, integrity, retention, restore, and controlled delivery | `storage/STORAGE/` |
| `research` | Source and claim review | `research/SOURCES/` |
| `taxonomy` | Device/software/eclass stammbaum | `taxonomy/TAXONOMY/` |

## External control plane

`n-e-o-w-u-l-f/myAPI` provides authenticated mode, repository, path, redaction, validation, and audit gates for writes. It is a separate private control-plane dependency, not a `doktor-debug/*` content repository.
