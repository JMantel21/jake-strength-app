# Jake's Strength App — Version 0.2

This is the first feature upgrade after the initial deployed PWA.

## New in v0.2

- Dashboard tab
- Today's workout progress card
- Exercise checkboxes
- Core exercise checkboxes
- Rest timer with 1:00, 1:30, and 2:00 presets
- Workout notes
- Workout completion streak
- Completion percentage
- Coach note on dashboard
- Improved local progress storage
- Existing complete workout and skip/push-back logic retained

## Deployment

Replace the files in your GitHub Pages repo with the contents of this folder, then commit and push.

Important files:
- index.html
- program.json
- manifest.webmanifest
- service-worker.js
- assets/icon-192.png
- assets/icon-512.png

If your phone still shows the old version, refresh the page once or remove/re-add the Home Screen app. The service worker cache version has been updated to `jakes-strength-v02`.
