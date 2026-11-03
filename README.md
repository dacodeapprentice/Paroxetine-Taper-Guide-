# Taper Diary

A personal dose and symptom diary for tracking daily medication intake and self-reported symptoms over time.

## Overview

Taper Diary is a static, client-side single-page application (SPA) with **no API keys, external servers, or cloud databases required**.

- **No API key needed**: Runs entirely in the browser with no AI models, cloud backends, or third-party APIs.
- **Client-Side Privacy**: All logged doses, formulations, symptom scores, notes, and orientation schedules are stored locally on your device in `localStorage`.
- **Offline Capable**: Works entirely offline in any modern web browser.
- **Data Portability**: Includes built-in JSON backup export and import, as well as a print-friendly summary for healthcare provider discussions.

## Development

```bash
# Start local development server
npm run dev

# Build static production bundle into dist/
npm run build

# Preview production build locally
npm run preview
```
