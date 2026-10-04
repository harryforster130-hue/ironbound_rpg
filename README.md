# Ironbound Fitness RPG

A no-build static web app/PWA. It tracks workouts, XP, levels, quests, weekly sessions, and lift records.

## Deploy with GitHub Pages
1. Sign in to GitHub and create a new public repository named `ironbound-rpg`.
2. Upload `index.html`, `manifest.json`, and `sw.js` to the repository's top level.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for GitHub to publish the site. Open the URL it provides in Safari on your iPhone.
6. In Safari, tap **Share → Add to Home Screen**. Open Ironbound from the new Home Screen icon.

## Data
Workout data is stored locally in the browser on the device. It does not sync automatically between devices. Use Settings → Export backup periodically. Keep a copy of the backup somewhere safe.

## Notes
- Use HTTPS hosting for the installable/offline app behavior.
- If you update the files later, the service worker may briefly serve a cached version. Closing and reopening the app, or clearing the website data, can refresh it.
