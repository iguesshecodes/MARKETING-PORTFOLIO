# Varesh Studio

Creative and marketing portfolio for Varesh Nirbhavne. One self-contained
`index.html`, no build step, no dependencies. Just static files.

Covers video and film, 3D and motion, brand (Destyle Apparels), graphic and
visual design, plus a Marketing Lab for CRM, SEO, a marketing audit and the
M&S vs Tesco comparison.

## Run locally
Open `index.html` in a browser. That is it.

## Deploy to Vercel (two easy ways)

### A. Drag and drop (fastest, no git needed)
1. Go to https://vercel.com and sign in.
2. Click **Add New > Project > Deploy** and drag this whole folder in,
   or use the Vercel CLI: `npx vercel` from inside this folder.
3. It goes live on a `*.vercel.app` URL in seconds.

### B. GitHub + Vercel (best for updates)
1. Create a new empty repo on GitHub, e.g. `varesh-studio`.
2. In this folder:
   ```
   git remote add origin https://github.com/<you>/varesh-studio.git
   git branch -M main
   git push -u origin main
   ```
3. On Vercel: **Add New > Project > Import** that repo. Framework preset
   **Other**, no build command, output directory is the repo root.
4. Every push to `main` now redeploys automatically.

## Custom domain
In Vercel: Project > Settings > Domains. Add your domain and follow the
DNS instructions.
