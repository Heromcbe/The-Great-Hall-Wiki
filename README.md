# The Great Hall Wiki

Source for https://wiki.thegreathall.world/ — built with MkDocs + Material.

- Pages live in `docs/` (one folder per server, shared pages in `docs/network/`).
- Navigation and settings are in `mkdocs.yml`.
- Pushing to `main` rebuilds and publishes the site automatically (`.github/workflows/deploy.yml`).
  The build runs in strict mode, so a broken link fails the build instead of going live.

## Preview locally (optional)

    pip install -r requirements.txt
    mkdocs serve

Then open http://127.0.0.1:8000

## Rules for editing

- Never post server addresses, IPs, ports, or passwords. Access is through Discord only: https://discord.gg/PNdRF6eg5j
- The rules PDF is the official rulebook. Rules pages here are summaries that link to it.
- Only document features that are verified working in-game.
