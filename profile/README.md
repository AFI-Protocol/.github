# AFI Protocol

**Agentic Financial Intelligence (AFI)** — an open protocol for turning trading
signals, produced by human or agentic analysts, into scored, auditable,
replayable evidence.

## Start here

- **[afi-protocol](https://github.com/AFI-Protocol/afi-protocol)** — the
  organization map: authority hierarchy, repository roles, implementation
  status, and entry points for developers, analysts, validators, operators,
  and researchers.
- **[afi-docs](https://github.com/AFI-Protocol/afi-docs)** — the documentation
  hub.

## Protocol authority

Protocol authority lives in exactly three repositories:

1. **[afi-governance](https://github.com/AFI-Protocol/afi-governance)** —
   accepted protocol decisions (protocol law), in
   [`decisions/`](https://github.com/AFI-Protocol/afi-governance/tree/main/decisions).
2. **[afi-config](https://github.com/AFI-Protocol/afi-config)** — canonical
   schemas, registries, conventions, and known-answer tests.
3. **[afi-math](https://github.com/AFI-Protocol/afi-math)** — canonical
   deterministic math kernels and golden vectors.

## Operation

AFI Protocol defines the interoperable rules; **AFI Research Institute is
designated (non-exclusively) to operate AFI's official open reference services**
— a hosted Gateway reference service for structured ingress and an
oracle-ingress / CPJ-normalization reference service for message- and
source-derived signals. Independent parties may run their own conforming
Gateway, collectors, and infrastructure; conformance is defined by the
contracts, not by who operates. Operating a reference service confers no
protocol authority, and **no live deployment is claimed** — the pipeline is
CI-proven, not hosted. See the
[afi-protocol map](https://github.com/AFI-Protocol/afi-protocol) for detail.

## Repositories at a glance

- **Protocol definition (must-conform):**
  [afi-governance](https://github.com/AFI-Protocol/afi-governance) ·
  [afi-config](https://github.com/AFI-Protocol/afi-config) ·
  [afi-math](https://github.com/AFI-Protocol/afi-math)
- **Governed implementation (replaceable via the same contracts):**
  [afi-core](https://github.com/AFI-Protocol/afi-core) ·
  [afi-reactor](https://github.com/AFI-Protocol/afi-reactor) ·
  [afi-infra](https://github.com/AFI-Protocol/afi-infra) ·
  [afi-gateway](https://github.com/AFI-Protocol/afi-gateway) ·
  [afi-mint](https://github.com/AFI-Protocol/afi-mint) ·
  [afi-token](https://github.com/AFI-Protocol/afi-token)
- **Support and reference:**
  [afi-docs](https://github.com/AFI-Protocol/afi-docs) ·
  [afi-factory](https://github.com/AFI-Protocol/afi-factory) ·
  [afi-xerc20](https://github.com/AFI-Protocol/afi-xerc20) ·
  afi-tiny-brains *(private)*
- **Research and records (non-canonical):**
  [afi-econ](https://github.com/AFI-Protocol/afi-econ) ·
  [afi-artifacts](https://github.com/AFI-Protocol/afi-artifacts)
- **Organization surfaces:**
  [afi-protocol](https://github.com/AFI-Protocol/afi-protocol) ·
  [.github](https://github.com/AFI-Protocol/.github)

## Status

The implemented lifecycle currently reaches `SCORED`: signals are ingested,
validated against USS v1.1, scored by the governed UWR engine, and persisted
to the canonical evidence store keyed by `signalId`. Post-`SCORED` finality,
epoch accounting, rewards, settlement, and the external API surface are not
yet implemented or not yet governed. See the
[afi-protocol map](https://github.com/AFI-Protocol/afi-protocol) for the full
picture.
