# Manuals

Internal user manuals for the three TUW apps. Private.

| App | Path | Status |
|-----|------|--------|
| The Udder Dairy | `dairy/index.html` | Live source |
| The Udder Driver | `driver/` | Not written yet |
| The Udder Venue | `venue/` | Not written yet |

Each app is a static HTML page plus an `assets/` folder. Open `index.html` in a browser. Images must be relative (`assets/...`), never absolute local paths.

Published copy of the dairy manual: https://manual.theudderdairy.com/

That site is a copy on the AWS box (`/var/www/dairy-manual` on `54.79.1.1`). Editing this repo does not update the site until the `dairy/` folder is rsynced there. Do not change `theudderdairy.com` or the dashboard.
