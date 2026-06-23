# Forecasting & Modeling  `reason.forecast`

> category: `reasoning`

Project metrics forward (pipeline, cash, headcount) with stated assumptions.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (14 agents)
- [Pipeline Forecast Agent](../agents/revenue_gtm/pipeline-forecast.md)
- [Burn Rate Monitor](../agents/finance_ops/burn-rate-monitor.md)
- [Cash Flow Forecaster](../agents/finance_ops/cash-flow-forecaster.md)
- [Cap Table Manager](../agents/finance_ops/cap-table-manager.md)
- [Headcount Planning Agent](../agents/people/headcount-planning.md)
- [API Cost Tracker](../agents/finance_ops/api-cost-tracker.md)
- [Support Workforce Planning Agent](../agents/customer_success/cs-workforce-planning.md)
- [Capacity and Skills Forecaster Agent](../agents/engineering/eng-capacity-forecaster.md)
- [Budgeting & Forecasting Agent](../agents/finance_ops/fin-budgeting-forecasting.md)
- [Debt & Investment Management Agent](../agents/finance_ops/fin-debt-investment.md)
- [Network Management Agent](../agents/security_it/it-network-management.md)
- [Litigation & Dispute Agent](../agents/legal_compliance/legal-litigation-management.md)
- [Workplace & Real Estate Agent](../agents/procurement/proc-workplace-real-estate.md)
- [Sales Budget Agent](../agents/revenue_gtm/rev-sales-budget.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

