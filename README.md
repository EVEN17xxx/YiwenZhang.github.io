# Yiwen Zhang's personal academic website

Built on [al-folio](https://github.com/alshedivat/al-folio), a Jekyll theme for academic websites.

Live at: <https://even17xxx.github.io/YiwenZhang.github.io/>

## Local development

```
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000/YiwenZhang.github.io/`.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch. GitHub Pages must be set to serve from `gh-pages` (Settings → Pages → Branch).

## Content

- `_pages/about.md` — bio and profile
- `_news/` — news/timeline entries
- `_projects/` — research and coursework projects
- `_pages/publications.md` — publications and working papers
- `_data/cv.yml` — CV content (rendered at `/cv/`)
- `_data/socials.yml` — social/contact links
