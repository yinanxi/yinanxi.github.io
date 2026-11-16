# Nanxi Yi — Academic Website

Personal academic website for Nanxi Yi, built with [al-folio](https://github.com/alshedivat/al-folio).

Intended GitHub Pages address: https://yinanxi.github.io

## Update content

- Biography: `_pages/about.md`
- Papers: `_bibliography/papers.bib`
- Research: `_projects/`
- CV webpage: `_pages/cv.md`
- Photo: `assets/img/nanxi-yi.jpg`
- Contact links: `_data/socials.yml`
- Site settings: `_config.yml`

## Build locally

Requires Ruby 3.3 or later and Bundler.

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000. The GitHub Pages deployment workflow builds the same Jekyll source.

See `DEPLOYMENT.md` for publication steps and `CONTENT_SOURCES.md` for source notes. The al-folio MIT license is preserved in `LICENSE`.
