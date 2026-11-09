# The Clock - for MGF: owner and fleet pages

Static pages served by GitHub Pages. They hold no data: each page fetches it from the Google Apps Script web app named in `config.js`.

- `car.html#<token>` - an owner's page. The token after `#` is private to one car and is never sent to GitHub.
- `fleet.html#<fleet key>` - the fleet overview (key from the sheet's Config tab, FLEET_KEY).
- `index.html` - a plain landing page.

The emails link here when the sheet's Config `PAGES_URL` is set to this site's address.
