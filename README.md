# RoninSec

Source for the RoninSec website, the umbrella brand for my projects and sub-brands.
Live at https://r0n1n9.github.io/roninsec/

## Structure

| Path | Site |
|---|---|
| `index.html` | RoninSec home: the three pillars, project links, journal, network |
| `recon/index.html` | RoninRecon (travel, aerial photo and video) → `/roninsec/recon/` |

To add a sub-brand, create a folder (for example `rhythm/`) with its own `index.html`.
It goes live at `/roninsec/rhythm/`.

## Pillars and projects

- **Past · Inner Terrain**: monogatari, haiku
- **Present · Field Craft**: vigilance, vigil
- **Future · Digital Recon**: katana, karambit

No build step. `.nojekyll` tells GitHub Pages to serve the files as-is.
