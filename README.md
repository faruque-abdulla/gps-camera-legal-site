# Legal Site Deployment (GitHub Pages)

## Files
- `index.html`
- `privacy-policy.html`
- `terms-and-conditions.html`
- `styles.css`

## Deployment Model
This repository includes a GitHub Actions workflow that deploys the `legal-site/` folder to GitHub Pages.

Workflow file:
- `.github/workflows/deploy-legal-site.yml`

## One-time GitHub setup
1. Push this repository to GitHub.
2. Open **Settings -> Pages**.
3. Under **Source**, select **GitHub Actions**.
4. Push any change in `legal-site/` (or run workflow manually).

## URLs after deployment
If your repo is `https://github.com/<username>/<repo>`:
- Legal Home: `https://<username>.github.io/<repo>/`
- Privacy Policy: `https://<username>.github.io/<repo>/privacy-policy.html`
- Terms: `https://<username>.github.io/<repo>/terms-and-conditions.html`

## Before using in Play Console
- Replace `your-email@example.com` in both legal pages with your real support email.
- Keep these pages public and accessible without login.
