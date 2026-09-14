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

The public GitHub Pages deployment is served from the `gh-pages` branch. The `main` branch contains the editable source and the `dist/` output used for Workers/Sites publishing.
