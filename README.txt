BTP 61016 Message Builder — installable PWA

Files:
- index.html: responsive message builder
- manifest.webmanifest: app identity and install settings
- sw.js: offline cache
- icon-192.png and icon-512.png: app icons in the app root

To install as a PWA:
1. Upload/extract these files to the same folder on a static HTTPS web host.
2. Open the hosted URL in a supported browser.
3. Use the browser's Install App / Add to Home Screen option.
4. Open it once online so the service worker can cache the app files.

A PWA cannot be installed directly from a ZIP or file:// URL. Text BTP opens the device SMS composer where supported; the user must review and send the message manually. Clipboard and SMS behavior depends on browser/device permissions.
