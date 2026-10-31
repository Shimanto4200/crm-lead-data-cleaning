# CRM Lead Data Cleaning Pipeline

Cleans, normalizes and deduplicates a messy lead sheet with JavaScript code nodes.

Built in n8n with Google Sheets and JavaScript (n8n Code nodes).

## Files

- `workflows/messy_crm_leads.json` — importable n8n workflow (11 nodes)

## How it works

- Reads a messy CRM lead sheet from Google Sheets
- Cleans and standardizes the data with JavaScript code nodes
- Deduplicates leads and writes back a clean sheet

## Setup

1. In n8n, go to Workflows → Import from File and import the JSON above.
2. Replace every `YOUR_...` placeholder with your own credentials and sheet IDs.
3. Connect your own Google Sheets account — no credentials are included in this repo.

> Sanitized for public sharing: credential references and personal sheet references were replaced with placeholders. The workflow logic is unchanged.

More of my work: https://hafizwork.lovable.app
