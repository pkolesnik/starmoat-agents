# Anomaly Detection  `reason.anomaly`

> category: `reasoning`

Spot outliers, regressions, and out-of-policy events in data or activity.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (26 agents)
- [Health Score Monitor](../agents/customer_success/health-score-monitor.md)
- [Expansion Signal Detector](../agents/customer_success/expansion-signal-detector.md)
- [Revenue Reconciliation Agent](../agents/finance_ops/revenue-reconciliation.md)
- [Vendor Invoice Review](../agents/finance_ops/vendor-invoice-review.md)
- [Payroll Anomaly Detector](../agents/finance_ops/payroll-anomaly-detector.md)
- [Deployment Monitor](../agents/engineering/deployment-monitor.md)
- [Employee Sentiment Analyzer](../agents/people/employee-sentiment.md)
- [App Store Monitor](../agents/customer_success/app-store-monitor.md)
- [API Cost Tracker](../agents/finance_ops/api-cost-tracker.md)
- [Strategic Risk Scanner](../agents/executive/strategic-risk-scanner.md)
- [Regulatory Change Monitor](../agents/legal_compliance/regulatory-change-monitor.md)
- [Access Review Agent](../agents/security_it/access-review-agent.md)
- [SaaS & License Monitor](../agents/security_it/saas-license-monitor.md)
- [Phishing Report Triage](../agents/security_it/phishing-report-triage.md)
- [SaaS Spend Optimizer](../agents/procurement/saas-spend-optimizer.md)
- [Ad Campaign Optimizer](../agents/marketing/ad-campaign-optimizer.md)
- [Test Coverage Monitor](../agents/engineering/test-coverage-monitor.md)
- [Performance Regression Detector](../agents/engineering/performance-regression-detector.md)
- [AP & Bill Pay Agent](../agents/finance_ops/ap-bill-pay.md)
- [Backup & DR Monitor](../agents/security_it/backup-dr-monitor.md)
- [Device Compliance Monitor](../agents/security_it/device-compliance-monitor.md)
- [Service Analytics Agent](../agents/customer_success/cs-service-analytics.md)
- [HRIS & People Analytics Agent](../agents/people/hr-people-analytics.md)
- [Cloud & Infrastructure Operations Agent](../agents/security_it/it-cloud-infra-operations.md)
- [Infrastructure Configuration Agent](../agents/security_it/it-config-management.md)
- [Network Management Agent](../agents/security_it/it-network-management.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

