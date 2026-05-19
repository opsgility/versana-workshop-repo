# Hour 2 — Use Case Library

Twelve short walkthroughs the facilitator can pull from in real time during hour 2. Each is small enough to demo in 3–5 minutes. Use them as scaffolding when the audience is silent, or to drive into a specific role-relevant question.

> **How to use this library live:**
> 1. Audience asks a question.
> 2. Pattern-match to one of the use cases below.
> 3. Open the relevant app, run the prompt as written, iterate live, hand it back to the room.
> 4. If nothing matches, write the prompt from scratch — show the framework working in real time.

Each use case is tagged by **app** and by **role lean** so you can pick from the right shelf when the room asks.

---

## Outlook (4 use cases)

### UC-01 — Reply to a long thread you haven't read
**Roles:** Everyone
**Setup:** Open a long Teams chat thread or email thread you'd actually like to respond to. (For demo: any internal thread that's gone past 10 messages.)

**Prompt:**
> Summarize this thread in 4 bullets. Then draft a reply that addresses the most recent two messages, acknowledges the question raised in message 3, and proposes a 15-minute call to close the loop. Tone: professional, not stiff. Under 100 words.

**Iteration to demo:**
> Tighten the reply — drop the recap, just answer the questions. People in the thread already know what's been said.

**Why this lands:** Everyone has these threads. The save-time factor is immediate.

---

### UC-02 — Draft a status update no one will skip
**Roles:** Ops, Product, Customer Success, Exec Assistants
**Setup:** None — pure prompt.

**Prompt:**
> I'm a [role] sending a weekly status update to my leadership team. Draft an email with three sections: (1) Wins from this week — 2 bullets, specific. (2) Risks or blockers — 2 bullets, with the ask if any. (3) Next week — 2 bullets. Tone: confident, not over-explained. Under 200 words. Use bold for section headers but no other formatting.

**Iteration to demo:**
> Replace the bullet "Customer feedback was positive" with something more specific — what feedback, from which segment, and what we're doing about it.

**Why this lands:** Status updates are a near-universal weekly task; bad ones are forgettable, good ones build trust.

---

### UC-03 — Decline an internal meeting without sounding cold
**Roles:** Everyone
**Setup:** Pretend you got a meeting invite that doesn't quite fit.

**Prompt:**
> Draft a polite reply declining a meeting invitation. The meeting is a recurring sync that I don't think I add value to. Acknowledge the importance of the work, offer to be looped in async on key decisions, and suggest the organizer send me the agenda 24 hours in advance so I can flag if I should join a specific session. Tone: respectful, not apologetic. Under 80 words.

**Iteration to demo:**
> Make the offer to be looped in more specific — "send me the meeting summary instead of the calendar invite" is a cleaner ask than "loop me in async."

**Why this lands:** Most people overuse "I'm busy" or under-use "no." This shows that "no, here's how I can still be useful" is a learnable pattern.

---

### UC-04 — Write the email you've been putting off
**Roles:** Everyone
**Setup:** Ask the room: "What's an email you've been putting off?" Take a real example.

**Prompt template (fill in live):**
> I need to email [recipient role] about [topic]. The hard part is [what makes it hard — bad news, asking for something, telling someone they were wrong]. Draft the email so that I lead with the hard thing — don't bury it. Be respectful but direct. Offer one constructive next step. Under [length].

**Iteration:** Whatever the audience says is wrong with the draft, ask Copilot to fix that specifically.

**Why this lands:** This is the single best icebreaker for hour 2 if the room is quiet. Volunteer your own email to put the audience at ease.

---

## Teams (3 use cases)

### UC-05 — Prep for a meeting in 10 minutes
**Roles:** Everyone (especially exec assistants and product)
**Setup:** Open the Teams Copilot pane.

