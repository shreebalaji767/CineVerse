# CineVerse

CineVerse is a deliberately over-the-top, static movie-poster parody with a pretend premium paywall. It is a visual joke, not a streaming service and not a real checkout.

## Cost

- **Build cost: ₹0** using plain HTML, CSS and JavaScript.
- No paid hosting or build tool is required. GitHub Pages can host this static repository at no charge within GitHub's applicable usage terms.
- No paid APIs, frameworks, package installs, server, or build command.

## What visitors see

- A responsive, dark poster gallery containing movie and series artwork.
- The site intentionally shows posters only in the gallery: no search box, title descriptions, categories, watchlist, or episode/player interface.
- Clicking any poster opens a mock premium-access panel.
- The displayed ₹999 unlock price and upgrade option are parody UI only. Buttons produce joke messages and do not unlock or play anything.

## Payments and privacy

- **There is no payment gateway.** No payment can be made or collected.
- The site does not request card details, UPI IDs, bank details, passwords, email addresses, or other payment information.
- No database, backend, login, analytics, cookies, or `localStorage` is used.
- No user selections or visitor information are saved.
- The mock checkout buttons only update text in the page; they do not contact a payment service.

## Media and copyright

- The gallery loads poster artwork from external image URLs. An internet connection is needed to load those images, and third-party image URLs may change or fail.
- This project does not host or stream movies, television episodes, or other video.
- Poster artwork and names may be copyrighted or trademarked by their respective owners. This is a fan-made parody/catalog display, not an official service or endorsement. For public deployment, use artwork you have rights or permission to display and follow the relevant providers' terms.
- No poster click opens an unauthorized stream, paid platform, or external checkout.

## Files and implementation

- `index.html`: the entire site, including styles, gallery data, and interaction logic.
- `.nojekyll`: lets GitHub Pages publish the root files without Jekyll processing.
- `README.md`: project behavior, limitations, privacy, and deployment notes. These implementation details are intentionally documented here rather than displayed on the site.

The page is a static front end. It can be opened directly in a modern browser.

## GitHub Pages deployment

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. Wait for GitHub Pages to publish. The final URL appears in the Pages settings; for this repository it is normally `https://shreebalaji767.github.io/CineVerse/`.

No other setup is required.
