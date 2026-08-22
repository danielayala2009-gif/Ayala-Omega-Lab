# Ω-Lab — Blind Localization Simulator
Version 1.5 PWA deployment package

## Run locally
From this folder:
`python3 -m http.server 8000`
Then open `http://localhost:8000`.

## GitHub Pages
Upload all files to a GitHub repository root, then enable Settings → Pages → Deploy from branch → main → root.

## Frozen scientific core
Benchmark Protocol v1.0 remains fixed:
2,700 deterministic trials; seed base 20260821; ±25 MeV hit tolerance; Ω blend, pointwise max, χ² window, shape TV; amplitudes 0.25/0.50/1.00/2.00%; noise 0.10/0.30/0.60%; correlation 0.00/0.40/0.80; 56 bins; 25 replications per parameter cell.

Packaging changes must not alter this frozen battery without a new scientific version.


## Licensing and attribution

- Original Ω-Lab software: **AGPL-3.0-or-later**
- Original research documentation/data when explicitly released as such:
  **CC BY 4.0**
- Third-party material: original licenses remain controlling.
- Project identification: **Ω-Lab™**
- Copyright: **© 2026 Daniel Ayala Feliciano**

Please retain `CITATION.cff`, `NOTICE.md`, `COPYRIGHT.md`, and
`SCIENTIFIC_VERSION_NOTICE.md` in redistributed official-source packages.

Before making the GitHub repository public, use GitHub's built-in
**GNU Affero General Public License v3.0** template to add the complete
verbatim license text.
