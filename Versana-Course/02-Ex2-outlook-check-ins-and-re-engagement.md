---
lab:
  title: 'Exercise 2: Outlook — Check-ins, Warm Intros, and Re-engagement'
  description: 'Use Copilot in Outlook for periodic stakeholder maintenance — check-ins that aren''t "just checking in," warm intros across teams, and re-engagement of relationships that have gone quiet. Uses the Versana customer activity history as context.'
  duration: 20 minutes
  level: 100
  islab: true
  primarytopics:
    - Microsoft 365 Copilot
    - Outlook
    - Stakeholder and customer maintenance
---

# Exercise 2: Outlook — Check-ins, Warm Intros, and Re-engagement (20 min)
---

Exercise 1 covered the "I have a thing to send today" pattern. This exercise covers the harder one: the email you've been meaning to send for weeks but keep putting off because the situation is awkward — the customer who's gone quiet, the stakeholder you haven't talked to in three months, the new contact at a partner team you should have introduced yourself to.

The patterns translate cleanly across roles:

- **Customer Success** — checking in with a customer who's gone silent; re-engaging an at-risk account
- **Product** — periodic outreach to a partner team about a long-running initiative; warm intros between engineering groups
- **Operations** — re-engaging a vendor or partner contact; introducing yourself to a new partner-system contact
- **Exec Assistants** — relationship maintenance on an exec's behalf; warm intros between two teams

> [!TIP]
> The framework — **Goal, Context, Sources, Expectations** — is even more important for these "soft" emails. Generic outreach is what causes "just checking in" emails. Specific, grounded outreach is what gets a reply.

### Scenario

You're on a Versana team and you have three relationship-maintenance emails you've been putting off:

- A **check-in** to Belmont Trust Services. Stable customer, good relationship, but you haven't talked to them in three months and don't want the next contact to be "just checking in."
- A **warm intro** between a new Versana CS contact and Marie Chen at Cresswell. You've worked with Marie for years and want the handoff to feel natural, not transactional.
- A **re-engagement** to Ellesmere Funds. Their usage has dropped 60% in six months. The COO has gone silent. You need to reach out without sounding desperate or like you're chasing.

---

### Pre-flight: have the activity history open

Before starting, open `Versana_Customer_Activity_History.docx` in Word for the web. You don't need to read it — opening it adds it to your Most Recently Used list so Copilot can find it when you reference it in the prompts below.

---

### Task 1: Check-in that isn't "just checking in" (7 min)

You haven't talked to Belmont Trust Services in three months. The relationship is good and you want to keep it that way — but a generic "circling back" email is forgettable.

1. In **Outlook on the web**, click **New email**.

2. Open **Draft with Copilot** (the pencil icon in the message body).

3. Attach `Versana_Customer_Activity_History.docx`.

4. Enter:

    ```
    Draft a check-in email to Marcus Chen, Senior Director of Operations at Belmont Trust Services. I haven't talked to them in 3 months. Reference the attached activity history — Belmont is a stable Type A customer, and they've expressed interest in Type B once it ships. Lead with a specific insight, not a generic greeting. The insight should be something I'd know from the activity history — for example, that their team has been the most consistent user of the discrepancy dashboard, or that their volume has been stable through Q1. Offer one concrete next step — a 20-minute call to walk them through the Type B GA timeline. Under 120 words. Tone: warm, peer-level, not transactional.
    ```

5. Review the draft. Check:
    - Does the opening reference something specific from the activity history (not "I hope you're doing well")?
    - Is the next-step ask concrete (a 20-minute call) or vague ("let's catch up")?

6. Iterate:

    ```
    The opening is still a little generic. Rewrite it to lead with a single specific observation — for example, that Belmont's volume has held steady through Q1 while many comparable customers have fluctuated. Make it sound like I actually pay attention.
    ```

7. Try a tone refinement:

    ```
    Make the next-step ask more confident. Instead of "if it works for you," propose two specific time windows and let them pick.
    ```

8. **Keep it** when satisfied.

> [!TIP]
> **The "lead with an insight" pattern:** every check-in email should open with something you know that the recipient would expect you to know. If you can't think of one, you don't have enough context to send the email yet — go gather it first.

---

### Task 2: Warm intro between teams (7 min)

A new colleague is taking over the day-to-day relationship with Cresswell Asset Management (your largest customer and Type B design partner). You want to introduce them to Marie Chen, Cresswell's Senior Operations Manager, in a way that feels natural — not like a transactional handoff.

1. In **Outlook on the web**, create a new email.

2. Open **Draft with Copilot** and attach `Versana_Customer_Activity_History.docx`.

3. Enter:

    ```
    Draft a warm intro email to Marie Chen at Cresswell Asset Management. The intro is for my colleague Jordan Reyes, who is taking over as the primary day-to-day Versana CS contact for Cresswell. Reference the attached customer activity history — Cresswell is our largest customer, has been a Type B design partner since Q3 2025, and Marie's team has been the heaviest user of the discrepancy dashboard. The email should: (1) acknowledge the strength of the existing relationship with Marie, (2) introduce Jordan with one or two specific details that establish credibility (e.g., Jordan's background working with other top-tier Type B pilot customers), (3) make clear that I'm staying involved at the strategic level — this is not me leaving, this is Jordan joining. Tone: collegial, not formal. Under 130 words.
    ```

