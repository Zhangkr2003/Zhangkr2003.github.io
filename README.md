# Kairui Zhang's Academic Homepage

This personal academic homepage is based on the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) template.

## Main Files

- `_config.yml`: site metadata, author profile, social links, and GitHub Pages repository.
- `_pages/about.md`: homepage biography, news, publications, awards, and education.
- `images/avatar.png`: sidebar avatar.
- `images/favicon-16x16.png`, `images/favicon-32x32.png`, `images/favicon.ico`, `images/apple-touch-icon.png`, `images/android-chrome-192x192.png`, and `images/android-chrome-512x512.png`: site icons generated from the avatar.

## Publish on GitHub Pages

1. Create a GitHub repository named `Zhangkr2003.github.io`.
2. Upload all files in this directory to that repository.
3. Commit and push to the `main` branch.
4. Open `https://Zhangkr2003.github.io` after GitHub Pages finishes building.

## Optional Google Scholar Citation Stats

The Google Scholar profile ID is already set to `woe63wsAAAAJ`.

To enable automatic citation stats:

1. In GitHub, go to `Settings -> Secrets and variables -> Actions -> New repository secret`.
2. Add `GOOGLE_SCHOLAR_ID` with value `woe63wsAAAAJ`.
3. Enable GitHub Actions for the repository.

## Local Preview

Install Ruby/Jekyll, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000`.
