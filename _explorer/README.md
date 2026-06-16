# Explorer

Self-contained interactive explorer for the vault. Single HTML file that consumes three JSON data files and renders:

- **Topics tab** -- 9 curated entry-point cards
- **Timeline tab** -- drag-through 1981-2026 events (vis-timeline)
- **Power Map tab** -- force-directed entity graph (Cytoscape.js + cose-bilkent layout)
- **Ask the Vault** -- chat widget stub. Backend not yet connected -- see `00-Home/Future Builds.md`.

## Files

- `index.html` -- the explorer page (uses CDN libraries, no build step)
- `topics.json` -- 9 topic-card definitions
- `timeline.json` -- ~47 documented events
- `graph.json` -- ~81 nodes + ~97 edges + cluster legend

## Hosting

Three options:

1. **Open locally**: open `index.html` directly in any browser
2. **GitHub Pages on the vault repo**: enable Pages with source = main / root, then visit `https://terry1818.github.io/cambridge-analytica-vault/_explorer/`
3. **Embedded in Quartz site**: copy `_explorer/` into the Quartz site repo under `static/explorer/` and link from there

## Regenerating data

Run `p33_build_explorer_data.ps1` to regenerate the three JSON files. Re-run any time the vault changes substantively.

## Next-level builds

See `00-Home/Future Builds.md` for architecture sketches: Ask the Vault Q&A chatbot, long-form articles, mobile PWA wrapper.

## License

CC BY-SA 4.0, matching the vault.