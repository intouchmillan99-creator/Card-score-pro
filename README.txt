CARD SCORE PRO — INSTALLATION GUIDE

Included files:
- index.html: the complete app
- manifest.json: installable web app metadata
- sw.js: offline cache/service worker
- icon.svg: app icon

IMPORTANT:
This is an installable PWA package, not a signed Android APK.

OPTION 1 — Run locally for testing:
Open index.html in a modern browser. Score entry and local saving work; install/offline PWA features require HTTPS or localhost.

OPTION 2 — Install on Android (recommended):
1. Upload all four app files to a static HTTPS host (for example GitHub Pages, Netlify, or your own website).
2. Open the HTTPS URL in Chrome on Android.
3. Open Chrome menu (⋮) and choose "Install app" or "Add to Home screen".
4. Launch Card Score Pro from the new home-screen icon. It supports offline use after the first successful load.
No account is required. Score history is stored locally in the browser on that device.

GAME RULES IMPLEMENTED:
- Four players split into two teams (players 1–2 vs 3–4).
- Each player enters a call from 1–13 and actual tricks from 0–13.
- A player's points equal +call if tricks >= call; otherwise -call.
- The four players' tricks must total exactly 13.
- Combined calls may not exceed 13.
- Team round points are the sum of its two players' points.
- First team reaching the selected target wins (default 100).
- Undo last round, CSV export, local autosave, and new game reset are included.

DATA:
Scores are saved in the browser's local storage. They do not automatically sync between devices. Export CSV periodically if you need a backup.

PNG install icons (192x192 and 512x512) are included for Android PWA installation.
