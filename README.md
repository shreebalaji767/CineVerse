# CineVerse

CineVerse is a static poster-gallery parody/catalog for movies, dramas, anime, manga, and donghua. Its premium checkout is a **simulation only**—not a real payment service.

## Features

- Responsive dark poster gallery with search and category filters.
- Categories include latest 2026 titles, Hollywood, K-drama, C-drama, Japanese drama, anime, manga, donghua, Indian cinema, classics, and documentaries.
- Catalog includes titles across multiple eras, from classic films to newer releases.
- Clicking a poster opens the ₹999 mock premium paywall.
- The demo checkout offers simulated UPI, card, and net-banking choices, then displays a clearly labeled simulated receipt with a demo-only reference and timestamp.
- Some artwork URLs are official distributor images; other catalog items use visual placeholders. Third-party image URLs may change or fail.

## Payment simulation and safety

- **No real payment gateway is integrated.**
- The checkout never asks for card numbers, CVV, UPI IDs, bank credentials, or other real payment information.
- The demo receipt is explicitly marked **SIMULATION ONLY / NOT A REAL TRANSACTION**. Its reference is prefixed with `DEMO-CV-` and is not proof of payment.
- No bank, UPI app, card network, or payment processor is contacted. No money can be collected or charged.
- No title is actually purchased or unlocked by the simulation.
- No backend, database, login, analytics, cookies, or `localStorage` is used. The simulated receipt is generated in the browser and is not saved.

## Cost and technology

- Static HTML, CSS, and JavaScript; no framework, package installation, build tool, or paid API is required.
- GitHub Pages can host a public static site at no charge within GitHub's applicable usage terms.
- No movie or episode video is hosted or streamed by this repository.

## Media and copyright

- Artwork is loaded from external URLs, so an internet connection is needed and third-party images may stop working.
- Some manga/donghua/catalog artwork is a placeholder rather than the official cover. Release information and availability can change; this is a manually curated static catalog, not a live or automatically updated database.
- Posters, logos, and titles may be copyrighted or trademarked by their respective owners. This is not an official service or endorsement. For public deployment, use artwork you have permission or rights to display and comply with providers' terms.

## Files

- `index.html`: gallery, catalog entries, filters, paywall, and mock checkout/receipt.
- `.nojekyll`: prevents Jekyll processing for static publishing.
- `.github/workflows/pages.yml`: builds and deploys the static site to GitHub Pages on pushes to `main`.
- `README.md`: project behavior, privacy, and deployment notes.

## GitHub Pages deployment

The workflow is committed on `main` and deploys on each push. In repository **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions** if it is not already selected. Then check the **Actions** tab for the deployment result.

The expected project URL is:

https://shreebalaji767.github.io/CineVerse/
