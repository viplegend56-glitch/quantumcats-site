# Quantum Cats — the website

One file: `index.html`. Everything (map, simulation, pages, styles) is inside it.

## Deploy with Netlify from GitHub
1. Put this folder in a GitHub repo (e.g. `quantumcats-site`).
2. Netlify → **Add new project → Import an existing project → GitHub** → pick the repo. Build command: none. Publish directory: `.`
3. Every push to `main` redeploys automatically. Git-connected sites don't get the Netlify badge.

## Settings
At the top of the script in `index.html`, the `CONFIG` block:
- `BRAIN_URL` — the brain's URL. Empty = the page runs its own demo simulation. Set = the page shows the shared block from the server.
- `CA`, `BUY_URL`, `CHART_URL`, `X_URL`, `TG_URL` — used when there is no brain; with a brain, the admin panel's values win.
- `SOL_USD`, `START_MC_USD`, `LAB_MC_USD` — the demo chart and the lab threshold.

## Editing
Edit `index.html` in GitHub's web editor (pencil icon) → commit → Netlify redeploys in under a minute.
