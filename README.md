# GitHub Pages Publish Folder

This folder is prepared to be published as a standalone GitHub Pages site.

Files:
- `index.html`
- `cv_rahdouni_yassir_eng_3.pdf`
- `.nojekyll`

Recommended approach:
1. Create a new public GitHub repository just for the portfolio.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the `main` branch and the `/ (root)` folder.
6. Save and wait for the site URL to appear.

If you prefer using git locally:
```bash
cd /Users/fouzirahoudni/Desktop/cv/github-pages-site
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```
# yassirrahdouni.github.io
