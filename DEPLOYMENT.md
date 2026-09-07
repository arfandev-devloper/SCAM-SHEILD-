# Deployment Guide

## GitHub Pages
1. Push this repository to GitHub.
2. Open **Settings → Pages**.
3. Select **GitHub Actions** as the source.
4. Push to `main` or manually run the included Pages workflow.
5. Wait for the deployment action to finish.

## Local
```bash
npm install
npm start
```

## Environment variables
The current static v1 does not require secrets. Future backend integrations should use environment variables based on `.env.example`.
