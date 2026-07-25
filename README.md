# shoaibrain.github.io

My personal website & developer portfolio, served at
**<https://shoaibrain.github.io>**.

It's a single static page — plain HTML and CSS with a few lines of vanilla
JavaScript. No build step, no framework, no dependencies to install.

## Structure

| File | Purpose |
|------|---------|
| `index.html` | The page itself (Hero · About · Now · Skills · How I work · Contact). |
| `styles.css` | All styling and the light/dark theme tokens. |
| `script.js` | Theme toggle (remembers your choice) + footer year. |
| `favicon.svg` | The "SR" monogram tab icon. |
| `404.html` | Styled not-found page. |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is (no Jekyll build). |

## Editing

Just edit `index.html` — the content is plain, well-labelled HTML. To change the
look, the color and font tokens live at the top of `styles.css` (`:root` for
light, `[data-theme='dark']` for dark).

Preview locally by opening `index.html` in a browser, or run a tiny static
server from this folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## How it publishes

This repository is named `shoaibrain.github.io`, so GitHub Pages automatically
publishes it as a **user site** from the default branch (`main`). Pushing to
`main` updates <https://shoaibrain.github.io> within a minute or two.

If the site isn't live, check **Settings → Pages** and confirm the source is
**Deploy from a branch → `main` / `(root)`**.

## Ideas for later

- A **Projects** section with cards for individual repos.
- A **custom domain** (add a `CNAME` file + a DNS record).
- Links to **LinkedIn / X** or a **résumé PDF**.
