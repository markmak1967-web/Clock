# The Clock - for MGF: owner and fleet pages

Static pages served by GitHub Pages. They hold no data: each page fetches it from the Google Apps Script web app named in `config.js`.

- `car.html#<token>` - an owner's page. The token after `#` is private to one car and is never sent to GitHub.
- `fleet.html#<fleet key>` - the fleet overview (key from the sheet's Config tab, FLEET_KEY).
- `approve.html#<serial>.<token>` - the admin "approve this gauge" page, opened from the new gauge email.
- `index.html` - the public capability statement: capabilities, product configurations, the owner log page (sample screens in `img/`), specification, data handling and status. Set `CONTACT_URL` near the bottom of the file once a contact form or address exists.

The emails link here when the sheet's Config `PAGES_URL` is set to this site's address.
