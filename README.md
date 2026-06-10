# PCC Coaching Client Onboarding Kit

The standard set of materials for welcoming a new coaching client to the Ascend Executive Coaching Program. It sets the tone, makes expectations clear, and gets the client thinking about what they want from the work before the first session.

## What's in here

| File | What it is | Audience |
|------|------------|----------|
| `index.html` | Landing page that links to everything below. The homepage when served via GitHub Pages. | Client |
| `PCC_Ascend_Pre_Coaching_Survey.html` | The pre-coaching survey. Fillable in the browser with a save-to-PDF button. 8 questions, four of them multiple choice. | Client |
| `PCC_Coaching_Agreement_2026_06_10.pdf` | The coaching agreement: scheduling, session length, fees and invoicing, confidentiality, recording, and cancellations. | Client |
| `Welcome_Email_New_Coaching_Client.md` | The welcome email template sent to new clients. | Coach |

## How to use it

**Sending to a client directly.** Email the welcome note, attach the agreement PDF, and either attach the survey HTML or send the link (see below). The survey opens in any browser, the client types their answers, then clicks **Save as PDF / Print** to send a completed copy back.

**Hosting the survey online (optional).** This repo is ready for GitHub Pages. Once enabled, `index.html` becomes the homepage and links through to the survey and agreement. To turn it on:

1. Push this repo to GitHub.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set the source to the `main` branch, root folder.
4. Save. Your site will be live at `https://<username>.github.io/<repo>/` within a minute or two.

## Before you send

A couple of placeholders need filling in each time:

- **Calendly link** — replace `[Calendly link]` in both the welcome email and the agreement.
- **Client name** — add the client's first name at the top of the welcome email.

## The survey at a glance

Four parts, kept short on purpose:

1. **The Goal** — the result they want and how they want to change (open text).
2. **The Fuel** — core values and the end-state they're after (multiple choice), plus the desire they haven't given themselves permission to chase (open text).
3. **The Barriers** — common patterns to tick, plus the hard truth a trusted advisor would name (open text).
4. **The Partnership** — how they want to be challenged and held accountable (multiple choice, with room to add).

The multiple-choice questions all include an "add your own" field so nobody is boxed in.

## A note on confidentiality

These are confidential client materials. If you host them on GitHub, use a **private repository** unless you have a specific reason to make the templates public. Never commit a client's completed survey to the repo.

## Branding

Navy (`#1A2B3C`) and gold (`#B8974A`) on clean white, with the PCC logo in the header. The survey and landing page are single self-contained HTML files with the logo embedded, so they work offline with no external dependencies.

---

Performance Coaching & Consulting. Prepared by Omar Hikal.
