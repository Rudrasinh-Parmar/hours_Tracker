# Work & Travel Tracker — PWA

Installable phone app to track shifts, pay, and travel costs.

## Deploy to Vercel (2 minutes)

1. Go to https://vercel.com/new
2. Click **"Deploy without Git"** or drag this whole folder in
3. Alternatively: install Vercel CLI → `cd` into this folder → run `vercel` → follow prompts
4. You'll get a URL like `work-tracker-xxx.vercel.app`

## Install on your phone

**iPhone (Safari):**
1. Open the Vercel URL in Safari
2. Tap the Share button (square with up arrow)
3. Scroll → tap **"Add to Home Screen"**
4. Tap Add — icon appears on home screen, opens fullscreen like a real app

**Android (Chrome):**
1. Open the URL in Chrome
2. Tap the three-dot menu
3. Tap **"Install app"** or "Add to Home Screen"
4. Confirms install → icon on home screen

## Features
- Works offline after first load (service worker caches everything)
- Data saved on your phone (localStorage)
- Export/import JSON backup so you never lose data
- 30-minute unpaid break auto-deducted for shifts ≥6h

## Files
- `index.html` — the app
- `manifest.json` — PWA config (name, icons, colors)
- `sw.js` — service worker for offline
- `icon-192.png`, `icon-512.png` — app icons
