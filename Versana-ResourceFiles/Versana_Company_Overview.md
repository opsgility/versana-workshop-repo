# Versana — Company Overview

> **Fictional.** This document is a clearly fictional sample created for a Microsoft 365 Copilot workshop. None of the metrics, customer references, partner names, or financial figures represent Versana's actual product, customers, partners, or roadmap. Use only as a reference for workshop demos.

---

## About Versana

Versana is a B2B SaaS platform serving the syndicated loan and structured-finance markets. Our platform gives participants — banks, asset managers, fund administrators, and agent-system providers — a single operational source of truth for participant-facing data across the loan lifecycle.

For institutions that previously stitched together partner-system data via CSV exports, manual reconciliation, and re-keyed data, Versana provides an integrated platform that pulls partner positions, reconciles them against platform-side records, and surfaces discrepancies in a unified workflow.

Our mission is simple: let operations teams focus on resolving real exceptions, not on chasing data across systems.

## What Versana Does

Versana provides three integrated capability areas:

### Partner Integration Layer
We connect to partner systems on the customer's behalf, pulling position, event, and settlement data on a defined cadence. Customers stop maintaining their own connectors.

- **Coverage:** Supports loan administration agent systems (Type A) and settlement/operations agent systems (Type B)
- **Cadence:** 15-minute polling baseline; lower-cadence options on supported partner APIs; event-driven for partners with eventing support
- **Reliability:** Per-partner caching and graceful degradation when partner APIs are slow or unavailable
- **Onboarding:** White-glove integration onboarding for the first cohort of customers per partner type

### Reconciliation Engine
We reconcile partner-side positions against platform-side records and surface discrepancies in a workflow attached to a single dashboard.

- **Discrepancy detection:** Configurable thresholds for high/medium/low severity tiers
- **Resolution workflow:** All reconciliation actions logged for auditability
- **Reporting:** On-demand and scheduled reconciliation reports
- **Performance:** Average end-of-day reconciliation run reduced from 18 minutes to 9 minutes for top-quartile customers in the Sprint 47 release

### Operational Reporting & Audit
We provide the reporting layer customers need for compliance reviews, regulatory reporting, and internal audits.

- **Discrepancy reporting:** Volume, severity, time-to-resolution metrics
- **Audit logging:** All actions captured with user, timestamp, and partner-side reference
- **Standard reports:** Daily reconciliation summaries, weekly trend reports, quarterly review packs

## Who We Serve

Versana customers are typically:

- **Asset managers** with high-volume exposure to multiple partner-system providers
- **Fund administrators** who reconcile partner-side data daily for their underlying funds
- **Banks and lenders** participating in syndicated loan markets where position data lives across counterparties
- **Servicers** managing structured finance portfolios with cross-system data dependencies

Top-quartile customers process between 25,000 and 100,000+ daily transactions across partner systems.

## Differentiators

- **Integration breadth, not just depth.** Most platforms force customers to choose one or two partner systems. Versana supports a multi-partner footprint so customers don't pick the platform based on which partner they happen to use today.
- **Discrepancy resolution, not just detection.** Detecting a partner-side discrepancy is the easy half. Versana provides the unified workflow that gets the discrepancy resolved without leaving the platform.
- **Compliance-grade audit trail.** Every reconciliation action is captured for compliance and internal-audit review. Customers stop maintaining a parallel spreadsheet-based audit log.
- **Customer-led onboarding.** Customers participate in the design of new partner integrations via the design-partner program — they get the integration they actually need, not the integration we guess they need.

## Customer Outcomes

For top-quartile customers in 2026:

| Outcome | Metric |
|---|---|
| Reconciliation time reduction | ~50% versus the prior CSV-export workflow |
| Discrepancy time-to-resolution | Reduced from 3 business days to 1 business day for high-severity items |
| Manual re-keying | Eliminated for supported partner-system integrations |
| Audit prep time | Reduced from days to hours per quarterly audit |

## How Customers Onboard

1. **Discovery (Week 0):** Customer-side stakeholders confirm partner-system coverage requirements
2. **Integration setup (Weeks 1–3):** Versana's integration team enables partner connections; customer enables credentials
3. **Pilot (Weeks 4–8):** Single business unit or product line runs in parallel with existing workflow
4. **Cutover (Weeks 9–12):** Full migration of operational workflow to Versana
5. **Optimization (Quarter 2):** Adjust polling cadence, discrepancy thresholds, and reporting cadence

## Contact

For workshop purposes:
- General inquiries: hello@versana.example (fictional)
- Operational issues: ops@versana.example (fictional)
- Customer success: cs@versana.example (fictional)

---

*Document version: Workshop sample, May 2026. All content fictional.*
