# Golf Lounge -suunnittelija
- Offline single file: `golf-lounge-suunnittelija.html` (double-click; also the file to publish as a web page).
- Dev version: `index.html` + `app.bundle.js` (works from file:// too). Sources: `app.js`, `textures.js`, `catalog.js`, `style.css`.
- Rebuild after edits: `./build.sh` (npm installs three@0.160.0 + esbuild into node_modules on first run).
- Add catalog items in `catalog.js` (or the "EDITABLE CATALOG" block in the single file).
- Textures are procedural (drawn on canvas in `textures.js`), no external image files, no licence obligations.
- Quality: matala (tablet) / korkea (shadows) / esittely (shadows + GTAO ambient occlusion + bloom).
- To publish on GitHub Pages: push `golf-lounge-suunnittelija.html` as `index.html` to a public repo and enable Pages.
