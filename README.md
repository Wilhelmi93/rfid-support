# rfid-support

Marketing website for **RFIDapp**, an iOS/iPadOS app for reading, managing and
reviewing RFID/NFC tags (ISO 14443, ISO 15693, and other NFC tag types
supported by the iPhone).

Live at **https://teuma.dev**.

## Structure

- `index.html` — root redirect to `de/` or `en/` based on browser language
- `de/`, `en/` — the German and English site (home, support, privacy policy)
- `assets/` — shared CSS and images

Plain static HTML/CSS, no build step. Serve any of these directories with a
static file host (e.g. GitHub Pages) to publish the site.

Support email: **support@teuma.dev**.

## Notes

- Privacy policy (`de/datenschutz.html`, `en/privacy.html`) is filled in with
  the controller's details and current data-handling practice, but is not
  reviewed by a lawyer — worth a final legal check before going live,
  especially once analytics, surveys, or collaboration features are added.
