# Himalayan Institute Course Board

A single-page reference to every programme run by eight Indian mountaineering and adventure institutes, with sanctioned intake per course and — where the institute publishes it — seats remaining on each batch.

**Institutes covered**

| Institute | Location | Seat data |
|---|---|---|
| HMI — Himalayan Mountaineering Institute | Darjeeling, WB | live seats per batch |
| NIM — Nehru Institute of Mountaineering | Uttarkashi, UK | sanctioned intake |
| JIM & WS — Jawahar Institute of Mountaineering & Winter Sports | Pahalgam, J&K | vacancies + full/closed status |
| NIMAS — National Institute of Mountaineering & Adventure Sports | Dirang, AR | live seats per batch |
| ABVIMAS — Atal Bihari Vajpayee Institute of Mountaineering & Allied Sports | Manali, HP | sanctioned intake |
| SGMI — Sonam Gyatso Mountaineering Institute | Gangtok, SK | not published |
| HAWS — High Altitude Warfare School | Gulmarg / Sonamarg | not published (service only) |
| MSI — Mountaineering & Skiing Institute, ITBP | Auli, UK | not published (service only) |

Data captured **5 September 2026** from the institutes' own portals and published course programmes. Seat counts on HMI and NIMAS move daily — treat them as a snapshot, not a booking guarantee. Sources are linked in the page footer.

## Running it

`index.html` is a self-contained static page. No build step, no dependencies. Open it directly, or serve the folder:

```bash
python3 -m http.server 8000
```

## Publishing with GitHub Pages

Push this folder to a repository, then in **Settings → Pages** set the source to `main` / `/ (root)`. The page will be served at `https://<username>.github.io/<repo>/`.

## Updating

Edit `index.html` directly — the course tables are plain HTML, and every course row follows the same shape. Colours and type are set as CSS custom properties in the `:root` block at the top, with dark-theme values redefined below it.

## Licence

The page is free to reuse. Course data belongs to the respective institutes.
