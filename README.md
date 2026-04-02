# Taiye Chen Academic Website

This repository contains the source for Taiye Chen's personal academic website, built with GitHub Pages, Jekyll, and a customized Academic Pages-style structure.

## Upstream Credit

This site was originally forked from [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io), which was adapted from the [Minimal Mistakes Jekyll Theme](https://github.com/mmistakes/minimal-mistakes) by Michael Rose.

This repository is now customized for personal use, but the upstream project structure and theme lineage are intentionally acknowledged here. The original license and changelog files are retained in this repository.

## Main Structure

- `_pages`: main website pages such as About, CV, Research, Teaching, and Publications
- `_publications`: publication entries
- `_posts`: blog posts and writing
- `files`: downloadable PDFs and static HTML resources
- `images`: images used across the site

## Local Development

1. Install Ruby dependencies with `bundle install`
2. Run the site locally with `bundle exec jekyll serve --config _config.yml,_config.dev.yml`
3. Open `http://localhost:4000`

## Notes

- Some template routes are intentionally kept as placeholders for future expansion.
- Site-wide settings live in `_config.yml`.
