# Quantum Cats — the website

One file: `index.html`. Everything (map, simulation, pages, styles) is inside it.

## Hosting (GitHub Pages)
The repo `quantumcats-site` is published with GitHub Pages at quantumcatssol.com (the `CNAME` file in the repo holds the domain).
To update the site: open `index.html` in the repo → pencil icon → replace the contents with the new file → commit. Pages redeploys in about a minute.

## Settings
At the top of the script in `index.html`, the `CONFIG` block:
- `BRAIN_URL` — the brain's URL. Empty = the page runs its own demo simulation. Set = the page shows the shared box from the server.
- `CA`, `BUY_URL`, `CHART_URL`, `X_URL`, `TG_URL` — used when there is no brain; with a brain, the admin panel's values win.
- `SOL_USD`, `START_MC_USD` — the demo chart.
