---
lab:
  title: 'Exercise 6: Hands-On Practice — Multi-App Scenarios'
  description: 'Apply the prompting framework end-to-end across Outlook, Teams, Excel, Word, and PowerPoint. Pick one Product / Ops scenario and one Customer Success / Exec Assistant scenario.'
  duration: 30 minutes
  level: 200
  islab: true
  primarytopics:
    - Microsoft 365 Copilot
    - Multi-app workflows
    - Hands-on practice
---

# Exercise 6: Hands-On Practice — Multi-App Scenarios (30 min)
---

This is your end-to-end practice. The previous exercises showed individual Copilot patterns in one app at a time. Real work spans apps: a meeting → a summary → an email → a memo → a deck.

Pick **one Product / Ops scenario** and **one Customer Success / Exec Assistant scenario** from the four below. Each scenario uses two or three apps. Plan to spend 12–15 minutes on each.

> [!TIP]
> Pick a scenario **outside your usual lane** if you have time — Ops people pick the CS scenario, Product people pick the exec-assistant scenario. The framework (Goal / Context / Sources / Expectations) transfers across roles. You'll prove it to yourself.

---

## Pick one Product / Ops scenario

### Scenario A — Sprint kickoff package

You're starting a sprint focused on the partner-integration work in the attached PRD. You need to walk the team through it in three deliverables.

**Step 1 — Word (5 min):** Open `Versana_Sample_PRD.docx` in Word for the web. In the Copilot pane:

> Outline a 6-slide sprint kickoff deck for the engineering team based on this PRD. Slide 1 = problem, Slide 2 = goals, Slide 3 = scope (Type A first, Type B next release), Slide 4 = key risks, Slide 5 = milestones, Slide 6 = open questions for engineering. Each bullet under 12 words.

Copy the outline.

**Step 2 — PowerPoint (5 min):** Create a new blank presentation. Use **Copilot → Create presentation from an outline**. Paste the outline. Generate. Then iterate:

> Make slide 3 (scope) the most visually emphasized. Add a brief speaker note to each slide.

**Step 3 — Outlook (3 min):** Create a new email. Draft with Copilot, attach the deck:

> Draft a kickoff invite to the squad. The kickoff is Friday at 10am. Reference the attached deck (sprint kickoff). Ask the team to come with one question or one concern. Tone: warm, not stiff. Under 100 words.

**Deliverable:** outline in Word, deck in PowerPoint, kickoff email in Outlook. All three drafted in under 15 minutes.

---

### Scenario B — Reconciliation runbook audit

You need to do a quarterly audit of the reconciliation runbook and propose three specific improvements.

**Step 1 — Teams (4 min):** Open Copilot in Teams. Attach `Versana_Sample_Ops_Runbook.docx`. Prompt:

> Read this runbook and identify three specific gaps in the escalation matrix. For each gap, describe the scenario where it would fail. Be concrete — point at a specific row or table in the runbook.

Copy the response.

**Step 2 — Word (6 min):** Create a new Word document. Draft with Copilot, attach the runbook:

> Draft a one-page proposal to address the three gaps you identified. Use this structure: (1) Summary — 2 sentences, (2) Gap 1 / Recommendation / Effort estimate, (3) Gap 2 / Recommendation / Effort estimate, (4) Gap 3 / Recommendation / Effort estimate, (5) Decision sought — which of the three should we tackle this quarter. Tone: neutral, decision-oriented. Keep to one page.

Iterate the Recommendation sections to be decisive (avoid "we could," prefer "we should").

**Step 3 — Outlook (3 min):** Draft an email to the Ops Lead with the proposal attached:

> Draft an email to my Ops Lead with the attached one-pager. The lead is busy, so the email should give them just enough context to know whether to read the proposal now or schedule a meeting. Under 60 words.

**Deliverable:** a runbook audit memo + cover email. Three improvements identified, each with a clear ask.

---

## Pick one Customer Success / Exec Assistant scenario

### Scenario C — Customer escalation aftermath

A customer (Cresswell Asset Management) hit a Type B discrepancy that took three days to resolve. You need to do post-mortem comms.

