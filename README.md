# theosis.org — concept

Theosis Publishing: "Where consciousness studies meets everyday wisdom."

This is a **concept site**: the design and overall idea are real, but almost all content is placeholder
(sample authors, essays, reviews and books). It was moved here as-is from its old host on 2026-10-26
so the hosting could be cancelled. It is plain HTML and CSS: no build step, no framework.

```
index.html  blog.html (Essays)  reviews.html  authors.html  books.html
css/stylesheet-01.css
images/
```

## Known gaps (as on the old host)

- The pages link to 19 detail pages (`author-*.html`, `essay-*.html`, `review-*.html`) that were never created.
- The pages reference 29 images (`author-*.jpg`, `book-*.jpg`, `book-cover-*.jpg`, `coming-soon-*.jpg`, and others)
  that were never created, so they show as broken images.
- `images/` also holds 10 design assets that no page uses yet (alternative header images, extra icons),
  kept from the old host.
- Fonts load from Google Fonts (Crimson Text, Inter).

The only change from the original: asset paths were made relative (`css/…`, `images/…` instead of `/css/…`),
so the site also works on the github.io preview address.

Push to `main` deploys to GitHub Pages.