**Prompt:**
> I have a meeting in 30 minutes. The topic is [topic]. Attendees are [roles, not names]. I haven't reviewed the relevant materials. Build me a one-page prep sheet with: (1) what I should already know — bulleted background, (2) three discovery questions I should ask, (3) one likely objection or concern and how to respond, and (4) one risk or watch-out I should be ready for.

**Iteration to demo:**
> The discovery questions are too generic. Make them specific to a [topic-specific lens — ops review, product feature decision, vendor escalation].

**Why this lands:** Saves 15+ minutes of prep per meeting. People feel that immediately.

---

### UC-06 — Summarize a meeting recording for a Teams channel
**Roles:** Everyone
**Setup:** Open a recorded meeting in Teams. (Use the sample meeting transcript file as backup if the recording is touchy.)

**Prompt:**
> Summarize this meeting recording. Output: (1) 2-sentence overview, (2) decisions made — bulleted, (3) action items with owners and dates, (4) open questions, (5) any risk or escalation flags. Format as a Teams channel post — short, scannable, no buried information.

**Iteration to demo:**
> Pull the action items into a single dedicated section at the top — that's what people will actually scan for. Move the overview to the bottom.

**Why this lands:** Universally useful, immediately reusable, low risk of getting weird output.

---

### UC-07 — Catch up on a channel you've been ignoring
**Roles:** Everyone
**Setup:** Pick a Teams channel that's been busy this week.

**Prompt:**
> I haven't been checking this channel for a week. Summarize what's happened: the main threads, any decisions that were made, any action items that have my name on them, and anything I should respond to today. Format as a quick scan list with the most urgent items at the top.

**Iteration to demo:**
> Surface anything where someone tagged me directly or asked a question I didn't answer.

**Why this lands:** Nearly everyone has a channel they're behind on. Fixing this is genuinely useful.

---

## Word (2 use cases)

### UC-08 — Internal memo / decision one-pager
**Roles:** Product, Ops, Leadership
**Setup:** Blank Word document.

**Prompt:**
> Draft a one-page internal decision memo for our leadership team on the topic of [topic]. Use this structure: (1) Issue — 2 sentences, (2) Background — 3–4 sentences, (3) Options — 2 or 3, with one anticipated benefit and one trade-off each, (4) Recommendation — clear, with a brief rationale, (5) Decision sought — what specifically you want from leadership and by when. Tone: neutral, decision-oriented. Reference the attached document. Keep to one page.

**Iteration to demo:**
> Make the recommendation more decisive. Right now it reads like option 2 *might* be better; I want a clear "we should do this" with a 1-sentence reason.

**Why this lands:** Decision memos are everywhere, and most are bad. This pattern produces good ones consistently.

---

### UC-09 — Release notes from a sprint summary
**Roles:** Product, Engineering, Customer Success
**Setup:** Have a sprint-summary doc or paste a list of completed items into Word.

**Prompt:**
> Convert this list of sprint-completed items into customer-facing release notes. Structure: (1) Headline (one sentence), (2) What's new — 3 highlights with a one-sentence customer benefit each, (3) Improvements — bulleted, terse, (4) Fixes — bulleted, terse. Tone: confident but not marketing-y. Avoid adjectives like "exciting," "powerful," "robust."

**Iteration to demo:**
> The "What's new" highlights are too feature-focused. Rewrite them as customer-benefit-focused — what the customer can now do that they couldn't before.

**Developer callout:** *"This is one place M365 Copilot earns its keep for engineering teams that already use GitHub Copilot. Sprint summary in Word → release notes draft in 60 seconds."*

**Why this lands:** Crosses product and engineering, makes the developer audience lean in.

---

## PowerPoint (1 use case)

### UC-10 — Roadmap deck from a one-page outline
**Roles:** Product, Ops, Leadership, Customer Success
**Setup:** A one-page outline (write it live in Word, or use a saved one).

