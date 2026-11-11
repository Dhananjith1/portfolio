# Dhananjith Swarnahansa – Portfolio

Static portfolio website (plain HTML, CSS and JavaScript, no build step).

## Files
- `index.html` – the whole website. All content lives in the `DEF` block near the top of the script, between the `EDIT YOUR CONTENT HERE` comments.
- `assets/photo.webp` – profile photo (background removed).
- `assets/portfolio-preview.png` – Open Graph image for LinkedIn and other social previews.
- `infecsure.html` – academic InfecSure project case study.
- `CV.pdf` – file used by the Download CV button. Replace it with a new PDF using the same name to update the CV.

## Publish on GitHub Pages
1. Create a new GitHub repository (for example `portfolio`). For a root address like `username.github.io`, name it `username.github.io`.
2. Upload or push all files in this folder to the `main` branch.
3. Repository Settings → Pages → Source: "Deploy from a branch" → Branch: `main` → Folder: `/ (root)` → Save.
4. After about a minute the site is live at `https://USERNAME.github.io/REPO/`.

## Update workflow with Antigravity
1. Clone the repository and open the folder in Antigravity.
2. Ask the agent for a change, for example: "In index.html, update the Trex Labs end date to Aug 2026" or "Add a new project card to the DEF data". Content changes belong in the `DEF` block.
3. Review the change, then commit and push to `main` (Antigravity's terminal or source control panel).
4. GitHub Pages redeploys automatically. Refresh the live site after a minute or two (Ctrl+Shift+R).

## Notes
- The built-in edit mode from the Claude version is disabled here. Edit the `DEF` data instead.
- Email button opens a Gmail compose window. LinkedIn is the primary social contact link; the personal phone number is not displayed publicly.
- Keep CV, LinkedIn and this site consistent before applying.
