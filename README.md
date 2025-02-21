# Data 102 Spring 2025 Website

[![Deploy Jekyll site to Pages](https://github.com/ds-102/sp25/actions/workflows/jekyll.yml/badge.svg)](https://github.com/ds-102/sp25/actions/workflows/jekyll.yml)
[![Run all page a11y tests](https://github.com/ds-102/sp25/actions/workflows/rspec.yml/badge.svg)](https://github.com/ds-102/sp25/actions/workflows/rspec.yml)

This [video](https://www.youtube.com/watch?v=azPPK5aOcV0) walks you through how to make changes to the website (just replace all instances of fa19 with sp25 and DS100 with Data 102).

To add Jupyter notebook links to the webpage, use nbgitpuller: https://jupyterhub.github.io/nbgitpuller/link

## Installation

Prerequisites:

- You have everything that [Jekyll requires](https://jekyllrb.com/docs/installation/)
- You have installed [Bundler](https://bundler.io/): `gem install jekyll bundler`

After cloning this repository and navigating into the directory, run the following command to install dependencies
```
cd YOUR_REPO
bundle install
```

## Usage

To run the site locally, run:

```
bundle exec jekyll serve
```

## Deployment

This site is deployed via a [GitHub Action Workflow](.github/workflows/jekyll.yml). For more information see [GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).

## License

[MIT](LICENSE)