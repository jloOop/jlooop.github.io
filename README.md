# Alireza Jozani — one-page GitHub Pages homepage

This folder contains a clean one-page static homepage for GitHub Pages.

## Files

- `index.html` — the full one-page website.
- `.nojekyll` — tells GitHub Pages to serve the static files directly.
- `README.md` — these setup notes.

## Recommended GitHub Pages setup

Your GitHub profile appears as `jloOop`. GitHub Pages user/organization sites should use the lowercase username in the repository name, so the repository should be:

```text
jlooop.github.io
```

After publishing, the default site URL should be:

```text
https://jlooop.github.io/
```

## Web UI setup

1. On GitHub, create a new public repository named `jlooop.github.io`.
2. Upload `index.html`, `.nojekyll`, and this `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`, then save.
6. Wait for GitHub Pages to deploy.

## Command-line setup

```bash
git clone https://github.com/jloOop/jlooop.github.io.git
cd jlooop.github.io
cp /path/to/index.html .
cp /path/to/.nojekyll .
cp /path/to/README.md .
git add index.html .nojekyll README.md
git commit -m "Launch one-page research portfolio"
git push origin main
```

## Before wider sharing

Check these items:

- Confirm the contact email.
- Add or link a public CV PDF if desired.
- Confirm publication status wording.
- Confirm that each repository README is recruiter-readable.
- Add `EVIDENCE_FOR_RECRUITERS.md` to the main repositories.
- Add “What I personally implemented” and “Safe claims / boundaries” sections to repository READMEs.
- Ensure no private lab data, internal files, or unsupported claims are exposed.

## Safe positioning

The homepage is intentionally written as an R&D research portfolio. It frames GitHub as research-code, reproducibility, and physics-data-analysis evidence, not as production software evidence.
