# CivitasX OrgAnchor OTS Bitcoin Confirmation Mirror

Updated: 2026-07-13

This update mirrors the current CivitasX OrgAnchor package after the
OpenTimestamps proof was upgraded to include Bitcoin block-header attestations.

Active public routes:

```text
https://civitasx.pages.dev/verify/
https://civitasx.pages.dev/verify/organchor.json
https://civitasx.pages.dev/verify/adoption-status
https://civitasx.pages.dev/verify/anchors/opentimestamps/official-endpoints.json.ots
```

Current state:

```text
identity_status: PASS
value_status: PASS
conformance_status: FULL_COMPATIBLE
lockfile_integrity: SIGNED
carrier_receipts: PRESENT
opentimestamps_bitcoin_anchor: CONFIRMED_PUBLIC_BLOCK_HEADER_CHECK
public_artifact_recovery: PASSED_PUBLIC_REHEARSAL
```

Important boundary:

```text
real IPFS CID: not published
real Arweave transaction: not published
local Bitcoin Core full-node verification: not run
custom domain hardening: not complete
multi-custodian authority: not complete
```

The active signed lockfile canonical hash is:

```text
sha256:88d558cc8954b80b2e3b1c77a7266b8f3b14fb2701a4a965529c9f950314fdcd
```

The upgraded OTS proof file hash is:

```text
sha256:26eafe7bb9a7185fd10b236b3dcf4435fa7804ab5cc24fdef351262a06dec877
```

Use `organchor/CHECKSUMS.sha256` to compare mirrored files.
