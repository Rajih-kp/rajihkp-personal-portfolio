# AinUt AI Creative Studio Portfolio

This is a static multi-page portfolio website.

## Publish (GitHub Pages)

A GitHub Actions workflow is included at `.github/workflows/publish.yml`.

### One-time repository setup
1. Go to **Settings → Pages** in your GitHub repository.
2. Under **Build and deployment**, choose **Source: GitHub Actions**.

### Publish flow
- Push changes to `main`, `master`, or `work`.
- Or manually run the **Publish Portfolio** workflow from the **Actions** tab.
- The workflow deploys all static files in this repo to GitHub Pages.

## Local preview

```bash
python3 -m http.server 4173
```

Open `http://127.0.0.1:4173/` in your browser.
