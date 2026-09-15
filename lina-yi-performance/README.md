# LINA YI — An Immersive Sonic Performance

An immersive, interactive music portfolio — presented as a live show.

## Experience

- **Ticket gate** — tear your ticket to enter (unlocks the Web Audio engine)
- **Audio-reactive stage** — concentric sound rings and particles driven by the music
- **Playable piano** — 13 keys (C4–C5), click or use keyboard A–K
- **Per-track lighting cues** — every piece switches the stage palette and particle behavior
- **Mouse spotlight** — your cursor is a stage light (desktop)
- **The Artist** — she emerges into the spotlight when the performance begins
- **Encore** — call her back to the stage for contact info

## Run locally

Open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a repository (e.g. `lina-yi-performance`)
2. Upload all files in this folder (keep the structure: `index.html`, `styles.css`, `app.js`, `assets/`)
3. Repo **Settings → Pages → Source**: choose `main` branch, `/ (root)`
4. Your site goes live at `https://<username>.github.io/<repo>/`

## Tech

Plain HTML / CSS / JS. No build step, no dependencies.
Audio: Web Audio API (generative synth demos — set `src` on a track in `app.js` to use real audio files).

© 2026 Lina Yi
