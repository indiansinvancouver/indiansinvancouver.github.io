# Vancouver Indians for Democracy

A static site for the Vancouver solidarity gatherings. It has no build step.

## Files

- `index.html` — the home page
- `learn-more.html` — the long-form article
- `media-advisory.html` — the media advisory for the global day of action
- `styles.css` — all styles
- `assets/hero-jantar-mantar.jpg` — hero photo (CC BY-SA 4.0, credit is on the page)
- `assets/logo.svg` — favicon
- `.nojekyll` — tells GitHub Pages to serve the files as they are

## Before each meetup

Edit these values in `index.html`:

- In the `MEETUP` block: event name, day, date, time, location, address, notes, "Updated" date, and the **Get directions** link.
- In the footer of each page: the "Page updated" date.

## Preview locally

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765.

## Publish on GitHub Pages

1. Push this folder to a GitHub repository (files at the repository root).
2. On GitHub, open **Settings › Pages**.
3. Set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Save. The site is live at `https://<user>.github.io/<repo>/` after a minute or two.

## Not published

`media-advisory.pdf` is the source document for `media-advisory.html`. It is listed in `.gitignore` and must not be uploaded.
