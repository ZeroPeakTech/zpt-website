# ZeroPeak Tech (ZPT) Website

Static, fast, Netlify-hosted site for ZPT — energy analytics, compliance automation, and ZERO AI.

## Quick Start
1) Copy these files into a GitHub repo named `zpt-website`.
2) Netlify → New site from Git → Connect to GitHub → pick `zpt-website`.
3) Publish directory: `/` (root), build command: *none*.
4) Add your custom domain in Netlify (`zeropeaktech.com` + `www.zeropeaktech.com`).
5) In Cloudflare DNS:
   - `CNAME www → your-site.netlify.app`
   - `A @ → 75.2.60.5` (Netlify LB) **or** `CNAME @ → your-site.netlify.app` (flattening)
6) Enable HTTPS in Netlify.

## Branding
- Drop `assets/zpt_logo.png` and `assets/zero_logo.png` to replace the inline SVG orb.
- Colors are set in `style.css` (`--primary` `--accent` etc.).

## Roadmap
- Replace SVG mockups with live Power BI embeds.
- Add /deck and /privacy pages.
- Connect contact form to Formspree or Azure Function.
