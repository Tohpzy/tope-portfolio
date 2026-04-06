# 🚀 Deploying Your Portfolio

## Option A — Deploy to Vercel via GitHub (Recommended, ~2 min)

1. **Create a GitHub repo** at https://github.com/new
   - Name it: `tope-portfolio` (or anything you like)
   - Set to Public

2. **Push the code:**
   ```bash
   cd tope-portfolio/
   git init
   git add .
   git commit -m "Portfolio launch 🚀"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/tope-portfolio.git
   git push -u origin main
   ```

3. **Deploy on Vercel:**
   - Go to https://vercel.com/new
   - Click "Import Git Repository"
   - Select your `tope-portfolio` repo
   - Click **Deploy** — no configuration needed!
   - Your site goes live at: `https://tope-portfolio.vercel.app`

4. **Custom domain (optional):**
   - In Vercel dashboard → Settings → Domains
   - Add `adeoye.design` or any domain you own

---

## Option B — Drag & Drop on Vercel (30 seconds)

1. Go to https://vercel.com/new
2. Drag the entire `tope-portfolio` folder onto the page
3. Click Deploy — done!

---

## Files in This Portfolio
- `index.html` — Main page structure
- `style.css` — All styles, animations, dark theme
- `main.js` — Custom cursor, scroll reveals, interactions

## Update Your Links
Before deploying, update these in `index.html`:
- GitHub profile URL (search for `github.com` in the file)
- LinkedIn profile URL (search for `linkedin.com`)
- Behance URL is already set to `behance.net/adeoyejoseph` ✓
