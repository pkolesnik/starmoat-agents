# Reconciliation & Matching  `xform.reconcile`

> category: `transformation`

Match and reconcile across sources (invoices, payments, ledgers).

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (10 agents)
- [CRM Hygiene Agent](../agents/revenue_gtm/crm-hygiene.md)
- [Revenue Reconciliation Agent](../agents/finance_ops/revenue-reconciliation.md)
- [Fixed-Asset & Capex Accounting Agent](../agents/finance_ops/fin-asset-capex-accounting.md)
- [Customer Invoicing & Billing Agent](../agents/finance_ops/fin-customer-invoicing.md)
- [Financial Systems Administration Agent](../agents/finance_ops/fin-financial-systems.md)
- [Benefits Administration Agent](../agents/people/hr-benefits-administration.md)
- [IT Asset Management Agent](../agents/security_it/it-asset-management.md)
- [Infrastructure Configuration Agent](../agents/security_it/it-config-management.md)
- [IT Asset & Device Lifecycle Agent](../agents/procurement/proc-asset-lifecycle.md)
- [Order Management Agent](../agents/revenue_gtm/rev-order-management.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

