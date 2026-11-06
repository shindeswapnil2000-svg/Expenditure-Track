# Tally: Money Coach (PWA)

A private budget ledger and money coach. No backend, no account. All data is saved in your phone's browser (`localStorage`) and never uploaded.

## Files
`index.html`, `style.css`, `app.js`, `manifest.json`, `sw.js`, and `icons/` (keep it as a folder).

## Host free on GitHub Pages
1. Create a repo (e.g. `tally`) and upload every file here, keeping `icons/` as a folder.
2. Settings, Pages, Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Open `https://<username>.github.io/tally/` in Chrome on your phone, then menu, Add to Home screen.

## Privacy
Your entries, income and goals stay on the device. The only network request is Google Fonts for typography. Export a backup from Profile now and then, since clearing browser data erases the ledger.

## Upgrading from the old Tally
Old entries and goals (`tally-data-v1`) are imported automatically on first open, and the old data is left untouched.
