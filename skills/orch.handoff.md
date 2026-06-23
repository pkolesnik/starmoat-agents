# Hand-off Coordination  `orch.handoff`

> category: `orchestration`

Pass results and context to the next workflow or owner.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (16 agents)
- [ICP Lead Scorer](../agents/revenue_gtm/icp-lead-scorer.md)
- [Competitive Battlecard Generator](../agents/revenue_gtm/competitive-battlecard.md)
- [Deal Desk Router](../agents/revenue_gtm/deal-desk-router.md)
- [Bug Triage Agent](../agents/engineering/bug-triage.md)
- [Incident Response Coordinator](../agents/engineering/incident-response.md)
- [Employee Onboarding Agent](../agents/people/employee-onboarding.md)
- [Compliance Evidence Collector](../agents/legal_compliance/compliance-evidence-collector.md)
- [Vulnerability Triage Agent](../agents/security_it/vulnerability-triage-agent.md)
- [IT Provisioning Agent](../agents/security_it/it-provisioning-agent.md)
- [Purchase Approval Router](../agents/procurement/purchase-approval-router.md)
- [On-Call & Escalation Scheduler](../agents/engineering/oncall-scheduler.md)
- [Meeting Notes & Action Items](../agents/executive/meeting-notes-actions.md)
- [Device Compliance Monitor](../agents/security_it/device-compliance-monitor.md)
- [IT Service Desk Agent](../agents/security_it/it-service-desk.md)
- [Product Launch & GTM Agent](../agents/marketing/mkt-product-launch.md)
- [Order Management Agent](../agents/revenue_gtm/rev-order-management.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

