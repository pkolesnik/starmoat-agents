# Root-Cause Analysis  `reason.rootcause`

> category: `reasoning`

Diagnose why something happened and propose corrective actions.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (15 agents)
- [Win/Loss Analysis Agent](../agents/revenue_gtm/win-loss-analysis.md)
- [Bug Triage Agent](../agents/engineering/bug-triage.md)
- [Incident Response Coordinator](../agents/engineering/incident-response.md)
- [Vulnerability Triage Agent](../agents/security_it/vulnerability-triage-agent.md)
- [Landing Page & CRO Analyzer](../agents/marketing/landing-page-cro.md)
- [Performance Regression Detector](../agents/engineering/performance-regression-detector.md)
- [Budget vs Actual Analyzer](../agents/finance_ops/budget-variance-analyzer.md)
- [Process Excellence Agent](../agents/executive/exec-process-excellence.md)
- [Internal Controls Agent](../agents/finance_ops/fin-internal-controls.md)
- [Employee Relations & Labor Agent](../agents/people/hr-employee-relations.md)
- [Cloud & Infrastructure Operations Agent](../agents/security_it/it-cloud-infra-operations.md)
- [Problem & Change Control Agent](../agents/security_it/it-problem-change-control.md)
- [Security Operations & Incident Response Agent](../agents/security_it/it-security-operations.md)
- [Internal Audit Agent](../agents/legal_compliance/legal-internal-audit.md)
- [Remediation & Corrective Action Agent](../agents/legal_compliance/legal-remediation-action.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

