# CivitasX Carrier-Ledger Continuity Snapshot

Published: 2026-07-12

CivitasX deployed a refreshed OrgAnchor carrier-ledger package for parent
continuity.

This update preserves the existing public statement, FAQ, adoption-status
routes, and Parent Value V2 value layer, while adding signed publication-ledger
and carrier-receipt materials to the active verification package.

## Public Routes

```text
Active verification: https://civitasx.pages.dev/verify/
Beacon: https://civitasx.pages.dev/.well-known/organchor.json
Adoption status: https://civitasx.pages.dev/verify/adoption-status
Carrier-ledger history: https://civitasx.pages.dev/verify-history/2026-07-11-carrier-ledger-001/
```

Deployment URL:

```text
https://5ab7691b.civitasx.pages.dev
```

The initial carrier-ledger deployment was followed by a same-day
adoption-status refresh so the public status page no longer listed deployment
and GitHub mirroring as future actions after they were complete.

## Verification At Publication

The exact deployment URL passed byte-alignment verification:

```text
FilesExpected: 98
FilesChecked: 98
Failures: 0
```

The production URL passed byte-alignment verification:

```text
BaseUrl: https://civitasx.pages.dev
FilesExpected: 98
FilesChecked: 98
Failures: 0
```

The production carrier-candidate audit passed:

```text
Status: PASS
HtmlFiles: 11
InternalReferences: 139
JsonFiles: 49
ManifestArtifactChecks: 72
HttpRouteChecks: 14
Failures: 0
```

## Mirror Locations

This GitHub archive mirrors the active and historical OrgAnchor records at:

```text
organchor/current/well-known/organchor.json
organchor/current/verify/
organchor/history/2026-07-11-carrier-ledger-001/
organchor/CHECKSUMS.sha256
```

## What Changed

The live package now includes:

```text
organchor.lock.json
organchor.lock.json.sig
anchors/opentimestamps/official-endpoints.json.ots
arweave-manifest-complete-2026-07-11.json
arweave-package-complete-2026-07-11/
```

Current carrier-ledger state:

```text
lockfile_integrity: SIGNED
carrier_receipts: PRESENT
```

## What This Does Not Claim

This update does not claim:

```text
complete Level 3 adoption;
Level 4 completion;
Level 5 readiness;
real IPFS publication;
real Arweave transaction;
Bitcoin-confirmed OpenTimestamps anchoring;
custom-domain hardening;
multi-custodian authority;
decentralized governance;
or proof that CivitasX is correct.
```

OrgAnchor does not assign final trust, certify CivitasX, or prove future
outcomes. People, organizations, directories, and Agents still apply their own
external policy.
