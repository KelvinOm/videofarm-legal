# VideoFarm legal pages

Static pages hosted on GitHub Pages to satisfy platform developer-app requirements
(Terms of Service URL, Privacy Policy URL) for TikTok, Meta, etc.

## Push to GitHub and enable Pages

From this directory:

```
git init
git add .
git commit -m "Initial legal pages"
git branch -M main
git remote add origin git@github.com:<your-user>/videofarm-legal.git
git push -u origin main
```

Then on GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: main, folder: / (root) → Save**.

After ~1 minute, the pages are live at:

- `https://<your-user>.github.io/videofarm-legal/`
- `https://<your-user>.github.io/videofarm-legal/terms.html`
- `https://<your-user>.github.io/videofarm-legal/privacy.html`

Paste those URLs into the TikTok developer app form.
