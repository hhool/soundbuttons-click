# SoundButtons.click

Verbatim static clone of the soundbuttons.click site — **source only**.

| | |
|---|---|
| Target domain | `soundbuttons.click` |
| Pages | 28 (incl. feed fragments) |
| Audio | 3163 mp3 — **excluded** (427MB, see `.gitignore`) |
| Assets | CSS/JS/fonts/images fully localized |

## Structure

Repo root = site root (`index.html` at root). Deployable as-is to any static
host (GitHub Pages: Settings → Pages → main branch / root).

## Audio regeneration

`sounds/` is gitignored. To restore:

```bash
# option A — copy from canonical working copy
cp -r ~/Desktop/SEXTANT/sites/soundbuttons-click/clone/sounds/ .

# option B — re-clone with SEXTANT tools
python3 tools/clone_site.py https://soundbuttons.io --feed-pages 10 --target-domain soundbuttons.click
```

## Provenance

See `clone-manifest.json` for the full clone manifest (source, gaps,
compliance notes, asset edits).
