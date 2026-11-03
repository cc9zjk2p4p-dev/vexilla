# Vexilla

A flag quiz in a single HTML file. No build step, no dependencies.

- **Classic**: name the country from its flag (Easy, Medium, Hard, Expert).
- **Flashcards**: endless, hands-free flags with a 10 second countdown, then the country (with its Korean name), capital city, continent, languages, currency and landmarks.

## Put it on GitHub Pages

1. Unzip this file on your computer.
2. Create a new repository on GitHub.
3. Upload `index.html`, `.nojekyll` and `README.md` to the top level of the repository (not the `vexilla` folder itself).
4. Open **Settings > Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
5. After a minute your app is live at `https://<your-username>.github.io/<repository-name>/`.

## Notes

- Flags are emoji, so they look best on iPhone, iPad, Android and Mac.
- Flashcards keeps the screen awake (Screen Wake Lock on iOS 16.4 and later, plus a tiny hidden video as a backup).
