# Ulugbek — Personal Website

A minimal, single-file personal site (monospace / terminal theme). No build step,
no dependencies — just `index.html`.

## Run locally
Open `index.html` in any browser, or serve it:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages (free)
1. Create a repo on GitHub named **`UlugbekAbdumutalov.github.io`**
   (using your exact username gives you the clean URL `https://ulugbekabdumutalov.github.io`).
2. Push this folder to that repo (see commands below).
3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `root` → Save.**
4. Wait ~1 minute, then visit `https://ulugbekabdumutalov.github.io`.

### Push commands
```bash
git remote add origin https://github.com/UlugbekAbdumutalov/UlugbekAbdumutalov.github.io.git
git branch -M main
git push -u origin main
```

## Custom domain later
When you buy a domain, add it under **Settings → Pages → Custom domain**,
then point a CNAME/A record at GitHub Pages. The site itself needs no changes.
