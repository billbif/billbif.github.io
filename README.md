# billbif.github.io

Static GitHub Pages portfolio built with native HTML, CSS, and JavaScript. No build step or framework is required.

## Structure

- `index.html` — portfolio home and featured projects
- `projects/` — standalone project pages
- `css/style.css` — shared responsive visual layout
- `js/sidebar.js` — shared sidebar navigation and mobile drawer
- `images/` and `assets/` — future images and downloadable assets

## Local preview

From the repository root, run `python3 -m http.server 8000`, then open `http://localhost:8000/`.

## Adding a project

Create a page in `projects/`, assign its `<body>` a unique `data-page`, then add its filename and anchors to the `items` array in `js/sidebar.js`.
