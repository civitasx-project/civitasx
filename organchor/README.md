# CivitasX OrgAnchor Public Mirror

This directory mirrors immutable CivitasX OrgAnchor public snapshots in the
GitHub archive.

The active discovery and verification entrypoints remain:

```text
https://civitasx.pages.dev/verify/
https://civitasx.pages.dev/.well-known/organchor.json
```

## Current Adoption Status

```text
current/adoption-status.html
current/adoption-status.json
current/well-known/organchor.json
current/verify/
```

These files explain the current maturity and remaining gaps in CivitasX's own
OrgAnchor adoption.

They do not replace immutable history snapshots, do not create a new root
authority statement, and do not claim complete OrgAnchor paradigm adoption.
They make the live state legible:

```text
Level 1: PASS
Level 2: PASS WITH DOMAIN WARNINGS
Level 3: IN PROGRESS
Level 4: PARTIAL
Level 5: PARTIAL AND BLOCKED
```

The current active verification mirror also includes the signed lockfile and
carrier-ledger materials now deployed at:

```text
https://civitasx.pages.dev/verify/
```

Current carrier-ledger state:

```text
lockfile_integrity: SIGNED
carrier_receipts: PRESENT
opentimestamps_bitcoin_anchor: CONFIRMED_PUBLIC_BLOCK_HEADER_CHECK
public_artifact_recovery: PASSED_PUBLIC_REHEARSAL
```

The active mirror now includes the upgraded OpenTimestamps proof with Bitcoin
block-header attestations. It still does not include a real IPFS CID or a real
Arweave transaction.

## Historical Snapshots

```text
history/2026-07-09/
history/2026-07-10-parent-value-001/
history/2026-07-11-carrier-ledger-001/
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

The second snapshot is the first deployed CivitasX parent value package. It
preserves the same root authority and official statement while adding signed
parent claims, a signed evidence manifest, and the value-continuity audit.

It contains:

```text
root-authority.json
official-endpoints.json
official-endpoints.json.sig
organchor.json
index.html
claims/product-claims.json
claims/product-claims.json.sig
evidence/evidence-manifest.json
evidence/evidence-manifest.json.sig
reports/value-continuity-report.json
reports/value-continuity-report.md
beacon-at-publication.json
```

Production verification at publication reported `identity_status: PASS`,
`value_status: PASS`, and `conformance_status: FULL_COMPATIBLE`. That status is
a verification result, not an endorsement or final trust decision.

The third snapshot is the first carrier-ledger continuity snapshot. It preserves
the active signed parent value package and adds:

```text
organchor.lock.json
organchor.lock.json.sig
anchors/opentimestamps/official-endpoints.json.ots
arweave-manifest-complete-2026-07-11.json
arweave-package-complete-2026-07-11/
```

It records local publication-ledger and carrier-receipt evidence. It does not
claim complete Level 3 adoption, Level 4 completion, Level 5 readiness, real
IPFS publication, real Arweave transaction, Bitcoin-confirmed OpenTimestamps
anchoring, multi-custodian authority, or decentralized governance.

## Verification Boundary

The mirror helps preserve and compare public files. It does not assign final
trust, certify CivitasX, prove the theory is correct, or grant official
continuity to a fork.

Use `CHECKSUMS.sha256` to compare mirrored files. Use OrgAnchor verification
against the active public endpoint for the current package.

No private key material belongs in this directory or repository.
