# Document Generation  `gen.doc`

> category: `generation`

Produce a structured document (PRD, report, plan, runbook, policy).

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (40 agents)
- [Proposal & Quote Assistant](../agents/revenue_gtm/proposal-quote-assistant.md)
- [QBR Preparation Agent](../agents/customer_success/qbr-prep.md)
- [Board Report Generator](../agents/executive/board-report-generator.md)
- [Policy Document Generator](../agents/legal_compliance/policy-document-generator.md)
- [NDA Manager](../agents/legal_compliance/nda-manager.md)
- [Security Questionnaire Responder](../agents/security_it/security-questionnaire-responder.md)
- [PR & Press Release Drafter](../agents/marketing/pr-press-release.md)
- [Knowledge Base Maintainer](../agents/customer_success/knowledge-base-maintainer.md)
- [API Docs Generator](../agents/engineering/api-docs-generator.md)
- [Market Sizing & TAM Analyst](../agents/executive/market-sizing-analyst.md)
- [Service Strategy Agent](../agents/customer_success/cs-service-strategy.md)
- [Engineering Change Management Agent](../agents/engineering/eng-change-management-review.md)
- [Design Specification Agent](../agents/engineering/eng-design-spec.md)
- [Product Portfolio Governance Agent](../agents/engineering/eng-portfolio-governance.md)
- [Product Requirements Agent](../agents/engineering/eng-product-requirements-spec.md)
- [Roadmap and Launch Planner Agent](../agents/engineering/eng-roadmap-launch-planner.md)
- [Security Requirements (SDLC) Agent](../agents/engineering/eng-security-requirements-sdlc.md)
- [Business Model Architect](../agents/executive/exec-business-model-architect.md)
- [Enterprise Knowledge Management Agent](../agents/executive/exec-knowledge-management.md)
- [M&A & Corporate Development Agent](../agents/executive/exec-ma-corp-dev.md)
- [Strategy Synthesizer](../agents/executive/exec-strategy-synthesizer.md)
- [Customer Invoicing & Billing Agent](../agents/finance_ops/fin-customer-invoicing.md)
- [HR Compliance & Reporting Agent](../agents/people/hr-compliance-reporting.md)
- [Employee Relations & Labor Agent](../agents/people/hr-employee-relations.md)
- [Immigration & Relocation Agent](../agents/people/hr-immigration-relocation.md)
- [Learning & Career Development Agent](../agents/people/hr-learning-career-development.md)
- [Business Continuity Agent](../agents/legal_compliance/legal-business-continuity.md)
- [Internal Audit Agent](../agents/legal_compliance/legal-internal-audit.md)
- [Regulatory Compliance Agent](../agents/legal_compliance/legal-regulatory-compliance.md)
- [Remediation & Corrective Action Agent](../agents/legal_compliance/legal-remediation-action.md)
- [Brand Management Agent](../agents/marketing/mkt-brand-management.md)
- [Partner & Co-Marketing Agent](../agents/marketing/mkt-partner-comarketing.md)
- [Positioning & Messaging Agent](../agents/marketing/mkt-positioning-messaging.md)
- [Product Launch & GTM Agent](../agents/marketing/mkt-product-launch.md)
- [Segmentation & ICP Agent](../agents/marketing/mkt-segmentation-icp.md)
- [Key Account Management Agent](../agents/revenue_gtm/rev-key-account-management.md)
- [Sales Budget Agent](../agents/revenue_gtm/rev-sales-budget.md)
- [Sales Compensation Agent](../agents/revenue_gtm/rev-sales-compensation.md)
- [Sales Enablement & Onboarding Agent](../agents/revenue_gtm/rev-sales-enablement-training.md)
- [Sales Strategy Agent](../agents/revenue_gtm/rev-sales-strategy.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

