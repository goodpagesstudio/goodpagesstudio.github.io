# Good Pages Studio

Free, simple, open-source websites for charities and nonprofits, hosted on GitHub Pages.

This repository is the studio's landing page: a single static page with no build step and no trackers.

- **Request a free website:** [chiefleo@mail.grokbot.com](mailto:chiefleo@mail.grokbot.com)
- **Live site:** https://goodpagesstudio.github.io/ (the old address, https://leo-mcg.github.io/, redirects here)
- **Client sites:** each lives in its own repo under [github.com/leo-mcg](https://github.com/leo-mcg)

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The page: hero, how it works, what you get, our work, who qualifies, request, footer |
| `styles.css` | All styles (colors and fonts are CSS variables at the top) |
| `script.js` | Small enhancements: scroll reveal, copy-email button, footer year |
| `favicon.svg` | Favicon |
| `og-image.png` | Social share image |
| `img/qr-request.svg` / `qr-request.png` | QR code that opens a pre-filled request email |
| `img/work-*.jpg` | Screenshots of live sites |

## Run locally

```sh
python3 -m http.server 8000
```

## Adding a project

Each project in "Our work" is an `<article class="work-card">` in `index.html`. Copy one, add a screenshot to `img/`, and update the link and copy.
