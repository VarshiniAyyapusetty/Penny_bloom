PENNY BLOOM — INSTALLABLE WEB APP

Files:
- index.html: the expense tracker
- manifest.json: app name, icon, and standalone display settings
- sw.js: basic offline caching
- icons/: Android home-screen icons

IMPORTANT
The app must be served from HTTPS for Chrome's install/PWA features. Opening index.html directly from the phone's file manager will not enable the full installable/offline behavior.

EASIEST FREE ROUTE: GITHUB PAGES
1. On a computer, sign in to GitHub and create a new public repository named penny-bloom.
2. Upload the CONTENTS of this folder (index.html, manifest.json, sw.js, icons folder) to the repository's root.
3. Open the repository's Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to provide the HTTPS website URL.
6. Open that URL in Chrome on your Android phone.
7. In Chrome, tap the three-dot menu and choose Install app or Add to Home screen (wording varies).
8. Confirm. Penny Bloom should appear on your home screen.

DATA NOTE
Transactions and budgets are saved in the browser's local storage on that device/browser. They are not synced between devices. Clearing browser data may erase them, so add backup/export functionality before relying on it for important records.

This is a prototype, not a Play Store APK. No bank connection is used.
