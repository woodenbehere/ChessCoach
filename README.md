# Chess Game Coach

An installable web app (PWA) with a move-by-move coaching review of **Spryze713 vs jdparden** (Chess.com, 22 Nov 2026, 0-1). Each move is rated, explained from both White's and Black's side, and comes with better-move lines you can play out on the board.

## Files
- `index.html`: the app (board, move logic, commentary)
- `manifest.json`: app name, colors, icons for install
- `sw.js`: service worker for offline use
- `icons/`: home-screen icons

## Hosting on GitHub Pages
1. Create a repo (for example `ChessCoach`) and upload every file, keeping the `icons` folder.
2. Settings → Pages → deploy from the `main` branch, root folder.
3. Open `https://<username>.github.io/ChessCoach/` on your phone, then use **Install app** (Android/Chrome/Brave) or Share → **Add to Home Screen** (iPhone).

## Updating
After changing any file, bump `CACHE_VERSION` in `sw.js` (e.g. `chess-coach-v2`) so installed copies pick up the change.

Parden Web Apps · jdparden@gmail.com
