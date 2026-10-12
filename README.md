# PlayLab

PlayLab is a responsive, browser-based collection of 18 original mini-games and interactive experiences built with vanilla HTML, CSS, and JavaScript.

## Included games
1. The Big Clicker
2. Reaction Test
3. Memory Match
4. Number Merge (2048-style)
5. Snake
6. Brick Breaker
7. Tic-Tac-Toe
8. Rock Paper Scissors
9. Word Guess
10. Sudoku
11. Sky Hopper
12. Space Shooter
13. Physics Playground
14. Color Lab
15. Endless Runner
16. Maze Escape
17. Higher or Lower
18. Mini Universe

## Run locally
1. Extract `playlab.zip`.
2. Open the `playlab` folder in VS Code.
3. Open `index.html` in your browser. For a smoother developer workflow, install the VS Code **Live Server** extension and choose **Open with Live Server**.
4. No package installation or API keys are required.

## Deploy with GitHub Pages
1. Create a GitHub repository named `playlab` (or another name).
2. Upload `index.html`, `style.css`, and `app.js` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. The URL will be shown on the Pages settings screen.

You can also deploy the folder to Netlify or Vercel as a static site.

## Notes
- High scores and theme preference are saved in this browser using `localStorage`; they are not synced across devices.
- Sound is off by default and can be enabled with the music-note button.
- Some games use keyboard controls; touch-friendly controls are included for key games.
- Google Fonts are loaded from an external CDN. If unavailable, system fallback fonts are used.
- This is a static front-end project. Online accounts, shared leaderboards, and multiplayer would require a backend.
