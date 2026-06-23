# Record Enrichment  `extract.enrich`

> category: `extraction`

Augment a record with external/firmographic data and missing attributes.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (5 agents)
- [ICP Lead Scorer](../agents/revenue_gtm/icp-lead-scorer.md)
- [Outbound Personalization Engine](../agents/revenue_gtm/outbound-personalization.md)
- [CRM Hygiene Agent](../agents/revenue_gtm/crm-hygiene.md)
- [Vendor Intake & Risk](../agents/procurement/vendor-intake-risk.md)
- [Segmentation & ICP Agent](../agents/marketing/mkt-segmentation-icp.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

