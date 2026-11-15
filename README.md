# getclean-in.com

Website of **Clean-in**, a home cleaning company serving South Florida (Miami to Jupiter).

Rebuilt in August 2026 off a paid Wix plan onto plain static HTML, CSS and JavaScript, served by
GitHub Pages behind Cloudflare. The platform fee went to zero.

- Lighthouse: 100 for accessibility, best practices and SEO on every page; performance 98 on desktop
- six security headers at the edge (CSP with script hashes, HSTS and others)
- JSON-LD for the local business, sitemap, robots.txt and llms.txt
- quote and reservation forms posted to a small Cloudflare Worker that delivers them by email

The pages are generated from a single Python script in a private repository, then published here.
This repository is the deploy target, so pull requests are not accepted.

Built and maintained by [Matheus Corrêa](https://github.com/milhoando-dot).
