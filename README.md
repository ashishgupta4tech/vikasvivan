# Folder 2 — GitHub Drop-In 

Production domain: `https://vikasyadav.is-a.dev/`

This folder is a ready-to-push repository. `index.html` sits at the repo root,
so GitHub Pages works with "Deploy from a branch → / (root)" and no build step.
The existing repository is `https://github.com/ashishgupta4tech/vikasvivan`.

## How to upload (drag & drop)
1. Open the repository on GitHub and click **uploading an existing file**.
2. Drag this whole folder's *contents* (not the folder itself) into the browser window.
   Tip: open this folder in Explorer, select everything (Ctrl+A) and drag it in.
3. Wait for the upload, then **Commit changes**.

## After the upload
- **GitHub Pages**: Settings → Pages → Source: *Deploy from a branch* → branch `main`, folder `/(root)` → Save.
  The project URL is `https://ashishgupta4tech.github.io/vikasvivan`.
- **Vercel** (current live host): import this repository, set Framework Preset to *Other*,
  leave Build Command empty, set Output Directory to `/`, then Deploy.
- **Cloudflare Pages**: Pages → Create → *Connect to Git* → pick this repo →
  Build command: *leave empty* · Output directory: `/` → Deploy.

The `CNAME` file already contains `vikasyadav.is-a.dev` for GitHub Pages custom-domain use.
