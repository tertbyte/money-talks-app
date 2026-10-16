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
