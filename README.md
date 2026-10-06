# Back to Boise — return map

Interactive Folium map + locations table for Ed Henderson’s mid-October return:
**Blue Mounds MN → SD → Devils Tower WY → Casper → Rock Springs/I-80 → Lava Hot Springs ID → Boise/Meridian**.

## Live pages

Primary (GitHub Pages — deploy from branch `main`, folder `/`):

| Page | URL |
|---|---|
| **Map** | https://sharpertool.github.io/back_to_boise/ |
| **Locations** (water/closes) | https://sharpertool.github.io/back_to_boise/locations.html |

Interim, until Pages is enabled (renders the raw HTML):

| Page | URL |
|---|---|
| **Map** | https://htmlpreview.github.io/?https://raw.githubusercontent.com/sharpertool/back_to_boise/main/index.html |
| **Locations** | https://htmlpreview.github.io/?https://raw.githubusercontent.com/sharpertool/back_to_boise/main/locations.html |

jsDelivr is not a substitute for these pages. It serves the HTML as `text/plain`, so browsers show source instead of the map or table.

## Files

- `index.html` — interactive map (hour labels @ ~70 mph tow; Lava Hot Springs on spine)
- `locations.html` — full table with **OnX**, phone, website, and **water available until / closes** column
- `locations.md` — markdown source
- `boise-from-blue-mounds.png` — static snapshot (optional)
- `make_return_map.py` — regenerator

## Legend

- ★ CURRENT sit (Blue Mounds)
- ● Orange = STAY overnight
- ◇ = VISIT pass-through / day
- ● Blue = later corridor stays (Casper, Rock Springs, Lava Hot Springs)
- ● Green = Home (Boise/Meridian)
- `N.N h` = estimated hours @ ~70 mph (OSRM ÷ 70)

## Regenerating

```bash
python make_return_map.py
```

Cedar Pass remains **PROVISIONAL**. Do not email Vicki.
