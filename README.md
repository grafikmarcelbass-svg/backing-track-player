# Backing Track Player — PWA

## Deploy to GitHub Pages (5 minutes)

1. Go to github.com → sign in → click **New repository**
2. Name it: `backing-track-player`  
3. Set to **Public** → click **Create repository**
4. Click **uploading an existing file**
5. Drag ALL these files/folders into the upload area:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` (whole folder)
6. Click **Commit changes**
7. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
8. Wait 2 minutes → your URL will be: `https://YOUR_USERNAME.github.io/backing-track-player/`

## Install on iPhone

1. Open the URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow)
3. Scroll down → tap **"Add to Home Screen"**
4. Tap **Add**
5. Open from your home screen — it runs fullscreen like a native app
6. Audio will now work properly ✓

## Why this works

When installed as a PWA from Safari, iOS treats it as a standalone app,
not a web page. Audio playback restrictions are lifted, files work correctly,
and it runs without the Safari UI chrome.
