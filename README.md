# Portfolio site

Personal website of Brajabandhu Pradhan. One static file (`index.html`), no build step.

## Put it online with GitHub Pages

1. Create a GitHub account if you don't have one. Your username becomes the address.
2. Create a new **public** repository named exactly `<username>.github.io`.
3. Upload `index.html` and this `README.md` (Add file → Upload files → Commit).
4. Open Settings → Pages and check that the source is "Deploy from a branch", branch `main`, folder `/ (root)`.
5. After a minute or two the site is live at `https://<username>.github.io`.

## Editing

Everything is in `index.html`. Each section is marked with an `id` (`research`, `structures`, `software`, `publications`, `path`, `toolkit`, `interests`, `contact`). Colours and fonts are the variables at the top of the `<style>` block.

To add a photo, put `photo.jpg` next to `index.html` and add an `<img src="photo.jpg" alt="Brajabandhu Pradhan">` in the About section.
