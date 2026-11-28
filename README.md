# basicDEFAULT

The site for [basicdefault.com](https://basicdefault.com): a home for creative work and other things.

Plain HTML and CSS. No build step, no dependencies.

## Preview

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Editing

- **Work list:** each entry is an `<li class="item">` in `index.html`. To link one once it is live, wrap the `<h3>` text in `<a href="...">`; the arrow and underline appear on their own.
- **Colours:** tokens at the top of `styles.css`, shared by every page. Light only: cream `#F5E4D7`, deep green `#3E4D44` and a sage accent `#839788`, with blush `#E5D1D0` for hovers and tags.
- **Logo:** the BDHQ files and usage rules are in `brand/`.
- **Type:** Creato Display (SIL OFL, licence in `fonts/OFL.txt`).
