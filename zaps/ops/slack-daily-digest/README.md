# Slack Daily Digest

**Category:** ops  
**Summary:** Send a daily Slack message with a digest of new rows in a Google Sheet.  
**Apps:** Google Sheets → Slack  
**Tags:** #zapier #slack #sheets #digest #ops

## 🧰 What this Zap does
- Triggers daily at a set time.
- Searches Google Sheets for rows added in the last 24 hours.
- Formats a digest message.
- Sends the digest to a Slack channel.

## 📦 Requirements
- Google account with Sheets access
- Slack workspace with access to the target channel
- Sheet with relevant columns for the digest

## ⚙️ Setup
1. Create your digest Sheet and note the columns to include.
2. Connect Google Sheets and Slack in Zapier.
3. **Template link:** <paste-template-url>  
   **or** import `zap.json` (Team/Enterprise import).
4. Set the Schedule step to your desired time.
5. Map Sheet data to the Slack message.

## 🧪 Test data
| Task                | Owner   | Due Date   |
|---------------------|---------|------------|
| Approve budget plan | Alex    | 2025-08-15 |

## 🛠 Troubleshooting
- Ensure the Schedule trigger timezone matches your Slack workspace time.
- For large digests, Slack may truncate messages — use a file upload step if needed.
