# Prioritization & Scoring  `classify.priority`

> category: `classification`

Rank or score items against criteria (severity, ICP fit, value, risk).

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (19 agents)
- [ICP Lead Scorer](../agents/revenue_gtm/icp-lead-scorer.md)
- [Support Ticket Triage](../agents/customer_success/support-ticket-triage.md)
- [Expansion Signal Detector](../agents/customer_success/expansion-signal-detector.md)
- [Sprint Planning Assistant](../agents/engineering/sprint-planning-assistant.md)
- [Bug Triage Agent](../agents/engineering/bug-triage.md)
- [Incident Response Coordinator](../agents/engineering/incident-response.md)
- [Technical Debt Tracker](../agents/engineering/technical-debt-tracker.md)
- [Resume Screener](../agents/people/resume-screener.md)
- [Brand Mention Monitor](../agents/marketing/brand-mention-monitor.md)
- [Vulnerability Triage Agent](../agents/security_it/vulnerability-triage-agent.md)
- [Feature Request Analyzer](../agents/engineering/feature-request-analyzer.md)
- [Product Portfolio Governance Agent](../agents/engineering/eng-portfolio-governance.md)
- [Roadmap and Launch Planner Agent](../agents/engineering/eng-roadmap-launch-planner.md)
- [Strategic Initiative Portfolio Agent](../agents/executive/exec-initiative-portfolio.md)
- [PMO Portfolio & Program Agent](../agents/executive/exec-pmo-portfolio.md)
- [Process Excellence Agent](../agents/executive/exec-process-excellence.md)
- [Stakeholder & Public Affairs Agent](../agents/executive/exec-stakeholder-public-affairs.md)
- [IT Service Desk Agent](../agents/security_it/it-service-desk.md)
- [Segmentation & ICP Agent](../agents/marketing/mkt-segmentation-icp.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

