# Kun Huang’s personal website

Published at **https://kunh630.github.io/** with GitHub Pages.

A small, responsive website built with HTML and CSS. No framework, package installation, or build step is needed.

## Edit

- `index.html`: introduction, links, and selected projects. Copy an `<article class="project">` block to add a project; use a separate section for publications when ready.
- `styles.css`: colors, typography, spacing, and mobile layout.
- `assets/portrait.jpg`: currently the public GitHub avatar. Replace it with your preferred photo and update the image’s alt text and dimensions in `index.html`.

The biography and social links were supplied by Kun. The initial project list and avatar come from the public GitHub profile. The projects can be replaced with current work and publications; a preferred portrait and CV can be added later.

## Preview locally

From the repository directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000 in a browser.

## Publish

In **Settings → Pages**, use **Deploy from a branch**, branch **main**, folder **/ (root)**. Commits to `main` are automatically published. `.nojekyll` makes GitHub serve the HTML and assets directly.

The repository must be called `kunh630.github.io` and belong to `kunh630` to use this address. Do not add a CNAME file for the default github.io address.

The layout was inspired by Andy Zeng’s personal website, with original markup and styling. No text or images from that site are reused.
