# Karm Performance Management Toolkit Website

A clean, CSR-focused one-page website for Karm's free Performance Management Toolkit.

## What is included

- React-based single page interface
- Tailwind CSS styling through the Tailwind CDN
- Karm English and Arabic logo assets in `assets/`
- CSR initiative section
- Downloadable toolkit cards
- Required access form before downloads
- Real PDF manual and XLSX template files in `assets/downloads/`
- Local demo tracking for downloads, organizations, and template activity
- Training video placeholders
- Impact dashboard placeholder
- FAQ section

## How to preview

Open `index.html` in a browser.

Because this static prototype uses CDN scripts for React, ReactDOM, Babel, and Tailwind, the preview needs internet access. For production hosting, upload the full folder to any static host.

## Production notes

Before launch:

- Replace local browser tracking with a backend, Google Sheet, CRM form endpoint, or analytics service.
- Replace video placeholders with YouTube, Vimeo, or self-hosted embeds.
- Add the final privacy notice and consent language for form submissions.
- If desired, convert the static prototype into a Vite React app for a bundled production build.
