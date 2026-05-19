---
lab:
  title: 'Exercise 3: Excel — Vendor Analysis (Patterns and Watch-Outs)'
  description: 'Use Copilot in Excel to surface cost and quality patterns in a vendor list, identify watch-outs and bright spots, and build a renewal-priority action plan.'
  duration: 20 minutes
  level: 100
  islab: true
  primarytopics:
    - Microsoft 365 Copilot
    - Excel
    - Vendor / cost analysis
---

# Exercise 3: Excel — Vendor Analysis (20 min)
---

In this exercise, you use Copilot in Excel to analyze a fictional vendor list. You'll surface cost-and-quality patterns, identify watch-outs (expensive AND low quality) and bright spots (cheap AND high quality), and build a renewal-priority action plan.

> [!TIP]
> Copilot in Excel only works when the data is formatted as an Excel Table. **This is the single most common reason Excel demos fail.** The setup steps below take 30 seconds and unblock everything that follows.

### Scenario

You're on a Versana operations or procurement team reviewing the company's external vendor and service spend. You have a vendor list with 13 entries across 5 service categories. Your goal is to find:

- Which vendors cost the most
- Which deliver the highest quality
- The **watch-outs** (high cost + low quality — renegotiate or replace)
- The **bright spots** (low cost + high quality — expand)
- A 30-day renewal-priority action plan

---

### Pre-flight: Set up the workbook (2 min)

1. In **Excel for the web**, open `Versana_Sample_Vendor_List.xlsx` from your OneDrive.

2. Confirm **AutoSave** is **on** (the toggle in the top-left of the ribbon should read "AutoSave On"). If it's off, click it and confirm the file is saved to OneDrive.

3. Click any cell in the data range (rows 3 onward).

4. On the **Insert** ribbon, click **Table**.

5. In the dialog, confirm:
    - The range covers `A2:K15` (or however many rows your file has)
    - **"My table has headers"** is checked
    - Click **OK**

6. Click the **Copilot** icon in the ribbon. The Copilot pane should open on the right side.

> [!NOTE]
> If the Copilot icon doesn't appear or says "Copilot can't read this data": (1) check AutoSave is on, (2) confirm the data is formatted as a Table (not just a range), (3) confirm the file is in OneDrive (not a local copy). Fix one and click Refresh.

---

### Task 1: Cost & quality scan (6 min)

1. In the Copilot pane, enter this prompt:

    ```
    Summarize the patterns in this vendor list. Which vendors have the highest annual cost? Which have the highest quality scores? Give me a 4-row summary table I can paste into Teams.
    ```

2. Read Copilot's response. It should give you:
    - Top vendors by annual cost (likely Vendor Alpha appearing multiple times)
    - Top vendors by quality score
    - A short summary table

3. Notice that Copilot returns a summary, but doesn't always create a new sheet automatically. If you want the table embedded in the workbook:

    ```
    Add the summary table as a new sheet called "Cost_Quality_Summary."
    ```

4. Click **Insert** to add the summary table to the workbook (Copilot will prompt you to confirm placement).

5. Review the new sheet. The 4-row table is paste-ready for a Teams channel post.

> [!TIP]
> **Why "give me a 4-row summary table I can paste into Teams" works:** It tells Copilot the output format AND the destination, so the structure is right the first time. Without the destination, you'd get a wall of prose.

---

### Task 2: Watch-outs and bright spots (8 min)

The most useful vendor insights are usually the corners of the cost-quality matrix:
- **Watch-outs:** expensive AND low quality (renegotiate or replace)
- **Bright spots:** cheap AND high quality (expand or standardize on)

1. In the Copilot pane, enter:

    ```
    Identify watch-outs (high annual cost AND low quality score, below 75) and bright spots (low annual cost AND high quality score, above 85). Show me the vendor name, sub-service, category, annual cost, quality score, and contract status for each. Format as two separate tables.
    ```

2. Review Copilot's response. Look for:
    - **Watch-outs** — usually Vendor Delta on the translation service (low quality, "Watch List" status) and possibly Vendor Delta on the data feed (low quality, "Renewal Pending")
    - **Bright spots** — Vendor Epsilon on reference data (cheap, high quality, "bright spot" already flagged in the notes column)

3. Iterate to make the action implications explicit:

    ```
    For each watch-out, add a recommended action: "renegotiate," "replace," or "phase out." For each bright spot, add: "expand," "standardize," or "monitor." One-word recommendations, no explanations.
    ```

4. Try one more refinement:

    ```
    Sort each table so the highest-impact action item appears first — for watch-outs, that's the highest annual cost. For bright spots, the highest quality score.
    ```

> [!NOTE]
> Copilot's first answer is often broad — every iteration sharpens the output toward something you could actually act on. The pattern is identical to the Outlook draft → iterate flow from Exercise 1.

---

### Task 3: Renewal-priority action plan (4 min)

Now you'll build a one-page renewal-priority list you could hand to a finance or procurement lead.

1. In the Copilot pane, enter:

    ```
    Build a renewal-priority action plan. Filter to only the vendors with contract status "Renewal Pending" or "Watch List." For each, recommend an action — renew, renegotiate, replace, or expand — and add a one-sentence rationale. Sort by annual cost, highest first. Format as a 4-column table: Vendor / Sub-Service / Action / Rationale.
    ```

2. Review the output. It should produce a short, actionable list (typically 3–5 rows).

3. Optionally iterate to include a target date:

    ```
    Add a target-action-by-date column. Use 30 days for any "Watch List" item, 60 days for "Renewal Pending."
    ```

4. **Add the renewal-priority table as a new sheet called "Renewal_Priorities."**

5. Save and close the workbook. The new sheets are ready for downstream use.

> [!TIP]
> **The data-to-action shape:** every Excel prompt should eventually answer "what would I do with this?" If your output is just patterns or summaries, push Copilot one more iteration toward recommendations.

---

### Hands-On Practice: Your Turn (built into timing above)

If you have time remaining, try one of these on your own:

- **Cross-category check** — `Are there service categories where we're paying multiple vendors? Surface any duplication and flag whether the secondary vendor is justified by region, redundancy, or workload split.`
- **Spend rebalancing** — `If we wanted to reduce annual spend by 10% without compromising the highest-quality vendors, which 2-3 vendors would you recommend renegotiating first?`
- **Quality-by-category** — `Which service category has the most variation in quality scores? Where would standardizing on one vendor reduce risk?`

---

### What to take with you

- **The setup is the demo's hardest part.** Once data is in a Table with AutoSave on, Copilot is reliable. Without that setup, nothing works.
- **Push toward action.** Patterns are interesting; recommendations are useful. Add "what would I do" to every prompt.
- **Output format matters.** Telling Copilot "format as a 4-column table" produces something paste-ready; without it, you get prose.
- **New sheets.** Use "Add as a new sheet" to keep Copilot's outputs in the workbook for later reference — don't just paste-and-close.

Continue to **Exercise 4: Teams** when you're ready.
