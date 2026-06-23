# Field Mapping & Bridging  `xform.map`

> category: `transformation`

Map one step's output onto the next step's expected input.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (12 agents)
- [Revenue Reconciliation Agent](../agents/finance_ops/revenue-reconciliation.md)
- [Vendor Invoice Review](../agents/finance_ops/vendor-invoice-review.md)
- [IT Provisioning Agent](../agents/security_it/it-provisioning-agent.md)
- [Sales Call Summarizer](../agents/revenue_gtm/sales-call-summarizer.md)
- [AP & Bill Pay Agent](../agents/finance_ops/ap-bill-pay.md)
- [Capacity and Skills Forecaster Agent](../agents/engineering/eng-capacity-forecaster.md)
- [Business Model Architect](../agents/executive/exec-business-model-architect.md)
- [Enterprise Knowledge Management Agent](../agents/executive/exec-knowledge-management.md)
- [Process Excellence Agent](../agents/executive/exec-process-excellence.md)
- [Cost & Profitability Analytics Agent](../agents/finance_ops/fin-profitability-analytics.md)
- [HR Compliance & Reporting Agent](../agents/people/hr-compliance-reporting.md)
- [Regulatory Compliance Agent](../agents/legal_compliance/legal-regulatory-compliance.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

