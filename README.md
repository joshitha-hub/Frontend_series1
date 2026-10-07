# Developer Community Sastra × GDG — Frontend Task

A responsive, accessible frontend interpretation for Developer Community Sastra × Google Developer Groups.

## Included

- Semantic HTML5 structure
- Responsive desktop/tablet/mobile layout
- Mobile navigation
- Scroll/reveal animations
- Interactive event buttons with accessible status feedback
- FAQ accordion
- Accessible skip link and focus-friendly controls
- Reduced-motion support
- No external JavaScript dependencies
- Deployment-ready static site

## Run locally

No build step is required.

1. Open `index.html` directly in a browser, or
2. Run a local server:

```bash
python3 -m http.server 5500
```

Then visit `http://localhost:5500`.

## Deploy

### Netlify
Drag the project folder into Netlify Drop, or connect the GitHub repository.

### Vercel
Import the GitHub repository. Framework preset: Other. Build command: none. Output directory: `.`

### GitHub Pages
Push the files to a repository and enable Pages from the repository settings.

## Project structure

```text
dcs-web-cluster-frontend/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
```

## Notes

The supplied task brief states that the implementation should follow a separate design file linked from the PDF. The linked Google Drive design was not embedded in the supplied PDF, so this project is a modified DCS × GDG community interpretation of the brief rather than a pixel-for-pixel reproduction of that unavailable design.

The brief requires responsive design, interaction, cross-browser compatibility, performance, accessibility, clean code structure, a Git repository, README and deployment. This project addresses those requirements in a static implementation.
