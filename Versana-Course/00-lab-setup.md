---
lab:
  title: 'Lab Setup'
  description: 'Upload resource files and configure your environment for the Versana Microsoft 365 Copilot Workshop.'
  duration: 10 minutes
  level: 100
  islab: true
---

# Lab Setup

In this workshop you will use Microsoft 365 Copilot across Outlook, Teams, Excel, and Word to practice real workflows from a Versana team's day-to-day — CS↔Product syncs, integration PRDs, daily reconciliation, vendor analysis, and sprint release notes.

Before the workshop starts, download the resource files and upload them to OneDrive so Copilot can find them when you reference them in prompts.

## Step 1: Get the Resource Files

1. Open **Microsoft Edge**.
2. Navigate to the resource bundle:

   **`https://github.com/opsgility/versana/raw/refs/heads/main/Versana-ResourceFiles/ResourceFiles.zip`**

   *(If this URL is not yet live, your facilitator will share the correct link in the Teams chat at the start of the session.)*
3. Save `ResourceFiles.zip` to your `Downloads` folder.
4. Right-click the file → **Extract All...** → Extract to your `Downloads` folder or `Desktop`.

After extraction you should see the following files:

- `Versana_Sample_PRD.docx`
- `Versana_Sample_Meeting_Transcript.docx`
- `Versana_Sample_Ops_Runbook.docx`
- `Versana_Sample_Sprint_Summary.docx`
- `Versana_Sample_Vendor_List.xlsx`
- `Versana_Company_Overview.docx`
- `Versana_Integration_Catalog.docx`
- `Versana_Customer_Activity_History.docx`
- `Versana_Customer_Business_Review_Transcript.docx`
- `Versana_Account_List.xlsx`

**Option B — Shared SharePoint folder**

If the facilitator shares a SharePoint folder instead, follow the link from the Teams chat and skip to **Step 3**.

## Step 2: Upload Files to OneDrive

1. In **Microsoft Edge**, go to `https://www.office.com`.
2. Sign in with your Microsoft 365 work account.
3. Open **OneDrive**.
4. Click **+ Add new → File upload**.
5. Select all extracted files and upload them.

> **Why OneDrive matters:** Copilot in Word, Excel, and Outlook can only reference files your account can see in OneDrive or SharePoint. Files sitting on your `Downloads` folder are invisible to Copilot.

## Step 3: Open Each File Once

Open each file in its associated Microsoft 365 app for the web (Word, Excel) just long enough for it to appear in your **Most Recently Used (MRU)** list. You don't need to read them — opening is enough.

| File | App to open it in |
|---|---|
| `Versana_Sample_PRD.docx` | Word for the web |
| `Versana_Sample_Meeting_Transcript.docx` | Word for the web |
| `Versana_Sample_Ops_Runbook.docx` | Word for the web |
| `Versana_Sample_Sprint_Summary.docx` | Word for the web |
| `Versana_Sample_Vendor_List.xlsx` | Excel for the web |
| `Versana_Company_Overview.docx` | Word for the web |
| `Versana_Integration_Catalog.docx` | Word for the web |
| `Versana_Customer_Activity_History.docx` | Word for the web |
| `Versana_Customer_Business_Review_Transcript.docx` | Word for the web |
| `Versana_Account_List.xlsx` | Excel for the web |

> **Why MRU matters:** When you say *"reference the attached PRD"* in a Copilot prompt, Copilot searches your MRU list first. Files that haven't been opened recently can fail to resolve, which makes Copilot look like it ignored your attachment.

## Step 4: Confirm Copilot Is Active

1. Open **Outlook for the web** at `https://outlook.office.com`.
2. Click **New email**.
3. In the body of the message, look for the **Copilot pencil icon**. If it appears, your account is licensed and Copilot is ready.
4. If the icon does not appear, raise your hand in the session — the facilitator will help.

## Step 5: Confirm Excel Is Ready

1. Open `Versana_Sample_Vendor_List.xlsx` in **Excel for the web**.
2. Confirm **AutoSave** is **on** (toggle in the top-left of the ribbon).
3. Click anywhere in the data range.
4. On the **Insert** tab, click **Table**. Confirm "My table has headers" and click **OK**.
5. Click the **Copilot** icon in the ribbon. If the pane opens, you are ready.

> **Why Table format matters:** Copilot in Excel cannot read raw cell ranges reliably. The single most common reason Excel demos fail is that the data isn't formatted as an Excel Table. The setup above takes 30 seconds and unblocks every Excel demo in the workshop.

## You're Done

You are now set up. The first exercise begins with the prompting framework. Keep this lab-setup page open in a side tab if you need to come back to it.

---

## Troubleshooting

| Symptom | Likely cause | Fix |
|---|---|---|
| Copilot pencil icon does not appear in Outlook | License not provisioned | Raise hand — facilitator confirms with IT |
| "I couldn't find that file" in a prompt | File not opened recently | Open the file once in its associated app; retry |
| Copilot in Excel says it cannot read the data | Data not formatted as a Table | Insert → Table; retry |
| Files uploaded but not appearing in MRU | Uploaded to OneDrive Personal, not work account | Confirm you're signed into your work account; re-upload to the correct OneDrive |

---

*Lab setup document, Versana Workshop. All resource files are fictional and intended for workshop use only.*
