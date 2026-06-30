# Crown Fluid Systems — Website

A static, ready-to-launch website for Crown Fluid Systems (Vijayanagar, Mysore), supplier of refrigeration service valves, refrigeration charging valves, hydraulic fittings and hydraulic valves.

## Files

- `index.html` — all page content
- `style.css` — styling
- `script.js` — mobile nav, WhatsApp enquiry form

No build step, no dependencies. Pure HTML/CSS/JS.

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `crown-fluid-systems`).
2. Upload `index.html`, `style.css`, and `script.js` to the root of the repository (or push via git).
3. Go to **Settings → Pages** in the repository.
4. Under **Build and deployment**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. Save. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

If you'd like a custom domain (e.g. `crownfluidsystems.com`), add it under **Settings → Pages → Custom domain** and configure the DNS records your registrar requires.

## Editing content

- Phone/WhatsApp number: search for `919036070191` in `index.html` and replace everywhere it appears (header, hero, contact section, footer, floating button, and `script.js`).
- Address: edit the "Visit Us" card and the Google Maps embed URL in the Contact section.
- Products: each product is an `<article class="product-card">` block inside `#products` — duplicate or edit freely.

## Notes

- The contact form does not store data anywhere — submitting it opens WhatsApp with the message pre-filled, so there's no backend or database needed.
- The map uses a no-API-key Google Maps embed query, so it works out of the box on GitHub Pages.
