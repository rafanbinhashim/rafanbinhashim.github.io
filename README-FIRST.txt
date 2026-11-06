SMART MONEY TRACKER — BROWSER-ONLY PWA PACKAGE

This folder is ready to upload to a NEW PUBLIC GitHub repository and publish with GitHub Pages.

FILES
- index.html, styles.css, app.js: the app
- manifest.webmanifest: installable PWA metadata
- sw.js: offline app-shell cache
- icons/: app icons
- .nojekyll: tells GitHub Pages to serve files directly

GITHUB PAGES STEPS
1. Create a public repository named smart-money-tracker.
2. Extract this ZIP on your PC.
3. In the repository, choose Add file > Upload files. Upload the CONTENTS of this folder (including icons and .nojekyll), not the ZIP itself.
4. Commit the files to the main branch.
5. Open Settings > Pages. Under Build and deployment, choose Deploy from a branch; branch main; folder /(root); Save.
6. Wait for deployment. The app URL will be https://YOUR-USERNAME.github.io/smart-money-tracker/
7. Open the URL on Android Chrome, use the browser menu > Install app or Add to Home screen.

OFFLINE
Open the site once while online and wait for it to load. The service worker then caches the app shell. Transaction data is stored separately in that browser/app's local storage on that device. Back up data from inside the app before clearing browser data or uninstalling.

PRIVACY
The repository and hosted app code are public. Do not upload personal transactions or private Notion exports. The app stores transaction data locally on the device and does not sync it to GitHub.

GOOGLE PLAY
PWABuilder can package a valid HTTPS PWA as an Android Trusted Web Activity. Google Play publishing still requires a developer account (US$25 one-time) and the account holder must be at least 18. A newly created personal account may have closed-testing requirements. PWABuilder also requires correct Digital Asset Links setup. This package is a starting PWA and must be tested before publication; store acceptance is not guaranteed.