**Step 1 — Teams (4 min):** Open Copilot in Teams. Attach `Versana_Sample_Meeting_Transcript.docx` and `Versana_Customer_Activity_History.docx`. Prompt:

> Summarize the situation: a customer hit a Type B discrepancy that took 3 days to resolve. Pull from both the meeting transcript and the customer activity history. What's the customer's history? What's likely on their mind right now? What do they want from us going forward?

**Step 2 — Outlook (5 min):** Draft an email to the customer (Marie Chen, Senior Operations Manager at Cresswell). Attach the meeting transcript:

> Draft a follow-up email to Marie Chen at Cresswell about the Type B discrepancy that took 3 business days to resolve. Reference the attached transcript. Acknowledge the issue without finger-pointing — the root cause was partner-side, but the customer experience was poor. Outline what we're doing to make this faster next time (the per-partner backoff work in Sprint 48; the cross-side escalation spike). Propose a specific next step — a 30-minute call next week. Under 150 words. Tone: respectful, accountable, not apologetic.

Iterate to soften any defensive language.

**Step 3 — Word (4 min):** Draft an internal note for the product team:

> Draft a one-paragraph internal note for the product team summarizing what we promised the customer (Cresswell) about the cross-side escalation work. Include the timeline (Sprint 48 spike, Sprint 49 or 50 ship). Under 80 words.

**Deliverable:** a sensitive customer email + an internal commitment note. Both done in under 15 minutes.

---

### Scenario D — Exec prep package

You're an exec assistant prepping a Versana exec for a tough quarterly business review with a top-tier customer.

**Step 1 — Teams (5 min):** Open Copilot in Teams. Attach `Versana_Customer_Activity_History.docx` and `Versana_Customer_Business_Review_Transcript.docx`. Prompt:

> Build me a prep sheet for the exec who's going to lead a quarterly business review with Cresswell Asset Management. Use the attached activity history and the prior QBR transcript. Include: (1) relationship highlights from the last quarter, (2) five discovery questions the exec should ask, (3) two expansion topics to raise, (4) one risk signal to listen for, (5) the 30-second opening the exec should read at the start of the call.

**Step 2 — Word (5 min):** Create a new Word doc. Draft a briefing memo:

> Draft a one-page briefing memo for the exec based on the prep sheet above. Use this structure: (1) Who they are — 3 sentences, (2) Where the relationship stands — 3 bullets, (3) What's on their mind right now — 3 bullets, (4) What we want from this meeting — 1 sentence. Tone: written for someone who hasn't been in the day-to-day. No jargon.

**Step 3 — PowerPoint (3 min):** Create a single-slide summary the exec can have on screen. In PowerPoint, use **Copilot → Create presentation from an outline** with just the four sections from the briefing memo as bullets.

**Deliverable:** a prep sheet + briefing memo + single-slide summary. Three artifacts the exec can rely on.

---

### Debrief

After you finish both scenarios, take 2 minutes to think through these:

1. **Which app gave you the most leverage?** For most people it's not the one they expected.
2. **Where did you have to revise the most?** What did you change that improved the output?
3. **Where does this fit into your daily routine?** Before a meeting, after a call, during account planning, drafting outreach.
4. **What's one prompt worth saving to your personal library?**
5. **What's one task you'd hand to Copilot more often after today?**

If you're going through this self-paced after the workshop, write down your answer to #4 and add it to your copy of `03-take-home-prompt-sheet.md`. That's how your personal library grows.

---

### What to take with you

- **End-to-end is where Copilot earns its keep.** Outline in Word → deck in PowerPoint → email in Outlook in 15 minutes is the unlock.
- **Attach across the chain.** Each step in a multi-app workflow attaches a different file. The continuity is what makes the outputs cohere.
- **Pick a scenario outside your lane.** The framework transfers. You'll prove it to yourself faster by doing it than by being told.
- **Save what works.** Every iteration that produces something usable is a prompt template waiting to be added to your personal library.

You're done with the workshop. Review **`03-take-home-prompt-sheet.md`** — the library you'll keep open day-to-day — and add the prompts that worked for you above.
