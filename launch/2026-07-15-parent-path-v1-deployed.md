# CivitasX Parent Path V1 Deployment

Date: 2026-07-15

Status: deployed and production-verified.

## Public Routes

```text
Research: https://civitasx.pages.dev/research/
Parent-path note: https://civitasx.pages.dev/research/from-four-starting-points/
RSS: https://civitasx.pages.dev/research/feed.xml
Verification: https://civitasx.pages.dev/verify/
Snapshot: https://civitasx.pages.dev/verify-history/2026-07-15-parent-path-001/
GitHub tag: https://github.com/civitasx-project/civitasx/releases/tag/parent-path-v1-2026-07-15
```

Cloudflare deployment:

```text
deployment_url: https://c7b43e81.civitasx.pages.dev
files_expected: 155
files_checked: 155
byte_alignment: PASS
required_routes: 19 / 19 PASS
```

Production OrgAnchor verification:

```text
overall_status: PASS
identity_status: PASS
value_status: PASS
conformance_status: FULL_COMPATIBLE
statement_hash: sha256:bac1525f3f2c1f13b64325f50164443a6c53eac994ed3ce9756cb904adcd7578
lockfile_hash: sha256:6aa9e69c246fc7bc62b6a9b33ccf360e5e2ca7177535e49f3b105a00870c1456
```

Content checks:

```text
article_hash: sha256:db96f6e290305c5c983bf2c505cb929775cfba9d41dc0659e97ef097dc4ee322
RSS XML: PASS
HTML files: 21
internal references: 273
JSON files: 71
Arweave manifest artifact checks: 108
```

## Public Archive

```text
commit: 39727e27f4d763f4acb28d1606c1203459528cdc
tag: parent-path-v1-2026-07-15
```

The tag preserves the frozen snapshot and pre-deployment publication state. The
active site now points to the same signed statement, claims, evidence, lockfile,
research bytes, and immutable history snapshot.

## Carrier Retrieval

IPFS:

```text
cid: bafybeie7gdli6pislictn6qobwdkhkazdtbvwsjvtn5ijatjedb3626l4u
organchor.json: HASH VERIFIED
organchor.lock.json: HASH VERIFIED
HTML through Pinata shared gateway: BLOCKED BY SHARED-GATEWAY HTML POLICY
HTML through two independent public gateways: TEMPORARILY UNAVAILABLE
```

The machine-readable identity and signed ledger are retrievable and verified.
HTML gateway availability is not treated as identity failure.

Arweave Turbo:

```text
files: 45
directory_hash: sha256:dcb05c435e4d0d30d6090cc747e7f924ff3c8928cc27889f49efdbc626ebd790
turbo-gateway.com: 3 / 3 KEY FILES HASH VERIFIED
arweave.net: 3 / 3 KEY FILES HASH VERIFIED AFTER PROPAGATION
```

OpenTimestamps:

```text
2026-07-15 proof: PENDING BITCOIN CONFIRMATION
prior proof: BITCOIN-CONFIRMED AND PRESERVED
```

## Boundaries

This deployment publishes a working theory of change. It does not prove the
parent path is correct, turn K4 into a fifth project, complete multi-custodian
governance, or remove the need for models, implementations, pilots, and
independent evidence.
