# Value Continuity Report

Audited at: `2026-07-10T12:50:03.060Z`

Claims: `claims\product-claims.json`

Evidence: `evidence\evidence-manifest.json`

## Summary

| Status | Count |
| --- | ---: |
| PASS | 63 |
| WARN | 0 |
| FAIL | 0 |
| MANUAL_CHECK_REQUIRED | 8 |

## Value Metrics

| Metric | Count |
| --- | ---: |
| Total claims | 9 |
| Self-asserted claims | 0 |
| Evidence-linked claims | 9 |
| Third-party claims | 0 |
| Reproducible claims | 9 |
| Time-proven claims | 0 |
| Unsupported claims | 0 |
| Total evidence items | 8 |
| External evidence items | 8 |
| First-party evidence items | 8 |
| Stale evidence items | 0 |
| Profile-declared claims | 0 |
| Profile PASS claims | 0 |
| Profile gap claims | 0 |

## S2 Third-Party Material Metrics

| Metric | Count |
| --- | ---: |
| Effective S2 items | 0 |
| Candidate unverified external materials | 0 |
| S2 generic-route items | 0 |
| S2 verified-route items | 0 |
| S2 issuer-backed items | 0 |
| Expired S2 items | 0 |
| Broken S2 anchor URLs | 0 |
| S2 manual checks | 0 |

## S3 Random Purchase / Sampling Metrics

| Metric | Count |
| --- | ---: |
| Effective S3 items | 0 |
| Candidate unverified sampling items | 0 |
| S3 sampling-route items | 0 |
| S3 custody-documented items | 0 |
| S3 independent-test items | 0 |
| Organization-selected samples | 0 |
| Organization-provided samples | 0 |
| Missing sample identity | 0 |
| Missing claim binding | 0 |
| Missing sample pool | 0 |
| Missing sample slot | 0 |
| Missing finite sample policy | 0 |
| Missing duplicate control | 0 |
| Missing credential binding | 0 |
| Missing sampling plan | 0 |
| Organization can choose samples | 0 |
| Missing raw evidence reference | 0 |
| Organization-controlled raw storage | 0 |
| Missing custody documentation | 0 |
| S3 manual checks | 0 |

## S4 Real-World Observation Metrics

| Metric | Count |
| --- | ---: |
| Effective S4 items | 0 |
| Candidate unverified observation items | 0 |
| S4 observation-summary items | 0 |
| S4 raw-bundle-available items | 0 |
| S4 reviewed observation items | 0 |
| Current-window observations | 0 |
| Historical observations | 0 |
| Raw bundle available | 0 |
| Missing subject binding | 0 |
| S4 manual checks | 0 |

## Checks

