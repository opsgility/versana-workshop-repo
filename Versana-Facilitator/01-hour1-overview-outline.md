# Hour 1 — Overview & Follow-Along Outline

A 60-minute follow-along walkthrough. Build the actual deck from this outline, or use it as a script. Every slide has speaker notes and live demo cues. Demos are run in real time on the facilitator's screen; attendees follow along on their own machines.

> **Read first:** Hour 1 has one job — get every attendee to write and iterate on at least one prompt of their own. Quick-win demos are scaffolding around that goal, not the goal itself.

---

## Slide 1 — Title (1 min)

**Title:** Microsoft 365 Copilot — A Working Hour
**Subtitle:** Two hours, one goal: leave with a prompt you used today and will use again tomorrow.

**Speaker notes (~45 sec):**
> "Two hours total. The first hour we'll walk through the framework and demo a few quick wins. Bring up Outlook and Teams now — you'll be following along, not just watching. The second hour is yours: bring questions, share your screen, and we'll work through them live."

---

## Slide 2 — What this is, and what it isn't (2 min)

**Three bullets, no more:**
- This is **M365 Copilot** — the Copilot inside Outlook, Teams, Word, Excel, PowerPoint, and SharePoint
- It is **not** GitHub Copilot, Copilot Chat (the free web tier), or any internal LLM tooling — same instincts, different surface
- The goal of the session is fluency in **the prompting loop**, not memorizing tricks

**Speaker notes (~60 sec):**
> "Quick clarification because Versana has a lot of Copilots floating around. GitHub Copilot — that's the one that's already changed how about fifty people here write code. Today is the *other* Copilot — the one that drafts your emails, summarizes your meetings, and helps you turn a Word doc into a deck. Same family, different tool. If you're a developer in the room, the prompting habits transfer."

**Data-handling reminder (callout — read it out loud):**
> "Everything we demo today uses fictional data. Before you point Copilot at real customer, partner, or employee data, confirm Versana's data-handling guidance. Same rule applies as anywhere else: if you wouldn't send it to an external vendor, think twice before pasting it into a prompt."

---

## Slide 3 — The prompting framework (4 min)

**Title:** Goal → Context → Sources → Expectations
**Visual:** Four boxes, left to right.

| Element | What it answers | Example |
|---|---|---|
| **Goal** | What do I want? | "Draft a follow-up email after our call" |
| **Context** | What does Copilot need to know? | "I'm in product. The call was with our customer success team about a feature request from a top-three customer." |
| **Sources** | What should it look at? | "Reference the meeting transcript and the linked PRD" |
| **Expectations** | How do I want the output? | "Under 150 words, professional tone, ends with a clear next step." |

**Speaker notes (~3 min):**
> "If you remember one thing from this hour, remember these four. Most bad Copilot output is bad because the prompt was Goal-only. 'Write me an email.' That's how you get something that sounds like everyone else's email. Add Context — say who you are and what the situation is. Add Sources — point at the file, the meeting, the thread. Add Expectations — tell it length, tone, format. Watch what happens."

**Live demo cue (Outlook, ~90 sec):**
- Open Outlook on the web
- New email
- Click the Copilot pencil icon
- **First prompt** (intentionally bad): *"Write a follow-up email after our meeting."* → show the generic output
- **Second prompt** (using the framework): *"I'm a product manager at a fintech platform. After today's call with our customer success team, draft a follow-up to the team that captures the feature request from one of our top-three customers, names the next step (a discovery session in two weeks), and asks for any additional context they have. Under 150 words, professional tone, no exclamation points."*
- Side-by-side, the difference is the lecture

---

## Slide 4 — Demo 1: Outlook — Draft, then iterate (8 min)

**Title:** Outlook — get from blank to "good enough" in two iterations

**Live demo (~6 min):**
- Continue from slide 3 demo or start fresh
- Show **three iteration moves**:
    1. *"Make the opening more specific — name the customer's industry, not the customer."*
    2. *"Tighten the call to action. Right now it's three sentences; I want one."*
    3. *Use the **Change Tone** action* — try Direct, then Professional. Show that "Casual" is usually too casual for internal product comms; "Direct" usually lands.
- End with **Keep it** to insert into the email body

