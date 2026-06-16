# Pipelines

A pipeline is an **end-to-end chain of workflows**, defined by the handoff/trigger
edges between workflows in the operating model (the `dependsOn` edges in
`workflows/*.md`). The runtime executes a chain step by step, mapping each agent's
output to the next step's input.

- **Definition:** emergent from the operating-model DAG (`workflow_connections`),
  seeded from each workflow's `dependsOn`.
- **Execution:** `runOperatingModelChain(startWorkflowId)` in the app runtime.
- **Triggers:** a pipeline can run on a cadence (hourly | daily | weekly); the
  orchestrator cron sweeps due triggers.
- **Orchestrator:** a planner/monitor agent proposes which pipelines to run and how
  often, and summarizes runs. It recommends; humans approve; governance enforces.
- **Self-heal:** a failed step retries once, then escalates to a human and the chain
  continues. Outcomes feed agent graduation/demotion.

Pipelines are runtime constructs, so their executor lives in the app; this folder
documents the model.

