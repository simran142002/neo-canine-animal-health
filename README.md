# Neo Canine Animal Health — Website

A static marketing site for Neo Canine Animal Health's hemp wellness product line.

## Structure
- `index.html` — page content
- `styles.css` — design system & layout
- `script.js` — small runtime bits (footer year)
- `images/` — logo and product photography (extracted from the product brochure)

## Running locally
Any static file server works, e.g.:

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploying with GitHub Pages
1. Push this repo to GitHub.
2. In repo Settings → Pages, set the source to the `main` branch, root folder.
3. (Optional) Add a custom domain under Settings → Pages → Custom domain, and point your domain's DNS `A`/`CNAME` records at GitHub Pages.
