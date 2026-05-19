# Versana — Microsoft 365 Copilot Workshop

**Client:** Versana
**Delivery:** Virtual (Microsoft Teams), 2 hours
**Audience:** Mixed internal team — Product, Operations, Customer Success, Exec Assistants
**Licenses:** Microsoft 365 Copilot (individual licenses required)

---

## Workshop Agenda

| Time | Section | App | Focus | Duration |
|---|---|---|---|---|
| 0:00 – 0:10 | **Copilot Fundamentals** | All | Prompting framework (Goal, Context, Sources, Expectations), file upload, role overview | 10 min |
| 0:10 – 0:35 | **Exercise 1: Outlook** | Outlook | Draft, iterate, send — follow-up emails, tactful escalation, replies to long threads | 25 min |
| 0:35 – 1:00 | **Exercise 4: Teams** | Teams | Meeting prep + summaries — PRD review prep, ops runbook prep, transcript summary | 25 min |
| 1:00 – 1:05 | **Break** | — | — | 5 min |
| 1:05 – 1:25 | **Exercise 3: Excel** | Excel | Vendor analysis: patterns, watch-outs, renewal priorities | 20 min |
| 1:25 – 1:45 | **Exercise 5: Word** | Word | First-draft engine — internal memos and customer-facing release notes | 20 min |
| 1:45 – 2:00 | **Exercise 6: Hands-on practice** | All | Multi-app scenarios across product, ops, CS, exec assistants — and Q&A | 15 min |
| | | | **Total** | **2 hours** |

> The numbering follows the source `Versana_Copilot_Workshop.pptx` (Exercises 1, 3, 4, 5, 6 visible; Exercise 2 is hidden as a sales-only scenario and Outlook Exercise 1 covers the visible Outlook block).

---

## Audience & Role Lens

This workshop is built for a mixed internal audience. Each exercise calls out where specific roles get the highest leverage:

| Exercise | Product | Operations | Customer Success | Exec Assistants |
|---|---|---|---|---|
| Exercise 1: Outlook | • Status to stakeholders | • Partner-system escalations | • Customer follow-ups | • Calendar-driven coordination |
| Exercise 3: Excel | • Roadmap impact analysis | • Vendor / cost analysis | • Customer health scoring | • Quick-turn data summaries |
| Exercise 4: Teams | • Sprint review prep | • Incident retro summaries | • Customer-meeting summaries | • Exec-meeting prep |
| Exercise 5: Word | • PRDs, release notes, memos | • Runbook updates, audit notes | • Customer one-pagers, QBR prep | • Briefing memos, talking points |
| Exercise 6: Hands-on | All roles pick a scenario relevant to them |

---

## Resource Files

Participants download the resource files during lab setup, upload to OneDrive, and open each one once so Copilot can find them via MRU.

### Foundation set (every workshop)

| File | Format | Used in | Description |
|---|---|---|---|
| `Versana_Sample_PRD.docx` | Word | Ex 1, Ex 4, Ex 5 | Sample product requirements doc — partner-integration expansion |
| `Versana_Sample_Meeting_Transcript.docx` | Word | Ex 1, Ex 4 | CS ↔ Product weekly sync transcript |
| `Versana_Sample_Ops_Runbook.docx` | Word | Ex 4, Ex 5 | Daily reconciliation workflow runbook |
| `Versana_Sample_Sprint_Summary.docx` | Word | Ex 5 | Sprint 47 completion notes — base for release notes |
| `Versana_Sample_Vendor_List.xlsx` | Excel | Ex 3 | Vendor / external service reference (13 rows, formatted as Table) |

### Extended set (for hands-on and deeper demos)

| File | Format | Used in | Description |
|---|---|---|---|
| `Versana_Company_Overview.docx` | Word | Ex 1, Ex 4, Ex 5 | Platform overview, integration types, differentiators |
| `Versana_Integration_Catalog.docx` | Word | Ex 4, Ex 5, Ex 6 | Detailed Type A / Type B integrations, pricing tiers, onboarding |
| `Versana_Customer_Activity_History.docx` | Word | Ex 1, Ex 4, Ex 6 | 5 customer accounts with 12 months of activity |
| `Versana_Customer_Business_Review_Transcript.docx` | Word | Ex 4 | Quarterly business review with a top-tier customer |
| `Versana_Account_List.xlsx` | Excel | Ex 3, Ex 6 | 15 existing customers + 10 prospects |

---

## Prompt Library (Take-Home Deliverable)

**File:** `03-take-home-prompt-sheet.md`

Organized by use case:

- **Email drafting (Outlook)** — 4 prompt templates
- **Status updates & check-ins (Outlook)** — 3 prompt templates
- **Meeting prep (Teams)** — 3 prompt templates
- **Meeting summaries (Teams)** — 2 prompt templates
- **Internal memos (Word)** — 3 prompt templates
- **Customer-facing release notes (Word)** — 2 prompt templates
- **Vendor / data analysis (Excel)** — 3 prompt templates
- **Deck outlines (Word → PowerPoint)** — 2 prompt templates
- **SharePoint habit — quick reference table**

All prompts use bracketed placeholders `[like this]` for easy customization.

---

## Coverage Map

### Workshop requirements → exercises