| Status | Check | Summary |
| --- | --- | --- |
| PASS | claims_manifest | Claims manifest loaded from claims\product-claims.json. |
| PASS | evidence_manifest | Evidence manifest loaded from evidence\evidence-manifest.json. |
| PASS | correction_chain | A correction or supersession policy is present. |
| PASS | evidence:ev-public-intro-en:location | Evidence has at least one external/public location. |
| MANUAL_CHECK_REQUIRED | evidence:ev-public-intro-en:issuer | Evidence is first-party. This may be valid, but it is not independent evidence. |
| PASS | evidence:ev-public-intro-en:reproducibility | Evidence reproducibility is reproducible. |
| PASS | evidence:ev-public-intro-en:method_refs | Evidence links to a low-cost recheck method. |
| PASS | evidence:ev-public-faq-en:location | Evidence has at least one external/public location. |
| MANUAL_CHECK_REQUIRED | evidence:ev-public-faq-en:issuer | Evidence is first-party. This may be valid, but it is not independent evidence. |
| PASS | evidence:ev-public-faq-en:reproducibility | Evidence reproducibility is reproducible. |
| PASS | evidence:ev-public-faq-en:method_refs | Evidence links to a low-cost recheck method. |
| PASS | evidence:ev-official-endpoints-statement:location | Evidence has at least one external/public location. |
| MANUAL_CHECK_REQUIRED | evidence:ev-official-endpoints-statement:issuer | Evidence is first-party. This may be valid, but it is not independent evidence. |
| PASS | evidence:ev-official-endpoints-statement:reproducibility | Evidence reproducibility is reproducible. |
| PASS | evidence:ev-official-endpoints-statement:method_refs | Evidence links to a low-cost recheck method. |
| PASS | evidence:ev-history-snapshot-index:location | Evidence has at least one external/public location. |
| MANUAL_CHECK_REQUIRED | evidence:ev-history-snapshot-index:issuer | Evidence is first-party. This may be valid, but it is not independent evidence. |
| PASS | evidence:ev-history-snapshot-index:reproducibility | Evidence reproducibility is reproducible. |
| PASS | evidence:ev-history-snapshot-index:method_refs | Evidence links to a low-cost recheck method. |
| PASS | evidence:ev-public-license:location | Evidence has at least one external/public location. |
| MANUAL_CHECK_REQUIRED | evidence:ev-public-license:issuer | Evidence is first-party. This may be valid, but it is not independent evidence. |
| PASS | evidence:ev-public-license:reproducibility | Evidence reproducibility is reproducible. |
| PASS | evidence:ev-public-license:method_refs | Evidence links to a low-cost recheck method. |
| PASS | evidence:ev-founding-baseline:location | Evidence has at least one external/public location. |
| MANUAL_CHECK_REQUIRED | evidence:ev-founding-baseline:issuer | Evidence is first-party. This may be valid, but it is not independent evidence. |
| PASS | evidence:ev-founding-baseline:reproducibility | Evidence reproducibility is reproducible. |
| PASS | evidence:ev-founding-baseline:method_refs | Evidence links to a low-cost recheck method. |
| PASS | evidence:ev-github-history-snapshot:location | Evidence has at least one external/public location. |
| MANUAL_CHECK_REQUIRED | evidence:ev-github-history-snapshot:issuer | Evidence is first-party. This may be valid, but it is not independent evidence. |
| PASS | evidence:ev-github-history-snapshot:reproducibility | Evidence reproducibility is reproducible. |
| PASS | evidence:ev-github-history-snapshot:method_refs | Evidence links to a low-cost recheck method. |
| PASS | evidence:ev-github-checksums:location | Evidence has at least one external/public location. |
| MANUAL_CHECK_REQUIRED | evidence:ev-github-checksums:issuer | Evidence is first-party. This may be valid, but it is not independent evidence. |
| PASS | evidence:ev-github-checksums:reproducibility | Evidence reproducibility is reproducible. |
| PASS | evidence:ev-github-checksums:method_refs | Evidence links to a low-cost recheck method. |
| PASS | claim:cxt-parent-purpose:evidence | Claim references existing evidence. |
| PASS | claim:cxt-parent-purpose:limitations | Claim includes limitations. |
| PASS | claim:cxt-parent-purpose:scope | Claim includes explicit scope. |
| PASS | claim:cxt-parent-purpose:subject_coverage | All resolved evidence subject bindings match public_framework:civitasx-parent-framework. |
| PASS | claim:cxt-official-endpoints:evidence | Claim references existing evidence. |
| PASS | claim:cxt-official-endpoints:limitations | Claim includes limitations. |
| PASS | claim:cxt-official-endpoints:scope | Claim includes explicit scope. |
| PASS | claim:cxt-official-endpoints:subject_coverage | All resolved evidence subject bindings match public_framework:civitasx-parent-framework. |
| PASS | claim:cxt-starting-directions:evidence | Claim references existing evidence. |
| PASS | claim:cxt-starting-directions:limitations | Claim includes limitations. |
| PASS | claim:cxt-starting-directions:scope | Claim includes explicit scope. |
| PASS | claim:cxt-starting-directions:subject_coverage | All resolved evidence subject bindings match public_framework:civitasx-parent-framework. |
| PASS | claim:cxt-public-boundaries:evidence | Claim references existing evidence. |
| PASS | claim:cxt-public-boundaries:limitations | Claim includes limitations. |
| PASS | claim:cxt-public-boundaries:scope | Claim includes explicit scope. |
| PASS | claim:cxt-public-boundaries:subject_coverage | All resolved evidence subject bindings match public_framework:civitasx-parent-framework. |
| PASS | claim:cxt-temporary-founder-authority:evidence | Claim references existing evidence. |
| PASS | claim:cxt-temporary-founder-authority:limitations | Claim includes limitations. |
| PASS | claim:cxt-temporary-founder-authority:scope | Claim includes explicit scope. |
| PASS | claim:cxt-temporary-founder-authority:subject_coverage | All resolved evidence subject bindings match public_framework:civitasx-parent-framework. |
| PASS | claim:cxt-first-snapshot:evidence | Claim references existing evidence. |
| PASS | claim:cxt-first-snapshot:limitations | Claim includes limitations. |
| PASS | claim:cxt-first-snapshot:scope | Claim includes explicit scope. |
| PASS | claim:cxt-first-snapshot:subject_coverage | All resolved evidence subject bindings match public_framework:civitasx-parent-framework. |
| PASS | claim:cxt-public-text-license:evidence | Claim references existing evidence. |
| PASS | claim:cxt-public-text-license:limitations | Claim includes limitations. |
| PASS | claim:cxt-public-text-license:scope | Claim includes explicit scope. |
| PASS | claim:cxt-public-text-license:subject_coverage | All resolved evidence subject bindings match public_framework:civitasx-parent-framework. |
| PASS | claim:cxt-founding-continuity-baseline:evidence | Claim references existing evidence. |
| PASS | claim:cxt-founding-continuity-baseline:limitations | Claim includes limitations. |
| PASS | claim:cxt-founding-continuity-baseline:scope | Claim includes explicit scope. |
| PASS | claim:cxt-founding-continuity-baseline:subject_coverage | All resolved evidence subject bindings match public_framework:civitasx-parent-framework. |
| PASS | claim:cxt-github-snapshot-mirror:evidence | Claim references existing evidence. |
| PASS | claim:cxt-github-snapshot-mirror:limitations | Claim includes limitations. |
| PASS | claim:cxt-github-snapshot-mirror:scope | Claim includes explicit scope. |
| PASS | claim:cxt-github-snapshot-mirror:subject_coverage | All resolved evidence subject bindings match public_framework:civitasx-parent-framework. |

