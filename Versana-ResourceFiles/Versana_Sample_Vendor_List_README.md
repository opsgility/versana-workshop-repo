# Versana_Sample_Vendor_List.xlsx — Spec & Source Data

> **Fictional.** All vendors, prices, and quality scores are placeholders for a Microsoft 365 Copilot workshop demo (UC-11). Don't use this as a model for real vendor analysis without replacing the data with validated, internally-sourced exports.

---

## File: Versana_Sample_Vendor_List.xlsx

**Used in:** UC-11 — Excel vendor / external service comparison
**Sheets:** 1
**Format note:** Title row in row 1; column headers in row 2; data starting row 3. Format A2:K15 as an Excel Table when populating.

### Title Row
- Row 1: `Versana — External Service / Vendor Reference (FICTIONAL — Workshop Use Only)`

### Columns

| # | Column | Notes |
|---|---|---|
| 1 | Service Category | Reference Lab / Imaging / Translation / Transport / DME — adapt to fintech-friendly categories: Cloud Hosting, Data Vendor, Identity Provider, Document Storage, Translation/Compliance Tooling |
| 2 | Sub-Service | E.g., "Region: US-East compute," "Real-time market data feed," "OAuth identity provider," "Signed document archive," "Compliance translation memory" |
| 3 | Vendor | Vendor Alpha, Vendor Beta, Vendor Gamma, Vendor Delta, Vendor Epsilon |
| 4 | Unit | "per hour," "per query," "per active user," "per GB-month," "per minute" |
| 5 | Unit Cost (USD) | Fictional |
| 6 | Annual Volume | Fictional |
| 7 | Annual Cost (USD) | Unit Cost × Annual Volume |
| 8 | Avg Turnaround / Latency | E.g., "p95 < 200ms," "next-day," "real-time" |
| 9 | Quality Score | 1–100 fictional composite |
| 10 | Contract Status | Active / Renewal Pending / Watch List |
| 11 | Notes | Free text |

### Sample Rows

Build **13 rows** distributed across 5 categories and 5 vendors. Patterns to embed:
- One vendor consistently expensive but high quality (e.g., Vendor Alpha = premium reliability)
- One vendor cheap but low quality with Renewal Pending (e.g., Vendor Delta = price/quality risk)
- One vendor mid-priced and consistently mid-quality (Vendor Gamma = workhorse)
- A clear "watch-out": expensive AND low quality (one row across categories)
- A clear "bright spot": cheap AND high quality (one row)

| Service Category | Sub-Service | Vendor | Unit | Unit Cost | Annual Vol | Annual Cost | Latency / Turnaround | Quality | Status | Notes |
|---|---|---|---|---|---|---|---|---|---|---|
| Cloud Hosting | US-East compute | Vendor Alpha | per hour | $0.85 | 720,000 | $612,000 | p95 < 100ms | 94 | Active | Premium reliability |
| Cloud Hosting | US-East compute | Vendor Beta | per hour | $0.62 | 200,000 | $124,000 | p95 < 200ms | 81 | Active | Workhorse for non-critical |
| Data Vendor | Real-time market data | Vendor Gamma | per query | $0.012 | 30,000,000 | $360,000 | real-time | 88 | Active | Reliable |
| Data Vendor | Real-time market data | Vendor Delta | per query | $0.009 | 5,000,000 | $45,000 | real-time | 71 | Renewal Pending | Cheaper but stale 3% of the time |
| Identity Provider | OAuth IdP | Vendor Alpha | per active user | $4.20 | 2,400 | $10,080 | p95 < 80ms | 92 | Active | Standard |
| Identity Provider | OAuth IdP | Vendor Epsilon | per active user | $2.95 | 600 | $1,770 | p95 < 150ms | 86 | Active | Backup IdP |
| Document Storage | Signed document archive | Vendor Beta | per GB-month | $0.025 | 480,000 | $12,000 | next-day retrieval | 82 | Active | Compliance use |
| Document Storage | Signed document archive | Vendor Gamma | per GB-month | $0.038 | 120,000 | $4,560 | same-day retrieval | 89 | Active | Faster retrieval |
| Translation / Compliance | Compliance translation memory | Vendor Alpha | per minute | $1.95 | 12,000 | $23,400 | <30s | 91 | Active | Reliable |
| Translation / Compliance | Compliance translation memory | Vendor Delta | per minute | $1.40 | 3,000 | $4,200 | <60s | 68 | Watch List | Quality issues; under review |
| Cloud Hosting | EU-West compute | Vendor Alpha | per hour | $0.95 | 200,000 | $190,000 | p95 < 110ms | 93 | Active | EU footprint |
| Cloud Hosting | EU-West compute | Vendor Gamma | per hour | $0.68 | 80,000 | $54,400 | p95 < 220ms | 78 | Renewal Pending | Cheaper but considering switch |
| Data Vendor | Reference data | Vendor Epsilon | per query | $0.005 | 8,000,000 | $40,000 | next-day | 90 | Active | Bright spot — cheap and reliable |

### Conversion instructions

1. Open Excel Online or Excel desktop.
2. Create a new workbook named `Versana_Sample_Vendor_List.xlsx`.
3. Enter the title in row 1, column headers in row 2, and rows 3–15 with the sample data above.
4. Highlight A2:K15 → **Insert > Table** → confirm "My table has headers."
5. Confirm AutoSave is **on** (file must be saved to OneDrive for Copilot to read it).
6. Save to the OneDrive folder the facilitator account uses for the workshop.
7. Open the file once in Excel for the web — this adds it to your Most Recently Used list.

> **All values are fictional.** Don't reuse this dataset as a real vendor benchmark.
