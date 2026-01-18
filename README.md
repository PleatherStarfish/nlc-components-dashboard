# NLC Components Explorer

A beautiful, vaporwave-styled data visualization site exploring the component DNA of **100 Nonlinear Circuits Eurorack modules**.

🌐 **[View Live Site](https://yourusername.github.io/nlc-components/)**

## About

This site provides an interactive exploration of Bill of Materials (BOM) data from Andrew Fitch's legendary [Nonlinear Circuits](https://www.nonlinearcircuits.com/) DIY synthesizer modules. All data is processed live from the source CSV — no hardcoded values!

## Data Visualizations

- **Component Taxonomy** — Category breakdown by type and quantity
- **The Usual Suspects** — Most ubiquitous components across modules
- **Resistor Cartography** — Value distribution and decade analysis
- **Capacitor Spectrum** — From picofarads to millifarads
- **Silicon Census** — Op-amps and specialty ICs
- **Transistor Territory** — Discrete semiconductors analysis
- **Complexity Spectrum** — Module complexity scatter plot
- **Specialization Index** — Modules with most unique components
- **One of a Kind** — Single-module components
- **Component Companions** — Co-occurrence patterns

## Tech Stack

- Pure HTML/CSS/JavaScript (no build step)
- [PapaParse](https://www.papaparse.com/) for CSV parsing
- [Chart.js](https://www.chartjs.org/) for data visualizations
- Google Fonts (Orbitron + Rajdhani)
- Vaporwave color palette: `#F2507B` `#5F1773` `#26BF94` `#F2D64B` `#F2836B`

## Files

```
├── index.html    # Main visualization page
├── data.csv      # Source BOM data
└── README.md     # This file
```

## Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Upload both `index.html` and `data.csv` to the repository
3. Go to Settings → Pages
4. Set source to "Deploy from a branch" and select `main` / `root`
5. Your site will be live at `https://yourusername.github.io/repo-name/`

## Updating Data

Simply replace `data.csv` with updated BOM data. The CSV should have these columns:
- `_module` — Module name
- `_source_file` — Source PDF filename
- `VALUE` — Component value/name
- `QUANTITY` — Quantity needed
- `DETAILS` — Optional notes

## License

Data belongs to Nonlinear Circuits. Visualization code is MIT licensed.

---

*Made with 💜 for the DIY synth community*
