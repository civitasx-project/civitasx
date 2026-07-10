# CivitasX OrgAnchor Public Mirror

This directory mirrors immutable CivitasX OrgAnchor public snapshots in the
GitHub archive.

The active discovery and verification entrypoints remain:

```text
https://civitasx.pages.dev/verify/
https://civitasx.pages.dev/.well-known/organchor.json
```

## Historical Snapshots

```text
history/2026-07-09/
```

This is the first deployed CivitasX identity-continuity snapshot under OrgAnchor
schema v1.0.

It contains:

```text
root-authority.json
official-endpoints.json
official-endpoints.json.sig
organchor.json
index.html
beacon-at-publication.json
```

The snapshot is historical, not the active discovery route. Future protocol or
value-layer upgrades may add stronger checks without silently replacing this
record.

## Verification Boundary

The mirror helps preserve and compare public files. It does not assign final
trust, certify CivitasX, prove the theory is correct, or grant official
continuity to a fork.

Use `CHECKSUMS.sha256` to compare mirrored files. Use OrgAnchor verification
against the active public endpoint for the current package.

No private key material belongs in this directory or repository.
