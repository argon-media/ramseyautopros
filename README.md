# Ramsey Auto Pros

Marketing site for **Ramsey Auto Pros** — certified ceramic coating, paint protection film (PPF),
window tint, and detailing serving Daphne, Mobile, and the greater Gulf Coast.

## Stack

Plain static HTML/CSS/JS — no build step. Implemented from the Claude Design handoff
(`Homepage.dc.html`) as a single self-contained `index.html`.

```
index.html        # the homepage (CSS inlined, vanilla JS for interactivity)
images/           # photos, certification logos, favicon, wordmark
fonts/            # Bank Gothic (also embedded as base64 in index.html)
vercel.json       # static deploy config
```

## Local preview

```bash
python3 -m http.server 4321
# open http://localhost:4321
```

## Deploy

Static site — deploys on Vercel with zero configuration. Connect the repo in Vercel
and point your custom domain at it.

## Interactivity (vanilla JS, no framework)

- Rotating hero background slideshow
- Sticky header that darkens on scroll
- Reveal-on-scroll animations
- Projects gallery + Google reviews carousels
- FAQ accordion (single-open)
- Quote form with success state
- Mobile slide-down menu
