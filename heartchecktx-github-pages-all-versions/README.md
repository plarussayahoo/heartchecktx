# Heart Check TX — GitHub Pages design gallery

All seven independent designs are under `/v1/` through `/v7/`. The root `index.html` is a selection gallery. No build step is needed.

## Deploy to personal GitHub
1. Create a **public** repository named `heartchecktx.com` (or another name) in your personal account.
2. Extract this ZIP, open a terminal in the extracted `heartchecktx-github-pages` directory, and run:

```bash
git init
git add .
git commit -m "Add Heart Check TX design gallery"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/heartchecktx.com.git
git push -u origin main
```

3. In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
4. Your initial URL will be `https://YOUR_USERNAME.github.io/heartchecktx.com/`.
5. To use `heartchecktx.com`, go to **Settings → Pages → Custom domain**, enter `heartchecktx.com`, and follow the GitHub-provided DNS verification/instructions at your DNS provider. Set up HTTPS once DNS resolves. The repository does not include a `CNAME` file yet so the domain will not be claimed prematurely.

**Important:** This package is meant for a public GitHub Pages site. Anyone can view the design versions. All merchandise is mock-only and no real checkout is configured. Update placeholder dates, links, band text and email before publishing as a production site.

Do not point DNS away from an existing live website until you are ready to switch.
