# Christina's Hair Salon

Website for Christina's Hair Salon (Hair Couture), Milpitas, CA. Plain HTML, CSS and JS with no build step.

Live preview: https://markdv03.github.io/Christinas-salon/ (GitHub Pages, deploys on every push to `main`).

## Files

- `index.html`: the whole site, one page. Sections in order: hero, offer, services and prices, rebonding and keratin, our work and before and after, about, team, hours and location, request form.
- `styles.css`: styles, grouped in the same order as the page. Phone first, with tablet and desktop rules at the end.
- `script.js`: menu, open-now hours, photo viewer, before and after slider, form checks, scroll animations.
- `assets/img/`: site photos as WebP. `*-sm.webp` are square thumbnails for the photo collage; the full photo opens in the viewer.
- `404.html`, `robots.txt`, `sitemap.xml`, `favicon.svg`, `apple-touch-icon.png`, `assets/img/share.jpg` (link preview image).

After changing `styles.css` or `script.js`, bump the `?v=` number on both in `index.html` so phones load the new version.

Before launch: remove the `noindex` line in `index.html` once Christina approves the site.
