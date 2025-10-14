## Personal website (template)

This repository contains a personal website built from the Strata HTML5 UP template. It has been customized with
content and assets in the `assets/`, `images/`, and `pdf/` folders. Use this repo as a starting point for your own
personal page.

How to personalize
- Replace the name, title and short bio in `index.html` (search for "Your Name" and the commented guidance near the top).
- Replace `images/avatar.jpg` with your avatar (keep the filename or update the `index.html` img src).
- Update the email address placeholders (search for `email@example.com` in `index.html`).
- Replace or add PDFs in `pdf/` and update links in `index.html` (e.g. lectures, CV, publications).
- Update or remove social links in the footer.
- If you have a custom domain, update or add `CNAME` file at the repo root (one domain per line). Remove it if you
	don't use a custom domain.

License & credits

The HTML/CSS design comes from **Strata** by [HTML5 UP](https://html5up.net) (Creative Commons Attribution 3.0). Keep the
license attribution if you publish this site publicly.

If you'd like, I can:
- Replace the avatar with a neutral placeholder image and add a sample CV.
- Update the site title and metadata programmatically.
- Wire up a simple deploy workflow (GitHub Pages) and example `gh-pages` instructions.

---

## Deploying this site

Recommended quick option: GitHub Pages (free for static sites)

1. Create a GitHub repository and push this project to it (replace <your-repo-url> below):

```bash
git init
git add .
git commit -m "Initial personal website"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

2. The repository already contains a GitHub Actions workflow at `.github/workflows/deploy-pages.yml` which will publish the repository root to the `gh-pages` branch automatically when you push to `main`.

3. In your GitHub repository settings -> Pages, set the site source to the `gh-pages` branch (if not set automatically). If you want a custom domain, add the domain to the `CNAME` file (root) and configure DNS to point to GitHub Pages.

Alternatives
- Netlify: Drag the repo into Netlify, or connect via the Netlify UI. Netlify will detect this as a static site and publish the root.
- Vercel: Connect the repository in Vercel dashboard and set the output directory to root (`/`).

If you want, I can also:
- Create a sample `pdf/CV.pdf` placeholder and rename the publications link.
- Set up an automated preview or PR preview workflow.
