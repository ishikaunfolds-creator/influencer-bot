# Sankar Group influencer outreach demo

This package turns the internship assignment into a browser-based workflow demo, a Google Sheets–importable CRM CSV, a workflow export, synthetic test records, and sample outreach copy.

## Open the demo

Open `app/index.html` in a recent desktop or mobile browser. It runs locally and does not need an install, account, server, or internet connection. The first view loads eight synthetic test prospects. Changes are saved in that browser's local storage.

Use **Campaign setup** to adjust the brand, audience criteria, and offer. Use **Prospects** to add a public-profile record or import a CSV. Review a prospect to edit the record, inspect the fit score, and edit the message drafts. The review checkbox is required before the app logs a demo send. Use **Replies** to add a synthetic response, see its local keyword classification, and stop follow-ups.

Use **Export CSV** to download the browser's current records. Upload `CRM_import.csv` to Google Sheets or import it from the app. This package does not create a live Google Sheet in an account.

## Included files

- `app/index.html` - complete local demo app and source.
- `CRM_import.csv` - synthetic records for Google Sheets, Excel, or app import.
- `workflow_export.json` - workflow steps, scoring, review gates, and stop rules.
- `Sample_Email_Examples.md` - initial email, two follow-ups, reply drafts, and opt-out behavior.
- `Assignment_Analysis.md` - assignment requirements, rubric, and delivery coverage.
- `Demo_Walkthrough.md` - short recording script for the requested screen-capture demo.

## Demo boundary

The app is functional with synthetic test data, but the email and AI steps are simulated. Its fit score and reply classification are transparent local rules; message drafts are template-based. A demo send only records a reviewed action locally. It does not contact a creator, read Gmail, call Claude, scrape Instagram, or sync with Google Sheets. This avoids implying authorization or making real outreach from test records.

To turn this into a live workflow, connect authorized services and replace the demo actions with approved integrations. Use a permitted source for public profile research, a securely stored AI credential, and OAuth for a monitored Gmail account. Keep the human review gate before the initial campaign and generated replies, enforce sending limits and suppression, and retain an audit log. The supplied app does not contain live credentials or a backend.

## Assignment submission items

The working local demo, source, workflow export, synthetic CRM records, sample email copy, tool explanation, and a recording walkthrough are included. The requested screen-recorded video itself is not included. Record the walkthrough after opening the app; the demo script lists the clicks and visible outcomes. A live service demonstration needs authorized test accounts and credentials.

## Sample data

All creator names, Instagram handles, business emails, bios, replies, and activity dates in the included data are fictional fixtures. The `example.com` addresses are placeholders. Do not send to them.
