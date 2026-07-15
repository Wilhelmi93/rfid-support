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

Domain: **teuma.dev** (see `CNAME`, used by GitHub Pages custom domains).
Support email: **support@teuma.dev**.

## Before publishing

- Icon is still a placeholder (`assets/img/icon.svg`) — swap in the real app
  icon once available.
- Review and fill in the `TODO` sections in the privacy policy pages
  (`de/datenschutz.html`, `en/privacy.html`) — they are drafts, not reviewed
  legal text (data controller name/address, and whether the app uses
  analytics, crash reporting, iCloud sync, or ad SDKs).