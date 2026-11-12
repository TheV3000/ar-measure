# Private Measure

On-device AR measuring web app for Chrome on Android. No analytics, ads, accounts, or third-party scripts.

## Files
- `index.html` — app (inline CSS/JS)
- `manifest.webmanifest` — PWA manifest
- `sw.js` — optional same-origin offline cache
- `icon-192.png`, `icon-512.png` — icons

## Privacy
- Strict CSP; no third-party origins
- Measurements saved only in `localStorage` on the device
- Delete all button clears them
- Optional: open in Chrome Incognito so the visit is not in history

## Use
Serve over **HTTPS** (WebXR requirement), open in Chrome on an ARCore Android phone, tap Start AR.

## Modes
- **Line** — point to point length
- **Furniture** — width, depth, height
- **Room** — wall lengths, perimeter, floor area; optional height
