# MavenSource Global

Your Trusted Strategic Sourcing Partner – connecting buyers and suppliers across international markets.

## GitHub Pages Deployment

1. **Create a new repository** on GitHub (e.g. `mavensource-global` or `username.github.io` for a user site).

2. **Push this folder** to the repository:
   ```bash
   cd mavensource-global
   git init
   git add .
   git commit -m "Initial commit: MavenSource Global website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages** in your repo:
   - Go to **Settings** → **Pages**
   - Under **Source**, select **Deploy from a branch**
   - Branch: **main** (or **master**)
   - Folder: **/ (root)**
   - Click **Save**

4. Your site will be live at:
   - `https://YOUR_USERNAME.github.io/YOUR_REPO/` (project site)
   - or `https://YOUR_USERNAME.github.io/` (if repo is `username.github.io`)

## Custom Domain (Optional)

To use a custom domain like `mavensourceglobal.com`:
1. Add a `CNAME` file with your domain
2. Configure DNS as per [GitHub Pages docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
