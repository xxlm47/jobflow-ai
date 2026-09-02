# JobFlow AI

**Your automated secretary in your pocket.**

JobFlow is a mobile-first operating assistant for solo service businesses: lawn care, plumbing, roofing, detailing, pressure washing, fencing, painting, cleaning, HVAC, handyman work, and more.

## Product principle

> You work. JobFlow handles the office.

It turns a messy stream of leads, messages, quotes and follow-ups into a single next-action queue.

## MVP features

- Today screen with next actions and Money Radar
- Universal customer/job model across trades
- Lead scoring and observable opportunity signals
- CSV import with deduplication and suppression checks
- Customer conversation history
- AI-style response drafting and negotiation guidance
- Approval gate for price/scope/refund/contract commitments
- Follow-up scheduling that stops when the customer replies
- Pipeline: New → Contacted → Replied → Qualified → Quote Sent → Negotiating → Won/Lost
- Business Brain settings
- Internal notes and activity history
- Lightweight SQLite database
- FastAPI backend and phone-friendly frontend

## Run on Android / Termux

```bash
pkg update
pkg install python
pip install -r requirements.txt
python -m uvicorn app.main:app --host 0.0.0.0 --port 8000
```

Open `http://127.0.0.1:8000` in your Android browser.

## Product direction

JobFlow is designed to become an AI office manager: capture opportunities, qualify customers, draft responses, schedule follow-ups, help negotiate within owner-defined rules, remember customer preferences, surface unpaid work, and tell the owner the single most important next action.

## Safety

JobFlow is designed for legitimate customer communication and authorized lead sources. It does not implement credential harvesting, synthetic identities, fingerprint/proxy evasion, or deceptive impersonation.

## Status

Mobile-first MVP / active development.
