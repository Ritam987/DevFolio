# Ritam Chatterjee – Portfolio

Static portfolio site built with HTML, Tailwind CSS, and a serverless contact form (Formspree). Designed to run on GitHub Pages.

## Files
- `index.html` – main site
- `thankyou.html` – redirect page after successful contact form submission
- `Ritam Chatterjee_Resume.pdf` – your resume (place in repo root or update the link in `index.html`)

## Local preview
Open `index.html` in a browser. No build steps required.

## Contact form (Formspree)
- Endpoint: `https://formspree.io/f/mgvnrlpo`
- Fields: `name`, `email`, `message`
- Success redirect: `/thankyou.html` via hidden `_next` input
- Manage submissions and email notifications in your Formspree dashboard.

## Deploy to GitHub Pages
1. Create a new public repo (or push this folder to an existing repo).
2. Commit and push all files, including `index.html` and `thankyou.html`.
3. In GitHub: Settings → Pages → Build and deployment → Source: `Deploy from a branch`.
4. Branch: `main` (or `master`), Folder: `/ (root)`. Save.
5. Wait for Pages to publish, then open the provided URL.

## Customization checklist
- Update social links in `index.html`.
- Replace `og:url` and `og:image` in `<head>` with your real domain and preview image.
- Ensure `Ritam Chatterjee_Resume.pdf` is present or update the resume link.

## Security
All external links that open in a new tab use `rel="noopener noreferrer"`.

## License
This portfolio content is © Ritam Chatterjee. Code snippets may be reused with attribution.
