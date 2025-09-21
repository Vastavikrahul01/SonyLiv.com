# YouTube-style HLS Player (GitHub Pages)

Files:
- index.html  -> main player page
- styles.css  -> styling
- config.js   -> edit DEFAULT_M3U8 and JOIN_LINKS
- README.md   -> this file

## How to use
1. Create a new GitHub repository.
2. Upload these files to the repository root.
3. In `config.js` set `window.DEFAULT_M3U8` to your stream (optional) and update `JOIN_LINKS`.
4. Deploy via GitHub Pages: Settings → Pages → Source: `main` (or `master`) branch → `/ (root)`.
5. Open the provided GitHub Pages URL.

## Features
- Default 16:9 locked aspect (YouTube-like).
- Aspect selector: 16:9, 4:3, 21:9, Stretch.
- Cinema mode (wider look) and Fullscreen.
- 4 JOIN NOW buttons (2x2 grid). Button text size = 10px as requested.
- Clicking a JOIN button that points to a `.m3u8` will load that stream into the player.

## Edit stream/promo
Edit `config.js` values and push to repo to change defaults.
