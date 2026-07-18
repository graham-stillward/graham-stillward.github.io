# Graham Stillward — site source

Source for the site, built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)
and published via GitHub Pages.

## Adding a post

1. Open `docs/posts/` on github.com.
2. **Add file → Create new file**, named like `2026-08-01-short-title.md`.
3. Start with the front-matter block (see any existing post for the pattern),
   write in Markdown, put `<!-- more -->` after the opening paragraph.
4. Commit. The site rebuilds automatically in about a minute
   (progress visible under the **Actions** tab).

## Editing a page

Open the file (`docs/about.md`, or any post), click the pencil icon, edit, commit.

## Layout

- `docs/posts/` — dated posts (the front-page stream)
- `docs/about.md` — the About page
- `docs/index.md` — front-page title (the post list is generated automatically)
- `mkdocs.yml` — site configuration (title, theme, navigation)
