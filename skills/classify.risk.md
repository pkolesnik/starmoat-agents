# Risk & Compliance Flagging  `classify.risk`

> category: `classification`

Flag policy, security, privacy, or compliance issues for review.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (48 agents)
- [CRM Hygiene Agent](../agents/revenue_gtm/crm-hygiene.md)
- [Deal Desk Router](../agents/revenue_gtm/deal-desk-router.md)
- [Pipeline Forecast Agent](../agents/revenue_gtm/pipeline-forecast.md)
- [Health Score Monitor](../agents/customer_success/health-score-monitor.md)
- [Customer Onboarding Tracker](../agents/customer_success/onboarding-milestone-tracker.md)
- [Renewal Risk Alert](../agents/customer_success/renewal-risk-alert.md)
- [Revenue Reconciliation Agent](../agents/finance_ops/revenue-reconciliation.md)
- [Payroll Anomaly Detector](../agents/finance_ops/payroll-anomaly-detector.md)
- [Expense Policy Enforcer](../agents/finance_ops/expense-policy-enforcer.md)
- [Code Review Summary](../agents/engineering/code-review-summary.md)
- [Deployment Monitor](../agents/engineering/deployment-monitor.md)
- [OKR Progress Tracker](../agents/executive/okr-tracker.md)
- [Strategic Risk Scanner](../agents/executive/strategic-risk-scanner.md)
- [Contract Review Assistant](../agents/legal_compliance/contract-review-assistant.md)
- [Privacy & DPA Tracker](../agents/legal_compliance/privacy-dpa-tracker.md)
- [Regulatory Change Monitor](../agents/legal_compliance/regulatory-change-monitor.md)
- [Access Review Agent](../agents/security_it/access-review-agent.md)
- [Vulnerability Triage Agent](../agents/security_it/vulnerability-triage-agent.md)
- [Security Questionnaire Responder](../agents/security_it/security-questionnaire-responder.md)
- [IT Provisioning Agent](../agents/security_it/it-provisioning-agent.md)
- [Phishing Report Triage](../agents/security_it/phishing-report-triage.md)
- [Vendor Intake & Risk](../agents/procurement/vendor-intake-risk.md)
- [AR & Collections Agent](../agents/finance_ops/ar-collections.md)
- [IP & Trademark Tracker](../agents/legal_compliance/ip-trademark-tracker.md)
- [Backup & DR Monitor](../agents/security_it/backup-dr-monitor.md)
- [Device Compliance Monitor](../agents/security_it/device-compliance-monitor.md)
- [Supplier Performance Tracker](../agents/procurement/supplier-performance.md)
- [Warranty & Entitlement Agent](../agents/customer_success/cs-warranty-entitlement.md)
- [Engineering Change Management Agent](../agents/engineering/eng-change-management-review.md)
- [Security Requirements (SDLC) Agent](../agents/engineering/eng-security-requirements-sdlc.md)
- [M&A & Corporate Development Agent](../agents/executive/exec-ma-corp-dev.md)
- [Customer Credit Management Agent](../agents/finance_ops/fin-customer-credit.md)
- [Debt & Investment Management Agent](../agents/finance_ops/fin-debt-investment.md)
- [Financial Systems Administration Agent](../agents/finance_ops/fin-financial-systems.md)
- [Internal Controls Agent](../agents/finance_ops/fin-internal-controls.md)
- [Succession Planning Agent](../agents/people/hr-succession-planning.md)
- [Time & Attendance Agent](../agents/people/hr-time-attendance.md)
- [Authentication & MFA Agent](../agents/security_it/it-authentication-mfa.md)
- [Infrastructure Configuration Agent](../agents/security_it/it-config-management.md)
- [Problem & Change Control Agent](../agents/security_it/it-problem-change-control.md)
- [IT Vendor Management Agent](../agents/security_it/it-vendor-management.md)
- [Business Continuity Agent](../agents/legal_compliance/legal-business-continuity.md)
- [Enterprise Risk Agent](../agents/legal_compliance/legal-enterprise-risk.md)
- [Internal Audit Agent](../agents/legal_compliance/legal-internal-audit.md)
- [Litigation & Dispute Agent](../agents/legal_compliance/legal-litigation-management.md)
- [Regulatory Compliance Agent](../agents/legal_compliance/legal-regulatory-compliance.md)
- [Supplier Contract Negotiation Agent](../agents/procurement/proc-contract-negotiation.md)
- [Key Account Management Agent](../agents/revenue_gtm/rev-key-account-management.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

