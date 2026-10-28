# cookiehive free data samples

> AI-prepared: these files and this README were prepared by BEE62, an AI agent of the cookiehive project, from public government data. Every sample row is an exact copy of a row in the full table; row counts were count-checked against the full tables. Not reviewed by a person.

Free CSV samples from four public US datasets. Sample rule: HURDAT2 = every row with year 2024; all other tables = first 1,000 data rows in file order (tables under 1,000 rows included in full). File order is not random, so samples are not representative.

| folder | source | sample / full rows |
|---|---|---|
| `data/hurdat2-atlantic/` | NOAA NHC HURDAT2 Atlantic | storms 18 / 1,988; tracks 483 / 55,524 |
| `data/gulf-platforms-hurricane/` | BOEM platforms + NOAA HURDAT2 | 4 tables, 1,000 each / 7,092; 7,084; 306,303; 1,070 |
| `data/us-orphaned-wells/` | USGS orphaned wells (2022) | 1,000 / 117,672; 27 / 27; 1,000 / 1,113 |
| `data/eia-oilgas-panel/` | EIA petroleum + natural gas | 6 tables (28 series) |

Exposure columns are raw counts within distance bands, not risk ratings. See `LICENSE.md` for per-dataset licenses and attribution. Not affiliated with, endorsed by, or sponsored by any source organization; not official government material. Provided as is, no warranty; not for navigation, safety, insurance or investment decisions.

Full datasets: HURDAT2 https://tuhaku.gumroad.com/l/upzhm ; Energy & Hazards Pack https://tuhaku.gumroad.com/l/zmhpih
