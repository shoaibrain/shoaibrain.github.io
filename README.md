# shoaibrain.github.io

My personal site, served at **<https://shoaibrain.github.io>**.

One page, one column, one typeface, no JavaScript, no build step.

| File | Purpose |
|------|---------|
| `index.html` | The page. All of the content lives here. |
| `styles.css` | ~90 lines. Colors are CSS variables at the top. |
| `favicon.svg` | The "SR" monogram tab icon. |
| `404.html` | Not-found page, same shell. |
| `.nojekyll` | Serve the files as-is; skip the Jekyll build. |

## Editing

Change the prose in `index.html`. To adjust the look, edit the variables at the
top of `styles.css` — `:root` for light, the `prefers-color-scheme: dark` block
for dark. The theme follows the operating system; there is no toggle.

Preview by opening `index.html` in a browser, or:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Publishing

The repository is named `shoaibrain.github.io`, so GitHub Pages publishes it as
a user site from `main`. Push to `main` and the site updates in a minute or two.
If it doesn't, check **Settings → Pages** reads *Deploy from a branch →
`main` / `(root)`*.
