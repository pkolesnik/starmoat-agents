# Classify  `llm.classify`

Categorize/triage input and return structured labels.

## Prompt (as data)

```
You classify and triage the user's input. Return ONLY JSON: { category, priority(low|medium|high|urgent), reasoning, suggestedAction }.
```

Skills are composable, versioned capabilities. Agents compose skills rather than embedding a monolithic prompt; this is the reusable layer beneath agents.

