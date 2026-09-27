# Mr. ASA Food Hub

The Mr. ASA food-security website for Prince George's County, with a section for UMD students.

## Files

- `index.html` is the whole website in one file. Double-click it to open it in a browser. You can also upload it to any static host, like GitHub Pages or Netlify.
- `umd-student-orgs-template.csv` is a sheet for collecting each org's mission, meeting times, and links.
- `pg-county-food-sites.json` holds the 41 verified food sites taken from the county pantry map (verified May 29, 2026). The same data is already built into `index.html`.

## Pages

These pages are sections of the same file, reached with `#` links:

- Home: `#home`
- Find Food: `#food`
- Volunteer: `#volunteer`
- Donate: `#donate`
- UMD Students: `#umd`
- About and FAQ: `#about`

## Still to do

- Replace the sample volunteer rows with the PGCPS volunteering database. Look for `const VOL` in `index.html`.
- Fill in each UMD student org's mission statement, meeting times, and Instagram, GroupMe, and TerpLink links. Use `umd-student-orgs-template.csv`, or edit `const ORGS` in `index.html` directly. Empty fields stay hidden on the site.
- Check the UMD campus resources. Look for `const FOOD`.
- Add a contact email or form on the About page.
