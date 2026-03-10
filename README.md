# Dummy-website-

This repository contains a simple personal portfolio site (`index.html`) for Mahtab Alam.

## Deployment

The site is hosted using **GitHub Pages**. The workflow defined in `.github/workflows/pages.yml` automatically publishes the repository's root directory to Pages whenever a commit is pushed to the `main` branch.

To deploy manually:

1. Ensure the repository is pushed to GitHub (`git push origin main`).
2. In the repository settings on GitHub, under **Pages**, verify that the source is set to the `main` branch and the root (`/`). GitHub will serve `index.html` from the root.
3. After the workflow runs, your site will be available at `https://<username>.github.io/<repository-name>/` (for example, https://alammahtab771.github.io/Dummy-website-).

You can also use other static hosts (Netlify, Vercel, etc.) by pointing them at this repo.
