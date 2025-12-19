# GitHub Pages Setup

This package provides a GitHub Pages-ready portal using **Jekyll** (Cayman theme) + Softnifty brand styling.

## Files included
- `README.md` (root) with a clear portal entry link
- `SECURITY.md` (public disclosure)
- `NOTICE.md` (public-safe, non-commercial reuse)
- `_config.yml`
- `/assets/css/style.scss` (Softnifty colors + buttons + callouts)
- `/docs/*` (portal pages)
- Optional: `/.github/*` (docs link-check workflow)

## Enable GitHub Pages
Repository → **Settings → Pages**
- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

Portal homepage:
- `docs/index.md`

Your Pages URL:
- `https://<org>.github.io/<repo>/docs/`
