# Downers Grove picture puzzle

## Play
Open index.html in Chrome, Edge, Firefox, or Safari. Everything, including the image, is embedded in this one file; internet access is not required for local play.

- 5 columns × 5 rows, with 4 px gaps and 4 px outer padding.
- Drag any piece onto another to swap them, or click/tap two pieces.
- Keyboard: Tab to a piece, arrows to move focus, Enter/Space to select, Escape to cancel.
- Shuffle starts a fresh game; Show picture reveals the reference.
- Includes a move counter and a timer that starts with the first swap.
- On completion, the gaps disappear to reveal the whole image.

The image is an AI-generated scene inspired by Downers Grove, not a photograph of a specific street.

## Publish on GitHub Pages
1. Sign in at github.com and create a public repository called downers-grove-puzzle.
2. Upload index.html into the top level of the repository, not a subfolder. Commit the upload to main. The image is embedded, so no extra image files or installation are needed.
3. Open the repository's Settings → Pages.
4. Under Build and deployment → Source, choose Deploy from a branch.
5. Select main and /(root), then Save.
6. Wait for deployment. The Pages screen will show the live URL, typically https://YOUR-USERNAME.github.io/downers-grove-puzzle/.
7. To update it later, upload a replacement index.html and commit again.

If you get a 404, check that index.html is lowercase and at the repository root, verify the branch setting, and look in the Actions tab for deployment errors.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

The game has not been published to GitHub. Game logic was checked separately; browser appearance and touch interaction have not been verified in this environment.
