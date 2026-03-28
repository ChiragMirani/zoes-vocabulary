# Zoe's Vocabulary

A lightweight K-12 vocabulary flashcard app built as a Progressive Web App (PWA).

**Live:** [chiragmirani.github.io/zoes-vocabulary](https://chiragmirani.github.io/zoes-vocabulary/)

## What it does

- **1,937 vocabulary words** organized across 14 grade levels (Kindergarten through Grade 12, plus SAT Prep)
- Flip cards to reveal definitions
- Shuffle for random practice
- Navigate forward/backward through each grade's word list
- Works offline once installed

## Install on your phone

1. Open the link in Safari (iOS) or Chrome (Android)
2. Tap **Share** → **Add to Home Screen**
3. It installs as a standalone app with its own icon

## Tech

Single HTML file with embedded CSS, JS, and all word data. No build step, no dependencies, no server.

- `index.html` — the entire app
- `manifest.json` — PWA manifest
- `sw.js` — service worker for offline support
- `icon-192.png` / `icon-512.png` — app icons

## License

MIT
