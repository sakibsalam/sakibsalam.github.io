# Writing a blog post

English posts live in `_posts/en/`. Bangla posts live in `_posts/bn/`. The folder decides the language, so nothing else needs to be set.

## New post

1. Copy `post-en.md` (or `post-bn.md`) from this folder into `_posts/en/` (or `_posts/bn/`).
2. Rename it `YYYY-MM-DD-short-slug.md`, for example `2026-12-01-why-priors-matter.md`. The date is the publish date and the slug becomes the URL. Use English letters in the slug even for Bangla posts; the Bangla title goes in `title:`.
3. Fill in `title`, `date`, `description`, and `tags`. Tags I use: `math`, `philosophy`, `observations`.
4. Write below the second `---`.

## Translations

If a post exists in both languages, give both files the same `ref:` value. Each version then links to the other. If a post has no translation, delete the `ref:` line.

## Drafts

Add `published: false` to the front matter and the post stays off the site until you remove that line. You can also keep unfinished posts in `_drafts/`, which never gets published.

## Math

Use `$$ ... $$` for math. Inside a sentence it renders inline; on its own paragraph it renders as a centered equation.

## Images

Put image files in `assets/img/blog/` and link them as shown in the template.

## Publishing

```
git add -A
git commit -m "New post: short title"
git push
```

The site rebuilds on GitHub in a few minutes. Check progress under the Actions tab of the repository.
