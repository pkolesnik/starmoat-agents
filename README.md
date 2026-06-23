# Aiformia Agents

Agent identities, skill manifests, workflow specs, and pipeline configs for
[Aiformia / StarMoat](https://github.com/pkolesnik/starmoat) — an AI Transformation
Operating System. **Generated from the app's source of truth** (do not hand-edit;
run the generator in the app repo: `node --experimental-strip-types gen-agents-repo.mts`).

## Hierarchy

`skills` (reusable building blocks) → `agents` (compose skills) → `workflows`
(a company applies an agent to a job) → `pipelines` (chain workflows end to end).

## Structure

- `agents/{function}/{slug}.md` — 176 agent identities, **grouped by function**, each listing the skills it composes
- `skills/{slug}.md` — 34 composable skill manifests (prompt-as-data), flat (skills are cross-cutting)
- `workflows/{key}.md` — 204 canonical operating-model workflows (purpose, KPIs, handoffs, powering agents)
- `pipelines/` — how workflows chain into runnable, scheduled pipelines
- `index.json` — machine-readable catalog (agents ↔ skills ↔ functions)

## Counts

- **Agents:** 176 (176 GA, 0 preview, 0 planned), by function:
  - `customer_success` Customer Success: 17
  - `engineering` Product & Engineering: 22
  - `executive` Executive & Strategy: 18
  - `finance_ops` Finance: 20
  - `legal_compliance` Legal & Compliance: 13
  - `marketing` Marketing: 19
  - `people` People: 19
  - `procurement` Procurement: 10
  - `revenue_gtm` Revenue & GTM: 20
  - `security_it` Security & IT: 18
- **Skills:** 34
- **Workflows:** 204 (75 essential)

## Generic library vs. per-organization model

This repo is the **generic library** — the templates available to every org. Each
**organization's customized operating model** (which agents it activated, its
workflows with chosen automation modes, its connections, schedules, runs, and
memory) is **per-tenant data in the app database**, not here. The app composes a
company's model by selecting and tailoring from this library at onboarding.

## Runtime vs. definitions

The **runtime** (Next.js app, agent runners, the orchestrator/executor) lives in the
app repo. **This repo holds the definitions** the app links to by slug. The base URL
is configured in **Admin > Organization > Developer Settings**.
