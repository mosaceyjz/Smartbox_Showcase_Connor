# Smartbox GitHub Pages Package

This folder is a minimal static package for publishing the Smartbox deck through GitHub Pages.

## What to upload

Upload the full contents of this folder to a dedicated GitHub repository.

Recommended repository name:

- `smartbox-roadshow`

## Files included

- `index.html` as the site entry page
- local images used by the deck
- `assets/` and `Hightlights/` folders required by the deck
- `.nojekyll` for GitHub Pages compatibility

## Publish steps

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select branch `main` and folder `/ (root)`.
6. Save and wait for GitHub Pages to publish.

## Access URL

If your GitHub username is `USERNAME` and the repo is `smartbox-roadshow`, the site URL will be:

`https://USERNAME.github.io/smartbox-roadshow/`

## Important note

Do not publish the whole workspace. Only publish this `smartbox-pages` folder.