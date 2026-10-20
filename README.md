# CineVerse

CineVerse is a responsive, static catalog for movie and TV posters, K-drama, C-drama, Japanese drama, anime, manga, donghua, and more. It provides poster browsing and title descriptions only; it does not host or stream films, episodes, or manga pages.

## Features

- Responsive poster grid, search, and category filters for mobile, tablet, and desktop.
- Custom CineVerse logo and SVG favicon.
- Progressive Web App (PWA) manifest, install button where supported, and service-worker app-shell caching for basic offline access.
- Clicking a poster opens a premium demo flow; completing the demo and closing its receipt opens that title's description and metadata.
- Optional official-information links are provided where available.

## Checkout and privacy

- The checkout is a **simulation only**. It does not process purchases or unlock paid content.
- Demo UPI, card, and net-banking choices never request payment credentials.
- Demo receipts are clearly marked as not proof of payment and use browser-generated references. No bank, UPI app, card network, or payment processor is contacted; no money can be charged.
- There is no backend, database, login, analytics, cookies, or `localStorage`. Demo unlock status exists only in the current page session.
- Never enter real payment information into this site.

## PWA installation

The app can be installed when served over HTTPS by a compatible browser. On supported browsers, use **Install app**. On iOS, open the browser's Share menu and choose **Add to Home Screen**. Browser support and install prompts vary by device and browser.

The service worker caches the static app shell. Poster images are hosted externally, so they may not be available offline.

## Catalog and media notes

- The catalog is manually curated, not a live release feed. Some newer titles and international animation entries use placeholder artwork, and external image URLs can change or fail.
- Title availability, dates, and official links may vary by region.
- Posters, logos, and names may be copyrighted or trademarked by their owners. Use artwork you have permission to display and follow providers' terms.

## Files

- `index.html`: catalog, styles, demo checkout, and title details.
- `favicon.svg`: brand icon and PWA icon source.
- `manifest.webmanifest`: PWA metadata.
- `sw.js`: service worker for app-shell caching.
- `.github/workflows/pages.yml`: GitHub Pages build/deploy workflow; copies all PWA assets to the published artifact.
- `README.md`: project documentation.

## GitHub Pages

The workflow deploys on pushes to `main`. In **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions** if needed.

Expected URL: https://shreebalaji767.github.io/CineVerse/
