# Neha Prajapati — Portfolio (Static)

This is a single-page, responsive portfolio website for **Neha Prajapati** (BE CSE — Data Science).  
Built with plain HTML, CSS and JavaScript — no build step required.

## Files
- `index.html` — main page
- `styles.css` — styling
- `script.js` — interactivity (smooth scroll, menu, form)
- `resume.pdf` — **(replace)** put your resume file here or update the link in `index.html`
- `profile.jpg` — **(optional)** add your profile image in the same folder, or keep default initials

## How to run locally
1. Put all files in one folder.
2. Replace `profile.jpg` and `resume.pdf` with your actual files (or change the filenames/paths in `index.html`).
3. Open `index.html` in your browser.

## Deployment
- **GitHub Pages**: create a repository, push files to `main` branch and enable GitHub Pages (serve from root).
- **Netlify / Vercel**: drag & drop the folder (or connect to GitHub) — both support static sites out of the box.
- **Custom Domain**: configure DNS on your hosting provider.

## Customization tips
- Replace placeholder avatar: in `index.html` change the `<img src="profile.jpg">` path or replace the avatar block.
- Add project links: wrap `.project-card` with `<a href="...">` or add a "View repo / Demo" button.
- Form handling: currently falls back to `mailto:`. To collect messages, connect to Formspree / Netlify Forms or a small serverless endpoint.
- Color / fonts: edit `styles.css` variables at the top (`--accent-start`, `--accent-end`).

## Notes
- Accessible and responsive layout.
- Uses progressive enhancement so it works without JS for static content.
