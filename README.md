# Laya Consulting Website

This is a cleaned static website package generated from `index (68).html`.

## Structure

- `index.html` - production page markup.
- `services.html` - services-link bridge back to the services section.
- `assets/css/styles.css` - extracted site styles.
- `assets/js/main.js` - extracted site interactions.
- `assets/images/` - local image assets used by the page.
- `docs/` - deployment and asset notes.
- `source/index-original.html` - untouched original single-file export.
- `tools/check-local-assets.js` - checks that local page references exist.

## Run Locally

Open `index.html` directly in a browser, or run a static server from this folder:

```bash
npx --yes serve .
```

## Notes

Some image files referenced by the original HTML were not found next to the source file. Labeled placeholder images were generated so the page has no broken local image paths. Replace those placeholder files in `assets/images/` with the final brand/media assets when available.
