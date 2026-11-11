# Options Trading

The browser front end of my options-trading tracker, served by GitHub Pages.

This repo holds only the web page. It has no keys, no passwords and no trade data.
Members sign in with Google or with email/phone and a password. Each member's
trades live in their own workbook, read and written by the app's Apps Script data
service, which checks every request. New accounts wait for approval.

- `index.html`: the whole app (HTML, CSS and JS in one file)
- `manifest.webmanifest` and the icons let it be added to a phone home screen
