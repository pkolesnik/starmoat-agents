# Structured Field Extraction  `extract.fields`

> category: `extraction`

Pull structured fields from unstructured text or documents into a typed object.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (31 agents)
- [Demo Follow-Up Agent](../agents/revenue_gtm/demo-followup.md)
- [Proposal & Quote Assistant](../agents/revenue_gtm/proposal-quote-assistant.md)
- [Vendor Invoice Review](../agents/finance_ops/vendor-invoice-review.md)
- [Expense Policy Enforcer](../agents/finance_ops/expense-policy-enforcer.md)
- [Cap Table Manager](../agents/finance_ops/cap-table-manager.md)
- [Technical Debt Tracker](../agents/engineering/technical-debt-tracker.md)
- [Resume Screener](../agents/people/resume-screener.md)
- [Performance Review Synthesizer](../agents/people/performance-review-synthesizer.md)
- [Privacy & DPA Tracker](../agents/legal_compliance/privacy-dpa-tracker.md)
- [Compliance Evidence Collector](../agents/legal_compliance/compliance-evidence-collector.md)
- [Contract Renewal Tracker](../agents/procurement/contract-renewal-tracker.md)
- [Sales Call Summarizer](../agents/revenue_gtm/sales-call-summarizer.md)
- [Meeting Scheduler](../agents/revenue_gtm/meeting-scheduler.md)
- [API Docs Generator](../agents/engineering/api-docs-generator.md)
- [AP & Bill Pay Agent](../agents/finance_ops/ap-bill-pay.md)
- [Interview Scheduler](../agents/people/interview-scheduler.md)
- [PTO & Leave Tracker](../agents/people/pto-leave-tracker.md)
- [IP & Trademark Tracker](../agents/legal_compliance/ip-trademark-tracker.md)
- [Warranty & Entitlement Agent](../agents/customer_success/cs-warranty-entitlement.md)
- [Product Requirements Agent](../agents/engineering/eng-product-requirements-spec.md)
- [Fixed-Asset & Capex Accounting Agent](../agents/finance_ops/fin-asset-capex-accounting.md)
- [Customer Invoicing & Billing Agent](../agents/finance_ops/fin-customer-invoicing.md)
- [Tax Management Agent](../agents/finance_ops/fin-tax-management.md)
- [Benefits Administration Agent](../agents/people/hr-benefits-administration.md)
- [Employee Records Management Agent](../agents/people/hr-employee-records.md)
- [Time & Attendance Agent](../agents/people/hr-time-attendance.md)
- [IT Asset & Device Lifecycle Agent](../agents/procurement/proc-asset-lifecycle.md)
- [Supplier Contract Negotiation Agent](../agents/procurement/proc-contract-negotiation.md)
- [Supplier Quote Comparison Agent](../agents/procurement/proc-quote-comparison.md)
- [Contract & Renewal Admin Agent](../agents/revenue_gtm/rev-contract-renewal-admin.md)
- [Order Management Agent](../agents/revenue_gtm/rev-order-management.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

