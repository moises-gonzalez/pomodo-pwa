# PomoDO PWA
#### PomoDO helps you to DO things

Minimalist Pomodoro timer with custom cycles. Installable as a Progressive Web App, works offline.

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

## Visit PomoDO on the Web

You can visit PomoDO here: https://pomodo.thetestingnest.com/.

Works on your mobile too!

## Help A Dude Out!

You can send a buck if you like my work, via Buy Me A Coffee: 

https://buymeacoffee.com/thetestnestmx
