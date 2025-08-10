# Contributing

## What to contribute
- New Zaps with clear business value.
- Variants of existing Zaps (different apps, improved mappings).
- Docs improvements and troubleshooting notes.

## Folder format
zaps/<category>/<workflow-slug>/
├─ zap.json # If available (Team/Enterprise export)
├─ README.md # Use the template in /templates
└─ assets/ # Screenshots / diagrams (optional)

## Exports & templates
- **JSON Import/Export:** Only on Team/Enterprise. Put the single-Zap JSON in `zap.json` (or name it `Zapfile.json` if you exported a bundle). :contentReference[oaicite:4]{index=4}
- **Template Links:** If you can’t export JSON, include a Zap **Share Template** link in the workflow README. :contentReference[oaicite:5]{index=5}

## Style guidelines
- Use clear, descriptive slugs (`gmail-new-subscriber-welcome`).
- Keep secrets out of JSON and screenshots.
- Add **Prereqs**, **Setup**, **Testing**, and **Cost/Rate Limit Notes**.

Thanks for contributing!
