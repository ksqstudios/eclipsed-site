# eclipsed-site

Marketing site for [Eclipsed](https://eclipsedsleep.com), a sleep debt utility for iOS.

## Stack

- Static HTML/CSS, no build step
- Hosted on Cloudflare Pages (auto-deploy from `main`)
- Plausible Analytics (privacy-friendly, no cookies)
- Custom domain: `eclipsedsleep.com`

## Local preview

Just open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Pages

- `/` — `index.html`, marketing landing
- `/privacy` — `privacy.html`, App Store-required privacy policy
- `/support` — `support.html`, FAQ + email contact

## Assets

- `favicon.svg` — small crescent on Vigil gradient
- `apple-touch-icon.png` — 180x180 app-icon-style
- `og.png` — 1200x630 social share card

## Design tokens

The Vigil palette stays in sync with `EclipsedPalette.swift`. Five stages:

- Slate `#3A5878 → #6E92B5`
- Mist `#4F5680 → #8484AE`
- Plum `#6E4569 → #A66E8C`
- Rust `#8B3D45 → #BD6968`
- Crimson `#5E1418 → #8B252A`

All gradients run 135° (top-leading → bottom-trailing).
