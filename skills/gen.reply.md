# Reply & Response Drafting  `gen.reply`

> category: `generation`

Draft a grounded reply to a ticket, question, or message.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (11 agents)
- [Customer Onboarding Tracker](../agents/customer_success/onboarding-milestone-tracker.md)
- [Support Ticket Triage](../agents/customer_success/support-ticket-triage.md)
- [Event & Webinar Coordinator](../agents/marketing/event-coordinator.md)
- [App Store Monitor](../agents/customer_success/app-store-monitor.md)
- [Phishing Report Triage](../agents/security_it/phishing-report-triage.md)
- [Meeting Scheduler](../agents/revenue_gtm/meeting-scheduler.md)
- [Community Management](../agents/marketing/community-manager.md)
- [AR & Collections Agent](../agents/finance_ops/ar-collections.md)
- [Interview Scheduler](../agents/people/interview-scheduler.md)
- [Security Awareness Trainer](../agents/security_it/security-awareness-trainer.md)
- [IT Service Desk Agent](../agents/security_it/it-service-desk.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

