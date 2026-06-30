# GitHub Deploy Practice

A tiny static website for practicing GitHub + GitHub Pages deployment.

## Run locally
Just open `index.html` in a browser — no build step needed.

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g. `deploy-practice`).
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source → Deploy from branch → main / (root)** → Save.
4. After a minute, your site is live at:
   `https://<your-username>.github.io/<repo-name>/`
5. Make a small change (e.g. edit the heading in `index.html`), commit, push, and refresh the live URL to see it update.

## License
MIT — see [LICENSE](LICENSE).
