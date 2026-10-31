# Georgio & Christina — Wedding Website

A single-page, bilingual (English / Arabic) wedding invitation site.
Live domain: **https://georgioandchristinawedding.com**

- **Date:** 02 July 2027 · 17:30
- **Venue:** Monastery of Saint John Chrysostom — Selaata, Batroun
- **Colours:** dark sage green & white
- **Hosting:** GitHub Pages (account `gmassaad1`), custom domain via `CNAME`

## Structure

```
index.html            # the whole site (HTML + CSS + JS, no build step)
CNAME                 # custom domain for GitHub Pages
.nojekyll             # serve files as-is
assets/img/           # hero.jpg, feature.jpg, gallery-01..06.jpg
music/song.mp3        # background song (add this file — see music/README.txt)
```

## Still to add (placeholders are in place)

Search `index.html` for `TODO`:

1. **Photos** — replace the sage placeholder images in `assets/img/`
   (`hero.jpg`, `feature.jpg`, `gallery-01.jpg` … `gallery-06.jpg`).
2. **Song** — drop the mp3 at `music/song.mp3`.
3. **RSVP numbers** — replace `96100000000` with Georgio's and Christina's
   real WhatsApp numbers (international format, no `+` or spaces).
4. **Our Story** — the two paragraphs are placeholder text; swap in their words.
5. **RSVP deadline** — currently set to 1 June 2027; adjust if needed.

## Editing

Open `index.html` in any editor. Text comes in EN/AR pairs:
`<span data-lang="en">…</span><span data-lang="ar">…</span>`.
Commit and push to `main` — GitHub Pages redeploys automatically.
