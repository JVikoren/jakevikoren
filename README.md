# Jake Vikoren — Personal Website

Personal website for Jake Vikoren, Machine Learning Engineer focused on AI for Scientific Discovery.

Live at: https://jvikoren.github.io/jakevikoren

## Stack

- [Jekyll](https://jekyllrb.com/) static site generator
- Hosted on GitHub Pages

## Pages

- `index.html` — Home / hero page
- `resume.html` — Resume
- `publications.html` — Publications
- `projects.html` — Projects index
- `projects/particle-life.html` — Particle Life project

## Local Development

```bash
bundle exec jekyll serve --config _config.yml,_config_local.yml
```

Then open http://localhost:4000.

## Project Structure

```
_layouts/       # HTML layout templates
assets/         # CSS, JS, images
projects/       # Project sub-pages
_site/          # Build output (auto-generated, not committed)
```
