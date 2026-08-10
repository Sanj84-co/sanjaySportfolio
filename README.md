# Sanjay Senthilkumar — Portfolio

Personal portfolio site: a "case-file" postmortem write-up of three backend/AI
projects (Vision-RAG QA, StockSee, Exoplanet Explorer), plus experience and
skills.

## Tech stack

Plain HTML / CSS / JS. No framework, no build step, no npm dependencies.

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy

Pushing to `main` triggers `.github/workflows/deploy.yml`, which publishes
this folder to GitHub Pages automatically. No build step is required.

To enable Pages the first time:

1. Go to the repo's **Settings → Pages**.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Push to `main` — the workflow will run and publish the site.