4. Review the draft. Check:
    - Does it acknowledge Marie specifically rather than addressing her as a generic contact?
    - Is the handoff framed as "Jordan joining" rather than "I'm leaving"?
    - Is Jordan introduced with specifics, not adjectives ("strong communicator" is filler; "previously led the integration onboarding for two Type B pilot customers" is real)?

5. Iterate:

    ```
    Add one sentence that proposes a specific first interaction — maybe a brief 30-minute introductory call where Marie can walk Jordan through Cresswell's priorities for the next quarter. That gives Marie a clear next step.
    ```

6. Try a refinement to remove filler:

    ```
    Drop any adjectives I haven't earned. Don't call Jordan "experienced" or "trusted" — say what Jordan has actually done.
    ```

7. **Keep it** when satisfied.

> [!NOTE]
> Warm intros are one of the highest-leverage uses of Copilot because most people don't write them well — they default to "I'd like to introduce..." form letters. The framework here forces you to make a real introduction.

---

### Task 3: Re-engagement of a quiet account (6 min)

Ellesmere Funds has gone quiet. Usage dropped 60% in six months. Their Director of Operations left in Q4. The COO, Carolyn Foster, has not responded to your last two check-ins. You need to reach out one more time — without sounding desperate or like you're chasing.

This is the email most people get wrong. The instinct is either to apologize too much or to lead with feature news. Neither works.

1. In **Outlook on the web**, create a new email.

2. Open **Draft with Copilot** and attach `Versana_Customer_Activity_History.docx`.

3. Enter:

    ```
    Draft a re-engagement email to Carolyn Foster, COO of Ellesmere Funds. The attached activity history shows their usage has dropped 60% in 6 months, their Director of Operations left in Q4 2025, and Carolyn has not responded to my last two check-ins. The Q4 escalation experience (a high-severity discrepancy that took 3 business days to resolve due to partner-side issues) was likely a factor. The cross-side escalation flow that we're spiking in Sprint 48 directly addresses what went wrong in Q4. Draft the email to: (1) acknowledge the silence without being weird about it, (2) lead with the specific product change that addresses what they actually experienced — not a generic feature update, (3) propose a low-commitment next step — a 20-minute call where I walk them through what's shipping and how it would have changed the Q4 outcome. Under 130 words. Tone: confident, accountable, not apologetic.
    ```

4. Review the draft. Check for the three most common failure modes:
    - **Too apologetic.** Phrases like "sorry for the radio silence" or "apologies for missing you." Cut them.
    - **Generic feature pitch.** If the email reads like a release-note announcement, it's wrong. The customer needs to see how the change addresses what they experienced specifically.
    - **Vague next step.** "Let's catch up" or "let me know if you're interested" — both forgettable. The ask should be concrete.

5. Iterate to fix the most common weakness:

    ```
    The opening still sounds apologetic. Rewrite it to acknowledge the gap as a fact without making it about me. The Q4 escalation was real and the customer experience was poor — own that directly without sounding sorry for myself.
    ```

6. Try one more iteration to make the next step specific:

    ```
    Instead of "a 20-minute call," propose two specific time windows next week. Add one specific topic you'd cover in the call beyond just the escalation flow — for example, the Type B GA timeline now that the pilot is expanding.
    ```

7. **Keep it** when satisfied.

> [!TIP]
> **Re-engagement emails fail when they prioritize the writer's comfort over the reader's experience.** The temptation to soften, hedge, or apologize is about reducing your own discomfort. Read the email from the recipient's point of view: did you tell them something specific they care about? Did you give them a clear way to respond? If yes to both, send it.

---

### Hands-On Practice: Your Turn (built into timing above)

Pick one real relationship from your own work that's gone quiet or needs a check-in:

- A customer or partner you haven't talked to in 2+ months
- A stakeholder on a long-running internal initiative
- A new contact at a team you should have introduced yourself to
- A vendor or partner contact who has gone silent

Use the same pattern: attach a relevant file (even if it's just your own notes), lead with something specific, propose a concrete next step, iterate to drop filler.

---

### What to take with you

- **Lead with an insight, not a greeting.** If you can't open with something specific, you don't have enough context — gather it first.
- **Warm intros are a separate genre.** Frame them as "X joining," not "I'm handing off." Make the new person earn their introduction with specifics, not adjectives.
- **Re-engagement emails fail when they're about your comfort.** The temptation to apologize, hedge, or soften is about reducing your own awkwardness, not the reader's experience.
- **Concrete next steps.** "Let's catch up" is forgettable. "Two specific time windows next week, here's what I'd cover" is action-forward.

Continue to **Exercise 3: Excel** when you're ready.
