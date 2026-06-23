# Invoice & 3-Way Match Reconciliation  `proc.invoice_three_way_match`

> function: `procurement` · value stage: Business Operations · **essential** · stage: series_a · default execution: `hybrid`

**Why you need this:** Match invoices to purchase orders and receipts before payment is released.

**What good looks like:** Invoices are paid only after a clean three-way match, with exceptions routed for review.

## KPIs
- % invoices auto-matched
- invoice exception rate

## Powered by (candidate agents)
- `vendor-invoice-review`

## Recommended tools
stripe, google, slack

## Handoffs (the canonical company flow)
- (terminal)

