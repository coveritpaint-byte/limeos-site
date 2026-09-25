# limeos.ai

The LimeOS site. One page, no build step, no dependencies.

`index.html` is self-contained: the font is inlined as woff2 and the mark is drawn on a
canvas at runtime, so the page makes **zero external requests** and renders identically
with no network.

- `index.html` the site
- `og.png` the 1200x630 card shown when the link is pasted into Slack, iMessage, LinkedIn
- `CNAME` the custom domain, required by GitHub Pages

## Deploying

Push to `main`. GitHub Pages serves it at https://limeos.ai.

## Editing

Open `index.html`. There is no toolchain. If you change the copy, change it in the
`og:description` and `twitter:description` meta tags too, or the link preview will
disagree with the page.
