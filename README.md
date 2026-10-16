# Novumism

Static site for the Novumism series by Ryan Miller (no build step: `index.html` + `style.css`).

## Filling in links
Edit the `BOOK_LINKS` block near the top of `index.html`:
- `pdf`: path to a PDF in this repo (e.g. `pdfs/novum-carta.pdf`) or a full URL
- `amazon`: the Amazon product URL
- `cover`: optional image, e.g. `images/novum-carta.jpg` (leave `""` for the ornamental fallback)

Buttons whose link is still `#` show dimmed and do nothing until filled in.

## Enabling GitHub Pages
1. Push these files to the `main` branch.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Source: Deploy from a branch**.
4. Select branch **main** and folder **/ (root)**, then **Save**.
5. After a minute the site is live at `https://rsmiller.github.io/Novumism/`.

`.nojekyll` tells Pages to serve the files as-is, without Jekyll processing.
