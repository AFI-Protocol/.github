# AFI Protocol – Repository Map

This org is structured around how AFI actually works in the wild: the Machine, the Mint, the Ops, and the Lore.

---

## 1. Runtime & DX (the Machine)

Core execution, DAG reactor, plugins, and developer experience.

- **afi-core** – Validators + mentors, production signal logic.
- **afi-reactor** – Signal DAG / orchestrator, Codex integration, replay.
- **afi-sdk-ts** / **afi-sdk-python** – TypeScript & Python SDKs for AFI reactors and nodes.
- **afi-starters** – Minimal starter templates for agents, validators, and reactors.

---

## 2. Protocol & On-chain (the Mint)

Canonical rules and token / minting logic – where validated intelligence gets turned into AFI.

- **afi-protocol** – Formal protocol spec, ADRs, versioned definitions.
- **afi-governance** – Governance logic, proposal schema, DAO + Epoch Pulse policy.
- **afi-mint** – Agentic minting logic, thresholds, challenge windows, validation flows.
- **afi-token** – Canonical token contract logic for AFI (Epoch Pulse, rewards, wiring).

---

## 3. Benchmarks (the Scoreboard)

Evaluation and reproducible metrics.

- **afi-benchkit** – Benchmarks, simulations, and PoI/PoInsight eval harness for AFI.

---

## 4. Ops, Infra & Factory (the Nerves)

Deployment, infra, and droid/augment workflows.

- **afi-infra** – Base infra, vault utilities, images.
- **afi-ops** – Deploy & health scripts, runbooks, operational SOPs.
- **afi-factory** – Agent templates, droid manifests, Codex/bootstrap tasks.

---

## 5. Docs, Site & Artifacts (the Lore)

What humans (and some agents) read.

- **afi-docs** – Developer and operator docs for AFI.
- **afi-artifacts** – Versioned artifacts for AFI papers (schemas, codex, samples, replay).
- **afi-research-site** – Public research / institute site for AFI.

---

## 6. Brand, Config & Labs (the Style & Sandbox)

Configuration, branding, and experiments.

- **afi-config** – Codex schema, persona files, validator/mentor registries.
- **afi-labs** – Private research and prototyping modules for AFI Protocol.
- **.github** – Org-wide workflows, issue templates, policies, and this map.

---

### Archived (Historical Only)

The following repos are archived and kept for historical context:

- **afi-agents** – Early CLI entry-points and manifests.
- **afi-construct** – Early simulation dojo before the multi-repo layout.

AFI is live in the repos above; everything else is fossils.
