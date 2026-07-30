# The Sorted Home — Blog

Blog companion to [The Sorted Home](https://www.pinterest.com/SortedHomeStudio/) Pinterest account — each post links several products at once, and gets pinned as multiple pin designs pointing back at it.

Static site built with Jekyll, auto-deployed to GitHub Pages via GitHub Actions on every push to `main`.

## Structure
- `_posts/` — blog posts, one product-roundup per file
- `about.md`, `disclosure.md`, `privacy-policy.md` — standing pages (Amazon Associates disclosure required on every affiliate-linking page)
- `assets/css/custom.scss` — brand palette override on top of the Minima theme
- `.github/workflows/jekyll.yml` — build + deploy pipeline

## Local preview (optional, requires Ruby)
```
bundle install
bundle exec jekyll serve
```