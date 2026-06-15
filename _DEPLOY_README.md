# DEPLOY — ÅTERFÖDELSEN / REBIRTH

Showcase / press site for the room-scale XR installation by **Silvana Imam ✕ Paula Strunden**, commissioned by MUNCH (Oslo), funded by XTREME (EU Horizon Europe, Grant No. 101136006).
Live: https://aterfodelsen.com

## ✅ Deploy THIS folder only (`aterfodelsen_fable_2026-06-12/`)
Entry page: **`index_2026-06-15.html`** ← the latest, current version.
Plus the asset folders it needs:
- `media/` — videos (1080p, optimized, ~73 MB)
- `img/` — photos, logos, posters
- `sound/` — per-act audio (act1/2/3.mp3)
- `favicon.ico`, `apple-touch-icon.png`, `og-image.jpg`

> For GitHub Pages (or any host expecting a default page): rename `index_2026-06-15.html` → `index.html`, or point the host's entry at it. Internal links are all relative, so renaming is safe.

## 🚫 Do NOT deploy
- `../_aterfodelsen_TEMP_do-not-deploy/` (sibling folder, outside this one):
  - `large_originals_and_backups/` — 4K video originals, hero/audio backups, old HTML versions (~316 MB)
  - `other_pages/` — old standalone `about.html`, `impressum.html`, `EXTENDED_CREDITS.md` (NOT used by the single-page site; About/Impressum live inside the index overlay)
- This `_DEPLOY_README.md` is just a note (harmless if it ships, but not needed).

## Already optimized — don't redo
Videos were compressed 4K → 1080p (CRF 20, muted). Originals are in the TEMP folder. Posters (first frame) are in `img/posters/`.

— prepared 2026-06-15
