# FOAMfrat Rhythm Lab — The SA Node Drives the Beat

An interactive, single-file web lesson that visualizes how the sinoatrial (SA) node initiates the cardiac impulse and how that maps onto the surface ECG. Built for nurses and EMS professionals as part of FOAMfrat's continuing-education content.

## Live demo

The lesson is live at:

**https://rhythm.foamfratsandbox.com/**

(Also served by GitHub Pages at `https://tylerchristifulli.github.io/foamfrat-rhythm-lab/`.)

## What's inside

The entire lesson is a single, dependency-free `index.html` — HTML, CSS, and JavaScript in one file. No build step, no frameworks, no external assets. Open it in any modern browser and it runs.

## Run locally

Just open the file:

```bash
open index.html        # macOS
```

Or serve it (useful for testing as it would behave on Pages):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Enabling GitHub Pages

1. Push this repo to GitHub (see below).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, branch **main**, folder **/ (root)**.
4. Save. Your lesson will publish at the URL shown above.

## License

© FOAMfrat. All rights reserved. This material is proprietary educational content and may not be copied, redistributed, or reused without permission.
