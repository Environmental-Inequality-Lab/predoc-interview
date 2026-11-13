# predoc-interview

Redirect page for **environmental-inequality-lab.github.io/predoc-interview**.

Visitors land on a short Environmental Inequality Lab page and are sent to the
[UVA Pre-Doctoral Associate interview scheduler](https://scheduler.zoom.us/d/wn0wz97y/uva-pre-doctoral-associate-interview-scheduling)
on Zoom after about three seconds. A button sends them right away.

## Files

- `index.html`: the redirect page (JavaScript redirect after 3 s, meta-refresh fallback after 4 s)
- `eil-logo.png`: EIL logo
- `.nojekyll`: tells GitHub Pages to serve the files as they are

## Changing the destination

The scheduler URL appears four times in `index.html` (meta refresh, canonical link,
button, script). Replace all four.

## Deploying

Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
