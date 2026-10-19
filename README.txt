MARVEL DOOMSDAY COUNTDOWN — iPhone PWA

FILES
- index.html: the checklist app
- manifest.webmanifest: installable app metadata
- service-worker.js: offline cache
- icons/: home-screen/app icons

IMPORTANT
An iPhone cannot install a PWA directly from a local HTML file. The files must be hosted at an HTTPS URL first.

EASIEST FREE SETUP: GITHUB PAGES
1. On a computer, sign in or create an account at https://github.com.
2. Create a new public repository named marvel-doomsday-countdown.
3. Upload all files and folders from this package (upload index.html, manifest.webmanifest, service-worker.js, and the icons folder; do not upload only the ZIP).
4. In the repository, open Settings → Pages.
5. Under Build and deployment, choose “Deploy from a branch”, select the main branch and /(root), then Save.
6. Wait for GitHub Pages to publish the site. The URL will look like:
   https://YOUR-USERNAME.github.io/marvel-doomsday-countdown/
7. Open that HTTPS URL on your iPhone in Safari (not an in-app browser).
8. Tap Share (the square with the upward arrow) → Add to Home Screen.
9. If shown, enable “Open as Web App”, then tap Add.
10. Launch it from the new Doomsday icon on your Home Screen.

FEATURES
- Progress percentage and watched count
- Search and All / Unwatched / Watched filters
- Progress automatically saved in that browser on that device
- Custom app icon and standalone/full-screen-style launch
- Offline cache after the first successful online load

NOTES
- Local progress is stored on that device/browser; it does not sync across devices.
- Do not clear Safari website data if you want to preserve the local checklist progress.
- “Full-screen” means standalone app presentation, not a native App Store app.
- This is a fan-made checklist and is not affiliated with Marvel.
