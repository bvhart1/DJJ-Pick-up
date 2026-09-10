# DJJ-Pick-up

A single-page checklist for a 34-stop DJJ site visit route, grouped into four legs (Panhandle, Northeast, Central, South). For each stop you can call ahead, get driving directions, and check it off — progress is saved in your browser (`localStorage`) so it persists between visits on the same device.

## Running it

Just open `index.html` in a browser, or serve the repo with any static file host.

## GitHub Pages

This repo includes a workflow (`.github/workflows/deploy.yml`) that deploys `index.html` to GitHub Pages automatically on every push to `main`.

To turn it on (one-time setup): go to **Settings → Pages** and set **Source** to **GitHub Actions**. After that, the site will be published at `https://<owner>.github.io/DJJ-Pick-up/` and stay up to date automatically.
