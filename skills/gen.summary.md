# Summarization & Synthesis  `gen.summary`

> category: `generation`

Condense and synthesize many inputs into a tight, faithful summary.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (42 agents)
- [Company Researcher](../agents/executive/company-researcher.md)
- [Demo Follow-Up Agent](../agents/revenue_gtm/demo-followup.md)
- [Win/Loss Analysis Agent](../agents/revenue_gtm/win-loss-analysis.md)
- [Partner & Channel Agent](../agents/revenue_gtm/partner-channel.md)
- [CSAT Analysis Agent](../agents/customer_success/csat-analysis.md)
- [Burn Rate Monitor](../agents/finance_ops/burn-rate-monitor.md)
- [Changelog Generator](../agents/engineering/changelog-generator.md)
- [Code Review Summary](../agents/engineering/code-review-summary.md)
- [Technical Debt Tracker](../agents/engineering/technical-debt-tracker.md)
- [Performance Review Synthesizer](../agents/people/performance-review-synthesizer.md)
- [Employee Sentiment Analyzer](../agents/people/employee-sentiment.md)
- [Campaign Performance Summarizer](../agents/marketing/campaign-performance.md)
- [Email Newsletter Drafter](../agents/marketing/newsletter-drafter.md)
- [Board Report Generator](../agents/executive/board-report-generator.md)
- [OKR Progress Tracker](../agents/executive/okr-tracker.md)
- [Competitive Intelligence Monitor](../agents/executive/competitive-intelligence.md)
- [Investor Update Drafter](../agents/executive/investor-update.md)
- [Strategic Risk Scanner](../agents/executive/strategic-risk-scanner.md)
- [Contract Review Assistant](../agents/legal_compliance/contract-review-assistant.md)
- [Regulatory Change Monitor](../agents/legal_compliance/regulatory-change-monitor.md)
- [SaaS Spend Optimizer](../agents/procurement/saas-spend-optimizer.md)
- [Sales Call Summarizer](../agents/revenue_gtm/sales-call-summarizer.md)
- [Voice of Customer Synthesizer](../agents/customer_success/voice-of-customer.md)
- [Feature Request Analyzer](../agents/engineering/feature-request-analyzer.md)
- [Product Analytics Insights](../agents/engineering/product-analytics-insights.md)
- [Meeting Notes & Action Items](../agents/executive/meeting-notes-actions.md)
- [Budget vs Actual Analyzer](../agents/finance_ops/budget-variance-analyzer.md)
- [Supplier Performance Tracker](../agents/procurement/supplier-performance.md)
- [Service Quality Assurance Agent](../agents/customer_success/cs-quality-assurance.md)
- [Service Analytics Agent](../agents/customer_success/cs-service-analytics.md)
- [Product Discovery Research Agent](../agents/engineering/eng-product-discovery-research.md)
- [Strategic Initiative Portfolio Agent](../agents/executive/exec-initiative-portfolio.md)
- [Internal Capability & Health Assessment](../agents/executive/exec-internal-assessment.md)
- [PMO Portfolio & Program Agent](../agents/executive/exec-pmo-portfolio.md)
- [Budgeting & Forecasting Agent](../agents/finance_ops/fin-budgeting-forecasting.md)
- [Tax Management Agent](../agents/finance_ops/fin-tax-management.md)
- [DEI Program Agent](../agents/people/hr-dei-program.md)
- [HRIS & People Analytics Agent](../agents/people/hr-people-analytics.md)
- [Succession Planning Agent](../agents/people/hr-succession-planning.md)
- [Enterprise Risk Agent](../agents/legal_compliance/legal-enterprise-risk.md)
- [Litigation & Dispute Agent](../agents/legal_compliance/legal-litigation-management.md)
- [Customer & Market Research Agent](../agents/marketing/mkt-market-research.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

