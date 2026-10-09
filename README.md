# Wulan's portfolio — GitHub Pages

A static website: HTML + CSS, no build tools needed.

## Publish
1. Create a **public** repository named `YOURUSERNAME.github.io` on GitHub.
2. Upload the **contents** of this folder (not the ZIP), keeping `index.html` at the repository root and the `assets` and `projects` folders intact.
3. Go to **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
4. Open `https://YOURUSERNAME.github.io/` after deployment completes.

## Edit
- Homepage copy and links: `index.html`
- Project pages: `projects/*.html`
- Art page: `art.html`
- Colors, typography, layout: `assets/style.css`
- Replace the portrait placeholder by adding an image to `assets/` and replacing the `photo-placeholder` div in `index.html` with `<img src="assets/portrait.jpg" alt="Portrait of Wulan" class="portrait">`; then add `.portrait{width:100%;height:100%;object-fit:cover;}` to CSS (or size as desired).
- Replace project gradient blocks with your own approved project photos/maps by adding CSS `background-image:url('filename.jpg')` to the appropriate `.visual` class, or replacing blocks with `<img>` tags.
- Art page: replace the `.art-box` placeholders with your artwork images.
- Update the LinkedIn URL in the footer in each HTML file (currently a generic LinkedIn link).
- Verify publication DOIs and program names before public launch.
- Confirm permissions before posting partner reports, guidebooks, maps or proprietary data.

Google Fonts are loaded via CSS and need internet access. All other site content is static.
