# JEE Study Tracker

A static, single-page study tracker (Class 11 + 12): tick off Lectures / PYQ / Module / Notes / Book per chapter,
filter by study mode, search, print, and download the Excel sheet. No build step, no dependencies.

## Files
- `index.html` - the whole site (HTML + CSS + JS)
- `Study_Tracker.xlsx` - the file behind the **Download .xlsx** button (must sit next to `index.html`)

## Run locally
Open `index.html` in a browser, or from this folder run `python3 -m http.server` and visit http://localhost:8000

## Host on GitHub Pages
1. Create a new public repository on GitHub.
2. Upload `index.html`, `Study_Tracker.xlsx` and `README.md` to the repository root.
3. Go to **Settings -> Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then Save.
4. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.

## Notes
- Ticks are saved in the visitor's own browser (localStorage), per device.
- To update the spreadsheet, replace `Study_Tracker.xlsx` with the new file using the same name.
