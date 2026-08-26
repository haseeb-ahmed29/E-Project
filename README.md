# E-Project

E-Project is a static educational website focused on Nobel Prize history, award fields, laureates, galleries, and related information.

## Main pages

- `index.html` — home page
- `about.html` — project information
- `fields.html` — Nobel Prize fields
- `history.html` — historical information
- `winners.html` — laureate information
- `gallery.html` — image gallery
- `contact.html` — contact page
- `Sitemap.html` — navigation map

The project keeps page styles in `CSS/`, JavaScript in `JS/`, and visual assets in `images/`.

## Run locally

The site does not require a build step. Clone the repository and serve it with a local static server:

```bash
git clone https://github.com/haseeb-ahmed29/E-Project.git
cd E-Project
python3 -m http.server 8000
```

Open <http://localhost:8000> in a browser.

## Contribution guidelines

Keep links relative so the site works on GitHub Pages and local servers. When changing a page, check its navigation, linked assets, and responsive layout before opening a pull request.

## License

No license file is currently included. Add an explicit license before redistributing the project or its assets.
