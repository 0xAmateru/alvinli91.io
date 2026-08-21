# alvinli91.io

Personal website / blog built with Jekyll.

Live site: grappler91.github.io/alvinli91.io/ (if deployed)

## About
This repository contains the source for my personal website. It is built using Jekyll and SCSS, with site configuration in `_config.yml` and content in Markdown.

## Features
- Static site generated with Jekyll
- Posts and pages written in Markdown
- Styles written in SCSS
- Easy to preview locally using Jekyll's dev server

## Tech stack
- Ruby (see `Gemfile` for exact gems/versions)
- Jekyll
- SCSS

## Prerequisites
- Ruby (recommended version: check `Gemfile`)
- Bundler

## Local development
1. Install dependencies:
   - gem install bundler
   - bundle install
2. Serve the site locally:
   - bundle exec jekyll serve
3. Open http://localhost:4000 in your browser. Changes to Markdown/SCSS will rebuild automatically.

(If you use a specific Jekyll version or additional commands such as `bundle exec jekyll serve --livereload`, add them here.)

## Deployment
- This site can be deployed via GitHub Pages by pushing to the repository's default branch and enabling Pages in the repo settings.
- If you use a CI workflow, add deployment instructions or the workflow file reference here.

## Repository layout
- `_config.yml` — Jekyll configuration
- `index.md` — home page content
- `assets/` — styles, scripts, images
- `images/` — site images
- `Gemfile` — Ruby/Jekyll dependencies

## Contributing
1. Fork the repo
2. Create a feature branch: `git checkout -b feat/your-change`
3. Make changes, commit, and push
4. Open a pull request

Please keep changes focused and include a short description of your change.

## License
See the `LICENSE` file for license details.

## Contact
GitHub: https://github.com/grappler91
Email: (add your email if you want direct contact)
