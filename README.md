# NPCBook

**NPCBook** is a fictional, text-first social feed where original characters from anime-inspired worlds, fantasy realms, sci-fi settings, supernatural towns, dramas, and more share ordinary moments, gossip, rivalries, strange jobs, and wonderfully chaotic problems.

The characters have their own lives and perspectives. They speak from inside their worlds and do not refer to themselves as fictional characters or acknowledge an audience, authors, chapters, or a story being told.

**Live repository:** https://github.com/shreebalaji767/NPCBook

## Features

### A feed from many worlds
- A randomized selection of worlds and posts is assembled when the page loads or refreshes.
- Posts cover everyday life, relationships, training, magic, work, travel, mysteries, and absurd mishaps.
- World labels, genre filters, search, feed views, and sorting help you explore the feed.
- The content is text-first, with stylized post cards and mood icons rather than a catalog of external media.
- NPC posts are handcrafted in the page source; the site does not generate new dialogue with a live AI service.

### Fictional names and character profiles
- NPCs use distinct, realistic-sounding fictional names and natural-looking usernames.
- Select a character's name or avatar to open their profile.
- Profile cards show the character's world, a short in-world bio, profile stats, and recent moments.
- Follow or unfollow characters to explore a feed centered on the people you choose.

### Social interactions
- **Like** and unlike posts.
- **Comment** on posts and read the visible conversation.
- **Reshare** a post into the current feed.
- **Save** posts for the Saved view.
- **Follow** and unfollow characters.
- **Screenshot** creates a downloadable PNG card containing the post's character name, handle, world, and text.
- Share and interaction feedback is shown in the interface as you use it.

### Create a post
Use the post composer to write a status update for your own universe persona. Choose a name, username, universe category, mood, and icon, then publish the post into the current feed.

### Responsive design
The dark, neon-accented interface is designed for desktop and smaller screens, with navigation, a central feed, discovery panels, and profile dialogs.

## Privacy and persistence

NPCBook is a browser-only front-end demo:
- No backend, database, account system, or server-side profile storage is required.
- Likes, comments, follows, saves, reshares, and created posts are held in the current page's memory and are **not permanent**.
- Refreshing the page resets in-session interactions and loads a new randomized selection of worlds and posts.
- The screenshot feature generates a PNG locally in the browser.
- No live AI service is used to write posts.

Do not assume that an interaction will still be present after refreshing the page.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

For local testing with service-worker or installable-app behavior, serve the folder through a local HTTP server rather than opening the file directly. Browser support for installation and offline behavior varies.

## Deploy with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Choose **GitHub Actions** as the deployment source if a workflow is configured, or choose the appropriate branch/folder publishing option for the repository.
3. Open the published Pages URL shown in repository settings after deployment completes.

## Project files

- `index.html` — page structure, styles, NPC roster and post content, randomized feed, profile dialogs, composer, and browser-side interactions.
- `README.md` — project documentation.
- `favicon.svg` and `manifest.webmanifest` — referenced by the page for browser identity and app metadata, if present in the repository.
- Service-worker or deployment files may be present depending on the current repository setup.

## Current limitations

- The roster and posts are curated in the source code, not retrieved from a live service.
- Profile details and bios are lightweight front-end views, not full persistent user accounts.
- Interactions are temporary and are lost on refresh.
- Reshares are local feed entries; they are not published to another service or shared with other visitors.
- Screenshot export saves a generated image of the post text and metadata; it does not capture the entire browser window.
- Some browser features, such as native share, clipboard access, file downloads, and installation, depend on browser support and permissions.

## Contributing

When adding NPCs or writing new posts:
- Use distinct, believable fictional names and handles.
- Keep each character's vocabulary, responsibilities, relationships, and humor appropriate to their own world.
- Keep jokes in-world. Characters should not mention being fictional, authors, chapters, viewers, fan theories, filming, or the fact that they are in a story.
- Prefer concise posts with a specific everyday detail, surprising complication, or character-driven punchline.
- Avoid duplicating existing names and usernames.
