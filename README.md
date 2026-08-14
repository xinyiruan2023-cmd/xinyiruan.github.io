# She Women / 畲族女性 — Digital Curation

A no-build static website designed for GitHub Pages. Open `index.html` locally or upload the entire folder to a GitHub Pages repository.

## Editing without code

1. Open the website and click **Edit site**.
2. Click any outlined text and type.
3. Click an image, choose **Replace selected image**, then drag the image to change its focal point or use the zoom slider.
4. Adjust the four theme colors.
5. Choose **Save in this browser** for a draft, or **Download edited index.html** to create the publishable page. Upload that downloaded `index.html` over the existing one in GitHub. **Export settings backup** creates a reusable JSON backup.

Browser saves use local storage and are private to that browser. They do not automatically publish to GitHub. To make edits visible to everyone, download the edited `index.html` and upload it over the repository's existing `index.html`. Large photographs should be compressed for web use before replacement.

## Publishing at xinyiruan.github.io

This URL normally comes from the repository named `xinyiruan.github.io` in the GitHub account `xinyiruan`.

1. Back up or download the current repository first.
2. In GitHub, open `xinyiruan/xinyiruan.github.io`.
3. Choose **Add file → Upload files**.
4. Upload `index.html`, `styles.css`, `app.js`, and the entire `assets` folder to the repository root. Replace files with the same names.
5. Commit directly to the branch currently used by Pages (usually `main`).
6. Open **Settings → Pages** and confirm **Deploy from a branch**, branch `main`, folder `/ (root)`.
7. Wait a few minutes, then refresh `https://xinyiruan.github.io/` with a hard reload.

The address stays unchanged because the repository name and GitHub account remain unchanged. Do not create a second Pages repository if the goal is to preserve the exact URL.

## File map

- `index.html` — all exhibition content and structure
- `styles.css` — layout, typography and theme
- `app.js` — on-page editor and local saving/export
- `assets/` — replaceable default artwork
