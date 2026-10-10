# Kun Huang’s personal website

Published at **https://kunh630.github.io/** with GitHub Pages.

A small, responsive website built with HTML and CSS. No framework, package installation, or build step is needed.

## Edit

- `index.html`: introduction, social links, and Career Highlights. Copy an `<article class="highlight">` block to add another highlight.
- `styles.css`: colors, typography, spacing, and mobile layout.
- `assets/kun-huang.jpg`: the Slack profile photo selected by Kun. Update the image’s alt text and dimensions in `index.html` when replacing it.

The biography, social links, and career highlights were supplied by Kun. The preview videos and poster images match the cards on https://www.dyna.co/research. Poster images are stored locally; videos stream from their original Dyna URLs and use native playback controls. No autoplay is used.

Preview sources:
- Dyna-2.1: `/assets/videos/whole-employee-card.mp4` and `/assets/videos/whole-employee-card-poster.jpg`
- Dyna-2: `/assets/videos/dyna2-mosaic-ego.mp4` and `/assets/research/dyna-2-mosaic-card.jpg`
- Dyna-1: `/assets/research/dyna-1-model-card.mp4` and `/assets/research/dyna-1-model-card.png`

All preview paths above are on https://www.dyna.co. Dyna retains ownership of its media.

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
