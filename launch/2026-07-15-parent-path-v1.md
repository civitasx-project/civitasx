# CivitasX Parent Path V1 Release

Date: 2026-07-15

Status: published, mirrored, signed, and production-verified.

## Scope

This release publishes CivitasX's first parent-level research note:

```text
From Four Starting Points to a Testable Parent Path
```

It connects OrgAnchor, EchoEnginer, ProvisionLoop, and WillFlow into a working
theory of change. It treats K4 as the missing transition between reproducible
automated supply and unconditional basic provision, not as a fifth project.

The note is a working map, not proof that the proposed path is correct. It names
evidence requirements, failure signals, and a stop rule against further theory
work without a model, implementation, or new evidence.

## Signed Identity State

```text
snapshot_id: 2026-07-15-parent-path-001
root_authority_hash: sha256:a5fed87b2948159240708c29b341e9a4717093787679711f8e8c50644953228f
statement_canonical_hash: sha256:bac1525f3f2c1f13b64325f50164443a6c53eac994ed3ce9756cb904adcd7578
statement_file_hash: sha256:a69dbab599f9dd8a9a485226799ca1d21654525f4e378d5c5f8a2006460aaffd
claims_canonical_hash: sha256:54825ef691435b0fb864b01bcfaf00624880b1e2a4d0541e9603f1415d7703f4
evidence_canonical_hash: sha256:41e58c241fd159454debc85ca6df87fa24c992fb212a9d9447f9f228807ac020
signed_lockfile_hash: sha256:6aa9e69c246fc7bc62b6a9b33ccf360e5e2ca7177535e49f3b105a00870c1456
```

The root authority and stable parent values are unchanged. This is an
operational, evidentiary, and discovery-route update, not an authority change.

## Independent Carriers

IPFS Pinata:

```text
cid: bafybeie7gdli6pislictn6qobwdkhkazdtbvwsjvtn5ijatjedb3626l4u
directory_hash: sha256:fd7a6b2b85077a8db7a62721ac1aa2ecd33e4a85ceffd114a4e7b770a3ec7783
files: 37
```

Arweave Turbo:

```text
owner: FPp1-IGNqgBFcvYTzahkoNx7NlwLgcrwUD3flushljA
directory_hash: sha256:dcb05c435e4d0d30d6090cc747e7f924ff3c8928cc27889f49efdbc626ebd790
manifest_canonical_hash: sha256:5ae0a440f0fbc05e84dd10f44364514215c6662055445a7ce80a47cfb7cb893a
files: 45
verify/index.html: am0WOCZKl7pnWgiHqbk3XyewMmDJZAG6d_1iw2bmZAA
verify/organchor.json: MaicGQb-id8okLSTtSJimf12uBoXNI0VWawCNlgLNJA
verify/organchor.lock.json: oKGb5dXeAuuiXVqqu3ezju7XziLF5-zcbjPIhKqkoxI
```

The three key Arweave files were retrieved from both `turbo-gateway.com` and
`arweave.net` and matched their local SHA-256 hashes. The public Arweave gateway
initially returned 404 while the transactions propagated, then passed the same
hash checks after propagation.

OpenTimestamps:

```text
proof: anchors/opentimestamps/official-endpoints-2026-07-15.json.ots
proof_hash: sha256:363ffd1daa04606a90f8b0a2ea5bb266a6565dda11a4dc3dfb76823ba2a28cef
calendar_receipts: 4 / 4
bitcoin_anchor_status: PENDING
```

The earlier proof remains Bitcoin-confirmed and is not overwritten.

## Supersession

This snapshot supersedes `2026-07-11-carrier-ledger-001` as the active discovery
and evidence package. The earlier snapshot remains historical truth and must
remain byte-identical.

Unchanged:

```text
root authority;
stable parent value core;
four project directions;
CC BY-SA 4.0 reuse boundary;
OrgAnchor verification contract;
Temporary Founder Authority 1-of-1 limitation.
```

Changed:

```text
new official Research index and RSS feed;
new parent-path research note;
new signed parent-path claim and evidence entry;
new carrier receipts and timestamp proof;
new immutable history snapshot.
```

## Known Boundaries

```text
The research note is first-party working theory, not proof.
The 2026-07-15 OpenTimestamps proof is pending Bitcoin confirmation.
The new Arweave transactions are hash-verified through Turbo and arweave.net.
CivitasX still uses civitasx.pages.dev rather than a dedicated domain.
The current authority remains a truthful 1-of-1 Temporary Founder Authority.
Independent S2/S3/S4 evidence remains limited.
```
