# Deploy These Portfolio Changes to `daviddxuee.github.io`

I attempted to clone `https://github.com/daviddxuee/daviddxuee.github.io.git` directly from this environment, but network access to GitHub is blocked here.

## Files to copy into `daviddxuee.github.io`
- `index.html`
- `styles.css`

Optional (profile repo only):
- `README.md` (contains instructions/context for this repo, not required by GitHub Pages)

## Fastest path (local machine)

```bash
# 1) Clone your site repo locally
git clone https://github.com/daviddxuee/daviddxuee.github.io.git
cd daviddxuee.github.io

# 2) Copy files from this generated portfolio set into repo root
# (copy index.html and styles.css)

# 3) Commit and push
git add index.html styles.css
git commit -m "Update portfolio homepage with professional layout and content"
git push origin main
```

## GitHub Pages settings check
1. In `daviddxuee.github.io` repo, open **Settings → Pages**.
2. Source: **Deploy from a branch**.
3. Branch: `main` and folder `/ (root)`.
4. Save.

Your site should publish at: `https://daviddxuee.github.io/`.
