# KidZy 🐆
Mobile-friendly landing page for [KidZy Fun Books](https://www.instagram.com/kidzyfunbooks) — Montessori-inspired worksheets, flashcards & coloring books for kids aged 2–6.

## Files
- `kidzy_mobile.html` — the entire website (single file, no build tools needed)

## How to run
Just open `kidzy_mobile.html` in any browser. That's it.

## Deploy
Rename the file to `index.html` and drop it into:
- **Netlify** — drag & drop at [netlify.com](https://netlify.com) (free, instant)
- **GitHub Pages** — push to a repo, enable Pages in Settings

## Forms → Google Sheets
Both the waitlist and freebies form submit to the same Google Sheet via Apps Script.
To update the endpoint, search for `script.google.com/macros` in the HTML and replace both URLs.

## Quick edits
| What | How |
|------|-----|
| Change text | `Ctrl+F` in any text editor |
| Update waitlist count | Search `247 / 500` and `width: 49%` |
| Add a review | Duplicate a review card `<div>` in the Community Reviews section |

## Contact
kamlachodhary182@gmail.com · [@kidzyfunbooks](https://www.instagram.com/kidzyfunbooks)
