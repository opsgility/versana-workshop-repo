---
lab:
  title: 'Exercise 1: Outlook — Draft, Iterate, Send'
  description: 'Use Copilot in Outlook to draft post-meeting follow-ups, tactful escalation emails, and informed replies to long Teams threads — using the Versana resource files as context.'
  duration: 25 minutes
  level: 100
  islab: true
  primarytopics:
    - Microsoft 365 Copilot
    - Outlook
    - Internal email workflows
---

# Exercise 1: Outlook — Draft, Iterate, Send (25 min)
---

In this exercise, you use Copilot in Outlook for three realistic internal workflows: drafting a post-meeting follow-up grounded in a transcript, drafting a tactful escalation email referencing the ops runbook, and replying to a long Teams thread you haven't fully read.

> [!TIP]
> Remember the four elements of an effective prompt: **Goal, Context, Sources, Expectations.** You'll use these throughout.

### Scenario

You're on a Versana product / ops / customer-success team with three real workflows this morning:

- **Follow-up** — After today's CS↔Product sync, you need to send a follow-up that captures the decisions (Type A first, Type B next release) and asks the team for additional context.
- **Escalation** — A partner-system contact has flagged a Type B discrepancy. You need an email that's tactful, references the runbook, and proposes a clear next step.
- **Catch-up reply** — A long Teams thread has gone past 20 messages and you're behind. You need to reply without re-reading every message.

Your goal: outreach and replies that are specific, grounded in the attached resource files, and short enough to send.

---

### Task 1: Post-meeting follow-up email (10 min)

You just left the weekly CS↔Product sync and you owe the team a follow-up that captures decisions and action items.

1. In **Outlook on the web**, click **New email**.

2. In the message body, click the **Open Copilot** (pencil) icon to open the **Draft with Copilot** window.

3. Before writing the prompt, attach the meeting transcript: click the **Attach** (paperclip) icon and select `Versana_Sample_Meeting_Transcript.docx` from your OneDrive.

4. In the Copilot prompt field, enter:

    **I just left a CS↔Product sync about our partner-integration roadmap. Draft a follow-up email to the team that references the attached transcript and captures: (1) the decision on integration sequence — Type A first, Type B in the next release, (2) action items with owners and due dates, (3) open questions, (4) a clear next-step ask. Under 150 words. Professional tone, no exclamation points.**

5. Review the draft Copilot generates. Check:
    - Does it correctly identify Type A first, Type B next?
    - Are the action items grouped at the top where they're easy to scan?
    - Is anything missing or wrong?

6. Iterate the draft. In the prompt field below the draft, enter:

    **Tighten the call to action — right now it's three sentences; I want one. Move the action items to the top so it's the first thing the reader sees.**

7. Review draft 2. Try one more refinement to adjust tone:

    **Change the tone to be more confident — drop any hedging like "I think" or "maybe." Be direct.**

8. Navigate between drafts 1, 2, and 3 using the forward/backward arrows. Select the version you prefer and click **Keep it**.

9. After the draft is inserted into the email body, highlight any single sentence you want to refine, click the **Open Copilot** icon, and try **Change Tone** → **Direct** to see how a single paragraph rewrite differs from a full-draft rewrite.



---

### Task 2: Tactful escalation email (8 min)

A partner-system contact's team caused a Type B discrepancy that took until Tuesday to resolve. You need to write an email that acknowledges the issue, references the daily reconciliation runbook, and proposes a constructive next step — without finger-pointing.

1. In **Outlook on the web**, click **New email**. Open the **Draft with Copilot** window.

2. Attach `Versana_Sample_Ops_Runbook.docx` from your OneDrive.

3. Enter this prompt:

    **Draft an email to a partner-system contact about a Type B discrepancy that took 3 business days to resolve. Reference the daily reconciliation runbook (attached) — specifically the escalation matrix for partner-side issues. Acknowledge that the root cause was partner-side without finger-pointing. Ask whether their team can scope a cross-side escalation flow so future incidents move faster. Under 120 words. Respectful but direct. End with a specific next step.**

4. Review the draft. Look for:
    - Does it avoid blaming language while still naming the issue?
    - Does it reference the runbook specifically (not just "your process")?
    - Is the next-step ask concrete?

5. Iterate:

    **Make the next-step ask more specific — propose a 30-minute call this week to scope the cross-side escalation idea rather than a vague "let's discuss."**

6. Optionally try a tone shift:

    **Make the opening less apologetic. Acknowledge the impact without minimizing it, but don't open with "I'm sorry."**

7. Select **Keep it** when satisfied.

> [!TIP]
> **Why the runbook attachment matters:** When you say "reference the daily reconciliation runbook," Copilot pulls the actual escalation matrix from the attached file rather than inventing language. The email reads as informed, not generic.

---

### Task 3: Reply to a long Teams thread you haven't read (7 min)

A Teams thread has gone past 20 messages over the last two days. You're behind. You need to acknowledge the conversation, address the most recent message, and ask one clarifying question — without re-reading every reply.

1. Open **Microsoft Teams** in your browser.

2. Find a real thread in any of your channels that has gone past 10 messages and that you've fallen behind on. *(If you don't have one, use a long internal email thread instead — open Outlook, find a long reply chain, and continue with the steps below.)*

3. At the top of the thread, click the **Copilot** icon (it appears in the thread toolbar next to the reply box, depending on your Teams version).

4. Enter:

    **Summarize this thread in 4 bullets. What's the main question or decision on the table right now? Who is asking it? What's the latest message?**

5. Read the 4-bullet summary. Now switch to drafting a reply.

6. In the reply box of the thread, click the **Copilot** icon to draft a response. Enter:

    **Draft a reply to this thread. Acknowledge the latest message, give a one-sentence response to the question being asked, and propose a 15-minute call to close the loop on the bigger discussion. Tone: professional, not stiff. Under 100 words.**

7. Iterate if needed:

    **Tighten the reply — drop the recap, just answer the questions. People in the thread already know what's been said.**

8. Send the reply when satisfied.

> [!NOTE]
> If the Copilot icon isn't visible inside Teams (depends on tenant rollout), do the same exercise in Outlook with a long email thread instead — the same pattern works.

---

### Hands-On Practice: Your Turn (built into timing above)

Pick one real workflow from your own week and use the same pattern:

- An email you've been putting off (cold reach-out to a peer team, polite decline of a recurring meeting, status update you owe someone)
- A long thread you haven't engaged with
- A tactful escalation to a vendor or cross-team contact

Use the prompting framework (Goal, Context, Sources, Expectations) and iterate at least twice before sending.

> [!TIP]
> **What "good" looks like:** Your finished email is specific (references a real person, file, or moment), short (under 150 words for most internal emails), and ends with a clear next step. If it could have come from any vendor about any topic, iterate again.

---

### What to take with you

- The **draft → iterate → keep it** flow works for every Outlook draft. Don't try to make the first prompt perfect.
- **Attach files for context.** Saying "reference the attached transcript" is the difference between a generic draft and a draft grounded in your actual work.
- **Change Tone** acts on a selection. Don't rewrite the whole email if you only want to fix one paragraph.
- The **SharePoint habit:** put your reusable content where the team's Copilot can see it. Sent-items are invisible to everyone else.

Continue to **Exercise 3: Excel** when you're ready.
