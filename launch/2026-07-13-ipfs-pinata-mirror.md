# CivitasX OrgAnchor IPFS Pinata Mirror

Updated: 2026-07-13

This update mirrors the current CivitasX OrgAnchor package after a real IPFS
publication through Pinata was recorded in the signed publication ledger.

Active public routes:

```text
https://civitasx.pages.dev/verify/
https://civitasx.pages.dev/verify/organchor.json
https://civitasx.pages.dev/verify/adoption-status
https://civitasx.pages.dev/verify/organchor.lock.json
```

IPFS carrier:

```text
provider: ipfs-pinata
CID: bafybeibqtofd5n74wyiteepu34irjlllzazsndliglpwk6ogduayaumlc4
gateway check: https://gateway.pinata.cloud/ipfs/bafybeibqtofd5n74wyiteepu34irjlllzazsndliglpwk6ogduayaumlc4/organchor.json
uploaded_directory_hash: sha256:51ef917683a4af249719e0e78d51059a0663ede4d0925dc986e7ece0fb048356
pin_size: 447805
```

Current state:

```text
identity_status: PASS
value_status: PASS
conformance_status: FULL_COMPATIBLE
lockfile_integrity: SIGNED
carrier_receipts: PRESENT_WITH_IPFS_AND_OTS
content_addressed_mirror: PUBLISHED_IPFS_PINATA
opentimestamps_bitcoin_anchor: CONFIRMED_PUBLIC_BLOCK_HEADER_CHECK
```

Important boundary:

```text
IPFS/Pinata is a carrier, not the identity root.
real Arweave transaction: not published
local Bitcoin Core full-node verification: not run
custom domain hardening: not complete
multi-custodian authority: not complete
```

The active signed lockfile canonical hash is:

```text
sha256:7c94c2ec834f8db730cd87127077cd693bb9c83ae9c11f89fa7fcc1dac277066
```

Use `organchor/CHECKSUMS.sha256` to compare mirrored files.
