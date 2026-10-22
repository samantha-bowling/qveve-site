# qveve.music — static site

Single-page static replacement for the Squarespace site. No build step, no framework.

## Files
- `index.html` — the whole site (Home, For Artists, For Listeners, About, footer)
- `privacy-policy.html`, `terms-of-service.html` — legal pages, same header/footer
- `assets/logo-black.png`, `assets/logo-white.png` — logo (light / dark mode)
- `assets/favicon.ico`, `assets/founder.jpg`

## Deploy
Any static host works. Easiest:

**GitHub Pages**
1. Push this folder to a repo (e.g. `samantha-bowling/qveve-site`).
2. Settings → Pages → Source: `main` / root.
3. Add a `CNAME` file containing `www.qveve.music`, then point the domain's DNS at GitHub Pages.

**Vercel / Netlify / Cloudflare Pages**
Import the repo, no build command, output directory `/`. Add the custom domain in the dashboard.

## Things to finish
- **Founder photo**: `assets/founder.jpg` is in place; swap the file to change it.
- **Privacy Policy / Terms**: `privacy-policy.html` and `terms-of-service.html` describe the site as it is (no data collection). Update them before adding analytics with cookies or a mailing list.
