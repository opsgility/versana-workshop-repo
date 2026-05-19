# Sample PRD — Expanded Partner Integration Coverage

> **Fictional.** This is a clearly fictional product requirements document created for a Microsoft 365 Copilot workshop. Nothing in it represents Versana's actual product, roadmap, customers, or partners.

---

## Summary

Expand our platform's integration coverage to support two new categories of partner systems — **agent system Type A** (loan administration) and **agent system Type B** (settlement/operations). The goal is to reduce manual reconciliation work performed by users and to position the platform as the source of truth for participant-facing operational data.

## Problem

Today, several user-facing workflows depend on data that lives in partner systems we don't yet integrate with. Users either re-key the data manually or download CSV exports from partner portals and re-upload to our platform. This is time-consuming, error-prone, and undermines our positioning as the operational source of truth.

Two specific friction points show up repeatedly in customer feedback:

1. **Reconciliation lag.** When data lives in two places, end-of-day reconciliation can take several hours — particularly for participants with high-volume relationships across multiple partner systems.
2. **Discrepancy resolution.** When a discrepancy surfaces, users must dig into the partner system, then back into our platform, then re-key the resolution into both. This is the single most-cited friction point in the most recent customer survey.

## Goals

- **Primary:** Reduce reconciliation time for high-volume customers by 50% within 90 days of pilot launch.
- **Secondary:** Ship integrations to two partner system types (Type A, Type B) covering ~80% of the volume our top-quartile customers carry.
- **Quality:** No regression in existing integration reliability metrics.

## Non-goals

- Real-time settlement (out of scope for this initiative — separate roadmap item).
- Historical data backfill beyond 90 days from go-live.
- Integration with regional / non-North-American partner systems in the first release.

## User stories

- *As a loan operations analyst*, I want partner-system positions to appear in my platform dashboard so I don't have to switch tools.
- *As an operations lead*, I want a reconciliation report I can run on demand so end-of-day cleanup is one click instead of a workflow.
- *As a settlement specialist*, I want discrepancies flagged with both source values shown side-by-side so I can resolve them without leaving the platform.

## Proposed solution

A new **Partner Integration Layer** that:

1. Pulls position and event data from supported partner systems on a defined cadence (initial: 15-minute polling; future: event-driven).
2. Reconciles partner-side data with platform-side data and surfaces discrepancies in a unified workflow.
3. Logs all reconciliation actions for auditability.

### Integration scope

| Partner Type | Initial Coverage | Future |
|---|---|---|
| Agent System Type A | Position, event, status data | Real-time eventing |
| Agent System Type B | Position, event, settlement data | Eventing + write-back |

## Risks

- **Partner API stability.** We are dependent on partner API uptime and rate limits. Mitigation: per-partner caching and graceful degradation.
- **Data classification.** Some partner data may be classified more strictly than our existing data. Compliance review required.
- **Customer onboarding friction.** Each customer must enable the integration with their partner credentials. Mitigation: white-glove onboarding for the first cohort.

## Open questions

1. Should the polling cadence be configurable per customer or fixed?
2. Do we expose the reconciliation report via API or only via UI in the first release?
3. What's the right cohort size for the pilot — 5 customers or 15?

## Milestones (illustrative)

| Milestone | Target |
|---|---|
| Internal alpha | Q+1 month |
| Pilot launch (first 5 customers) | Q+2 months |
| GA | Q+3 months |
