# NEXUS ARCHIVE v3.1

**AntManThePro × GROK** — living portfolio vault. 41 artifacts, floating in space — a grid, a constellation map, and a sealed vault for the classified ones.

Live: https://nexus-archive-v3.netlify.app/

## How to use

1. Open the live site — the grid shows every artifact, ranked, with live search and tag filters. Click a card to open its spec.
2. Switch views with the **GRID / CONSTELLATION / VAULT** tabs, or press `g` `c` `v`. Constellation is a drag-the-nodes tag map.
3. Press `/` to search, `Ctrl/Cmd+K` for the command palette, `?` for a surprise artifact.
4. The vault and live links are gated on purpose — follow the unlock steps below. Close the tab to reseal; nothing persists past the tab.

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
icons/icon-180.png
icons/icon-192.png
icons/icon-512.png
icons/favicon-32.png
icons/favicon.ico
icons/favicon-192.png
icons/favicon-512.png
icons/apple-touch-icon.png
```

## Links

- Live site: https://nexus-archive-v3.netlify.app/
- NEXUS World Hub: https://nexus-world-hub.netlify.app/
- Repo: https://github.com/AntManThePro/nexus-archive-v3
