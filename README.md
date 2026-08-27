# doktor-debug/.github

Version: 2.4.0  
Date: 2026-08-27

This repository publishes the `doktor-debug` organization profile and its public repository map. GitHub renders `profile/README.md` on the organization profile.

The profile describes the current 16-repository Dr.Debug architecture. Private source/governance repositories use the leading-dot convention where applicable; `wiki` and `doktor-debug.github.io` are public presentation/release surfaces with distinct roles.

API responsibility is split deliberately:

- `doktor-debug/.api` owns Dr.Debug-specific contracts and behavior under `/doktor-debug/**`.
- `n-e-o-w-u-l-f/myAPI` is the external shared gateway/control plane for `/`, shared health/system information, cross-project API discovery, shared authentication/owner resolution, audit, and dispatch.

Read `AGENTS.md` before changing profile content. `profile/TOC1.md`, `profile/TOC2.md`, and `profile/TOC3.md` are maintained navigation pages.

This public repository must not disclose secrets, private payloads, personal data, unredacted private logs, or non-public archive/storage locators.
