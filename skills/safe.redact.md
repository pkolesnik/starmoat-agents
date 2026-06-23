# PII Redaction & Guardrails  `safe.redact`

> category: `other`

Detect and redact sensitive data; enforce output guardrails.

## How it is applied

This is a reusable capability composed by the agents listed below. Its concrete
prompt is specialized inside each agent's bespoke runner (the agent tailors the skill
to its workflow), so it is documented here by capability rather than a single prompt.

## Used by (5 agents)
- [Job Description Generator](../agents/people/job-description-generator.md)
- [Access Review Agent](../agents/security_it/access-review-agent.md)
- [Security Requirements (SDLC) Agent](../agents/engineering/eng-security-requirements-sdlc.md)
- [Employee Records Management Agent](../agents/people/hr-employee-records.md)
- [Authentication & MFA Agent](../agents/security_it/it-authentication-mfa.md)

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

