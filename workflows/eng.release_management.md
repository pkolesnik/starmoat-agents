# Release & Deployment  `eng.release_management`

> function: `engineering` · value stage: Delivery & Execution · **essential** · stage: seed · default execution: `ai`

**Why you need this:** Ship safely and often, with changelogs and deployment health tracked.

**What good looks like:** Frequent low-risk deploys with automated changelogs and monitoring.

## KPIs
- Deploy frequency
- Lead time for changes
- Change failure rate

## Powered by (candidate agents)
- `deployment-monitor`
- `changelog-generator`

## Recommended tools
github, slack

## Handoffs (the canonical company flow)
- → `eng.incident_response` (trigger: deploy regression)

