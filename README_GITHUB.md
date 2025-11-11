
# F1 Driver Ratings — Static Site (GitHub Pages)

This folder contains a static website generated from your uploaded Excel file.
Files:
- index.html
- styles.css
- script.js
- data.json  (the data extracted from the Excel file: 2024, 2025, 2026)

## How to publish on GitHub Pages (simple steps)

1. Create a GitHub account at https://github.com if you don't have one.
2. Create a new repository (e.g. `f1-driver-ratings`) and **do not** initialize with README/GitHub will suggest it but it's fine either way.
3. On your computer, clone the repo, or upload the files directly on GitHub using the web UI.
   - To upload via web UI: go to the repo, click "Add file" → "Upload files" and upload all files from this folder.
   - OR use git commands (example):
     ```bash
     git clone https://github.com/YOURUSERNAME/YOURREPO.git
     cd YOURREPO
     # copy the files from the 'site_files' folder into the repo folder, then:
     git add .
     git commit -m "Initial site"
     git push origin main
     ```
4. Enable GitHub Pages: Go to Settings → Pages → Branch: `main` (or `gh-pages`) → Save. GitHub will produce a URL like `https://YOURUSERNAME.github.io/YOURREPO/`.
5. Visit that URL — your dashboard should be live!

## Adding ads later
- To add Google AdSense you will eventually need a custom domain and to meet AdSense requirements.
- For quick monetization alternatives, consider affiliate links or donation buttons (Patreon/Ko-fi).

-- Files generated automatically from your Excel.
