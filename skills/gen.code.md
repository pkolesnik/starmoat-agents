# Code & Changelog Generation  `gen.code`

> category: `generation`

Summarize diffs, generate changelogs, draft code or config snippets.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (3 agents)
- [Changelog Generator](../agents/engineering/changelog-generator.md)
- [Code Review Summary](../agents/engineering/code-review-summary.md)
- [API Docs Generator](../agents/engineering/api-docs-generator.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

