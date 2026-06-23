# Approval & HITL Gating  `orch.approval`

> category: `orchestration`

Prepare an item for human approval and enforce the review gate.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (31 agents)
- [Proposal & Quote Assistant](../agents/revenue_gtm/proposal-quote-assistant.md)
- [Deal Desk Router](../agents/revenue_gtm/deal-desk-router.md)
- [Vendor Invoice Review](../agents/finance_ops/vendor-invoice-review.md)
- [Expense Policy Enforcer](../agents/finance_ops/expense-policy-enforcer.md)
- [Cap Table Manager](../agents/finance_ops/cap-table-manager.md)
- [Social Media Scheduler](../agents/marketing/social-scheduler.md)
- [NDA Manager](../agents/legal_compliance/nda-manager.md)
- [Access Review Agent](../agents/security_it/access-review-agent.md)
- [IT Provisioning Agent](../agents/security_it/it-provisioning-agent.md)
- [Vendor Intake & Risk](../agents/procurement/vendor-intake-risk.md)
- [Purchase Approval Router](../agents/procurement/purchase-approval-router.md)
- [PTO & Leave Tracker](../agents/people/pto-leave-tracker.md)
- [Warranty & Entitlement Agent](../agents/customer_success/cs-warranty-entitlement.md)
- [Engineering Change Management Agent](../agents/engineering/eng-change-management-review.md)
- [Customer Credit Management Agent](../agents/finance_ops/fin-customer-credit.md)
- [Debt & Investment Management Agent](../agents/finance_ops/fin-debt-investment.md)
- [Financial Systems Administration Agent](../agents/finance_ops/fin-financial-systems.md)
- [Internal Controls Agent](../agents/finance_ops/fin-internal-controls.md)
- [Benefits Administration Agent](../agents/people/hr-benefits-administration.md)
- [HR Compliance & Reporting Agent](../agents/people/hr-compliance-reporting.md)
- [Employee Records Management Agent](../agents/people/hr-employee-records.md)
- [Employee Relations & Labor Agent](../agents/people/hr-employee-relations.md)
- [Immigration & Relocation Agent](../agents/people/hr-immigration-relocation.md)
- [Time & Attendance Agent](../agents/people/hr-time-attendance.md)
- [Authentication & MFA Agent](../agents/security_it/it-authentication-mfa.md)
- [Problem & Change Control Agent](../agents/security_it/it-problem-change-control.md)
- [Security Operations & Incident Response Agent](../agents/security_it/it-security-operations.md)
- [Remediation & Corrective Action Agent](../agents/legal_compliance/legal-remediation-action.md)
- [IT Asset & Device Lifecycle Agent](../agents/procurement/proc-asset-lifecycle.md)
- [Contract & Renewal Admin Agent](../agents/revenue_gtm/rev-contract-renewal-admin.md)
- [Sales Compensation Agent](../agents/revenue_gtm/rev-sales-compensation.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

