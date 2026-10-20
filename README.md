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

## Google Scholar Citation Stats

Automatic citation fetching is disabled: the `Get Citation Data` workflow has been removed, and the homepage no longer requests citation data. The Google Scholar profile link remains available.

The crawler and citation display source files are retained for possible future use. Removing the workflow takes effect on GitHub after these changes are pushed to the default branch.

## Local Preview

Install Ruby/Jekyll, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000`.
