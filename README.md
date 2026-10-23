# CineWave — Static Streaming Website

A responsive Netflix-inspired **front-end-only** streaming demo built with HTML, CSS and vanilla JavaScript. No framework, backend, login, database, API key, or build step required.

## Features
- Cinematic hero section and dark streaming-service style
- Responsive title cards with poster artwork
- Search/filter across the sample catalog
- Custom modal player using native HTML5 video controls
- Keyboard support: Enter/Space opens a selected card; Escape closes the player
- Hosted sample video URLs and replaceable poster URLs
- Works on GitHub Pages as a static site

## Run locally
Open `index.html` in a modern browser. For best results, use VS Code Live Server or any simple static server.

## Publish on GitHub Pages
1. Create a public GitHub repository named `cinewave-streaming-demo`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the URL shown in that section.

## Change the videos
Edit the `videos` array in `script.js`. Each item has:
- `title`, `type`, `year`, `score`, `tag`, `group`
- `poster`: a direct image URL
- `src`: a direct video file URL (MP4 or another browser-supported format)
- `desc`: card/player description

The sample video URLs are public demonstration clips (such as MDN's flower sample and W3Schools' Big Buck Bunny sample), not full movies. Some sample URLs may be blocked, moved, or unavailable depending on the host/browser. Use **Open source** in the player to test the original URL.

## Copyright note
This demo does **not** include pirated full movies or unauthorized streaming links. Poster artwork is loaded from Unsplash; video samples are public test clips. Before publishing a public site, check the current license and hotlinking terms for each asset, and only embed videos you own or are authorized to use. You can link to official trailers or public-domain films hosted by legitimate sources, but don't re-host copyrighted films without permission.

## Tech stack
HTML5 · CSS3 · Vanilla JavaScript · HTML5 `<video>`
