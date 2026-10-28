# PFI 3D Form Builder

Interactive 3D model of Pocket Form Isolator forms, used on pocketformisolator.com.

| Page | What it is | Used where |
|---|---|---|
| `index.html` | Full builder: shape, size, depth, views, parts list, build-it-yourself mode | 3D Builder page on the site; trade shows and sales meetings |
| `hero.html` | Compact model with shape chips and build mode | Home page hero (Wix "Embed a site" box) |
| `engine.js` | The 3D engine (three.js bundled), shared by both pages | — |

Live at https://wyattotto.github.io/pfi-3d/ (full builder) and https://wyattotto.github.io/pfi-3d/hero.html (hero).

To update the model, replace `engine.js` (or edit the pages) and push to `main`. GitHub Pages republishes in a minute or two and the Wix site shows the new version on its own; no Wix edits needed.
