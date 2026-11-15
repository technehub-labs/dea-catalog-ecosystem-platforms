# Change Requests: dea-catalog-ecosystem-platforms

This index tracks every change request that lands on this repository.

| CR | Title | Status | Notes |
|----|-------|--------|-------|
| [CR-EP-CAT-04](CR-EP-CAT-04-catalogue-foundation.md) | Catalogue foundation (kit bring-up) | Landed (this PR) | Standard kit: pointer, dependencies, schema projection, gates 1-6, workflows, FOUNDATIONS, record standard. No records admitted. |
| CR-EP-CAT-02 | Initial population | Planned | Evidence-gated seed population per FOUNDATIONS §7. |

## Numbering

Series tag `CR-EP-CAT-NN`, sequential. Cross-repo CRs that touch this
repository are recorded here with their home-repo identifier.
| [CR-EP-CAT-02](CR-EP-CAT-02-cr-ep-cat-02.md) | Entity Ingestion Groundwork (candidate intake queue + gates) | **Proposed (this PR)** | Gated intake: queue + blocking queue gate + admission tool (candidate-state subtrees, content-derived ids); pin v2.6.0→v2.8.0 + shard-aware toolchain re-vendor. No records. |
| [CR-EP-CAT-02](CR-EP-CAT-02-cr-ep-cat-02.md) | Entity Ingestion Groundwork (candidate intake queue + gates) | **Proposed (this PR)** | Gated intake: queue + blocking queue gate + admission tool (candidate-state subtrees, content-derived ids); pin v2.6.0→v2.8.0 + shard-aware toolchain re-vendor. No records. |
| [CR-EP-CAT-03](CR-EP-CAT-03-cr-ep-cat-03.md) | EcosystemPlatform Candidate Corpus | **Landed (this PR)** | 103 queue submissions from 1 bank(s); manifest with sha256s; queue gate CONFORMANT; no entities change. |
| [CR-EP-CAT-04](CR-EP-CAT-04-cr-ep-cat-01.md) | EcosystemPlatform Candidate Admission Batch 02 (1Password Integrations … Zoom Partner Program) | **Landed (this PR)** | Admitted 103 `EcosystemPlatform` CANDIDATE records via the gated intake workflow (queue gate → admission tool → catalog gates); candidates +103, canonical unchanged; records at `lifecycle_status: proposed` in `candidates/` subtrees. |
| [CR-EP-CAT-05](CR-EP-CAT-05-cr-ep-cat-05.md) | CR Numbering Correction | **Landed (this PR)** | Colliding batch CR numbers renumbered (mapping in the CR); content unchanged. |
| [CR-EP-CAT-06](CR-EP-CAT-06-cr-ep-cat-06.md) | Canonical Admission Wave (103) | **Landed (this PR)** | 103 records promoted candidates/ -> canonical root; ladder completed; evidence preserved; canonical 103, candidates 0. |
