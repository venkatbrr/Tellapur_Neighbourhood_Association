# TeNA Website

Static site for Tellapur Neighbourhood Association.

## Local preview

Open `index.html` directly, or run a local static server.

## Deploy on GitHub Pages

This repository includes a GitHub Actions workflow that deploys to GitHub Pages on every push to `main`.

### One-time setup

1. Push this project to a GitHub repository.
2. In GitHub, open **Settings -> Pages**.
3. Under **Build and deployment**, select **Source: GitHub Actions**.
4. Ensure your default branch is `main`.

### Deploy

1. Commit and push changes to `main`.
2. Open the **Actions** tab and confirm the workflow succeeded.
3. Your site will be available at:
   - `https://<your-username>.github.io/<repo-name>/`

## Notes

- The `404.html` page is included for friendly not-found handling.
- `vercel.json` remains for Vercel deployments and does not affect GitHub Pages.
