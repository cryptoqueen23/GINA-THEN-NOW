# Gina Hinojosa: Then & Now

Independent archival/documentary research site. Not affiliated with or authorized by Gina Hinojosa or her campaign.

## Data
- `data/hinojosa-votes.json` — official-record-only voting database.
- `data/hinojosa-research.json` — secondary research leads, Wayback inventory, campaign snapshots, scorecard inventory.

Ballotpedia is used as a secondary research index; its HTML, scripts, styling, images and design are not republished.


## Voting data update

Loaded 5 individual Vote Smart vote records from the supplied saved HTML. These records are labeled `PENDING_OFFICIAL_VERIFICATION`; Texas Legislature Online / certified House Journals control promotion to `VERIFIED`.


## 2026-08-15 repair pass
- Vote data now has an inline fallback so records render when index.html is opened locally as well as when hosted.
- Compare chronology now includes 2016, 2024, 2025 legislative-record leads, January 2026, and August 2026.
- Visual palette uses colors observed in the supplied Gina campaign HTML (#0a0b0d, #1b1c1d, #0052ff, #e8ff77, #fbfbf8), while retaining an independent archival identity.

- Compare table, issue trails, and the five supplied Vote Smart vote leads are now server/static HTML fallbacks. They remain visible even when JavaScript or local fetch is blocked.
