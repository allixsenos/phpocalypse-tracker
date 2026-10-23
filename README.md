# PHPocalypse Tracker

A list of sites that went offline because of the October 2026 PHP remote code execution flaws (CVE-2026-109618 and CVE-2026-109619), and when they came back.

Live page: https://allixsenos.github.io/phpocalypse-tracker/

## Data

All data is in [`sites.csv`](sites.csv). Times are UTC.

| Column | Meaning |
|---|---|
| `name` | The site or organization |
| `url` | The address that went dark |
| `country` | ISO country code, if the site is national |
| `type` | `government`, `university`, `platform` or `site` |
| `dark_since` | Time of the first public report that the site is dark |
| `back_up` | Time the site was first seen up again. Empty means it is still dark |
| `source` | Link to the report |
| `notes` | What the site shows, and any caveats |

## Status

All sites reported dark have recovered. Automated tracking stopped on 23 October 2026.

The page shows an estimated "time dark" for each site. It runs from `dark_since` to `back_up`. Because `dark_since` is the first public report, the real outage was often longer.

## Correct or expand the record

Pull requests are welcome. Edit `sites.csv`, and give a source link for every change. You can also open an [issue](https://github.com/allixsenos/phpocalypse-tracker/issues/new/choose) with the site, a source link and the time if you know it.
