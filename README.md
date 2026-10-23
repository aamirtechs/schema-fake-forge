# Schema Fake Forge
Live page: https://aamirtechs.github.io/schema-fake-forge/

Paste a JSON Schema or an OpenAPI file and generate realistic, seeded, reproducible fake data as JSON, CSV or SQL inserts. It solves the hand-work of doing this job row by row in a spreadsheet, entirely in the browser.

## Features
- Seeded, reproducible fake data from JSON Schema draft-07 subset
- Local $ref resolution, enum and format fidelity (email, uuid, date-time)
- Sample JSON inference and OpenAPI schema picking
- Export as JSON, NDJSON, CSV or SQL INSERT statements
- Runs entirely in your browser, up to 5,000 rows

## How it works
Provide the input in the tool card, run it, review the preview, then download the result. All processing happens locally in your browser using the logic in src/logic.js. No server is involved at any step.

## Privacy
Runs 100% in your browser. Your files never leave this device, nothing is uploaded,
and there is no tracking.

## Development
Core logic lives in `src/logic.js` and is shared by the page and the tests.
Run the tests with `npm test`.

## License
MIT, Copyright 2026 Amir Hussain.
