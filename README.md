# Dineth Jayakody

Personal academic website: <https://dineth99-bit.github.io>

The site is a single static page, `index.html`, styled by `stylesheet.css`. The design is adapted from
[Akanksha Saran's site](https://asaran.github.io/), which is based on [Jon Barron's template](https://jonbarron.info/).

## Editing

- **News**: add a `<li>` at the top of the list under "Recent News" in `index.html`.
- **Projects / publications**: copy an existing `<tr>` block in the Projects or Research table and edit it.
  Thumbnails live in `images/`. The `abstract` and `bibtex` links toggle the hidden blocks with matching ids.
- **CV**: replace `assets/pdf/Dineth_Jayakody_Academic_CV.pdf`.
- `papers.bib` holds the BibTeX entries shown on the page.

Pushing to `main` runs `.github/workflows/deploy.yml`, which publishes the files to the `gh-pages` branch.

To preview locally: `python3 -m http.server` and open <http://localhost:8000>.
