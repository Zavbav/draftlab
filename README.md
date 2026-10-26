# DraftLab

DraftLab is a responsive sports front-office prototype for fans who want to follow scores, draft a roster, and explore team-building strategy.

## Features
- NFL, NBA, MLB, and MLS sport selectors
- Public ESPN scoreboard feed attempts with clear failure states instead of fabricated scores
- Automatic scoreboard refresh every 30 seconds while the page is visible
- Favorite-team selection saved in the browser
- Searchable illustrative draft pools and optional public ESPN athlete-directory lookup
- Roster picks saved locally in the current browser
- Local rule-based General Manager preview

## Run
Open `index.html` in a modern browser. For local testing, serve the folder over HTTP, for example with `python3 -m http.server 8000`.

## Important limitations
This is a prototype, not a production sports data service. ESPN endpoints used by this page are public and undocumented and may change, be rate-limited, or be blocked by browser/network policy. Athlete directory results are not current-season statistics. Sample player ratings are illustrative, not official stats or projections. The General Manager is a rule-based preview, not a connected AI model. Rosters are saved only in local browser storage and are not shared across devices.

Do not put API secrets in this public repository. A production version needs a secure server-side backend, a vetted/licensed sports-data provider, an AI endpoint, and authentication/database services.

DraftLab is not affiliated with ESPN.
