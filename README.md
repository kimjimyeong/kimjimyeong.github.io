# GitHub Pages Deployment Notes

This project now includes a deployable GitHub Pages version under the `docs/` folder.

## What to edit

- Edit the website files inside `docs/`
- Main file: `docs/index.html`
- Subpages: `docs/pages/`
- Styles: `docs/assets/styles.css`
- Downloadable materials: `docs/downloads/`

## Recommended publishing setup

1. Create a GitHub repository for the thesis website.
2. Upload the files in this project.
3. On GitHub, open `Settings -> Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select branch `main` and folder `/docs`.
6. Save.

## URL format

- If the repository name is `username.github.io`, the site URL will be:
  `https://username.github.io/`
- If the repository name is `thesis-site`, the site URL will usually be:
  `https://username.github.io/thesis-site/`

## Important note

GitHub Pages sites are public on the internet. Do not upload private files or unrelated administrative documents to the public repository.
