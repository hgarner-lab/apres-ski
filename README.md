# Après Ski

Original uploaded experience: `apres-ski 13.html` (preserved unchanged).

## Vercel deployment
This repository contains a complete standalone HTML page, with `index.html` as the root homepage. No Node.js installation or build command is required. The `vercel.json` file sets the static output directory to the repository root.

## Microsoft Teams preview and favicon
- `teams-preview.png` is a 1200 x 630 Open Graph image used by Teams and other link-preview services.
- `favicon.svg` is the vector tab icon. `favicon.ico` and `favicon-32x32.png` provide browser fallbacks; `apple-touch-icon.png` supports mobile bookmarks. All are linked from the page head.
- Social tags refer to `https://apres-ski-beryl.vercel.app/`. If you use a different production domain, update the canonical and Open Graph URLs.

## Test after merge
- Confirm that the homepage and `/teams-preview.png` load without login or deployment protection.
- Paste the root URL into a **new** Teams message. Preview caching or an organisation's Teams policies may affect display.

## Domain note
Vercel assigned `apres-ski-beryl.vercel.app` as the public domain. The original metadata pointed to `apres-ski.vercel.app` by mistake; this revision corrects it. Confirm that this exact Vercel project is connected to `hgarner-lab/apres-ski` and its Production Branch is `main`.
