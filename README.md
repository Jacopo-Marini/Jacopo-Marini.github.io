# jacopo-marini.github.io

Personal academic site. Plain HTML + CSS, no build step.

- `index.html`: all content (bio, research). Commented-out blocks are ready-made slots for the email/CV row, a portrait, and paper entries.
- `style.css`: the whole design. Colors and fonts are the variables at the top.
- `assets/`: put `portrait.jpg`, `cv.pdf`, and paper PDFs here.

Pushing to `main` publishes to the `gh-pages` branch via `.github/workflows/deploy.yml`.

Preview locally: `python3 -m http.server 4000` and open <http://localhost:4000>.
