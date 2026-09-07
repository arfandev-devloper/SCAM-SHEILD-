# Architecture

## Frontend
- `index.html` — application structure
- `styles.css` — layout, responsive UI and visual theme
- `app.js` — navigation, analysis rules, scoring, history and tools

## Detection flow
Input → normalization → rule matching → weighted score → risk level → explanation → recommendation → optional LocalStorage history.

## Storage
Version 1 uses browser LocalStorage for scan history, demo profile and UI preferences.

## Future architecture
A production upgrade should place AI, OCR, authentication, database and URL-reputation calls behind a secure backend/serverless API. Secret credentials must never be embedded in frontend JavaScript.
