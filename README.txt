# Mary Rose GCash In/Out

## Files
- `index.html` — app interface and transaction logic
- `manifest.json` — installable app information and icon declarations
- `service-worker.js` — offline cache
- `icon-192.png`, `icon-512.png` — app icons

## Test in WebCode
Keep all five files in the same project folder. Open `index.html` in WebCode preview. Browser preview may not enable PWA installation or service workers unless served over HTTPS or localhost.

## Deploy with GitHub Pages
1. Create/sign in to GitHub.
2. Create a new public repository named `mary-rose-gcash`.
3. Upload all five files to the repository root (not inside another folder).
4. Open repository Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select `main` and `/ (root)`, then Save.
7. Wait for GitHub Pages to publish. Your URL will look like `https://YOUR-USERNAME.github.io/mary-rose-gcash/`.

## Install on Android
1. Open the published HTTPS URL in Google Chrome.
2. Tap Chrome's ⋮ menu.
3. Choose Install app or Add to Home screen.
4. Confirm the app name and tap Install/Add.
5. Find Mary Rose GCash In/Out on your home screen or app drawer.

## Important
This is an independent record-keeping calculator. It does not connect to GCash, move funds, verify payments, or provide official GCash fees. Transaction data is stored in this browser's local storage on this device. Clearing browser data, uninstalling, or changing browsers may remove or make records inaccessible. Export/backup is not included in this starter version. Do not use it as your only financial record.
