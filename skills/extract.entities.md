# Entity & Signal Extraction  `extract.entities`

> category: `extraction`

Identify entities, intents, and signals (people, accounts, risks) in content.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (5 agents)
- [Company Researcher](../agents/executive/company-researcher.md)
- [Bug Triage Agent](../agents/engineering/bug-triage.md)
- [Contract Review Assistant](../agents/legal_compliance/contract-review-assistant.md)
- [Meeting Notes & Action Items](../agents/executive/meeting-notes-actions.md)
- [Product Discovery Research Agent](../agents/engineering/eng-product-discovery-research.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

