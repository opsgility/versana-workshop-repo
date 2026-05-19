# Sample Ops Runbook — Daily Reconciliation Workflow

> **Fictional.** Clearly fictional sample content for a Microsoft 365 Copilot workshop. Not an actual operational runbook.

---

## Purpose

Standardize the daily reconciliation workflow performed by the operations team to verify platform-side records against partner-system positions and to identify discrepancies for resolution.

## Cadence

- Run **daily** by **end of business + 1 hour**
- Backstop run on Mondays for any weekend-pending items
- Quarterly review of the runbook itself

## Roles

| Role | Responsibility |
|---|---|
| **Ops Analyst (primary)** | Run the reconciliation, log discrepancies, escalate per the matrix below |
| **Ops Lead (secondary)** | Review the daily summary, sign off on any discrepancies that exceed the threshold |
| **Engineering on-call** | Tier-2 escalation for technical issues blocking the reconciliation run |

## Step-by-step

### 1. Pre-checks (5 min)
- Confirm partner-system data feeds have completed (status: green in the monitoring dashboard).
- Confirm platform-side end-of-day batch has completed.
- If either feed is delayed, hold the reconciliation run and escalate per the matrix below.

### 2. Run the reconciliation (10 min)
- Open the operations console.
- Select **Daily Reconciliation** for the current business day.
- Confirm the run completes without errors.
- Capture the run ID for the daily summary.

### 3. Review discrepancies (15–30 min depending on volume)
- Filter the discrepancy list by severity:
    - **High:** position or amount difference > defined threshold; investigate same-day.
    - **Medium:** difference within threshold but new since previous run; capture and review next-day if needed.
    - **Low:** stale items rolling forward from prior runs; review weekly.

### 4. Resolve or escalate (variable)
- For each High discrepancy: contact the partner ops desk via the standard channel; document the resolution path; update the discrepancy record.
- For Medium: assign to the appropriate analyst with a 24-hour follow-up.
- For Low: leave in the queue with the next review date.

### 5. Daily summary (10 min)
- Generate the daily summary report.
- Post to the Operations channel with: total discrepancies (by severity), notable items, items pending escalation.
- Tag the Ops Lead for sign-off.

## Escalation matrix

| Trigger | First escalation | Second escalation |
|---|---|---|
| Partner feed delay > 30 min | Partner ops desk | Engineering on-call |
| Platform batch failure | Engineering on-call | Engineering manager |
| Single discrepancy above threshold | Ops Lead | Head of Operations + Compliance |
| Five or more high-severity discrepancies in one run | Ops Lead | Head of Operations + Engineering |

## Exceptions

- **Holidays:** Run delayed to next business day. Communicate to customers per the standard holiday notification.
- **Half-day market closes:** Run on regular cadence; flag any reduced-volume conditions.
- **System maintenance windows:** Hold the run; resume next business day with a backfill flag.

## Metrics

The runbook is reviewed quarterly using these metrics:

- Average run completion time
- High-severity discrepancy rate per 1,000 transactions
- Time-to-resolution for high-severity discrepancies
- On-time rate (was the daily summary posted by the EOD+1h target)

## Change log

| Date | Author | Change |
|---|---|---|
| (fictional) | Ops Lead | Initial version |
| (fictional) | Ops Analyst | Added Medium severity tier |
| (fictional) | Ops Lead | Updated escalation matrix |
