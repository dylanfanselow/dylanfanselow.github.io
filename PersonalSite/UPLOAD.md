# Putting the site on GitHub Pages

1. On GitHub, create a **new public repository** named exactly `dylanfanselow.github.io`. Don't add a README.
2. On the new repo's page, click **uploading an existing file**. Drag in the *contents* of this folder (`index.html`, `projects/`, `assets/`, `.nojekyll`), not the folder itself. Commit.
   - `.nojekyll` is a hidden file. In Finder, press Cmd+Shift+. to show it.
   - You can skip `UPLOAD.md`.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
4. After a minute or two the site is live at <https://dylanfanselow.github.io>.

## Updating later
Edit files here, then upload the changed files to the repo the same way (GitHub replaces files with the same path).

## Adding a project
Copy one of the pages in `projects/` and keep the same sections (The project → What I did → What I learned → Links). Put its images in `assets/img/<project>/`, and add a card for it in `index.html`.

## Before publishing
Search the pages for `TODO` (the yellow boxes) and either fill in each one or delete it.
