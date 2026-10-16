# Absence Email Generator

Upload an attendance workbook (.xlsx) and get copy-and-paste absence emails. Everything runs in the browser, so student data is never uploaded anywhere.

- Reminder emails for students with 1 to 3 absences, grouped by absence count, with a BCC list
- Individual emails for students with more than 3 absences
- No email for students with 0 absences, and hidden Excel rows are skipped
- Email wording is editable on the page

## Expected workbook layout

- **Absence sheet:** a header row with `First`, `Last` and `Total Absences` columns
- **Student info sheet:** one or more side-by-side blocks with `First Name`, `Last Name` and `Email` headers

## Publish with GitHub Pages

1. Create a repository and upload `index.html`, `xlsx.full.min.js` (the bundled Excel-reading library, SheetJS 0.18.5) and this README. Keep `index.html` and `xlsx.full.min.js` in the same folder.
2. Go to **Settings > Pages**, set the source to the `main` branch and root folder, and save.
3. Open the URL GitHub gives you. To use it locally, just open `index.html` in a browser. It works offline.

Because the site is public, don't commit real student spreadsheets to the repository.
