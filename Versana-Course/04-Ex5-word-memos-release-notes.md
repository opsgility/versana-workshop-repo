---
lab:
  title: 'Exercise 5: Word — Memos and Release Notes'
  description: 'Use Copilot in Word as a first-draft engine for internal decision memos and customer-facing release notes — then use Word to outline a deck and generate the slides in PowerPoint.'
  duration: 20 minutes
  level: 100
  islab: true
  primarytopics:
    - Microsoft 365 Copilot
    - Word
    - PowerPoint
---

# Exercise 5: Word — Memos and Release Notes (20 min)
---

In this exercise, you use Copilot in Word as a first-draft engine for two common deliverables (an internal decision memo and customer-facing release notes), and then chain Word → PowerPoint to outline a deck and generate slides.

> [!TIP]
> The right ratio is **30 seconds drafting, 2 minutes revising.** Don't try to write the perfect prompt up front. Let Copilot give you something, then make it yours.

### Scenario

You owe two deliverables and have a meeting tomorrow:

- **Internal decision memo** — for the exec team on the partner-integration sequence (Type A first, Type B next release). Reference the PRD.
- **Customer-facing release notes** — for Sprint 47, drawn from the sprint summary.
- **Bonus** — turn the memo into a 6-slide exec deck in PowerPoint using the outline-first pattern.

---

### Task 1: Internal decision memo (8 min)

1. In **Word for the web**, click **New blank document**.

2. Above the empty document, you'll see the **Copilot prompt** field (Word's "Draft with Copilot" entry point). If you don't see it, click **Copilot** in the ribbon and select "Draft with Copilot."

3. Click the **paperclip / attach** icon and select `Versana_Sample_PRD.docx` from your OneDrive.

4. Enter:

    **Draft a one-page internal decision memo for the exec team on the partner-integration sequence. Reference the attached PRD. Use this structure: (1) Issue — 2 sentences, (2) Background — 3-4 sentences, (3) Options — 2 or 3, with one anticipated benefit and one trade-off each, (4) Recommendation — clear, with a brief rationale, (5) Decision sought — what specifically I want from leadership and by when. Tone: neutral, decision-oriented. Keep to one page.**

5. Click **Generate** and wait for the draft. You'll see a numbered version (Draft 1 of N).

6. Review the draft. The most common weakness in Copilot's first decision memo is a wishy-washy **Recommendation** section.

7. In the prompt field below the draft, iterate:

    **The Recommendation section is too hedged. Rewrite it as a clear "we should do X" with a one-sentence rationale. Keep the structure, just make it decisive.**

8. Use the arrows to navigate between drafts. Pick the version you like and click **Keep it** to insert it into the document.

9. Once the draft is in the document, find the **Options** section. Highlight one paragraph (just one option, not the whole section).

10. Click the **Copilot pencil** icon that appears in the margin → **Rewrite**.

11. In the Rewrite prompt, enter:

    **Make this option more specific. Name a concrete example of what we'd build for this integration type, and add one risk specific to this option that the exec team needs to know.**

12. Click **Replace** to swap the paragraph.

> [!TIP]
> **Why Rewrite matters:** It acts on a selection, not the whole document. Don't try to rewrite a whole memo when you only want to fix one section. Highlight, Rewrite, move on.

---

### Task 2: Customer-facing release notes (7 min)

Now you'll turn an internal sprint summary into customer-facing release notes. The audience is different (customers vs. internal), so the language must change.

1. In **Word for the web**, create a new blank document.

2. Open **Draft with Copilot** and attach `Versana_Sample_Sprint_Summary.docx`.

3. Enter:

    **Convert this sprint summary into customer-facing release notes. Structure: (1) Headline — one sentence, (2) What's new — 3 highlights, each with a one-sentence customer benefit, (3) Improvements — bulleted, terse, (4) Fixes — bulleted, terse. Tone: confident but not marketing-y. Avoid adjectives like "exciting," "powerful," or "robust." Avoid the words "robust," "leverage," and "seamless." Keep to under 250 words.**

4. Click **Generate** and review. Watch out for:
    - The "What's new" highlights — are they feature-focused (engineering language) or customer-benefit-focused (user-outcome language)?
    - The headline — is it specific or generic?

5. Iterate to make the highlights customer-focused:

    **The "What's new" highlights are too feature-focused. Rewrite each one as a customer-benefit-focused statement: lead with what the customer can now do that they couldn't before, not with what we built.**

6. Iterate once more on the headline:

    **The headline is generic. Make it specific to the biggest improvement — the reconciliation engine being roughly twice as fast for top-quartile customers. Keep it under 12 words.**

7. **Keep it** when satisfied.

> [!NOTE]
> **Why ban the buzzwords:** "Exciting," "powerful," "robust," "leverage," and "seamless" are corporate auto-pilot words that signal the writer didn't think. Explicitly forbidding them forces Copilot to be specific.

---

### Task 3 (Bonus): Outline-first PowerPoint (5 min)

The fastest way to generate a slide deck is to **outline in Word first**, then generate slides from the outline. Doing both in one PowerPoint prompt produces generic decks. Splitting it produces decks that say what you want.

1. Back in **Word for the web**, open the decision memo you wrote in Task 1.

2. Open the **Copilot pane** (click Copilot in the ribbon).

3. In the pane, enter:

    **Outline a 6-slide internal exec deck based on this memo. Each slide should have a title and 3-5 bullet points. Slide 1 = problem, Slide 2 = current state, Slide 3 = options, Slide 4 = recommendation, Slide 5 = risks, Slide 6 = next step. Each bullet should be under 12 words.**

4. Review the outline. Copy it to your clipboard.

5. Open **PowerPoint for the web**. Create a new blank presentation.

6. Click the **Copilot** icon in the ribbon → **Create presentation from an outline**.

7. Paste the outline. Click **Generate**.

8. Wait for the deck to generate. Review the slides — usually 6 slides matching your outline.

9. With the deck open, in the Copilot pane:

    **Replace the title slide background with a darker theme. Make slide 4 (recommendation) the most visually emphasized — bigger text, a contrasting layout. Add a brief speaker note to each slide summarizing the key argument.**

10. Save the deck.

> [!TIP]
> **Two-step beats one-step every time.** "Make me a deck about X" produces generic slides. "Outline first, then generate from the outline" produces a deck that actually says what you want.

---

### Hands-On Practice: Your Turn (built into timing above)

Pick one of these for your own work:

- A memo you owe — pick a real decision you need to write up. Use the (Issue / Background / Options / Recommendation / Decision sought) structure.
- A doc you'd like as a deck — outline it in Word, generate the deck in PowerPoint, iterate two or three times.
- A long Word document you haven't read — open it, ask Copilot in the pane to "summarize this in 5 bullets," then "what would I disagree with in this doc?" The second question is the more useful one.

---

### What to take with you

- **30-second draft, 2-minute revise.** That's the right ratio. First prompts are rough by design.
- **Rewrite acts on a selection.** Highlight one paragraph at a time when you want to revise a section.
- **Ban the buzzwords.** Explicitly forbidden buzzwords force Copilot to think harder.
- **Outline first.** Word → outline → PowerPoint produces better decks than going straight into PowerPoint.
- **Attach files.** "Reference the attached PRD" turns generic prose into grounded, useful prose.

Continue to **Exercise 6: Hands-on practice** when you're ready.
