# TurnScope public pages

Bilingual static landing, privacy, and support pages. No build step, dependencies, or analytics scripts.

## Hosting

GitHub repository: https://github.com/cczhong11/turnscope-site
GitHub Pages source: main branch, repository root.
Custom domain: turnscope.tczhong.com (defined in CNAME).

Public routes once DNS and HTTPS are ready:

- https://turnscope.tczhong.com/
- https://turnscope.tczhong.com/privacy/
- https://turnscope.tczhong.com/support/

Cloudflare DNS: four A records named `turnscope`, DNS only: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`. The repository CNAME file contains `turnscope.tczhong.com`. GitHub issues the HTTPS certificate for this hostname. Confirm all routes respond over HTTPS before using them in App Store Connect.

## Preview

Run `python3 -m http.server 8877 --bind 127.0.0.1` in this directory, then open http://127.0.0.1:8877/.

## Updates

Edit these files, commit, and push main to publish. Preserve CNAME and .nojekyll.

Support email: me@tczhong.com. Review privacy statements when changing data handling.
