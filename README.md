# Webinar → Content Pack (48h) — Implementation Package

This package includes:
- `index.html` — Landing page (Replit‑ready). Set your Calendly + AP Webhook in the <script> block.
- `activepieces/flow_webinar_to_assets.json` — **ActivePieces** flow blueprint with placeholders.
- `notion_templates/Leads.csv`, `Clients.csv`, `Deliverables.csv` — **Notion** database seeds.
- `notion_templates/Deliverables_Template.md` — the per‑item checklist template for Notion.
- `SLACK_messages.txt` — copy/paste Slack messages for #leads and #delivery.

## Quick Start (10–15 minutes)
1) **Notion** → Import each CSV as a Database (Leads, Clients, Deliverables). Add relations per the playbook.
2) **ActivePieces** → Import the flow JSON, create connections, replace placeholders, publish. Copy the Webhook URL.
3) **Replit** → Create HTML repl, upload `index.html`. In the <script>, set:
   - `WEBHOOK` = your AP webhook URL
   - Calendly URL = your Calendly link
4) **Slack** → Create `#leads` and `#delivery` (and optional `#ops-alerts`) and generate webhooks. Paste into AP.
5) **Instantly** (optional for v1) → Create lists (Hand Raisers, Nurture) and paste IDs/API key into AP HTTP steps.

Generated: 2025-09-20T19:18:26
