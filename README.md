# Charanjitt Meruga — Portfolio

A single-page personal portfolio site, built as plain HTML/CSS/JS (no build step, no dependencies to install).

## Files
- `index.html` — the whole site (photo is embedded inside the file, so there's nothing else to upload)

## View it locally
Just double-click `index.html`, or open it in a browser.

## Push it to GitHub and go live (GitHub Pages)

1. **Create a new repository** on GitHub — e.g. `charanjitt-portfolio`. Don't add a README from GitHub's side (you already have one here).

2. **Push this folder** to it. From inside this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Add portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

3. **Turn on GitHub Pages**:
   - Go to your repo on GitHub → **Settings** → **Pages**
   - Under "Build and deployment", set **Source** to `Deploy from a branch`
   - Set **Branch** to `main` and folder to `/ (root)` → **Save**

4. Wait about a minute, then your site will be live at:
   ```
   https://<your-username>.github.io/<your-repo>/
   ```

## Updating the site later
Edit `index.html` directly, then:
```bash
git add .
git commit -m "Update portfolio"
git push
```
GitHub Pages will redeploy automatically within a minute or two.
