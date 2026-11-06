# Nagoya Pocket

An unofficial mobile Love Live! Fest 2 Nagoya travel guide. Research snapshot: 6 November 2026.

50 places and activities, 26 listed stamp branches, 28 priced shopping items, official reference imagery, source and X announcement links. Some multi-branch offers and parking flag locations are nested inside their shop details.

## Publish on GitHub Pages

1. Create a public repository, for example `nagoya-pocket`, in your account.
2. Upload the files inside this folder to the repository root. Keep the `assets` folder intact. No build, npm, secrets or database are needed.
3. Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
4. Open the HTTPS address GitHub reports. Do not guess that publishing has completed before it loads.
5. On iPhone, use Safari → Share → Add to Home Screen. Open the icon and use Guide → Download offline.
6. Test airplane mode. Maps, X and external sources require a connection.

All paths are relative so a repository subpath works. Source files live at repository root. `.openai/` and `dist/` are local preview files and are excluded from the distribution ZIP.

## Local preview

Run `python3 -m http.server 8080` in this folder and open `http://localhost:8080`. Opening index.html directly from Files is not supported because the app loads JSON and uses a service worker. Offline capability needs HTTPS or localhost. HTTP LAN previews do not provide full PWA capabilities.

## User data

Checklist data is saved to localStorage under `nagoya-pocket-v1`. Export/import JSON is available in Guide. No analytics, server accounts, API keys or external script dependencies. Website storage can be cleared by iOS. Safari and Home Screen contexts may differ.

## Updates

Edit data.json and version references in data.json and sw.js together. Test new service-worker updates before travelling. Current service worker uses a versioned cache. A downloaded pack is specific to that guide version. Previously recorded progress remains local.

## Research and images

Published dates and offer rules are not a guarantee of live stock. Details retain uncertainties and source links. Official and reproduced announcement images are attributed in assets/credits.json. Love Live! and partner artwork belongs to its respective owners, and is not covered by the code licence. This is an unofficial reference guide, not affiliated with the franchise or participating shops.
