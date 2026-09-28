# Personal Website

This repository hosts the personal website for **Dmytro (Dima) Kashchuk** using GitHub Pages.

## Structure
- `index.html` — Main page, hand-written from `resume.md` content.
- `style.css` — Light, monospace, single-column styling. No shadows, gradients or frameworks. Print styles included.
- `script.js` — Dynamic year in the footer.
- `resume.md` — Source resume content for future updates.

## Features
- Semantic HTML with accessible landmarks and skip link.
- Responsive single-column layout (date/content grid collapses on small screens).
- Print-ready formatting for physical resume export.
- Basic SEO & Open Graph tags.
- Structured data (JSON-LD Person schema).

## Update Workflow
1. Edit `resume.md` as needed.
2. Reflect changes manually in `index.html` (or build a script later to automate parsing Markdown → HTML).
3. Commit and push to `main` to deploy via GitHub Pages.

## Possible Enhancements
- Automated Markdown → HTML build step (Node script or static site generator like Eleventy/Astro).
- Add RSS feed for publications/posts.
- Accessibility audit (axe / Lighthouse) and improvements.
- Add analytics (privacy-friendly, e.g., Plausible).
- Add a `/publications` subpage or filtering UI.
- Contact form using a serverless endpoint.

## Local Preview
Open `index.html` directly or serve:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## License
Content © Dmytro Kashchuk. Code snippets under MIT unless noted otherwise.
