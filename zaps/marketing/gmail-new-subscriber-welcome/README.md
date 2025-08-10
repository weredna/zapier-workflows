# Gmail: New Subscriber Welcome

**Category:** marketing  
**Summary:** Send a personalized welcome email when a new subscriber hits your Google Sheet.  
**Apps:** Google Sheets → Gmail  
**Tags:** #zapier #gmail #sheets #welcome

## 🧰 What this Zap does
- Triggers on **New Spreadsheet Row** in a “Subscribers” sheet.
- Sends a **Gmail** email using mapped fields.

## 📦 Requirements
- Google account with Sheets + Gmail
- A Sheet named `Subscribers` with columns: `Email`, `FirstName`

## ⚙️ Setup
1) Create the Sheet and columns.
2) **Template link:** <paste-if-available> :contentReference[oaicite:9]{index=9}  
   **or** import the JSON from `./zap.json` (Team/Enterprise). :contentReference[oaicite:10]{index=10}
3) Map `to`, `subject`, and `body` using row fields.
4) Turn on the Zap and add a test row.

## 🧪 Test data & mapping
- `Email`: user@example.com
- `FirstName`: Jamie

## 🛠 Troubleshooting
- If the trigger doesn’t find rows, reselect the spreadsheet and worksheet.
- Gmail sending limits may apply.
