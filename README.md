# SUMIT — Portfolio

A single-page static portfolio for Sumit Kumar Singh (SUMIT). This repository contains a standalone HTML/CSS portfolio that showcases projects, technical skills and contact information.

## What I changed
- Added `index.html` (renamed and cleaned up from `index-2.html`).
- Extracted inline CSS into `styles.css` for easier maintenance.
- Wired the contact form to Formspree with a placeholder form ID (`YOUR_FORM_ID`) — replace this with your Formspree form ID to receive messages.
- Added small accessibility improvements: skip link, labeled form controls, ARIA attributes for navigation and the menu.

## How to run locally
- Open `index.html` directly in a browser, or serve the repo with a simple static server:

  ```bash
  # Python 3
  python3 -m http.server 8000
  # then open http://localhost:8000/index.html
  ```

## Deploy to GitHub Pages (recommended)
1. Ensure the file is named `index.html` in the repository root (already done).
2. In the repository settings -> Pages, set the source to the `main` branch and root (/) folder.
3. Save — your site should be published at `https://<your-username>.github.io/Sumit-Portfolio` shortly.

## Configure the contact form (Formspree)
1. Sign up at https://formspree.io and create a new form to get a form ID.
2. Replace `YOUR_FORM_ID` in the `action` attribute of the form in `index.html` with your actual form ID.
3. Test the form by submitting from the live site.

## Removing the old uploaded file
I created `index.html` from the original `index-2.html`. I do not have permission (via this assistant) to delete files from the repository. If you want `index-2.html` removed, you can:

- Delete it in the GitHub web UI (open the file → click trash icon → commit), or
- Run locally:
  ```bash
  git rm "index-2.html"
  git commit -m "Remove uploaded duplicate file"
  git push
  ```

If you'd like, I can create a branch and open a PR that removes `index-2.html` so you can review the change before merging.

## Next steps I can do for you
- Create a PR that deletes `index-2.html` (so nothing duplicate remains).
- Replace Formspree placeholder with an actual form ID and test end-to-end (you'll need to provide the form ID or share access).
- Add a small Netlify/Render deploy config if you prefer automated deploys.

