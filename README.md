# ICON Landing Page

Pre-sign-up landing page for ICON — content that adapts to every visitor.

## Setup

1. Replace `YOUR_FORM_ID` in `index.html` with your [Formspree](https://formspree.io) form ID
2. Update the OG image URL in the meta tags once you have a screenshot

## Deploy

### Cloudflare Pages

```bash
# Connect repo via Cloudflare dashboard, or:
npx wrangler pages deploy . --project-name=icon-site
```

Build settings: none needed — it's a static HTML file.

### GitHub Pages

1. Go to repo Settings → Pages
2. Set source to `main` branch, root `/`
3. Save — site will be live at `https://dwehrmann.github.io/icon-site/`

## Local preview

```bash
python3 -m http.server 8000
# or
npx serve .
```
