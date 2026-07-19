# TOC3 — Preservation, Scanner, Import, and Canonical Lifecycle

```text
scanner/to_process
  -> scanner/processed when useful content should be imported
  -> scanner/unnecessary when not currently useful
  -> import/IMPORTS for extraction plans
  -> proposals/PROPOSALS for staged facts
  -> workflows/BATCHES for reusable plans, validation, apply, and rollback
  -> archive/ARCHIVE for provenance, preservation state, and reviewed snapshots
  -> storage/STORAGE for large/offline placement, integrity, retention, restore, and controlled delivery
  -> canonical/CANONICAL only after sufficient evidence and route validation
```

Archive and storage operate actively whenever an artifact is relevant to debugging or reproducibility. Distribution is a separate, item-specific decision based on rights, provenance, integrity, safety, and review evidence; source availability alone does not decide it.

All repository writes pass through the external private `n-e-o-w-u-l-f/myAPI` control plane. Proposals are created only in `doktor-debug/proposals`; workflow definitions, plans, and templates are created only in `doktor-debug/workflows`.
