# MONEY TALKS
### Your money, clearly.

MONEY TALKS is a lightweight, mobile-friendly personal finance tracker. It runs directly in the browser and stores transactions in local browser storage.

## Features
- Track income and expenses in INR (₹)
- Categories, account/method, date, and optional notes
- Dashboard with balance, monthly income, expenses, and a simple safe-to-spend indicator
- Search and filter recent transactions
- Monthly spending insights based only on entered transactions
- Light and dark themes
- Export transactions to CSV
- Download and restore a JSON backup
- Device-local storage; no account or server database required

## Run it
Open `index.html` in a modern browser, or serve this folder with any static web server.

### Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. Wait for GitHub Pages to publish the site.

## Privacy and limitations
Transactions are stored in the current browser on the current device. Clearing browser storage can erase them, so download a JSON backup periodically. This version does not sync data across devices and does not connect to bank accounts. The “safe to spend” figure is a simple calculation from the income and expenses entered for the current month, not financial advice. Insights are rule-based, not a cloud AI service.

## Project
- Main app: `index.html`
- No build step or third-party dependencies required.

Made for clear, private money tracking.


## Install as a Chrome app (PWA)
This repository now includes a web app manifest, an app icon, and a service worker.

1. Publish the site over **HTTPS** (GitHub Pages or Vercel).
2. Open the published website in an up-to-date version of Chrome.
3. Use the **＋ Install app** button when Chrome offers installation. You can also open Chrome's **⋮** menu and choose **Install page as app** if available.
4. After installation, MONEY TALKS opens in its own app window.

The install button depends on Chrome's install prompt. Browser policies and platform support can affect when the prompt appears. The service worker enables basic offline caching after the app has been visited once.

Note: SVG app icons are included in the manifest. If a target app store or browser requires raster 192×192 and 512×512 icons, add PNG versions before packaging for that store.