**Prompt (in Word, to build the outline):**
> Outline a 6-slide internal roadmap deck for our exec team on next quarter's plan. Slide structure: (1) Recap of last quarter — 3 bullets, (2) What we learned — 2 bullets, (3) Next quarter goals — 3 bullets, (4) Investments required — 2 bullets, (5) Risks — 2 bullets, (6) Asks of leadership — 2 bullets. Each bullet under 12 words.

**Then in PowerPoint:**
> Use **Copilot → Create presentation from outline** (or paste the outline into Copilot's chat in PowerPoint).

**Iteration to demo:**
> Make slide 4 (investments) the most visually emphasized — the audience needs to see the ask. Use a darker background or a contrasting layout.

**Why this lands:** Roadmap decks are universal product/ops work. The two-step (outline first, deck second) is the durable pattern.

---

## Excel (1 use case)

### UC-11 — Vendor / external service comparison
**Roles:** Ops, Finance, Procurement
**Setup:** Open `Versana_Sample_Vendor_List.xlsx`. Confirm it's formatted as a Table and AutoSave is on.

**Prompt:**
> Summarize the patterns in this vendor list. (1) Which vendors have the highest annual cost? (2) Which have the highest quality scores? (3) Are there vendors that are both expensive AND low quality — those are watch-outs. (4) Are there vendors that are both cheap AND high quality — those are bright spots. Output as a 4-section summary I can paste into a Teams channel post.

**Iteration to demo:**
> Add a 5th section: "Renewal-pending vendors and their position on the cost/quality matrix." This is the actionable list.

**Common failure mode to demo:**
- If Copilot says it can't read the data, show the audience why: data is not in a Table, or AutoSave isn't on, or the file isn't in OneDrive. Fix it live. The fix-it-live moment is the most valuable Excel teaching of the workshop.

**Why this lands:** Ops audiences immediately see what they could do with their own vendor or external-service spreadsheets.

---

## SharePoint (1 use case — really, 1 framing)

### UC-12 — "Where does Copilot find the files?"
**Roles:** Everyone
**Setup:** No demo file. Just walk through the framing.

**What to say (~2 minutes verbal):**

> *"Three things to know about how Copilot finds files. First — it can only see what your account can see. Same permissions as you. If you can't open it in OneDrive or SharePoint, Copilot can't either. Second — it works best with files that are in OneDrive or SharePoint, not files attached to emails. The single highest-leverage habit you can change as a team is moving working files into SharePoint instead of attaching them. Third — when you say 'reference the attached PRD,' Copilot looks at your Most Recently Used list first. If a file isn't on that list, open it once in the relevant app — that adds it. That's why my pre-session checklist always says 'open every demo file once before the session starts.'"*

**Question to take from the room:**
> "What kinds of files would your team want Copilot to be able to find? Where do they live now?"

This often surfaces the actual organizational change — files trapped in personal OneDrives or email attachments — that limits Copilot value across a team.

---

## Pulled-from-thin-air patterns (for when a question doesn't match anything above)

If the audience asks something off-script, fall back to the framework, write the prompt live, and iterate visibly. Two reliable shapes:

**The "translate this into that" shape:**
> Translate [input format — bullet list / transcript / customer email / spec doc] into [output format — internal memo / customer-facing release note / Teams summary / one-pager]. Use this structure: [give it a structure]. Tone: [tone]. Length: [length].

**The "review and iterate" shape:**
> I have a [doc / email / deck] I'm not happy with. Read it and tell me three things to fix — be specific, not generic. Then suggest a rewrite of the weakest section.

These two shapes cover ~80% of audience asks.

---

## Closing the second hour

Last 5 minutes:
- Ask: *"What's one prompt you'll use this week?"* Take 3–4 answers.
- Confirm the prompt sheet is in the Teams chat.
- Mention the use-case library is shared so they can come back to it.
- If hybrid delivery is planned, set the date for Part 2 and the homework (`04-hybrid-delivery-notes.md`).
