# dtolstoi-hub

A tiny, dependency-free link hub for [Dmitrii Tolstikhin](https://www.linkedin.com/in/dmitriitolstoi) — founder of H2 Element. One link for every social bio. It routes Russian-speaking visitors to a Telegram channel and English-speaking visitors to an email list, and points to the ventures.

**Live:** https://tolstihindmitry-ops.github.io/dtolstoi-hub/

## Why it exists

Built in public — one person running like a whole company by putting AI on operations. This page is itself an example: a single hand-rolled `index.html`, no framework, no tracker, no build step. Dark, restrained, fast.

## What's inside

- One file: `index.html` (HTML + CSS + a few lines of JS, zero dependencies).
- WCAG 2.2 AA: semantic landmarks, one `<h1>`, real form labels, visible focus, 44px touch targets, reduced-motion guard, bilingual `lang` attributes, contrast verified with the WCAG formula.
- Email capture posts to a Google Form (responses land in a private sheet).

## Run locally

Open `index.html` in any browser. That's it.

## License

MIT — see [LICENSE](LICENSE).
