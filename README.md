# jacopo-marini.github.io

Personal academic site. Plain HTML + CSS, no build step.

- `index.html`: the Home page (bio). `research/index.html`: the Research page. Commented-out blocks are ready-made slots for a portrait, extra contact links, and paper links.
- `style.css`: the whole design. Colors and fonts are the variables at the top.
- `assets/`: `Jacopo_Marini_CV.pdf` (replace the file, keeping the name, to update the CV), plus `portrait.jpg` and paper PDFs when available.

Pushing to `main` publishes to the `gh-pages` branch via `.github/workflows/deploy.yml`.

Preview locally: `python3 -m http.server 4000` and open <http://localhost:4000>.
