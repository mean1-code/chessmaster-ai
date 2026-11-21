# Chessmaster AI

A free chess game that runs in your browser. Stage 1 includes Play vs AI (Starter to Master), Two Player on one device, a timer, undo, move history and sound.

## Put it on GitHub (step by step)
1. Sign in at github.com (create a free account if needed).
2. Click the **+** at the top right, then **New repository**.
3. Name it `chessmaster-ai`, leave it **Public**, tick **Add a README file**, then click **Create repository**.
4. Click **Add file**, then **Upload files**. Drag in `index.html` and `logo.svg` from this folder, then click **Commit changes**.
5. Open **Settings**, then **Pages** in the left menu.
6. Under **Build and deployment**, set Source to **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then click **Save**.
7. Wait a minute or two and refresh. Your game link appears at the top of that page: `https://YOUR-USERNAME.github.io/chessmaster-ai/`.

## Testing on your laptop first
Double-click `index.html` to open it in your browser. You need an internet connection, because the chess rules library and Stockfish load from a CDN.

## Notes
- The AI uses Stockfish when it loads. If it cannot load, a simpler built-in engine plays instead, so the game always works.
- Coach mode, points, unlockable chess sets and logo polish come in stages 2 and 3.
