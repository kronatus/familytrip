# Family July Routing Map

An interactive map-based travel interface showing a family's multi-leg journey across three continents in July 2026.

## Features

- **Real Leaflet map** with CartoDB Dark basemap
- **9 color-coded flight legs** with curved routes
- **Interactive popups** showing destination, date, travelers, airline, and fare on hover/tap
- **Responsive legend cards** with trip details
- **Mobile-friendly** design with touch support
- **No backend required** — fully static HTML/CSS/JS

## Deployment

### Vercel (recommended)

1. Push this repo to GitHub
2. Connect to Github Pages
3. Pages auto-deploys on every push, link provided in pages tab — done!

### Other hosts

Any static host works: Netlify, GitHub Pages, AWS S3, etc. Just serve `index.html`.

## Local development

```bash
# No build step needed — just serve the file
python -m http.server 8000
# or
npx http-server
```

Then visit `http://localhost:8000`

## File structure

```
.
├── index.html       # Main page
├── package.json     # Metadata (optional for Vercel)
├── README.md        # This file
└── .gitignore
```

## Technologies

- **Leaflet.js** — map rendering
- **CartoDB basemap** — dark theme tiles
- **Vanilla JS** — no frameworks
- **CSS Grid/Flexbox** — responsive layout
- **Google Fonts** — Space Grotesk + IBM Plex Mono

## Customization

Edit the `legsData` array in `index.html` to change flights, dates, prices, or travelers. Update `cities` object to add/modify airports.

## License

MIT — use freely for personal or commercial projects.
