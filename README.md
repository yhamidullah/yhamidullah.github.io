# yhamidullah.github.io

Personal academic website of **Yasser Hamidullah** — sign language translation and multimodal NLP.

Live at **<https://yhamidullah.github.io>**.

Built with [al-folio](https://github.com/alshedivat/al-folio), a Jekyll theme for academics.

## Editing the content

Almost everything you'll want to change lives in a handful of files:

| What                                        | Where                      |
| ------------------------------------------- | -------------------------- |
| Bio, photo, affiliation on the landing page | `_pages/about.md`          |
| Publications                                | `_bibliography/papers.bib` |
| News / announcements                        | `_news/*.md`               |
| CV                                          | `_data/cv.yml`             |
| Social & profile links                      | `_data/socials.yml`        |
| Pinned GitHub repos                         | `_data/repositories.yml`   |
| Site title, URL, theme colours              | `_config.yml`              |

Publications are rendered from BibTeX by [jekyll-scholar](https://github.com/inukshuk/jekyll-scholar). To add a paper, paste its BibTeX entry into `_bibliography/papers.bib`. Useful extra fields al-folio understands:

- `abbr` — venue badge shown next to the entry (`ACL`, `WMT`, …)
- `selected={true}` — also show it on the landing page
- `abstract`, `code`, `arxiv`, `doi`, `html`, `pdf`, `poster`, `slides`
- `bibtex_show={true}` — adds a "BibTeX" button

## Running it locally

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

Alternatively, with Docker:

```bash
docker compose up
```

## Deployment

Pushing to `master` triggers `.github/workflows/deploy.yml`, which builds the site
and pushes the result to the `gh-pages` branch. GitHub Pages serves that branch.

Don't commit to `gh-pages` by hand — it is regenerated on every deploy.
