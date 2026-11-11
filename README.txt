MEDICAL REFERENCE SEARCH — HYBRID APP STARTER

WHAT THIS PACKAGE DOES
- Offline mode searches the small, included reviewed starter dataset.
- The PWA service worker caches the app and dataset after it is first opened from a secure HTTPS host.
- Online mode is a clearly marked placeholder. It is NOT connected to an AI or medical API yet.

IMPORTANT
- This is an educational reference, not a diagnostic or prescribing tool.
- It does not calculate or recommend patient-specific doses.
- Do not add API keys to index.html or any public file.
- Before adding online answers, use a secure backend and trusted, current clinical sources; have clinical content reviewed by a qualified professional.
- Do not claim to cover every disease. Offline search only covers conditions included in conditions.json.

ANDROID INSTALL
1. Upload all files/folders in this package to a static host that provides HTTPS.
2. Open the hosted site in Chrome on Android.
3. Use Chrome menu (three dots) > Install app or Add to Home screen.
4. Open it once while online so the offline files are cached.
5. Then test Offline mode with mobile data/Wi-Fi turned off.

FILES
- index.html: app screen
- conditions.json: offline reference pack
- manifest.webmanifest: install metadata
- sw.js: offline cache worker

To add a reviewed offline condition, append an entry to conditions.json using the same fields as existing entries.
