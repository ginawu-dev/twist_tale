# Twist Tale website

Standalone static website for the Twist Tale iOS app.

## GitHub Pages

This site has no build step. In repository settings, open Pages, choose Deploy from a branch, select the default branch and the root folder, then save.

Expected URL:

https://ginawu-dev.github.io/twist_tale/

All links are relative so the site works under the project path. Do not add API keys, session tokens, signing credentials, or environment files to this repository.

## Local preview

Run a simple static server from the repository root:

    python3 -m http.server 8000

Then open http://localhost:8000/.
