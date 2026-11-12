# Sevenne Studios

A 3D iPhone case designer. Pick a phone model, case style, material and colour, add text and images, and save a picture of the result.

The whole app is one file, `index.html`. It needs no build step and no server code. It loads Three.js and its fonts from public CDNs, so it needs an internet connection to run.

## Run it on your computer

Open `index.html` in a browser.

## Put it on GitHub

1. Create a new, empty repository on github.com (no README, no licence).
2. In a terminal, from this folder:

```
git init
git add .
git commit -m "Sevenne Studios"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

## Host it free with GitHub Pages

1. On github.com, open the repository, then Settings, then Pages.
2. Under "Build and deployment", set Source to "Deploy from a branch".
3. Choose the `main` branch and the `/ (root)` folder, then Save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

Netlify, Vercel and Cloudflare Pages also work: point them at the repository with no build command and the root folder as the publish directory.

## Good to know

- Saved designs are stored locally, in the browser on each person's own computer. Nothing is uploaded, and designs do not sync between computers.
- Phone body sizes follow Apple's published measurements. Camera layouts and cutouts are approximations for visualising a design, not manufacturing templates.
