# Epilogue Life - epilogue.life

Marketing website for Epilogue Life, based on the existing product design (app.epilogue.life):
deep sepia, cream text, burnt-orange accents, Fraunces + Inter.

- `index.html` - the whole site (single self-contained file, Google Fonts via CDN)
- `favicon.svg` - sunset mark

All calls to action point to the live app: `app.epilogue.life/signup` and `/login`.

## Deploy (static site, no build step)

- **Netlify:** New site from Git -> pick this repo -> Build command: (none) -> Publish directory: `/`
- **Vercel:** Import repo -> Framework preset: Other -> no build -> Output: root

Then point `epilogue.life` (and optionally `www.epilogue.life`) at the site.

Maintained by Brendan O'Keefe. (c) 2026 Employ AI Pty Ltd.
