# Spend & Expense Management  `fin.spend_management`

> function: `finance_ops` · value stage: Business Operations · **essential** · stage: foundational · default execution: `hybrid`

**Why you need this:** Control cash going out: invoices reviewed, expenses on-policy, no leakage.

**What good looks like:** Invoices and expenses reviewed against policy with exceptions flagged.

## KPIs
- Policy exception rate
- Invoice cycle time

## Powered by (candidate agents)
- `vendor-invoice-review`
- `expense-policy-enforcer`

## Recommended tools
stripe, google

## Handoffs (the canonical company flow)
- → `fin.cash_runway` (data: spend data)
- → `proc.purchase_approvals` (data: approved spend)

