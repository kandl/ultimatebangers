# Ultimate Bangers

Promo site for **Ultimate Bangers** — Freezer Beats × Peacock Beats.

A single-page, scroll-driven experience styled as a recovered "lost tape":
a film-leader countdown intro, then eighteen tracks presented one per screen
over a degraded broadcast signal, each with its own colour pulled from the cover art.

## Structure

- `index.html` — the whole site (self-contained; cover art is inlined).
- `assets/cover.jpg` — fallback cover image.

## Deploy

Static site deployed to GitHub Pages via the workflow in
`.github/workflows/deploy.yml` on every push to `main`.

## Editing

Track titles, accent colours, mystery copy and links live in the `TRACKS`
array near the top of the `<script>` in `index.html`. Real streaming links go
in `ALBUM` and each track's `url` (placeholders are `#`).
