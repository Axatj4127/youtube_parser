# YouTube Digest PWA

This package turns the single HTML tool into a small phone-installable web app.

## Files

- `index.html` — the updated app page.
- `manifest.json` — Android/Chrome home-screen metadata.
- `sw.js` — service worker for basic offline caching.
- `icons/` — app icons for iPhone and Android.

## Deploy on GitHub Pages

1. Create or open your GitHub repo.
2. Upload all files and folders in this package to the repo root.
3. Go to **Settings → Pages**.
4. Set source to **Deploy from branch**.
5. Select **main** and **root**.
6. Open the GitHub Pages URL on your phone.
7. Add to home screen:
   - iPhone: Safari → Share → Add to Home Screen.
   - Android: Chrome → three dots → Add to Home screen.

## Privacy note

The app parses pasted text locally in the browser. It does not use `fetch`, `XMLHttpRequest`, analytics, remote scripts, or server-side processing.
