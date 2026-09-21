# xuanchiren.com

Single-page personal site in the [Jon Barron](https://jonbarron.info) / [j-lab.ai](https://j-lab.ai) style.
No build step: Netlify publishes the repository root as-is (see `netlify.toml`).

- `index.html` — the whole site. Publications live in two `<script type="text/template">` blocks
  (`pubs_selected`, `pubs_by_date`); copy an existing `<tr>` block to add a paper.
- `stylesheet.css` — fonts and colors.
- `images/` — profile photo and 160x160 paper thumbnails (short looping `.mp4` or `.jpg`).
- `files/cv.pdf` — CV linked from the header.
- `pub/`, `look-ouside-room/`, `MOS/`, `review/` — legacy project pages kept so old links still work.
- `_redirects` — sends old `/publication/...` URLs to the publications section.
