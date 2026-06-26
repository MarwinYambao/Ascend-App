# ASCEND — Fitness System PWA

## Files
- `index.html` — Full app (single file)
- `manifest.json` — PWA manifest
- `sw.js` — Service worker (offline support)
- `icons/` — All icon sizes (72–512px)

## Deploy to GitHub Pages
1. Create a new GitHub repo (public)
2. Upload all these files to the root
3. Go to Settings → Pages → Deploy from branch → main → / (root)
4. Your URL: https://YOUR_USERNAME.github.io/REPO_NAME

## Convert to APK via PWABuilder
1. Go to https://www.pwabuilder.com
2. Enter your GitHub Pages URL
3. Score 100 → Package for Android
4. Download APK zip

## Reset app data (dev)
In browser console: `resetAscend()`
