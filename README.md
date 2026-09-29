# Kyeongho Bang

A responsive academic website for Kyeongho Bang, a PhD student in mathematics at KAIST. No build step or dependencies are required.

## Pages

- `index.html`: About (the homepage), biography, education, and contact email.
- `research.html`: Research interests and publications/preprints.
- `teaching.html`: Teaching assistantships from Fall 2024 through Fall 2026.
- `styles.css`: Shared styling for all pages.

## Publish on GitHub Pages

1. Create the public repository `kyeonghobang0103.github.io` under `kyeonghobang0103`.
2. Add all three HTML files, `styles.css`, `.nojekyll`, and this README to the root of its `main` branch. Keep the files together.
3. In **Settings → Pages**, select **Deploy from a branch**, **main**, and **/ (root)**, then save.
4. After GitHub finishes publishing, the site will be available at https://kyeonghobang0103.github.io/.

Official guide: https://docs.github.com/en/pages/quickstart

## Edit

Edit the relevant HTML page and use `styles.css` for visual changes. When changing navigation, update it on all three pages. The site uses the supplied biography, education, teaching history, and contact details. Paper metadata was verified at https://arxiv.org/abs/2608.26619. No journal publication is implied.

## Preview locally

Open `index.html` directly in a browser, or serve this directory with `python3 -m http.server 4173 --bind 127.0.0.1` and visit http://127.0.0.1:4173/.
