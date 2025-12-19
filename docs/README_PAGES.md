# GitHub Pages Setup

This package provides a GitHub Pages-ready portal using **Jekyll** (Cayman theme).

## Where to place files
Copy these into the root of your public docs repo:
- `SECURITY.md`
- `NOTICE.md`
- `_config.yml`
- `/docs/` (folder)

## Enable GitHub Pages
Repository → **Settings → Pages**
- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

The portal homepage is:
- `docs/index.md`

Your Pages URL will be:
- `https://<org>.github.io/<repo>/docs/`

> Keep content in `/docs` to keep the repo root tidy.
