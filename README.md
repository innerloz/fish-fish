# Fish, fish!

A gentle fishing game made for little ocean explorers. Six friendly fish, a framed collection inspired by the fish pictures in the reference photo, sound effects, and a treasure every five catches. Play with touch, a mouse, or Space/Enter. Fish wait for you and reel themselves in after a little while. Progress is saved in the browser.

## Play locally

Run `python3 -m http.server 4173 --directory dist` from this folder, then open http://localhost:4173. You can also open `dist/index.html` directly. No installation or build step is required.

## Files

- `dist/index.html` — page and accessible controls
- `dist/style.css` — responsive layout
- `dist/art.js` — original canvas illustrations
- `dist/game.js` — gameplay, sound, and local progress
- `.openai/hosting.json` — Sites publication configuration