**Speaker notes (~2 min):**
> "Two things to notice. First — I never tried to write the perfect prompt up front. I let Copilot give me something, and I told it what to fix. That's the loop. Second — the output is *my* draft, not Copilot's. I'm going to read it before I send it. Always. Copilot is a junior teammate, not an editor."

**Follow-along ask:**
> "On your machine, open Outlook, hit New, click the Copilot pencil, and write a prompt for an email *you actually need to send today*. Don't pick a fake task. Pick something real. I'll give you 90 seconds, then we'll move on."

⏱ **90-second silent practice block** — this is the most important moment of the whole hour.

---

## Slide 5 — Demo 2: Teams — Meeting prep + summary (8 min)

**Title:** Teams — walk in prepared, walk out with a summary

**Live demo (~6 min):**
- Open Teams Copilot pane (left nav)
- **Prep prompt:** *"I have a meeting in 30 minutes with our customer success team about a feature request from a top-three customer. I haven't reviewed the PRD or the previous call notes. Can you build me a quick prep sheet with: (1) what we know about the request, (2) three discovery questions I should ask, and (3) one risk I should flag?"* — attach a file from `Versana-ResourceFiles/` (e.g., the sample PRD)
- **Summary prompt** (after a fictional meeting, using the sample transcript): *"Summarize this meeting transcript. Pull out: decisions made, action items with owners, open questions, and a 2-sentence summary I can paste into the customer success channel."*
- Show that the structured output is paste-ready for a Teams channel post

**Role callouts (verbal, ~30 sec):**
- **Exec assistants** — this is your daily workflow. Prep sheets before; summaries after. The prep sheet alone saves 15 minutes per meeting.
- **Product** — use the summary prompt after every customer call. Paste into the customer record (or whichever system you use).
- **Ops** — use Copilot for incident retros. Same summary prompt; different transcript.

**Follow-along ask:**
> "If you have a Teams meeting recording from this week, open it now and ask Copilot to summarize it. If you don't, take any thread in Teams that's gotten long, ask Copilot to summarize the thread, and see what it pulls out."

⏱ **60-second silent practice block.**

---

## Slide 6 — Demo 3: Word — Draft, then revise (8 min)

**Title:** Word — Copilot is best as a first-draft engine

**Live demo (~6 min):**
- Open a blank Word document on the web
- **First-draft prompt:** *"Draft an internal product memo, ~one page, for our exec team. Topic: a proposal to expand our integration coverage to two new categories of partner systems next quarter. Use the framework: problem, options, recommendation, next step. Reference the attached product spec."* — attach the sample PRD from `Versana-ResourceFiles/`
- Show the draft
- **Revise live:** *"The 'options' section is generic. Make each option specific to the integration categories — name a clear example of what we'd build for each, and one risk for each."*
- Use the **Rewrite** action on a single paragraph to demonstrate selective revision (highlight a paragraph → Copilot icon → Rewrite)

**Speaker notes (~2 min):**
> "Two patterns to notice. First — I drafted the whole memo in 30 seconds, then spent two minutes revising. That's the right ratio. Don't try to make Copilot write the perfect thing. Get a draft on the page, then make it yours. Second — the **Rewrite** action lets you target one paragraph at a time. Don't rewrite the whole document if you only want to fix one section."

**Role callout:**
- **Product** — PRDs, release notes, internal memos. This is your home base.
- **Customer success / sales** — proposal drafts, customer-facing one-pagers. Same pattern.

---

## Slide 7 — Demo 4: PowerPoint — Outline first, slides second (6 min)

**Title:** PowerPoint — write the outline, then generate the deck

