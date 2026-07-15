# rfid-support

Marketing website for **RFIDapp**, an iOS/iPadOS app for reading, managing and
reviewing RFID/NFC tags (ISO 14443, ISO 15693, and other NFC tag types
supported by the iPhone).

## Structure

- `index.html` — root redirect to `de/` or `en/` based on browser language
- `de/`, `en/` — the German and English site (home, support, privacy policy)
- `assets/` — shared CSS and images

Plain static HTML/CSS, no build step. Serve any of these directories with a
static file host (e.g. GitHub Pages) to publish the site.

## Before publishing

- Replace the placeholder support email (`support@example.com`) in
  `de/support.html`, `de/datenschutz.html`, `en/support.html`, `en/privacy.html`.
- Review and fill in the `TODO` sections in the privacy policy pages
  (`de/datenschutz.html`, `en/privacy.html`) — they are drafts, not reviewed
  legal text.