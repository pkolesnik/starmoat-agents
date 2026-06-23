# Knowledge-Base Retrieval  `search.kb`

> category: `search`

Find and ground answers in internal docs, memory, and knowledge.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (9 agents)
- [Email Newsletter Drafter](../agents/marketing/newsletter-drafter.md)
- [Privacy & DPA Tracker](../agents/legal_compliance/privacy-dpa-tracker.md)
- [Policy Document Generator](../agents/legal_compliance/policy-document-generator.md)
- [Compliance Evidence Collector](../agents/legal_compliance/compliance-evidence-collector.md)
- [Security Questionnaire Responder](../agents/security_it/security-questionnaire-responder.md)
- [Vendor Intake & Risk](../agents/procurement/vendor-intake-risk.md)
- [Knowledge Base Maintainer](../agents/customer_success/knowledge-base-maintainer.md)
- [Enterprise Knowledge Management Agent](../agents/executive/exec-knowledge-management.md)
- [Sales Enablement & Onboarding Agent](../agents/revenue_gtm/rev-sales-enablement-training.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

