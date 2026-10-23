# ashmerra games

A page of buttons linking to each browser game.

**Visit: https://ashmerra.github.io/**

The site is `public/`, deployed to GitHub Pages on every push to `main`. To add a game, copy one `<a class="game">` block in `public/index.html` and give it a background color in `public/styles.css`. Bump `?v=` on `styles.css` when it changes.

Run locally: `python3 -m http.server -d public 8790`. Game links and icons use root paths (`/killer-koalas/`), so they only resolve on the live site.
