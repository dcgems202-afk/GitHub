# DC Home & Rental Navigation Hub — Rebuild Change Report

Prepared September 25, 2026, after assembling Postings 1–16 (Revision A).
Two copies were built from the same content: a private preview page in Claude and an unpublished Lovable project. Nothing was published or deployed.

## Corrected
- "Help from a person while I search" is replaced by the recovered "I want guidance from a person," with its subtitle, explanation, and four service types.
- The broken ovsa.dc.gov link does not appear. Veterans Affairs uses the Community Affairs URL.
- Safe at Home is described only as accessibility and fall-prevention home adaptation. The OVSJG camera incentive is a separate record.
- SFRRP and Safe at Home each have one record, using the Posting 13 version (owner decision).
- The rental flow was revised (Posting 16, Revision A) so Step 2 asks about situation details, repeats are removed, and every choice leads to a verified record.

## Added
- 37 verified resource records, 18 homeowner records, and 8 Education & Preparation cards, all taken from the log. Every record carries lastReviewed: null.
- Rental path (3 steps, proposed wording), homeowner path (2 steps, recovered wording), Get Housing Help page, results, About & Important Notice, and privacy statement.
- Header controls: Larger text and Listen to this page (browser speech only).
- Dashed review boxes at every gap, and "Time-sensitive status — verify before publication" chips on 6 records.

### New wording added during the build (owner review needed)
These are not recovered. They're labeled here so you can approve or change them.
- All rental-path questions, choices, hints, and the button "Choose what would help most" (Posting 16, Revision A).
- The "Why this may help" sentences on rental results. The recovered records 1–37 had no pathway-specific sentence.
- "Start here first" chip on urgent cards.
- "Bring these to the official program. Do not enter them on this hub." under What to prepare.
- "Why am I seeing this? You chose: … This is not an eligibility decision."
- Linking the Home-repair planning card to the homeowner "Repair or improve my home" choice.
- Abbreviations spelled out on first use in organization names (for example DHS, DOB, OAG, LIHEAP).

## Duplicate records prevented or consolidated
- SFRRP: one card (Posting 13). Earlier URL kept for click-testing only.
- Safe at Home: one card (Posting 13). Earlier URL kept for click-testing only.
- Emergency Mechanical Systems and Weatherization stay separate records even though they share a URL.
- Resources that match several choices (for example DCHousingSearch.org, the rental-assistance overview, SFRRP, Safe at Home, and Healthy Homes) show once, with reasons combined.
- The CBO directory is one record, with no per-CBO cards.

## Links needing the owner's manual click-test
None of these have been clicked by the owner yet.
- SFRRP canonical: https://dhcd.dc.gov/page/sfrrp-%E2%80%93-eligibility-and-how-apply
- SFRRP earlier: https://dhcd.dc.gov/SFRRP
- Safe at Home canonical: https://dacl.dc.gov/service/safe-home
- Safe at Home earlier: https://dacl.dc.gov/safe-home
- Emergency Mechanical Systems and Weatherization (shared): https://doee.dc.gov/service/weatherization-assistance-program-wap
- Veterans Affairs: https://communityaffairs.dc.gov/office-name/mayors-office-veterans-affairs
- The vacant-property dashboard (long Tableau URL) and ERAP
- All other resource links: every one of the 51 URLs on the page matched the transfer log exactly by automated check, but none has been opened.

## Time-sensitive statements to verify before publication
Weatherization, Affordable Electrification, Energy Bill Assistance, Solar for All, Lead Reduction, and Emergency Mechanical Systems. If any has changed, keep the recovered wording and record the verified current status next to it.

## Accessibility checks completed (Claude preview)
- Semantic headings and landmarks, a skip link, real buttons and links, and visible focus outlines.
- Whole-card clickable checkboxes, 44px minimum targets, and a " — selected" text cue alongside color.
- A text validation message, focus moved to each new step, and step and results announcements through a live region.
- Larger text toggle, Listen controls (play/pause, replay, speed), reduced-motion respected, and light and dark themes.
- Automated checks: no phone-number patterns, no ovsa.dc.gov, no old guidance wording, no Safe at Home camera wording, no generic button labels, no browser storage, and the script is syntax-clean.
- Not yet done: a screen-reader walkthrough and a keyboard-only test on a real phone. Those belong to the owner preview checklist.

## Anything that could not be completed
- The exact original rental-scam warning card text (placeholder shown on rental results).
- The complete original rental questions. A proposed replacement is in use and needs your approval.
- The homebuyer question flow (placeholder shown on Path 02).
- The complete original Get Housing Help questions (placeholder page). The legal-help, DOB, and camera records exist but aren't reachable from any path yet.
- Records 7–17 (homebuying, foreclosure, tax) aren't reachable from any path until the homebuyer and help flows exist.
- The reference file couldn't be uploaded to Lovable from this workspace, so the Lovable build was sent the full content as a written spec. Its output should be compared against the Claude preview.
