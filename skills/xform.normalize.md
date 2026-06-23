# Data Normalization & Hygiene  `xform.normalize`

> category: `transformation`

Clean, dedupe, and normalize records to a consistent shape.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (4 agents)
- [CRM Hygiene Agent](../agents/revenue_gtm/crm-hygiene.md)
- [Employee Records Management Agent](../agents/people/hr-employee-records.md)
- [Attribution Modeling Agent](../agents/marketing/mkt-attribution-modeling.md)
- [Supplier Quote Comparison Agent](../agents/procurement/proc-quote-comparison.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

