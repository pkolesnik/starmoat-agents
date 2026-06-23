# Sentiment & Tone Analysis  `classify.sentiment`

> category: `classification`

Detect sentiment, tone, and escalation risk in customer or employee signal.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (9 agents)
- [Support Ticket Triage](../agents/customer_success/support-ticket-triage.md)
- [CSAT Analysis Agent](../agents/customer_success/csat-analysis.md)
- [Employee Sentiment Analyzer](../agents/people/employee-sentiment.md)
- [Brand Mention Monitor](../agents/marketing/brand-mention-monitor.md)
- [App Store Monitor](../agents/customer_success/app-store-monitor.md)
- [Community Management](../agents/marketing/community-manager.md)
- [Voice of Customer Synthesizer](../agents/customer_success/voice-of-customer.md)
- [Service Quality Assurance Agent](../agents/customer_success/cs-quality-assurance.md)
- [Organizational Change Management Agent](../agents/executive/exec-change-management.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

