TCF FOCUS V4 — PHONE APP / PWA

This version keeps the V4 vocabulary and features and adds Progressive Web App support for Android and iPhone.

IMPORTANT: A PWA must be opened from HTTPS (or localhost) to be installable. Opening index.html directly from a file manager is not enough for Android Chrome installation.

FILES
- index.html — complete app
- manifest.json — app identity/icon/install settings
- sw.js — offline cache/service worker
- icons/ — home-screen icons

ANDROID
1. Host this folder on an HTTPS website.
2. Open the website in Chrome.
3. Use Install app / Add to Home screen when offered.
4. Launch TCF Focus from the phone home screen.

IPHONE
1. Host this folder on an HTTPS website.
2. Open it in Safari.
3. Share → Add to Home Screen.
4. Turn on “Open as Web App” if shown, then Add.

PRIVACY / STORAGE
The vocabulary and progress remain client-side. The app does not require a login. Browser localStorage stores progress on the device/browser.

NOTE
A PWA is not the same as an App Store / Google Play native app. Native store packaging requires platform-specific signing/distribution. This package is designed to be installable as a phone-style web app on both Android and iPhone.
