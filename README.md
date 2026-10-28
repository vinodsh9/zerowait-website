# ZeroWait website

Live at https://zerowaitai.com

Marketing site for ZeroWait, an AI WhatsApp receptionist for appointment-based businesses.

Before going live, replace these placeholders in every file:
- `zerowaitai.com` – your website address

- Dates, data-retention periods and refund policy in privacy.html and terms.html

## Structure
- `index.html` – home page (LED token-board design)
- `classic/` – earlier navy design, kept for reference (not indexed by Google)
- `privacy.html`, `terms.html` – legal pages
- `_headers`, `_redirects`, `404.html` – Cloudflare Pages settings

## Hosting
Cloudflare Pages, connected to this repo. No build step: build command empty, output directory `/`.
