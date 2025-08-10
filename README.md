# Zapier Workflows
Reusable Zapier automations for marketers, resellers, content creators, and ops teams. Each workflow includes a JSON export (when available), setup notes, and optional screenshots.

## 🔄 How to Use

### Option A: Import a JSON export (Team/Enterprise)
1) Download the `zap.json` from a workflow folder.
2) In Zapier, go to **Settings → Security & data → Data management** and use **Import** to bring Zaps into your account. (Import/export is available on Team/Enterprise.) :contentReference[oaicite:0]{index=0}

> Zapier exports a single `Zapfile.json` that contains your undeleted Zaps’ step inputs/outputs. This repo stores one-Zap JSONs for clarity. :contentReference[oaicite:1]{index=1}

### Option B: Use a Template link (All plans)
If a folder includes a **Template link** in its README, click it to create the Zap directly in your account—no import needed. :contentReference[oaicite:2]{index=2}

> If you don’t have import/export, templates are the easiest way to share Zaps across accounts. :contentReference[oaicite:3]{index=3}

---

## 📁 Repo Layout
- `zaps/<category>/<workflow-slug>/` – Each workflow with `zap.json` and a focused README.
- `templates/` – Contribution templates (`zap.sample.json`, README template).
- `meta/TAGS.md` – Common tags to keep searchability consistent.

## 🏷️ Tags
`#zapier #automation #nocode #marketing #contentops #webhooks #googleapi #slack #sheets #crm`

## 🤝 Contributing
1) Add your workflow in an appropriate category folder.
2) Include a `README.md` (use the template in `/templates`).
3) Include `zap.json` (if you can export) or a **Template link**.
4) Add any screenshots to `assets/`.
5) Open a PR.

Curated by **Andrew Luxem** · [andrewluxem.com](https://www.andrewluxem.com)