## Claims

| Status | Claim | Legacy level | Protocol support | Policy route | Profile | Subject coverage | Risk gaps | Resolved evidence | Missing evidence |
| --- | --- | --- | --- | --- | --- | --- | ---: | ---: | ---: |
| PASS | cxt-parent-purpose | REPRODUCIBLE | L3_REPRODUCIBLE_METHOD | EXTERNAL_POLICY_REVIEW | not_declared | PASS | 1 | 2 | 0 |
| PASS | cxt-official-endpoints | REPRODUCIBLE | L3_REPRODUCIBLE_METHOD | EXTERNAL_POLICY_REVIEW | not_declared | PASS | 1 | 1 | 0 |
| PASS | cxt-starting-directions | REPRODUCIBLE | L3_REPRODUCIBLE_METHOD | EXTERNAL_POLICY_REVIEW | not_declared | PASS | 1 | 3 | 0 |
| PASS | cxt-public-boundaries | REPRODUCIBLE | L3_REPRODUCIBLE_METHOD | EXTERNAL_POLICY_REVIEW | not_declared | PASS | 1 | 1 | 0 |
| PASS | cxt-temporary-founder-authority | REPRODUCIBLE | L3_REPRODUCIBLE_METHOD | EXTERNAL_POLICY_REVIEW | not_declared | PASS | 1 | 2 | 0 |
| PASS | cxt-first-snapshot | REPRODUCIBLE | L3_REPRODUCIBLE_METHOD | EXTERNAL_POLICY_REVIEW | not_declared | PASS | 1 | 3 | 0 |
| PASS | cxt-public-text-license | REPRODUCIBLE | L3_REPRODUCIBLE_METHOD | EXTERNAL_POLICY_REVIEW | not_declared | PASS | 1 | 1 | 0 |
| PASS | cxt-founding-continuity-baseline | REPRODUCIBLE | L3_REPRODUCIBLE_METHOD | EXTERNAL_POLICY_REVIEW | not_declared | PASS | 1 | 1 | 0 |
| PASS | cxt-github-snapshot-mirror | REPRODUCIBLE | L3_REPRODUCIBLE_METHOD | EXTERNAL_POLICY_REVIEW | not_declared | PASS | 1 | 2 | 0 |

## Evidence

| Status | Evidence | Subject | Issuer | Reproducibility | External location | S2 state | Effective S2 | S3 state | Effective S3 | S4 state | Effective S4 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MANUAL_CHECK_REQUIRED | ev-public-intro-en | public_framework:civitasx-parent-framework | first_party | reproducible | yes | NOT_S2 | no | NOT_S3 | no | NOT_S4 | no |
| MANUAL_CHECK_REQUIRED | ev-public-faq-en | public_framework:civitasx-parent-framework | first_party | reproducible | yes | NOT_S2 | no | NOT_S3 | no | NOT_S4 | no |
| MANUAL_CHECK_REQUIRED | ev-official-endpoints-statement | public_framework:civitasx-parent-framework | first_party | reproducible | yes | NOT_S2 | no | NOT_S3 | no | NOT_S4 | no |
| MANUAL_CHECK_REQUIRED | ev-history-snapshot-index | public_framework:civitasx-parent-framework | first_party | reproducible | yes | NOT_S2 | no | NOT_S3 | no | NOT_S4 | no |
| MANUAL_CHECK_REQUIRED | ev-public-license | public_framework:civitasx-parent-framework | first_party | reproducible | yes | NOT_S2 | no | NOT_S3 | no | NOT_S4 | no |
| MANUAL_CHECK_REQUIRED | ev-founding-baseline | public_framework:civitasx-parent-framework | first_party | reproducible | yes | NOT_S2 | no | NOT_S3 | no | NOT_S4 | no |
| MANUAL_CHECK_REQUIRED | ev-github-history-snapshot | public_framework:civitasx-parent-framework | first_party | reproducible | yes | NOT_S2 | no | NOT_S3 | no | NOT_S4 | no |
| MANUAL_CHECK_REQUIRED | ev-github-checksums | public_framework:civitasx-parent-framework | first_party | reproducible | yes | NOT_S2 | no | NOT_S3 | no | NOT_S4 | no |
