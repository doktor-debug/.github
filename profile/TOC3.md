# TOC3 — Diagnostic, Preservation, and Canonical Lifecycle

## Diagnostic lifecycle

```text
INTAKE
  -> TRIAGE
  -> REPRODUCE
  -> ISOLATE
  -> HYPOTHESIS
  -> ROOT_CAUSE_VERIFIED
  -> REPAIR_PLAN
  -> APPLY
  -> VERIFY_FIX
  -> REGRESSION_CHECK
  -> CANONICALIZE / POSTMORTEM
```

For an active incident, evidence-preserving mitigation may occur before root-cause verification when needed to reduce impact safely. A mitigation remains distinct from a verified causal repair.

## Repository routing

```text
.scanner/to_process
  -> .scanner/processed when an artifact is triaged for further use
  -> .scanner/unnecessary when currently unsuitable, with reason/reevaluation state
  -> .import for controlled extraction/staging
  -> .research for source/evidence/reproducibility analysis
  -> .proposals for unresolved claims, corrections, repair candidates, and review requests
  -> .workflows for repair playbooks, validation, apply sequences, migrations, automation, and rollback
  -> .archive for provenance, preservation state, hashes, and reviewed snapshots
  -> .storage for large-artifact placement, integrity, retention, restore, and controlled delivery
  -> .memory for accepted evidence-linked diagnostic observations
  -> .canonical only after sufficient evidence, validation, conflict review, and scope/lineage checks
```

Archive and storage operate actively whenever an artifact is relevant to debugging or reproducibility. Distribution is a separate item-specific decision based on rights, provenance, integrity, scan/safety evidence, sensitivity, and approval; source availability alone does not decide it.

## API lifecycle boundary

Dr.Debug-specific API behavior under `/doktor-debug/**` belongs to `doktor-debug/.api`. Shared root, health/system information, cross-project discovery, authentication/owner resolution, audit, and dispatch belong to the external `n-e-o-w-u-l-f/myAPI` gateway/control plane.

## Publication

`doktor-debug/.web` is private presentation/render source. `doktor-debug/doktor-debug.github.io` is deliberate sanitized public Pages output. A private dot-prefixed source repository is never mirrored wholesale into a public repository.
