# Aiformia Agents

Agent identities, skill manifests, workflow specs, and pipeline configs for
[Aiformia / StarMoat](https://github.com/pkolesnik/starmoat) — an AI Transformation
Operating System. **Generated from the app's source of truth** (do not hand-edit;
run the generator in the app repo: `node --experimental-strip-types gen-agents-repo.mts`).

## Structure

- `agents/{slug}.md` — 96 agent identities (system prompt, capabilities, integrations, governance)
- `skills/{slug}.md` — 5 composable skill manifests (prompt-as-data)
- `workflows/{key}.md` — 48 canonical operating-model workflows (purpose, KPIs, handoffs)
- `pipelines/` — how workflows chain into runnable, scheduled pipelines
- `index.json` — machine-readable catalog

## Counts

- **Agents:** 96 (52 GA, 2 preview, 42 planned)
  - Customer Success: 11
  - Product & Engineering: 13
  - Executive & Strategy: 7
  - Finance: 11
  - Legal & Compliance: 7
  - Marketing: 11
  - People: 9
  - Procurement: 5
  - Revenue & GTM: 13
  - Security & IT: 9
- **Skills:** 5
- **Workflows:** 48 (30 essential)

## Runtime vs. definitions

The **runtime** (Next.js app, agent runners, the orchestrator/executor) lives in the
app repo. **This repo holds the definitions** the app links to by slug. The base URL
is configured in **Admin > Organization > Developer Settings**.
