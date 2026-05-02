# Pomodoro PWA

Minimalist black and white Pomodoro timer with custom cycles. Installable as a Progressive Web App, works offline.

## Run locally

The service worker requires an `http://` origin, so `file://` won't work. Serve the directory with any static server, e.g.:

```bash
npx serve .
```

Then open the printed URL (typically <http://localhost:3000>) in Chrome.

## Files

- `index.html` — app shell, styles, and timer logic
- `manifest.webmanifest` — PWA manifest
- `sw.js` — service worker (cache-first app shell)
- `icon.svg`, `icon-192.png`, `icon-512.png`, `icon-maskable.png` — app icons
