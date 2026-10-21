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

## Report a site

Open an [issue](https://github.com/allixsenos/phpocalypse-tracker/issues/new/choose). Give the site, a link that shows it went dark or came back, and the time if you know it. Each report is checked before it goes on the list.

This repository does not accept pull requests. Pull requests are closed without review.