| Ask | Coverage |
|---|---|
| Hands-on practice throughout, tied to Versana scenarios | Every exercise has a guided demo + open practice block; all scenarios use the Versana resource files |
| Take-home prompt library | `03-take-home-prompt-sheet.md` — categorized templates with placeholders |
| Mixed internal audience (Product, Ops, CS, Exec Assistants) | Each exercise calls out the role-specific angle; Ex 6 lets each role pick a relevant scenario |
| SharePoint habit (replacing the HubSpot bridge from prior delivery) | Three dedicated slides + a quick-reference page; reinforced in every exercise |
| Compressed to 2 hours | Existing 4-hour skeleton retained; sales-only sections hidden in the deck; agenda restructured |

### Key prompts covered

| Prompt pattern | Where covered |
|---|---|
| "Draft a follow-up after our meeting that captures decisions and action items" | Ex 1 Task 1 |
| "Reply to a long Teams thread without re-reading every message" | Ex 1 Task 3 |
| "Build me a prep sheet for the meeting I have in 30 minutes" | Ex 4 Task 1 |
| "Summarize this meeting transcript with action items at the top" | Ex 4 Task 3 |
| "Find watch-outs in this vendor list — expensive AND low quality" | Ex 3 Task 2 |
| "Draft an internal decision memo using problem / options / recommendation / next step" | Ex 5 Task 1 |
| "Convert this sprint summary into customer-facing release notes" | Ex 5 Task 2 |
| "Outline a deck in Word, then generate the slides in PowerPoint" | Ex 5 Bonus |
| "What's the SharePoint habit I should adopt?" | SharePoint slides + quick-reference page |

---

## File Inventory

### Attendee-facing content (`Versana-Course/`)

Read in order — these are the idiot-proof, self-paced walkthroughs. If the live workshop runs short on time, attendees can complete every exercise on their own using these files.

1. `00-lab-setup.md` — get the resource files in place; confirm Copilot is enabled (10 min)
2. `01-Ex1-outlook-draft-iterate-send.md` — Outlook: draft, iterate, send (25 min)
3. `02-Ex2-outlook-check-ins-and-re-engagement.md` — Outlook: check-ins, warm intros, re-engagement (20 min)
4. `03-Ex3-excel-vendor-analysis.md` — Excel: vendor analysis (20 min)
5. `04-Ex4-teams-meeting-prep-summaries.md` — Teams: meeting prep + summaries (25 min)
6. `05-Ex5-word-memos-release-notes.md` — Word: memos + release notes + bonus PowerPoint (20 min)
7. `06-Ex6-hands-on-practice.md` — multi-app scenarios across product / ops / CS / exec assistants (30 min)
8. `03-take-home-prompt-sheet.md` — categorized prompt library to keep open day-to-day
9. `agenda.md` — schedule at a glance
10. `COURSE-OVERVIEW.md` — this document

> Total self-paced content: ~2 hours 20 minutes. The live workshop deck runs Exercises 1, 3, 4, 5, 6 in 2 hours (Exercise 2 is course-only, for attendees who want to keep going after the session).

### Facilitator-only content (`Versana-Facilitator/`)

Not shared with attendees. These contain speaker notes and live demo cues that dilute the demos if attendees have them in advance.

1. `00-facilitator-guide.md` — runbook for the facilitator
2. `01-hour1-overview-outline.md` — Hour 1 outline + speaker notes
3. `02-hour2-use-case-library.md` — 12 walkthroughs for live Q&A
4. `04-hybrid-delivery-notes.md` — virtual + onsite hybrid model

### Resource files (`Versana-ResourceFiles/`)

Foundation files (already in place):

1. `README.md`
2. `Versana_Sample_PRD.docx` (built from `Versana_Sample_PRD.md`)
3. `Versana_Sample_Meeting_Transcript.docx`
4. `Versana_Sample_Ops_Runbook.docx`
5. `Versana_Sample_Sprint_Summary.docx`
6. `Versana_Sample_Vendor_List.xlsx`

Extended set (newly added):

7. `Versana_Company_Overview.docx`
8. `Versana_Integration_Catalog.docx`
9. `Versana_Customer_Activity_History.docx`
10. `Versana_Customer_Business_Review_Transcript.docx`
11. `Versana_Account_List.xlsx`

### Slide deck

- `Versana_Copilot_Workshop.pptx` — 48 slides total (40 visible + 8 hidden sales-specific slides preserved as reference)

---

## Pre-Session Checklist

**One week out**

- Confirm Copilot license is provisioned for every attendee
- Send calendar invite with the lab-setup URL and a "make sure Copilot is enabled" line
- Confirm the deck is in the facilitator's OneDrive

**24 hours out**

- Open every resource file in its associated Microsoft 365 app on the facilitator's account so MRU is primed
- Confirm the Teams meeting recording and transcription are enabled
- Pre-format `Versana_Sample_Vendor_List.xlsx` as a Table (the demo's most common failure point)

**5 minutes before**

- Open Outlook web, Teams, Excel web, Word web in side-by-side browser tabs
- Open the prompt library in a separate tab so you can paste from it during the live Q&A
- Drop the lab-setup link in the Teams chat so attendees can complete setup while you do introductions

---

## Post-Session Follow-Up

- Send the take-home prompt sheet via Teams chat or follow-up email within 24 hours
- Share the recording link if recorded
- Track adoption signals: Teams-chat questions during session, follow-up demo requests, Copilot license usage uptick over the following 2–4 weeks

---

*Versana workshop overview, May 2026. All resource files are fictional and intended for workshop use only.*
