# WakeWell — Website

Design matches `WakeWell_Poster_60x80cm.html` poster (cream #FDFCFB, dark green #1A2E2A, sage #8EA89B, sand #C9B99A).
Fonts: Cormorant Garamond + Inter + Manrope.
Languages: AZE / EN toggle (top right). "WakeWell" never translates.

## Local preview
Just double-click `index.html` or run:
```
cd wakewell-website
python -m http.server 8000
```
Then open http://localhost:8000

## Publish to GitHub Pages (free domain)

1. Create a new GitHub repo (e.g. `wakewell`), **public**.
2. Push this folder:
```
git init
git add .
git commit -m "WakeWell website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/wakewell.git
git push -u origin main
```
3. On GitHub: Settings → Pages → Build and deployment: Source = `Deploy from a branch`, Branch = `main` / `root` → Save.
4. Your site will be live at `https://YOUR_USERNAME.github.io/wakewell/` in ~1 minute.

Optional custom domain: Settings → Pages → Custom domain → enter your domain and add DNS CNAME to `YOUR_USERNAME.github.io`.

No build step needed — single static `index.html`.
