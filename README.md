# Jake's Strength App — PWA

This is the next build step: an installable Progressive Web App.

## What this version includes

- Phone-friendly app UI
- Full 12-week workout program
- Starts Monday, July 6, 2026
- Complete workout button
- Skip / Push Back button
- Saved progress using localStorage
- Offline support through a service worker
- Web app manifest
- iPhone/iPad Home Screen support
- Windows Chrome/Edge install support
- App icons

## How to use locally

Because service workers usually require a local web server, do this on Windows:

1. Unzip the folder.
2. Open PowerShell in the folder.
3. Run:

python -m http.server 8000

4. Open:

http://localhost:8000

## iPhone/iPad install

To install on iPhone/iPad, the app needs to be hosted somewhere with HTTPS.

Best easy hosting options:
- GitHub Pages
- Netlify
- Vercel

Then open the hosted URL in Safari:
1. Tap Share.
2. Tap Add to Home Screen.
3. Open it like an app.

## Next Step

Deploy this PWA online so you can install it on your iPhone/iPad.
