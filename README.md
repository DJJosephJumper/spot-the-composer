# Spot the Composer 🎼

A free, static browser guessing game featuring 63 classical composers.

## Play locally
Open `index.html` in a modern browser. No build process or server is needed.

## Publish on GitHub Pages
1. Create a **public** GitHub repository (for example, `spot-the-composer`).
2. Upload `index.html`, `.nojekyll`, and `README.md` to the repository's main branch, at its root.
3. In the repository, go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then choose **main** and **/(root)**, and save.
4. Once GitHub finishes deployment, open the Pages address shown in Settings → Pages.

## Game behavior
- Daily challenge is selected by UTC date and is the same for everyone using this version of the game.
- Daily guesses and completion are stored locally in the browser; clearing browser storage resets them.
- Unlimited practice is separate from the daily challenge.
- The Share button creates an emoji grid without revealing the answer, using native sharing when available and clipboard otherwise.
- No analytics, login, or backend is included.

## Notes before wider release
The composer data and stylistic categories are editorial and should be reviewed. If the composer array or its ordering changes in a later release, existing daily answers can change because the daily puzzle is based on the array index. Before frequent updates, move to a stable daily answer schedule based on permanent composer IDs.
