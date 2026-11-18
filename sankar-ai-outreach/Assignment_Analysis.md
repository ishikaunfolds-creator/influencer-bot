# Assignment analysis and delivery coverage

## What the assignment asks for

The brief's objective is an AI-assisted influencer outreach workflow with these stages:

1. Find relevant Instagram creators using niche, keywords, location, and follower range; record public profile details and business contacts.
2. Filter and rank leads, summarize profile fit, and prioritize prospects.
3. Save leads in Google Sheets or a CRM, prevent duplicates, and track outreach statuses.
4. Draft personalized Gmail outreach with brand context, a collaboration opportunity, a reason for selection, a clear next step, sender identification, and opt-out language. Require human approval before the initial campaign send.
5. Track initial sends, send the first follow-up after 3–5 days and an optional second after another 5–7 days, and stop after a response, decline, or opt-out.
6. Classify incoming replies, draft a response, recommend a next action, and update the CRM. Require a human to approve AI-generated replies before sending.

The evaluation rubric assigns 20% each to Instagram research, AI personalization, Gmail and follow-ups, reply management, and end-to-end demonstration. The submission checklist also asks for a working demo, screen recording, source/workflow export, test CRM records, sample initial/follow-up/reply emails, and a short tool explanation. It says a static presentation is insufficient.

## What this package demonstrates

The local app gives a reviewer an interactive end-to-end run using synthetic records: add or import prospects, detect duplicate handles/emails, rank by visible scoring rules, create and edit drafts, require approval before logging a send, calculate follow-up due dates, add/classify replies, suppress opt-outs, and update statuses. A CSV provides CRM sample records for Google Sheets or another CRM import. The workflow JSON and email examples document the logic and sample content.

## What remains before a live submission

This is a working local demo with synthetic test data. It does not connect to Instagram, Claude, Gmail, or a Google account. The score, text generation, and reply classification are deterministic demo logic rather than a Claude integration. Demo send actions are locally logged only. The package does not contain the requested screen-recording file; `Demo_Walkthrough.md` is provided as a recording script.

To demonstrate the real services named in the brief, an authorized research source, a secured Claude API connection, a Gmail account with approved OAuth access, and a Google Sheet or CRM destination must be supplied and configured. The live version should retain human approval, sender limits, duplicate prevention, reply/opt-out stop rules, and auditable logs.
