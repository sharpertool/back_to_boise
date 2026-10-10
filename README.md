# Back to Boise — return map

Interactive Folium map + locations table for Ed Henderson’s mid-October return:
**Blue Mounds MN → SD → Devils Tower WY → Casper → Rock Springs/I-80 → Lava Hot Springs ID → Boise/Meridian**.

## Live pages (after GitHub Pages / CDN)

Once this repo is published (`sharpertool/back_to_boise`):

| Page | GitHub Pages (preferred) | jsDelivr fallback |
|---|---|---|
| **Map** | https://sharpertool.github.io/back_to_boise/ | https://cdn.jsdelivr.net/gh/sharpertool/back_to_boise@main/index.html |
| **Locations** (water/closes) | https://sharpertool.github.io/back_to_boise/locations.html | https://cdn.jsdelivr.net/gh/sharpertool/back_to_boise@main/locations.html |

> Placeholder until Pages is enabled. Prefer Pages URLs once `gh api .../pages` succeeds; otherwise use jsDelivr.

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

Cedar Pass is **LOCKED** as the next overnight (departed Luverne Sat Oct 10 2026). Do not email Vicki.
