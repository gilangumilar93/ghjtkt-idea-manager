# GHJTKT Idea Manager

Simple local web app to capture and manage ideas.

## What it does
- Add, edit, delete ideas
- Fields: Idea/Question, Why interesting, Unknowns, Next step, Status
- Search/filter
- Persist in browser localStorage (data never leaves your machine)
- Export / Import JSON
- **Export Markdown** (table matching Inbox format)

## How to run
1. Open `index.html` in any modern browser (double-click or drag into browser).
2. No server, no install, no dependencies.
3. Data stays in that browser’s localStorage.

## Files
- `index.html` — single self-contained app

## Limitations
- Data is per-browser / per-device (clearing browser data deletes ideas).
- No multi-device sync (by design for privacy and simplicity).
- No authentication.

## Next possible improvements
- Tags or project field
- Light theme option
- Sync notes (still local-only by design)

[DECISION]: Built as single-file local HTML app for zero setup and full data control.  
Created: 2026-10-18
