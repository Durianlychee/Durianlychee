# Assets

Everything the profile README renders is stored here, so nothing depends on a third-party service at view time.

- `banner-*.svg`, `h-*.svg`, `toolbox-*.svg`, `rule-*.svg`: hand-written, self-contained SVGs (no scripts). `-light` and `-dark` variants are swapped by `<picture>` in the README. Animation is plain CSS inside the SVG and is switched off under `prefers-reduced-motion`.
- `icons/`: the individual tool glyphs used in the toolbox strip.

## Icon sources

- Python, Power BI, Pandas, scikit-learn, Excel, TypeScript, Astro: paths taken from [simple-icons](https://github.com/simple-icons/simple-icons) v9.21.0, licensed CC0 1.0. That version is used because later releases dropped the Microsoft glyphs (Power BI, Excel). Colours are the brand colours, lightened in the dark variants where needed for contrast.
- Docker, FastAPI: paths taken from simple-icons v9.21.0 (CC0 1.0), as above.
- n8n: path taken from [simple-icons](https://github.com/simple-icons/simple-icons) v16.38.1, licensed CC0 1.0 (the n8n glyph is absent from v9.21.0). Brand colour, lightened in the dark variant.
- SQL (database cylinder) and DAX ("fx" mark): no official glyph exists in a permissive icon set, so these are simple original marks drawn for this repo.

Product names and logos are trademarks of their respective owners.
