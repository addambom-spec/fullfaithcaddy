# Full Faith Caddy v11

GitHub Pages-ready package for the latest Full Faith Caddy build.

## Files included
- `index.html` — main app
- `.nojekyll` — keeps GitHub Pages simple
- `README.md` — setup guide
- `UPLOAD_CHECKLIST.txt` — quick steps

## GitHub upload steps
1. Create a new **public** GitHub repository.
2. Upload all files from this folder to the **repository root**.
3. In GitHub, go to **Settings** → **Pages**.
4. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
5. Save.
6. Wait for GitHub Pages to publish the site.
7. Open the Pages URL on your phone.
8. Allow **Location** access when prompted.

## Important notes
- This version includes:
  - one-screen UI
  - GPS
  - auto wind
  - nearby course selector
- The course selector currently uses starter/sample hole data.
- For true on-course accuracy, replace sample tee/green coordinates with real ones hole by hole.
- GPS and auto wind work best from the live HTTPS GitHub Pages URL, not from a local file preview.

## Updating later
Replace `index.html` in the same repo with a newer version and GitHub Pages will republish automatically.

## Suggested repo names
- `full-faith-caddy`
- or `yourusername.github.io` if you want this as your main Pages site
