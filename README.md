# vladana-perlic.github.io

This is the source for Vladana Perlić’s portfolio and literary archive, published at [vladana-perlic.github.io](https://vladana-perlic.github.io/).

- **Live site:** https://vladana-perlic.github.io/
- **Main file:** [index.html](index.html)
- **How to preview locally:**
  1. Run `python -m http.server 8000` in the project folder.
  2. Open [http://localhost:8000/](http://localhost:8000/) in your browser.

**Sections:**
- News
- Research papers
- Literary works (books, translations, prizes, poems, prose, readings)
- Press, interviews, reviews
- Beta readers
- Author bio
- CVs
- Contact

All content is static, privacy-respecting, and designed for clarity and discoverability.

## Folder layout

```
index.html                  the whole site (HTML, CSS, JS)
data/
  site/                     banner, profile/press photos, favicon, link-preview image
  cv/                       Scholar CV and Author CV (PDF)
  images/
    books/                  book covers
    publications/           anthology, magazine and journal covers
    photos/                 readings, awards, residencies (named YYYY-event.jpg)
  poems/<language>/         poem texts (.txt / .docx / .jpg) shown in the poem reader
_source/                    local-only originals and archived drafts (git-ignored)
```

When adding or renaming a file, update its path in `index.html`. GitHub Pages is case-sensitive, so keep names lowercase where possible.