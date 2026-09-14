# Loco public site

Static public website and audit documentation for Loco, the iPhone beat publishing app.

## Local preview

```bash
python3 -m http.server 8080 --directory site-src
```

## Public routes

- `/` — product overview and workflow
- `/privacy.html` — Privacy Policy
- `/terms.html` — Terms of Use
- `/support.html` — support and troubleshooting
- `/delete-data.html` — deletion and revocation instructions

The repository deploys to GitHub Pages from the `main` branch through `.github/workflows/deploy-pages.yml`.
