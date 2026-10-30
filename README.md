# Après Ski

Original uploaded experience: `apres-ski 13.html` (preserved unchanged).

## Vercel deployment
This repository contains a complete standalone HTML page, with `index.html` as the root homepage. No Node.js installation or build command is required. The `vercel.json` file sets the static output directory to the repository root.

## Microsoft Teams preview and favicon
- `teams-preview.png` is a 1200 x 630 Open Graph image used by Teams and other link-preview services.
- `favicon.svg` is the tab icon, linked in the page head.
- Social tags refer to `https://apres-ski.vercel.app/`. If you use a different production domain, update the canonical and Open Graph URLs.

## Test after merge
- Confirm that the homepage and `/teams-preview.png` load without login or deployment protection.
- Paste the root URL into a **new** Teams message. Preview caching or an organisation's Teams policies may affect display.
