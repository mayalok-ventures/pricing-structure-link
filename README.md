# Deeplink Creators Pricing Landing Page

This project is ready for **Cloudflare Pages** deployment as a static site.

## Deploy on Cloudflare Pages (no local run required)

1. Push this folder to a GitHub/GitLab repo.
2. In Cloudflare dashboard, go to **Workers & Pages** -> **Create application** -> **Pages** -> **Connect to Git**.
3. Select your repo and use:
   - Framework preset: `None`
   - Build command: *(leave empty)*
   - Build output directory: `.`
4. Click **Save and Deploy**.

## Project Structure

- `index.html` - Cloudflare Pages entry file
- `pricing-structure.html` - editable source copy
- `assets/DLC_logo.png` - brand logo
- `wrangler.toml` - Cloudflare deployment config
- `_headers` - basic security headers
