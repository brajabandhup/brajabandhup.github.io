# Portfolio site

Personal website of Brajabandhu Pradhan, live at https://brajabandhup.github.io. Static, no build step.

- `index.html`: the whole page (markup, styles and a small script).
- `media/`: the hero loop, the two films (1080p) and the render stills.

## Publishing

GitHub Pages serves the `main` branch from the repository root. A push to `main` is live within a minute or two.

## Editing

Each section in `index.html` is marked with an `id` (`research`, `films`, `structures`, `software`, `publications`, `path`, `toolkit`, `interests`, `contact`). Colours and fonts are the variables at the top of the `<style>` block.

To preview locally, run `python3 -m http.server` in this folder and open the address it prints. Opening `index.html` directly also works, but the videos load more reliably from a server.
