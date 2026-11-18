# NEXUS ARCHIVE v3.1

**AntManThePro × GROK** — living portfolio vault.

v3.1: vault + live links. One brand card removed and two links re-pointed during the v3.1 cleanup (see git history).

Open `index.html` in any modern browser. Add to Home Screen — custom hex icon included.

## Why v3 exists

v2's classified layer leaked the PROTOCOL card into ALL, treated `godmode` as a search hijack (hiding the actual GodMode engine), and never felt like a vault — just another card. v3 rebuilds that as a real access control surface.

## Unlock the vault (pick one)

- Type exactly: `protocol` · `//protocol` · `vault` · `classified` · `nexus-7`
- Click the locked **VAULT** chip and enter a callsign
- Triple-click the hex logo
- Type `PROTOCOL` anywhere outside the search box
- Console: `NEXUS.unlock('protocol')`
- Deep link: `index.html#unlock=protocol`

`godmode` and `antman` stay as normal search terms so flagship artifacts remain findable.

State persists for the tab (`sessionStorage`). Close the tab to reseal.

## Views

- **GRID** — ranked cards, live search, tag filters, expand-to-spec
- **CONSTELLATION** — force-directed tag graph, drag nodes, click to open
- **VAULT** — classified terminal + sealed artifacts (after unlock)

## Keyboard

| Key | Action |
|-----|--------|
| `/` | Focus search |
| `Ctrl/Cmd+K` | Command palette |
| `?` | Surprise artifact |
| `g` `c` `v` | Grid / Constellation / Vault |
| `Esc` | Close overlays |
| `j` / `k` | Next / prev card |

## Stack

Vanilla HTML/JS/CSS. Canvas particle field + per-card generative headers + force graph. Zero build step. PWA manifest + icons for Home Screen.

## Repo layout

```
index.html
manifest.webmanifest
README.md
icons/icon.svg
icons/icon-180.png   (Apple touch)
icons/icon-192.png
icons/icon-512.png
icons/favicon-32.png
```
