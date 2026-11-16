Bhavishwa website: deploy-ready bundle
======================================
Upload the contents of this folder to the root of bhavishwa.com. No build step.

Every page has its own clean address, for example:
  bhavishwa.com/terravigil   bhavishwa.com/crosscheck   bhavishwa.com/a-mart
  bhavishwa.com/ikomai       bhavishwa.com/science-kits bhavishwa.com/water-recyclers
  bhavishwa.com/gas-plasma-synthesizer   bhavishwa.com/frontiers/space   bhavishwa.com/partner

Each main address already has its own folder with a page-specific title and
description, so it works on any static host (GitHub Pages, cPanel, S3...).
Other addresses fall back to index.html via the included host files:
  Netlify / Cloudflare Pages: _redirects     Vercel: vercel.json
  Apache / cPanel: .htaccess                 Nginx: nginx.conf.example
