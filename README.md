# Options Trading

The browser front end of my options-trading tracker, served by GitHub Pages.

This repo holds only the web page. It has no keys, no passwords and no trade data.
Everything is read from and written to my Google Sheet by its Apps Script data
service. The page asks for that service's address and passcode the first time it
opens in each browser, and keeps them in that browser only.

- `index.html`: the whole app (HTML, CSS and JS in one file)
- `manifest.webmanifest` and the icons let it be added to a phone home screen
- Open `…/#connect` to change the connection, copy a link for another device,
  or disconnect this browser
