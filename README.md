# Suraj SKS — Drawing Art Forms

A responsive, static GitHub Pages website for the 200-entry Indian Art Forms catalogue supplied by the site owner.

## Files
- `index.html` — page structure
- `style.css` — responsive visual design
- `app.js` — part navigation, search, filters, details and image lookup
- `artforms.json` — all 200 catalogue entries

## Publish on GitHub Pages
1. Create a new public repository on GitHub, for example `sks-art-forms`.
2. Upload **all four website files** (`index.html`, `style.css`, `app.js`, `artforms.json`) to the repository root. Keep the filenames unchanged.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then Save.
6. Wait for GitHub Pages to publish. Your site URL will look like `https://YOUR-USERNAME.github.io/sks-art-forms/`.

## Image references and content notes
The page requests up to three matching image results from Wikimedia Commons when an art-form detail is opened. A network connection is required. Each image opens its Commons file page; check attribution and licence terms before reuse. If images cannot load, the Commons search link remains available.

The 200 names, regions, categories and short descriptions are taken from the supplied PDF. The additional “Material & Process” and “What to Notice” text is general viewing guidance inferred from each entry's category, not a separately verified historical account. For publication-quality research, expand and verify individual entries against specialist or institutional sources.
