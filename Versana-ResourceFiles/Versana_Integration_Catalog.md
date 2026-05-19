# Versana — Integration Catalog

> **Fictional.** Clearly fictional sample content for a Microsoft 365 Copilot workshop. Integration types, partner-system references, pricing tiers, and SLAs are placeholders. Do not use as a real integration or pricing reference.

---

## Integration Types at a Glance

| Type | What it covers | Initial coverage | Future coverage |
|---|---|---|---|
| Type A — Loan Administration | Position, event, status data from loan-administration agent systems | Read-only ingest | Real-time eventing |
| Type B — Settlement / Operations | Position, event, settlement data from settlement and operations agent systems | Read-only ingest | Eventing + write-back |
| Type C — Reference Data | Reference data feeds (security master, counterparty master) | (Roadmap) | (Roadmap) |
| Type D — Regulatory | Compliance and regulatory data feeds | (Roadmap) | (Roadmap) |

This catalog details the two integration types available in the current release: Type A and Type B.

---

## Type A — Loan Administration Integrations (Detailed)

### What we ingest

- Position records (open balances, principal, interest accruals)
- Event records (rate resets, paydowns, draws, fundings)
- Status records (current loan state, lifecycle stage)
- Borrower-level summary fields where authorized

### How it works

1. Versana establishes the partner-system connection during onboarding
2. Customer authorizes the connection with their partner credentials
3. Versana polls the partner API on the configured cadence (15-minute baseline)
4. Versana writes the partner-side data to the customer's reconciliation staging area
5. Reconciliation engine compares partner-side data against the customer's platform-side records
6. Discrepancies surface in the unified workflow

### Pricing tiers (fictional)

| Tier | Annual Volume | Annual Cost (USD) | Polling Cadence | SLA |
|---|---|---|---|---|
| Starter | < 100,000 transactions | $60,000 | 15-min standard | Standard support |
| Growth | 100,000 – 500,000 | $180,000 | 15-min or 5-min | Dedicated CS contact |
| Enterprise | 500,000+ | Custom | 5-min or event-driven | Dedicated CS + ops support |

### Key differentiators

- 15-minute polling cadence (industry baseline: hourly)
- Supports the top 5 Type A partner systems out of the box
- Per-partner backoff and rate-limit handling
- Discrepancy resolution workflow integrated with the reconciliation engine

### Common customer questions

- *"Can we change polling cadence per partner?"* — Configurable for Growth tier and above
- *"What happens during a partner outage?"* — Graceful degradation; existing data remains queryable; reconciliation flags stale entries
- *"Can we backfill historical data?"* — Yes, up to 90 days from go-live for standard tier

---

## Type B — Settlement / Operations Integrations (Detailed)

### What we ingest

- Position records (settled positions, pending settlements)
- Event records (trades, allocations, confirmations)
- Settlement records (settlement-date data, cash projections)
- Cross-side discrepancy flags where partner exposes them

### How it works

The flow mirrors Type A but with these differences:

1. Type B partner APIs are typically less mature; Versana adds a longer engineering ramp during onboarding
2. Rate limits and intermittent timeouts are more common on Type B; per-partner backoff is more aggressive
3. Cross-side discrepancies (where partner-side and platform-side disagree on a settlement) are tagged with a partner-side issue flag and routed via the dedicated escalation flow

### Pricing tiers (fictional)

| Tier | Annual Volume | Annual Cost (USD) | Polling Cadence | SLA |
|---|---|---|---|---|
| Starter | < 50,000 transactions | $75,000 | 15-min standard | Standard support |
| Growth | 50,000 – 250,000 | $220,000 | 15-min only (cadence locked) | Dedicated CS contact |
| Enterprise | 250,000+ | Custom | Future: event-driven | Dedicated CS + ops support |

### Key differentiators

- Cross-side escalation workflow (where partner supports public ticket APIs)
- Settlement-date forecasting via the reconciled cash projection
- Higher-touch onboarding to handle Type B partner API immaturity
- Compliance-grade audit trail on every settlement-side discrepancy

### Common customer questions

- *"When does Type B go GA?"* — Following the Type A first-release pattern; Type B is the second release of the Partner Integration Layer
- *"Can polling be sub-5-minute?"* — Not in the first release; documented as a future-roadmap item pending partner-API behavior in production
- *"What about partner systems we don't see in your supported list?"* — Available via the design-partner program

---

## Bundling Benefits

Customers who adopt both Type A and Type B during onboarding receive:

- **15% bundled-tier discount** on Growth and Enterprise tiers
- **Shared dedicated CS contact** across both integration types
- **Joint onboarding sprint** — single integration-design workshop covering both types
- **Cross-type reporting** — single reconciliation report instead of two separate dashboards

## Integration Roadmap (Illustrative)

| Milestone | Target |
|---|---|
| Type A general availability | Now |
| Type B pilot launch (first 5 customers) | Quarter +1 |
| Type B general availability | Quarter +2 |
| Type C (reference data) pilot | Quarter +3 |
| Real-time eventing (Type A) | Quarter +4 |

---

## Onboarding Process

All integration onboardings follow a consistent process:

1. **Discovery workshop** (1 day) — Versana solutions team works with the customer to map integration scope, identify partner-side prerequisites, and confirm credentials
2. **Integration setup** (2–3 weeks) — Versana enables the connection; customer enables credentials; both sides validate connectivity
3. **Pilot run** (4 weeks) — Single business unit runs in parallel; reconciliation runs in observe-only mode
4. **Cutover** (2 weeks) — Customer fully migrates operational workflow to Versana
5. **Optimization review** (Quarter +1) — Versana CS reviews the customer's usage and recommends cadence and threshold adjustments

## Frequently Used Terms

- **Polling cadence:** How often Versana queries the partner API for new data. Standard is 15 minutes
- **Discrepancy severity tiers:** High / Medium / Low based on configured thresholds (defined per customer)
- **Cross-side discrepancy:** A discrepancy where the partner-side and platform-side records disagree; resolution typically requires partner involvement
- **Design partner:** A customer participating in the pre-release design of a new integration; receives priority onboarding and pricing in exchange for design feedback

---

*Document version: Workshop sample, May 2026. All content fictional.*
