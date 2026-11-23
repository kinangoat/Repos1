# Dayline

A minimalist, dark-mode iPad app for deadlines and events, laid out as a list by day instead of a calendar grid.

## Install on iPad (no Mac needed)
1. Open the app URL in **Safari** (see "Hosting" below).
2. Tap **Share → Add to Home Screen**.
3. Open it from the Home Screen icon. It runs full-screen and works offline.

## Using it
- **Quick add** (bottom bar): type naturally, then press Enter.
  - `Liverpool v Arsenal sat` → one-off on Saturday, tagged Sport
  - `Dinner at Sam's fri` → one-off, tagged Social
  - `Tutoring every mon` or `Gym mondays` → repeats weekly
  - Dates: `today`, `tomorrow`, `next fri`, `12 dec`, `12/12` (day/month), `in 3 days`, `next week`
  - Force a tag with `#sport`, `#school` etc.
  - Tap **+** with an empty bar to open the full form.
- **Tap the circle** to mark done. **Swipe right** = done. **Swipe left** = push to tomorrow (overdue → today, weekly → skip this week).
- **Tap an item** to edit. **Tap a day** in the week strip to jump to it, or to add something on an empty day.
- **Settings** (top right): show empty days, hide completed, edit tags and colours, view weekly repeats, export/import a backup.

Data is stored only on the device. Use **Export** in settings now and then as a backup.

## Hosting
Served as a static site with GitHub Pages: Settings → Pages → Deploy from a branch → pick the branch, `/ (root)`.
