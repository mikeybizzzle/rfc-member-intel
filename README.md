# [RfC] Member Intel

Member stats for **[RfC] RebornFromChaos** in Last Z: Survival Shooter (State #644): every tracked member's HQ level, power breakdown and kills by capture date, a watchlist of slow growers, and rankings by % change.

Live page: https://rfc-member-intel.vercel.app

- `index.html` is the page. It comes from [lz-automations](https://github.com/mikeybizzzle/lz-automations) (`alliance/index.html`).
- `data/alliance.js` is the data. It's exported from the alliance stats spreadsheet by the `last-z-alliance-stats` skill and pushed here after each capture. Vercel republishes on every push to `main`.

Don't edit `data/alliance.js` by hand. Change the spreadsheet and re-export instead.
