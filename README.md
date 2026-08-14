# BST Visualizer & Debugger

A free, browser-based tool that runs your own Python binary search tree / n-ary tree
code with a real Python interpreter (via [Pyodide](https://pyodide.org)) and visualizes
execution line by line — the tree redrawn at every step, current line highlighted, and
the live recursion path traced across the tree.

Everything runs client-side. No code is ever sent to a server.

## Deploying to GitHub Pages

1. Create a new GitHub repo (or use an existing one).
2. Put `index.html`, `robots.txt`, and `sitemap.xml` in the repo root (or in a `/docs`
   folder if you prefer — just point GitHub Pages at whichever you use).
3. In the repo's **Settings → Pages**, set the source to the branch/folder containing
   these files.
4. Your site will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Before you publish — replace these placeholders

Search `index.html`, `robots.txt`, and `sitemap.xml` for `YOUR-USERNAME` and `YOUR-REPO`
and replace with your actual GitHub Pages path, e.g. `janedoe.github.io/bst-debugger/`.
These appear in:
- `<link rel="canonical">`
- Open Graph (`og:url`, `og:image`) and Twitter meta tags
- the JSON-LD structured data block
- `robots.txt`'s `Sitemap:` line
- `sitemap.xml`'s `<loc>`

## Optional: add a social preview image

The meta tags reference `og-image.png` (1200×630px) for link previews on Twitter/X,
LinkedIn, Slack, etc. Add that file to the repo root, or remove the `og:image`/
`twitter:image` tags if you'd rather skip it — the page will still work and still be
indexed fine without one.

## Local testing

Just open `index.html` directly in a browser — no build step, no server required.
(First load takes a few seconds while Pyodide downloads the Python runtime from its CDN.)
