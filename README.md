# Color Hug(TM) - The Lucky Clover | Payment-Confirmed Questionnaire Report

Static preview site. Self-contained: no backend, no database, nothing stored.

## Structure
- `index.html` â€” the full application
- `webp/` â€” optimized image assets (keep together with index.html)

## Deploy (Railway)
1. In Railway: New Project -> Deploy from GitHub repo -> pick this repo
2. Railway auto-detects Node via package.json and runs `npx serve -l $PORT .`
3. Generate a public domain in Railway settings (Settings -> Networking -> Generate Domain)

## Also live on GitHub Pages
https://sindee-hub.github.io/color-hug-questionnaire/