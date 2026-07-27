# Deploy to GitHub Pages

This project is ready for a static GitHub Pages deployment.

## Recommended repository name

Create this repository under your GitHub account:

`sloppeh-gacha-simulator2`

Then the published site will be:

`https://<your-github-username>.github.io/sloppeh-gacha-simulator2/`

## What is already prepared

- `index.html`
- `styles.css`
- `app.js`
- `.github/workflows/pages.yml`
- local git repository initialized on `main`

## One-time publish steps

1. Sign in to GitHub with the account that will host the site.
2. Create a new repository named `sloppeh-gacha-simulator2`.
3. Push this project to that repository.
4. In the repository settings, open **Pages**.
5. Set the source to **GitHub Actions**.
6. Push again or run the workflow manually.

## Push commands

Run these from `d:\GachaSimulatorWeb2` after creating the GitHub repository:

```powershell
git remote add origin https://github.com/<your-github-username>/sloppeh-gacha-simulator2.git
git add .
git commit -m "Initial web version"
git push -u origin main
```

If Git asks for credentials, use your GitHub account login or a personal access token.

## Notes

- The app uses only static files, so it can be hosted free on GitHub Pages.
- Data is stored in `localStorage` in the browser.
- The workflow in `.github/workflows/pages.yml` deploys the `main` branch automatically.