**Live demo (~5 min):**
- Open Word — yes, Word — and ask Copilot: *"Outline a 6-slide internal exec deck on the same proposal we drafted in the memo. Each slide should have a title and 3–5 bullet points. Slide 1 = problem, Slide 2 = current state, Slide 3 = options, Slide 4 = recommendation, Slide 5 = risks, Slide 6 = next step."*
- Copy the outline
- Open PowerPoint, blank deck, **Copilot → Create presentation from outline** (or paste the outline into Copilot's chat in PowerPoint and ask for a deck)
- Show the deck
- Iterate: *"Replace the title slide background with a darker theme. Make slide 4 (recommendation) the most visually emphasized."*

**Speaker notes (~1 min):**
> "Two-step beats one-step. If you ask Copilot 'make me a deck about X' from scratch, you get something generic. If you write the outline first — even with Copilot's help — and *then* turn it into a deck, the slides actually say what you want them to say."

**Role callout:**
- **Product** — quarterly review decks, roadmap decks. This pattern saves an entire afternoon.
- **Exec assistants** — first-draft decks for an exec, then they revise. Same pattern.

---

## Slide 8 — Light touch: Excel + SharePoint (6 min)

**Title:** Two more places Copilot earns its keep

**Excel (live demo, ~3 min):**
- Open `Versana_Sample_Vendor_List.xlsx` (built from `Versana-ResourceFiles/`)
- Format as a Table (`Insert → Table`), AutoSave on
- Open Copilot in the ribbon
- **Prompt:** *"Summarize the patterns in this vendor list. Which vendors are most expensive per unit? Which have the highest quality scores? Are there vendors that are both expensive AND low quality — those are watch-outs. Give me a 4-row summary table I can paste into Teams."*

> Tell the room: "Excel needs the data formatted as a Table for Copilot to read it. That's the single most common reason Excel demos fail. AutoSave on, file in OneDrive, data in a Table."

**SharePoint (no demo, just a 90-second framing):**
> "SharePoint isn't a place you 'use' Copilot. It's the place Copilot looks for files. When I attach a file in Outlook or Word and say 'reference the attached PRD,' Copilot is searching across what your account can see in OneDrive and SharePoint. The implication: the more your team's working files live in SharePoint instead of email attachments, the more useful Copilot is to all of you. If you have to remember one habit from today: stop sending email attachments. Send links to SharePoint files."

**Why this slide is short:** Excel and SharePoint each deserve their own session for ops and platform teams. We'll cover them deeper in the use-case library during hour 2 if anyone asks.

---

## Slide 9 — Three habits to leave with (3 min)

**Title:** What to do tomorrow

1. **Use the framework on every prompt.** Goal → Context → Sources → Expectations. Even just naming them silently as you write the prompt.
2. **Iterate, don't perfect.** First prompt rough, second prompt better, third prompt sent.
3. **Move your working files to SharePoint.** Copilot is only as good as what it can see.

**Speaker notes (~2 min):**
> "Three habits, not seven. Pick one to start with this week. The framework is the highest-leverage one — it works for every Copilot, in every app, forever. Iteration is second — the people who get the most out of Copilot are the people who least often try to write a perfect prompt. SharePoint is third, but it's the one with the biggest organizational payoff: your whole team gets better Copilot results when files live in shared OneDrive / SharePoint instead of email attachments."

---

## Slide 10 — Hour 2 setup (3 min)

**Title:** Hour 2 — Bring your real work

**Bullet list:**
- Drop questions in the Teams chat right now while it's fresh
- Anyone who wants to share their screen and work on something live, raise a hand
- The take-home prompt sheet is being posted in the chat now
- Stay or drop — hour 2 is opt-in for those who want hands-on time

**Speaker notes (~2 min):**
> "We'll take a 5-minute break, then come back at the top of the hour. Bring something real — an email you owe someone, a deck you're stuck on, a meeting you need to summarize. We'll work it together. If you have to drop, that's fine — the prompt sheet has the patterns we covered today, and the use-case library has more depth on each app."

⏱ **Drop the take-home prompt sheet (`03-take-home-prompt-sheet.md` content) in the Teams chat NOW.**

⏱ **5-minute break before hour 2.**

---

## Live demo cue cheat sheet (for the facilitator's monitor)

| Demo | App | Sample file from `Versana-ResourceFiles/` | Backup if Copilot fails |
|---|---|---|---|
| Outlook draft + iterate | Outlook web | None required | Use any sent email as context — "reply to this in a more direct tone" |
| Teams meeting prep | Teams | Sample PRD | Open any past meeting in Teams; ask Copilot to summarize it |
| Teams meeting summary | Teams | Sample meeting transcript | Same backup |
| Word memo | Word web | Sample PRD | Skip the file attach; just describe the topic in the prompt |
| PowerPoint from outline | Word + PowerPoint web | Outline produced live | Use a hardcoded outline if Word demo went sideways |
| Excel vendor table | Excel web | Sample vendor list | Pre-formatted as Table; if Copilot doesn't appear, screen-share the use-case library walkthrough |

> **Single biggest failure mode:** demo file isn't in OneDrive, or isn't on the facilitator's MRU list. Open every demo file in its app for the web *before* the session starts.
