# Alireza Jozani — Physics R&D Portfolio

Single-page GitHub Pages portfolio.

## Files

- `index.html` — homepage
- `robots.txt` — allows search-engine crawling and points to the sitemap
- `sitemap.xml` — minimal sitemap for the homepage URL
- `.nojekyll` — disables Jekyll processing for this static site

## Deployment

Upload these files to the root of the `jlooop.github.io` repository and enable GitHub Pages from the `main` branch, root folder.

If the GitHub Pages URL changes, update the canonical URL in `index.html`, the sitemap URL in `robots.txt`, and the `<loc>` entry in `sitemap.xml`.



# Alireza Jozani — Physics R&D Portfolio

Single-page static GitHub Pages portfolio for selected research-code, publication, superconducting-device analysis, and instrumentation-oriented data-analysis material.

## Files

- `index.html` — homepage.
- `robots.txt` — crawler rules and sitemap pointer.
- `sitemap.xml` — minimal sitemap for the homepage URL.
- `.nojekyll` — optional empty file that disables Jekyll processing for a plain static site.
- `PREVIEW_CHECKLIST.md` — public-safe manual checklist before publishing changes.

## Local preview

```bash
python3 -m http.server 8000
```

Open:

```text
http://localhost:8000
```

## Deployment

Place the files in the root of the `jlooop.github.io` repository and enable GitHub Pages from the `main` branch, root folder.

If the site URL changes, update the canonical URL in `index.html`, the sitemap URL in `robots.txt`, and the `<loc>` entry in `sitemap.xml`.
