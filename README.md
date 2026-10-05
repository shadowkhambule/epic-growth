# Epic Growth — Landing Page

A single, self-contained HTML landing page for **Epic Growth**, an investing membership site.

## How to open

- **Easiest:** double-click `index.html` (or drag it into any modern browser — Chrome, Firefox, Safari, Edge).
- **From a terminal:**
  - macOS: `open index.html`
  - Linux: `xdg-open index.html`
  - Windows: `start index.html`
- **Optional local server:** `python3 -m http.server 8000` in this folder, then visit <http://localhost:8000>.

## Notes

- All CSS and JS are embedded in `index.html`; Google Fonts (Playfair Display + Inter) load over the internet, with Georgia / system sans as offline fallbacks.
- The email signup form has no backend — it validates the address and shows an on-page confirmation.
- Pricing (`$XX`) and testimonials are placeholders; replace them before launch.
