# Mod Junkie Garage MVP Website

Static MVP website for Mod Junkie Garage. No framework, backend, analytics, embeds, maps scripts, booking, payments, or JavaScript are required for this launch.

## Files

- `index.html` — Home
- `services.html` — Services
- `about.html` — About
- `contact.html` — Contact / request estimate checklist
- `assets/css/styles.css` — Shared stylesheet
- `assets/images/` — Optimized showcase image variants generated from `images/showcase.png`
- `robots.txt` and `sitemap.xml` — SEO basics using the production canonical host

## Maintenance

- Edit shared visual styles in `assets/css/styles.css`.
- Keep contact details consistent in every HTML page footer, header strip, mobile CTA bar, and JSON-LD block. Keep canonical URLs consistent in HTML, `robots.txt`, and `sitemap.xml`.
- The contact page intentionally uses a deferred/static request-estimate checklist. Add a real static form service or external serverless endpoint only after one is selected.
- Do not add a `CNAME` file with bracket placeholders. Add `CNAME` only after the real GitHub Pages custom domain is known.

## Launch values

Production launch values applied across the site:

- City: Hoschton, GA 30548
- Phone: 404-939-5778
- Email: info@modjunkiegarage.com
- Address: 130 Pearl Industrial Ave, Hoschton, GA 30548
- Hours: 9am-6pm M-F
- Service area: Gwinnett
- Google Business Profile URL: https://www.google.com/maps/place/MJ+Garage+LLC/data=!4m2!3m1!1s0x0:0x6686216ec899c056?sa=X&ved=1t:2428&ictx=111
- Production domain: modjunkiegarage.com
- Canonical host: modjunkiegarage.com
- GitHub Pages repository: github.com/68mschmitt/mod-junkie-website.git

## Deployment notes

- Publish from `github.com/68mschmitt/mod-junkie-website.git` using GitHub Pages.
- Point `modjunkiegarage.com` at GitHub Pages through DNS for canonical host `modjunkiegarage.com`.
- Configure the custom domain in GitHub Pages, then enable HTTPS.
- After deployment, verify canonical URLs, `robots.txt`, `sitemap.xml`, mobile CTA links, call/email links, directions link, and the request-estimate fallback.
