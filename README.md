# GachaSimulatorWeb2

Static browser version of the gacha simulator. It is ready for GitHub Pages and does not need a backend.

## Local use

Open `index.html` in a browser.

## Deploy on GitHub Pages

Create the repository under your GitHub account with the name:

`GachaSimulatorWeb2`

Then:

1. Push these files to the `main` branch.
2. In GitHub repository settings, open **Pages**.
3. Set the source to **GitHub Actions**.
4. Push again and wait for the workflow to finish.

The live link will be:

`https://<your-github-username>.github.io/GachaSimulatorWeb2/`

If you use a different repository name, the URL becomes:

`https://<your-github-username>.github.io/<repo-name>/`

## Features

- Draw 1 / 10 / 50
- Epic pity every 10 draws
- Legendary pity every 150 draws
- Inventory tracking
- Manual top up packages
- Currency switch THB / USD
- I'm rich auto top-up mode
- Local save with `localStorage`
