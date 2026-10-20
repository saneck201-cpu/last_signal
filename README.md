# LAST SIGNAL — Последний сигнал

A small Russian-language 8-bit mystery adventure made with vanilla HTML, CSS and JavaScript. No build step, no libraries required.

## Run locally
Open `index.html` in a modern browser. Click **НАЧАТЬ ИСТОРИЮ**. Audio starts only after you enable it, because browsers require user interaction.

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site.

## Controls
- Move: WASD or arrow keys
- Interact: E or Space
- On touch screens: use the directional buttons
- Click nearby objects to inspect them

Progress is saved in the current browser's localStorage. The atmospheric soundtrack and sound effects are synthesized using Web Audio API; no external audio files are needed.
