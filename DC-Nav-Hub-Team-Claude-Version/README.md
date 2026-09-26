# DC Home & Rental Navigation Hub

A plain-language navigation and education hub. It helps D.C. renters, homebuyers, homeowners, and people with urgent housing concerns find the right official starting point, then sends them to that organization's own website.

It is an independent demonstration prototype for project-team review. It does not determine eligibility, collect personal information, or replace any agency or professional.

Built by Devon Coleman as part of The Upskilling Labs (DC Housing Navigation Hub group). The hub was first built in Lovable, rebuilt in ChatGPT, and then recovered and rebuilt in Claude from the transfer postings in `docs/transfer-log.md`.

## What's in this folder

| Path | What it is |
|---|---|
| `site/index.html` | The whole website in one file. Open it in any browser to use it. This is the **team-review version**: it includes "Comment" buttons that only work when viewed on claude.ai. |
| `data/hub-content.json` | Every resource card, education card, and path question in one editable file. This is the easiest place to check wording and links. |
| `docs/transfer-log.md` | The recovered source material, Postings 1–16, kept word for word. **This is the source of truth.** |
| `docs/rental-path-proposal.md` | New proposed rental questions (Posting 16, Revision A), awaiting owner approval. |
| `docs/change-report.md` | What was corrected, added, and left as gaps, plus the click-test list. |

## Rules any change must follow

These come from Postings 5, 9, and 14 in the transfer log:

- No phone numbers, staff emails, or street addresses anywhere.
- Use only the exact URLs in the transfer log. Never invent or substitute a link.
- Never state or imply that someone qualifies, will get funding or housing, or will be assigned a counselor.
- One record per program. A program that fits several choices uses tags; it is never copied.
- No logins, databases, uploads, or collection of personal information.
- Buttons say where they go. Never "Learn more," "Click here," or "Visit website."
- Wording written to fill a gap is labeled **NEW PROPOSED CONTENT — OWNER REVIEW REQUIRED** until Devon approves it.

## Known gaps (still being recovered)

1. The original rental-scam warning card text
2. The complete original rental questions (a proposed replacement is in use)
3. The homebuyer question flow
4. The Get Housing Help question flow

## Before anything is published

- Click-test every link, especially the six listed in `docs/change-report.md`.
- Re-check the time-sensitive program statuses (Weatherization, Electrification, Energy Bill Assistance, Solar for All, Lead Reduction, Emergency Mechanical Systems).
- Remove the team-review "Comment" buttons and banner from the public version.
