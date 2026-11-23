# Assets

Everything the profile README renders is stored here, so nothing depends on a third-party service at view time.

- `banner-*.svg`, `h-*.svg`, `toolbox-*.svg`, `rule-*.svg`: hand-written, self-contained SVGs (no scripts). `-light` and `-dark` variants are swapped by `<picture>` in the README. Animation is plain CSS inside the SVG and is switched off under `prefers-reduced-motion`.
- `icons/`: the individual tool glyphs used in the toolbox strip.

## Icon sources

- Python, Power BI, Pandas, scikit-learn, Excel, TypeScript, Astro: paths taken from [simple-icons](https://github.com/simple-icons/simple-icons) v9.21.0, licensed CC0 1.0. That version is used because later releases dropped the Microsoft glyphs (Power BI, Excel). Colours are the brand colours, lightened in the dark variants where needed for contrast.
- SQL (database cylinder) and DAX ("fx" mark): no official glyph exists in a permissive icon set, so these are simple original marks drawn for this repo.

Product names and logos are trademarks of their respective owners.
