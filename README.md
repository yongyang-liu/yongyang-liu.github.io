# STAR Lab Website

Source for the website of the **Socially Intelligent Autonomy, Reasoning, and Learning Lab (STAR Lab)**,
Department of Mechanical and Nuclear Engineering, Tennessee Technological University.

Live site: https://yongyang-liu.github.io/

The site is built with [Jekyll](https://jekyllrb.com/) and published by GitHub Pages from the `master` branch.

## Where things live

| What | File |
| --- | --- |
| Site title, description, lab contact | `_config.yml` |
| Top navigation | `_data/navigation.yml` |
| Home page News list | `_data/news.yml` |
| Pages | `_pages/` (`home.html`, `facilities.html`, `research.html`, `people.html`, `publications.md`, `teaching.md`, `join-us.md`) |
| Page layout, header, footer | `_layouts/lab.html`, `_includes/lab/` |
| Styles | `assets/css/lab.scss` |
| Images | `images/research/`, `images/facilities/`, `images/people/` |

## Common edits

- **Add a news item:** add an entry at the top of `_data/news.yml`.
- **Add a publication:** edit `_pages/publications.md`.
- **Update teaching or recruiting text:** edit `_pages/teaching.md` or `_pages/join-us.md`.

## Local preview (optional)

With Ruby and Bundler installed:

```
bundle install
bundle exec jekyll serve
```

or with Docker: `docker compose up`, then open http://localhost:4000.

## History

The previous personal website is preserved on the `legacy-personal-site` branch.
This repository was originally created from the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template (MIT License, see `LICENSE`).
