# Scheduling & Cadence  `orch.schedule`

> category: `orchestration`

Decide when work runs and trigger it on the right cadence.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (23 agents)
- [Customer Onboarding Tracker](../agents/customer_success/onboarding-milestone-tracker.md)
- [Renewal Risk Alert](../agents/customer_success/renewal-risk-alert.md)
- [Employee Onboarding Agent](../agents/people/employee-onboarding.md)
- [Social Media Scheduler](../agents/marketing/social-scheduler.md)
- [Event & Webinar Coordinator](../agents/marketing/event-coordinator.md)
- [NDA Manager](../agents/legal_compliance/nda-manager.md)
- [Contract Renewal Tracker](../agents/procurement/contract-renewal-tracker.md)
- [Meeting Scheduler](../agents/revenue_gtm/meeting-scheduler.md)
- [On-Call & Escalation Scheduler](../agents/engineering/oncall-scheduler.md)
- [AR & Collections Agent](../agents/finance_ops/ar-collections.md)
- [AP & Bill Pay Agent](../agents/finance_ops/ap-bill-pay.md)
- [Interview Scheduler](../agents/people/interview-scheduler.md)
- [PTO & Leave Tracker](../agents/people/pto-leave-tracker.md)
- [IP & Trademark Tracker](../agents/legal_compliance/ip-trademark-tracker.md)
- [Security Awareness Trainer](../agents/security_it/security-awareness-trainer.md)
- [Support Workforce Planning Agent](../agents/customer_success/cs-workforce-planning.md)
- [Roadmap and Launch Planner Agent](../agents/engineering/eng-roadmap-launch-planner.md)
- [HR Compliance & Reporting Agent](../agents/people/hr-compliance-reporting.md)
- [Immigration & Relocation Agent](../agents/people/hr-immigration-relocation.md)
- [Partner & Co-Marketing Agent](../agents/marketing/mkt-partner-comarketing.md)
- [Product Launch & GTM Agent](../agents/marketing/mkt-product-launch.md)
- [Workplace & Real Estate Agent](../agents/procurement/proc-workplace-real-estate.md)
- [Contract & Renewal Admin Agent](../agents/revenue_gtm/rev-contract-renewal-admin.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

