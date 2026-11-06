# Hyundai Website Clone

A multi-page front-end practice clone of the Hyundai India website homepage and contact pages.

## Tech stack
- HTML5
- Custom hand-rolled responsive CSS grid (`.col-1`–`.col-12`, no framework like Bootstrap)
- jQuery 3.1.1 / 3.6.0 (CDN)
- bxSlider 4.2.12 (CDN) — homepage image slider
- Font Awesome 4.7.0 and Google Material Icons (CDN)
- Google Fonts — Montserrat Alternates

## Pages
- `index.html` — homepage with nav, image slider, Models section, and news section
- `page-2.html` — "Contact Us" page
- `form.html` — contact form page

## Assets
Images are stored locally in `img/` (unlike the BookMyShow project, this one does not hotlink to the original site's CDN).

## How to run
Open `index.html` directly in a browser. No build step or server required.

## Known limitations
- Most nav links (Buy a Car, Connect to Service, Hyundai Story, Click To Buy) are placeholders (`href="#"`).
- `img/asset 77.html` is a stray saved "500 Internal Server Error" page — likely an accidental save made while collecting assets from the live Hyundai site. Harmless, but not an actual part of the UI.
- News/press content is copied verbatim from real Hyundai press releases, for layout practice only.

## Status
Practice/learning project. Not production-ready.

## Versioning
This project follows [Semantic Versioning](https://semver.org/). See `CHANGELOG.md` for release history.
`v0.1.0` is the preserved baseline captured before any further improvements.
