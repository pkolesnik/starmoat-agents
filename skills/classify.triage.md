# Triage & Routing  `classify.triage`

> category: `classification`

Categorize an item and route it to the right owner, queue, or path.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (20 agents)
- [Deal Desk Router](../agents/revenue_gtm/deal-desk-router.md)
- [Support Ticket Triage](../agents/customer_success/support-ticket-triage.md)
- [Changelog Generator](../agents/engineering/changelog-generator.md)
- [Bug Triage Agent](../agents/engineering/bug-triage.md)
- [Phishing Report Triage](../agents/security_it/phishing-report-triage.md)
- [Purchase Approval Router](../agents/procurement/purchase-approval-router.md)
- [Community Management](../agents/marketing/community-manager.md)
- [Knowledge Base Maintainer](../agents/customer_success/knowledge-base-maintainer.md)
- [Feature Request Analyzer](../agents/engineering/feature-request-analyzer.md)
- [Service Channel Strategy Agent](../agents/customer_success/cs-channel-strategy.md)
- [Service Strategy Agent](../agents/customer_success/cs-service-strategy.md)
- [Financial Systems Administration Agent](../agents/finance_ops/fin-financial-systems.md)
- [Employee Relations & Labor Agent](../agents/people/hr-employee-relations.md)
- [IT Asset Management Agent](../agents/security_it/it-asset-management.md)
- [Security Operations & Incident Response Agent](../agents/security_it/it-security-operations.md)
- [IT Service Desk Agent](../agents/security_it/it-service-desk.md)
- [Brand Management Agent](../agents/marketing/mkt-brand-management.md)
- [IT Asset & Device Lifecycle Agent](../agents/procurement/proc-asset-lifecycle.md)
- [Sourcing & Category Strategy Agent](../agents/procurement/proc-sourcing-strategy.md)
- [Order Management Agent](../agents/revenue_gtm/rev-order-management.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

