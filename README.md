# Your Safari

Public website for **Your Safari**—a technology company building practical, AI-assisted digital services for international travelers in China (including the GoChina app direction reflected in legal pages).

## Live site

After GitHub Pages is enabled for this repository, the site is served at:

**https://your-safari.github.io/your-safari/**

Deploys automatically from `main` via [GitHub Actions](.github/workflows/pages.yml).

## What’s in this repo

| Path | Purpose |
|------|---------|
| `index.html` | Landing page (Tailwind via CDN, waitlist form posts to Google Forms) |
| `contact.html`, `privacy.html`, `terms.html` | Company contact and policies (`site.css`) |
| `site.css` | Shared styles for secondary pages |
| `.nojekyll` | Lets Pages serve static files as-is |

## Local preview

From the repo root:

```bash
python3 -m http.server 8080
```

Open http://localhost:8080/ — use a local server so form redirects and asset paths behave like production.

## Contact

General inquiries: [info.1@your-safari.com](mailto:info.1@your-safari.com)

## License

Site content © Your Safari Technology Group unless otherwise noted.
