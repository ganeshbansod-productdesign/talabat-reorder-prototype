# talabat mart – reorder list prototype

Static prototype (no build step). Open `index.html`, or serve the folder:

    python3 -m http.server 8765

## Auto-deploy
Every push to `main` deploys the whole folder to GitHub Pages via
`.github/workflows/pages.yml`. In the repo: Settings -> Pages -> Source = "GitHub Actions".
