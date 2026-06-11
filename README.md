# Slug Generator

A single-file browser tool that turns a title or phrase into a clean URL slug: lowercase, hyphen-separated, punctuation removed, accents optionally stripped, with optional stop-word removal and a length cap. It shows the slug, a preview URL, and a copy button.

**Live demo:** https://0xelitesystem.github.io/slug-generator/

It runs entirely in the browser. Nothing is uploaded, stored, or tracked.

## What it shows

- The generated slug, displayed on an embossed plate
- A preview of the slug in an example URL
- The character count
- A copy button for the slug

## How to use

Open `index.html` in any browser, or visit the GitHub Pages URL. Type or paste a title and the slug updates live. Strip accents is on by default. Stop-word removal is off by default, because dropping words like the and of can change meaning; turn it on only when the slug stays clear without them. Set a max length to cap the slug, which trims at a word boundary.

## Notes

Accent stripping uses Unicode normalization, so most accented Latin characters reduce to their base letters. Anything that is not a letter or digit becomes a hyphen, and repeated hyphens collapse.

## License

MIT. Copyright (c) 2026 0xelitesystem.
