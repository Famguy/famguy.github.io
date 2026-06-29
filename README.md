# Sagun Pai — Academic Homepage

A clean, static personal/academic website. No build step — it works as-is on GitHub Pages.

## Files
```
index.html              # the whole site (single page)
assets/css/style.css    # styling
assets/img/             # drop a profile photo here (see below)
cv.pdf                  # your CV (linked from the site)
.nojekyll               # tells GitHub Pages to serve files as-is (no Jekyll build)
```

## Deploy (GitHub Pages)
This is meant to replace the contents of your `Famguy/famguy.github.io` repo.

1. Copy every file in this folder into the repo root (replacing the old content).
2. Commit and push to the `master`/`main` branch.
3. The site goes live at `https://<username>.github.io`.

## Things you still want to fill in
- **Publications** — replace the placeholder entries in `index.html` (search for
  `placeholder-pub`) with your real titles/venues, or add a Google Scholar link.
- **Profile links** — in the hero and footer, replace `href="#"` for
  Google Scholar / GitHub / LinkedIn with your real URLs.
- **Profile photo (optional)** — add `assets/img/photo.jpg`, then in `index.html`
  uncomment the `<img>` line and remove the `<div class="monogram">` line.
