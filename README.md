# The 5-Day Tune-Up — landing page

Static preview of the DSC website tune-up landing page, published on GitHub Pages.

**Live:** https://dealersales.github.io/website-tune-up/

This is a draft for sharing with dealers, not the production page. Pricing is deliberately
TBC pending a decision, and the published copy carries `noindex` so it cannot compete with
sales-consultants.com. When the price is set and the page moves to the real domain, drop the
noindex and point the mailer at the live URL.

Generated from `~/Projects/dsc-website-tuneup/` — do not edit `index.html` here, rebuild it:

```bash
python3 build_landing.py && python3 publish_site.py
git add -A && git commit -m "rebuild" && git push
```
