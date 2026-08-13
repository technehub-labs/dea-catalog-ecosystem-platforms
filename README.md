# dea-catalog-ecosystem-platforms

> DEA catalog for **Ecosystem Platform** — OpenDEAM v0.3.0 (ADR-0003).

## Ecosystem Platform (`EP`)

- **Entity id:** `dea:entity-ecosystem-platform`
- **Allocation:** L1 · L1-ecosystem-platforms
- **Status:** proposed

A standing multi-sided structure the enterprise hosts for repeated exchange among many ecosystem actors (marketplace, partner API program, developer portal).

## Relationships (from the OpenDEAM model)

- **EP → EA** — hosts (aggregation, 1:0..N)
- **EP → API** — exposed via (realization, 1:0..N)

## Allocation contract

This repo's `metamodel-pointer.yaml` is validated in CI against the pinned
OpenDEAM root model (`v0.3.0`) via the reusable
`validate-against-model.yml` workflow. Drift fails CI.

Content (entity instances) lands when the entity promotes from
`proposed` to `planned`/`scaffold` per the model lifecycle.

## License

Apache 2.0 — see [LICENSE](./LICENSE) and [NOTICE](./NOTICE).
