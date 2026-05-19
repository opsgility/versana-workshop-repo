---
lab:
  title: 'Exercise 4: Teams — Meeting Prep and Summaries'
  description: 'Use Copilot in Teams to build prep sheets before meetings, summarize transcripts into structured channel posts, and turn raw meeting content into action items.'
  duration: 25 minutes
  level: 100
  islab: true
  primarytopics:
    - Microsoft 365 Copilot
    - Teams
    - Meeting prep and summaries
---

# Exercise 4: Teams — Meeting Prep and Summaries (25 min)
---

In this exercise, you use Copilot in Teams to prepare for two different kinds of meetings and to summarize a transcript into a channel-ready post. Each task uses one of the Versana resource files as the attached context — the same way a real meeting would attach the relevant doc.

> [!TIP]
> Copilot in Teams works best in **Work mode** (so it can access your Microsoft 365 content) and with files **attached to your prompt**. Both unlock the meaningful context that turns a generic answer into a useful one.

### Scenario

You have a busy day of meetings ahead:

- **Sync with the Product team** in 30 minutes — you need a prep sheet that pulls from the partner-integration PRD.
- **Quarterly runbook review** later — you want to come prepared with two questions and a sense of where the runbook has gaps.
- **Meeting recap** — you just finished the CS↔Product sync and want a clean summary you can paste into the team's channel.

---

### Task 1: Build a prep sheet for the Product sync (10 min)

You're on the Customer Success or Operations side and you have a meeting in 30 minutes with Product about the partner-integration roadmap. You haven't reviewed the PRD in a few weeks.

1. Open **Microsoft Teams**.

2. Click the **Copilot** icon in the left navigation pane to open the Copilot pane (you may see this under the "..." menu depending on tenant).

3. Confirm the **Work** toggle is selected (so Copilot can access your files).

4. Click the **paperclip / attach** icon and select `Versana_Sample_PRD.docx` from your OneDrive. Confirm it appears in the prompt context.

5. Enter this prompt:

    ```
    I have a meeting in 30 minutes with our Product team about the partner-integration roadmap. I haven't reviewed the attached PRD in a few weeks. Build me a one-page prep sheet with: (1) what we know about the integration scope — Type A and Type B in particular, (2) three discovery questions I should ask, (3) one risk to flag, (4) one likely objection from the Product team and how to respond.
    ```

6. Review Copilot's response. Check:
    - Did it correctly identify Type A (loan administration) and Type B (settlement / operations) from the PRD?
    - Are the discovery questions specific (e.g., "What's the customer-cohort target for Type B pilot?") or generic ("What are the goals?")?
    - Is the risk grounded in the PRD or invented?

7. Iterate to sharpen the discovery questions:

    ```
    The discovery questions are too generic. Rewrite them as specific to the integration sequence decision — Type A first vs. Type B first vs. both in parallel.
    ```

8. Save the prep sheet by copying it into a new OneNote page, Loop component, or Word doc. *(Copilot in Teams doesn't always offer a "save" button — copying to a persistent surface is the most reliable habit.)*

> [!TIP]
> **The prep-sheet pattern** — (1) what we know, (2) discovery questions, (3) risk, (4) likely objection — works for almost any meeting. Memorize it.

---

### Task 2: Prep for an ops runbook review (8 min)

Now prep for a quarterly review of the daily reconciliation runbook. You want to come in with a clear view of where the runbook is strong and where it has gaps.

1. In the Teams Copilot pane, start a new conversation (or scroll up to clear context).

2. Attach `Versana_Sample_Ops_Runbook.docx` from your OneDrive.

3. Enter:

    ```
    I'm prepping for a quarterly review of the attached daily reconciliation runbook. Build me a prep sheet with: (1) where the runbook is strong, (2) three gaps in the escalation matrix, (3) two questions worth raising in the review, (4) one risk if the gaps aren't addressed before the next compliance audit.
    ```

4. Review the response. Pay attention to:
    - The escalation matrix gaps — Copilot should call out at least one specific row or scenario (e.g., what happens at 3 high-severity discrepancies, not 5; what happens during a partner-side outage, etc.)
    - The two questions — are they specific or generic?

5. Iterate:

    ```
    Make the two questions more specific. They should each name a row or section of the runbook that needs clarification.
    ```

6. Optionally, ask Copilot to draft the meeting opening:

    ```
    Draft a 30-second opening I can read at the start of the review — something that frames why this review matters and surfaces the gaps without putting anyone on the defensive.
    ```

---

### Task 3: Summarize a meeting transcript into a channel-ready post (7 min)

You just finished the weekly CS↔Product sync. There's a transcript, and the team is waiting for a summary in their channel.

1. In the Teams Copilot pane, start a new conversation.

2. Attach `Versana_Sample_Meeting_Transcript.docx`. *(In a real workshop, you would attach the live meeting's transcript by clicking the Recap → Summary option after the meeting ends.)*

3. Enter:

    ```
    Summarize this meeting transcript. Pull out: (1) decisions made, (2) action items with owners and due dates, (3) open questions, (4) a 2-sentence overview I can paste into the customer success channel. Format as a structured Teams channel post — short, scannable, no buried information.
    ```

4. Review the summary. Check:
    - Action items should be at the top of any list — they're what people scan for
    - The 2-sentence overview should mention the integration sequence (Type A first, Type B next) decision
    - No filler / no padding

5. Iterate to put the most-scanned info at the top:

    ```
    Re-format so the action items section is first. Move the overview to the bottom. Add a "What was decided" section between them.
    ```

6. Try one more refinement to suit a different audience:

    ```
    Re-format the same summary for the engineering team rather than customer success. They care about the cross-side escalation API spike and the per-partner backoff work, not the customer messaging.
    ```

7. Copy the final summary and post it into the relevant Teams channel.

> [!NOTE]
> **SharePoint habit:** When you post the summary into a Teams channel, the channel's files live on SharePoint by default. Your team's future Copilot can search and reference these summaries. Compare to leaving the summary in a 1:1 chat or your personal notes, where Copilot can't find it for others.

---

### Hands-On Practice: Your Turn (built into timing above)

Use the same flow with one of your own meetings this week:

- A meeting where you have the recording / transcript — summarize it for a specific audience.
- An upcoming meeting where you can attach a relevant doc — build a prep sheet.
- A meeting where the document doesn't exist yet — ask Copilot to draft the doc from a 3-bullet description, then refine.

Pick one and run through it before moving on.

---

### What to take with you

- **Prep sheet pattern** — (1) what we know, (2) discovery questions, (3) risk, (4) likely objection. Use it everywhere.
- **Summary pattern** — (1) action items first, (2) decisions, (3) open questions, (4) overview last. Action items are what people scan for.
- **Attach the file.** Without attached context, Teams Copilot invents specifics. With it, the output is grounded.
- **Re-format for the audience.** The same transcript becomes a CS post, an engineering post, or an exec brief depending on how you ask.
- **Post into the channel,** not into 1:1 chat or personal notes. That's the SharePoint habit — make outputs findable to your team's future Copilot.

Continue to **Exercise 5: Word** when you're ready.
