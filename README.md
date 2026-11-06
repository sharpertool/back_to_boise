# Trip maps — Ed and Vicki Henderson

Two trips on this GitHub Pages site. The October return is unchanged. Christmas 2026 is a separate folder.

## Christmas 2026 — Boise to Heber Valley

Planning map for about Dec 20–31, 2026. Still home in Boise; nothing is locked. Suggested base is Mountain Valley RV Resort in Heber (Wasatch Mountain State Park, Soldier Hollow, is the other base to compare), with an optional night at Echo State Park.

| Page | URL |
|---|---|
| **Map** | https://sharpertool.github.io/back_to_boise/christmas-2026/ |
| **Locations** | https://sharpertool.github.io/back_to_boise/christmas-2026/locations.html |
| Tonight (home) | https://sharpertool.github.io/back_to_boise/christmas-2026/tonight.html |
| Tomorrow (first overnight idea) | https://sharpertool.github.io/back_to_boise/christmas-2026/tomorrow.html |

Drive is I-84 to I-80 through Echo Canyon, then US-40 into Heber Valley. The map opens on Boise. Orange is the current sit. Light blue is one pin per paid winter campground. Purple stars are the North Pole Express and Park City. White diamonds are skipped or closed places. No dispersed pins.

## Back to Boise — October 2026 return

Interactive map + locations table for the finished mid-October return:
**Custer SD (Wabash) → Devils Tower WY → Casper → Rock Springs/I-80 → Lava Hot Springs ID → Boise/Meridian**.

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

Status: Cedar Pass Sat Oct 10 → Black Hills Oct 11–17 → Devils Tower Oct 17.
Last connectivity check: 2026-10-16.
