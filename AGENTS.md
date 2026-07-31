# TuscanTech IT Services — Corporate Website

Agent instructions for working on this project.

## What this is
The official marketing website for **TuscanTech IT Services L.L.C** ("The Technocrats"),
a licensed IT services company in Dubai, U.A.E. Sister company of Zimplified Global
(zimplifiedglobal.com) — the two sites should feel like part of the same brand family.
Design reference points: zimplifiedglobal.com and astrolabs.com (clean, institutional,
premium corporate).

## Stack
- Pure static site: one `index.html` with embedded CSS and vanilla JS. No frameworks,
  no build step. Keep it that way unless explicitly asked to migrate.
- Logo assets live in `assets/` (`logo-dark.png` for light backgrounds,
  `logo-light.png` for dark backgrounds), referenced via CSS variables
  `--logo-dark` / `--logo-light`.
- Fonts: Newsreader (display serif) + Inter (UI/body) via Google Fonts.

## Brand tokens (do not change without instruction)
- Palette: paper `#FCFBF9`, ink `#16141F` / `#100E18`, violet `#6D5CE7`,
  violet-deep `#4B3FC4`, violet-2 `#B7A9F6`, mist `#F4F3F8`.
- The violet comes from the company logo. Never introduce a competing accent colour.
- Tagline: "The Technocrats — Empowering Business Through Technology".
- Tone of copy: confident, specific, institutional; no hype words, no emoji.

## Hard facts — never alter or invent
- Company: TuscanTech IT Services L.L.C · Trade License 1109645 (DET Dubai) · est. 2022
- Address: 301, Westburry Tower, Business Bay, Dubai, U.A.E. · P.O. Box 12584
- Phone: +971 4 553 6964 · Email: regulatory@tuscantechit.com · Domain: tuscantechit.com
- Do NOT add fictional clients, testimonials, client logos, or invented statistics.
  The stats band contains only verifiable facts (license, year, disciplines) — keep it that way.

## Section map (index.html)
nav → hero (headline + image panel + credentials badge) → trust strip → capabilities
(6 cards covering 12 licensed activities) → "The TuscanTech Method" (Assess / Engineer /
Sustain) → dark stats band → Why TuscanTech → image band → violet CTA → contact
(details + mailto form) → footer (with corporate info).

## Conventions
- Responsive breakpoints at 960px and 640px; keep both working when editing.
- `prefers-reduced-motion` must remain respected.
- Nav logo is intentionally large (70px, 50px scrolled) — the client wants the logo prominent.
- Hero/imagery: Unsplash institutional-architecture photos (same family as Zimplified's site),
  always with `onerror` fallback so the gradient shows if images fail.
- Contact form submits via `mailto:` — if asked to wire a real backend, suggest a static-friendly
  service (e.g. a form endpoint) rather than adding a server.

## Known follow-ups the client may request
- Swap logo PNGs for vector/high-res versions when supplied (current source is 380px — soft on retina).
- Add favicon derived from the emblem.
- Client logo wall + testimonials section (only with real client data).
- Deploy to GitHub Pages (repo may be named `tuscantech-website`).
