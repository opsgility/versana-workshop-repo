# Facilitator Guide — Versana M365 Copilot Workshop

A short guide for the person running the session. Read this end-to-end before the workshop. Most of the prep is logistical, not content.

---

## Format

**1 hour overview + 1 hour live Q&A.** Hard cap: 2 hours total. Versana asked for shorter sessions — protect that.

| Block | Time | What you do | What attendees do |
|---|---|---|---|
| Welcome + ground rules | 0:00 – 0:05 | Set expectations, AI / data-handling reminder, "follow along on your own machine" framing | Confirm Copilot is licensed and accessible |
| Prompting framework | 0:05 – 0:15 | Walk through Goal → Context → Sources → Expectations with one live example | Watch and follow along |
| Quick-win demos (3–4 apps) | 0:15 – 0:55 | Live demo one or two prompts per anchor app (Outlook, Teams, Word, PowerPoint), brief touches on Excel + SharePoint | Run the same prompts on their machine |
| Wrap hour 1 | 0:55 – 1:00 | Recap, set up hour 2: "what would you like to see in your role?" | Submit questions in Teams chat or speak up |
| Hour 2 — live Q&A | 1:00 – 2:00 | Pull from the use-case library to answer real-time questions; pause for live attempts | Ask questions, share their screen, try prompts |

> **Pacing tip:** If you over-run hour 1, drop a quick-win demo. Don't drop the framework. The framework is the only part that doesn't survive being unsaid.

---

## Pre-session checklist

### 1 week before
- [ ] Confirm Microsoft 365 Copilot license tier for all attendees (full Copilot vs. Copilot Chat free tier — they behave differently in demos)
- [ ] Confirm with Versana whether there is an internal AI / data-handling policy you should reference live (which data classifications are OK in prompts, which are not)
- [ ] Confirm group size and delivery mode (virtual / onsite / hybrid)
- [ ] Send a calendar invite that includes a 1-line "make sure Copilot is enabled in your Outlook, Teams, and OneDrive before the session" prompt

### 24 hours before
- [ ] Upload the demo resource files (`Versana-ResourceFiles/`) to your facilitator OneDrive folder
- [ ] Open each demo file in the relevant Office app for the web — this adds them to your Most Recently Used list so Copilot finds them in the prompts
- [ ] Test each anchor demo in your own Outlook / Teams / Word / PowerPoint (1 prompt per app is enough as a smoke test)
- [ ] Have the **Take-Home Prompt Sheet** ready to drop into Teams chat at the 5-minute-left mark

### 5 minutes before
- [ ] Close any browser tabs that contain real customer / partner / employee data — your screen will be visible
- [ ] Set Teams notifications to focus mode
- [ ] Confirm screen-sharing resolution is readable (zoom Outlook / Teams / Word / PowerPoint to ~125% at minimum)
- [ ] Have the use-case library open in a second window so you can pull from it during hour 2

---

## Audience and role callouts

This pack is for one mixed audience — ops, product, exec assistants, finance, legal, customer success, broader business. Where a use case naturally lands harder for one role, the use-case library tags it. During the session:

- **Ops** → emphasize Excel (vendor / external-service comparison), Outlook (status updates), Teams (incident retros)
- **Product** → emphasize PowerPoint (roadmap decks), Word (PRDs and release notes), Teams (sprint reviews)
- **Exec assistants** → emphasize Outlook (drafting on behalf of a leader), Teams (meeting prep + summaries), Word (internal memos)
- **Finance / legal / customer success** → cross-reference Word and Excel; Outlook drafting; SharePoint search

**Developers (~50) already on GitHub Copilot.** They're attending the same session. Don't duplicate GitHub Copilot content. When a use case is genuinely relevant for them — like turning sprint summaries into release notes in Word, or drafting a customer-comms note from a Teams incident retro — call it out as such.

---

## Live Q&A pattern (hour 2)

The second hour is live, audience-driven, and the most valuable part of the session. The pattern that works:

1. **Take a question.** "How would I do X?"
2. **Translate to the framework.** Re-state the question as Goal → Context → Sources → Expectations — out loud. This teaches the framework by example without re-lecturing it.
3. **Pull from the use-case library.** If the question matches one of the ~12 walkthroughs, demo it directly. If it doesn't, write the prompt live.
4. **Iterate visibly.** Show one refinement in the prompt. This is the single most important behavior to model — Copilot output is a starting point, not a finished product.
5. **Hand it back.** "Try this in your own Outlook / Word / Teams right now." Pause for 60–90 seconds.

> **You don't need to know every answer.** Saying "let me try a prompt and see what happens" — and then doing it — is better facilitation than pretending to be an expert. The whole point is to model the iteration loop.

---

## When the audience is silent in hour 2

It happens in mixed audiences where some people are shy or new to Copilot. Three reliable prompts to break the ice:

1. *"What's an email you wrote this week that took longer than it should have? Let's draft it together."*
2. *"What's a meeting you have on the calendar this week that you don't feel ready for? Let's prep for it."*
3. *"What's a doc you've been putting off writing? Let's get the first 80% in the next five minutes."*

Each has a corresponding walkthrough in the use-case library — you can drive into a prepared demo if the room takes the bait.

---

## What can go wrong, and what to do

| Problem | What to do |
|---|---|
| Copilot doesn't appear in a demo app | Confirm license tier; confirm the file is on OneDrive (not local); confirm AutoSave is on for Excel/Word. If the issue is licensing, switch demo to a participant who has it provisioned. |
| Copilot returns something generic / templated | Iterate live. The point of the workshop is showing the iteration. Don't try to "win" the prompt on the first shot. |
| A demo references a file Copilot can't find | Open the file once in the relevant app for the web — that adds it to the MRU list. Re-run the prompt. |
| Someone asks about PHI / customer data / contracts | Reinforce Versana's data-handling policy. Demo with **fictional** data only. If you don't know the policy, say so and recommend they confirm before using Copilot on that data class. |
| You over-run hour 1 | Skip a quick-win, not the framework |
| You under-run hour 1 | Take questions early — bring the audience-driven part forward |
| The audience pivots into questions about ChatGPT, Claude, GitHub Copilot, internal LLM tooling | Acknowledge briefly, redirect to M365 Copilot specifically: "Same prompting principles, different surface — but today's hour is about the Copilot inside the tools you use every day." |

---

## After the session

- [ ] Post the **Take-Home Prompt Sheet** in the relevant Teams channel
- [ ] Send a 5-line follow-up email: what we covered, the prompt sheet, link to the use-case library, calendar holds for any follow-up sessions
- [ ] Capture the questions you couldn't answer live — those become next session's content
