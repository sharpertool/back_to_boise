# Trip maps — Ed and Vicki Henderson

Trip maps on this GitHub Pages site. The October return is unchanged. Christmas 2026 Heber, the Leavenworth alternate, and the Phoenix scenic run each have their own folder.
Family Christmas 2026 (snow + hot springs shortlist): https://sharpertool.github.io/back_to_boise/family-christmas-2026/

## Phoenix 2026 — scenic run to Phoenix

Three weeks, planning only: an unhurried week down from Boise, a week with family in Phoenix, a week back. F-350 and the X195. No black tank. The map opens on Boise.

| Page | URL |
|---|---|
| **Map** | https://sharpertool.github.io/back_to_boise/phoenix-2026/ |
| **Locations** | https://sharpertool.github.io/back_to_boise/phoenix-2026/locations.html |
| Tonight (home) | https://sharpertool.github.io/back_to_boise/phoenix-2026/tonight.html |
| Tomorrow (Elko-area first night) | https://sharpertool.github.io/back_to_boise/phoenix-2026/tomorrow.html |

Four toggleable routes plus a dashed US-93 reference. Middle corridor is I-15 through Salt Lake and St. George (Route A). East of the Wasatch is Provo, Price, Green River, then US-89 (Route D). West is US-93 through Ely (the reference, and Route C as far as Ely before it turns east to Delta). Route B leaves I-15 at St. George for Kanab and Page and does not use the Zion tunnel. Orange is home. Green is a named public-land search. Light blue is a paid campground or park. Gold squares are two-day sit ideas. Purple stars are outings. White diamonds are viewpoints.

## Leavenworth 2026 — alternate Christmas (Wenatchee Valley)

Alternate to Heber Valley, not a stop on that trip. Still home in Boise; nothing is locked. Recommended base is Wenatchee Confluence State Park, with day trips into Leavenworth.

| Page | URL |
|---|---|
| **Map** | https://sharpertool.github.io/back_to_boise/leavenworth-2026/ |
| **Locations** | https://sharpertool.github.io/back_to_boise/leavenworth-2026/locations.html |
| Tonight (home) | https://sharpertool.github.io/back_to_boise/leavenworth-2026/tonight.html |
| Tomorrow (first overnight idea) | https://sharpertool.github.io/back_to_boise/leavenworth-2026/tomorrow.html |

Drive is I-84 to I-82, then US-97 over Blewett Pass and US-2 to Wenatchee. The map opens on Boise. Orange is the current sit. Light blue is one pin per winter campground. The purple star is Leavenworth Christmastown / Village of Lights. White diamonds are skipped or closed places. No dispersed pins.

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
