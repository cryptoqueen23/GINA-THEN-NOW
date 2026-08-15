# Gina Hinojosa: Then & Now

Independent archival/documentary research site. Not affiliated with or authorized by Gina Hinojosa or her campaign.

## Research model

The voting section is a **curated Key & Controversial Votes database**, not a dump of every roll call. The long-range target is roughly 100–250 high-salience votes across Hinojosa's Texas House service, selected for statewide consequence, recurring campaign issues, scorecard attention, unusual voting patterns, or major public controversy.

Official Texas House Journals and Texas Legislature Online control VERIFIED status. Ballotpedia, Vote Smart, scorecards, questionnaires, and other secondary sources are used to identify leads for official verification.

No vote is inferred from party affiliation, sponsorship, attendance, committee membership, or a voice vote.

## Current key-vote tranche

- **21 records indexed**
- **16 verified against official Texas House records**
- **5 Vote Smart leads pending official verification**
- Coverage currently spans the 85th through 89th Legislatures and selected called sessions.
- Initial issue coverage includes immigration/border, abortion, guns, elections, education, school vouchers, higher education/DEI, LGBTQ/gender policy, local control, religious issues, government ethics, and health care.

The research queue for additional high-salience votes is stored in `data/hinojosa-research.json` and is intended to be expanded in verified tranches.

## Data

- `data/hinojosa-votes.json` — structured curated vote database with verification status, record number, result, issue category, selection rationale, official journal source, and bill-history source when available.
- `data/hinojosa-research.json` — secondary research leads, official cross-check inventory, key-vote research queue, Wayback inventory, campaign snapshots, and scorecard inventory.
- `data/hinojosa-inline-data.js` — embedded runtime copy of both datasets so the site does not depend on `fetch()` to display records.

## Reliability / display safeguards

- Voting records have a static HTML fallback so the section remains readable even if JavaScript fails.
- Compare has a static HTML fallback with 2016, 2024, 2025 legislative record, January 2026, and August 2026 columns.
- 2024 RECORD and 2025 LEGISLATIVE RECORD are first-class sections in the main navigation and page flow.
- The site remains bilingual (English/Spanish), mobile responsive, keyboard accessible, reduced-motion compatible, and WCAG 2.2 AA-oriented.
- Visual identity uses the Gina campaign-derived palette while remaining clearly labeled as an independent documentary/archive project.

## Evidence language

A website change documents a change in presentation. It does not, by itself, prove a policy reversal or establish why the campaign made the change.

If content disappears from a page, the project says the position/content was no longer displayed on that archived page unless stronger evidence supports a broader conclusion.
