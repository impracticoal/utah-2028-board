# Utah 2028 Mega Board

A combined recruiting board tracking the University of Utah's 2028 football recruiting class, pulling ratings, predictions, and visit data from 247Sports and On3 into a single view.

**Live site:** https://impracticoal.github.io/utah-2028-board/

## What's on the board

- **All** — every tracked prospect with combined 247/On3 ratings
- **Utah Leading** — prospects where Utah is the current favorite
- **Crystal Ball** — real named-analyst predictions (247 Crystal Ball + On3 expert picks)
- **Committed Elsewhere** — tracked prospects who committed to another school
- **Visits** — official/unofficial visits to Utah
- **Utah Top 5** — prospects listing Utah among their top programs, with lean percentages where available

## How it stays updated

The board is regenerated automatically on an hourly cycle by a scraper that pulls fresh data from 247Sports and On3 and rewrites this page's data in place. It only pushes an update when something on the board actually changed.

## Roster

The tracked prospect list is a fixed roster for the 2028 class — it isn't self-expanding from every name either site mentions, so additions to the board are deliberate rather than automatic.

## Data sources

- [247Sports](https://247sports.com) — team targets pages, Crystal Ball predictions
- [On3](https://www.on3.com) — recruiting rankings (RPM), expert predictions, visits, offers
