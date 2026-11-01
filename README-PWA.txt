MY STUDY PLANNER V5 — PWA
========================
This is a complete installable PWA package.

IMPORTANT: A PWA cannot be installed by opening index.html directly from Downloads.
It must be served from HTTPS (or localhost for development).

Easiest deployment:
1. Upload every file in this folder to a new GitHub repository.
2. In repository Settings > Pages, deploy the main branch / root folder.
3. Open the generated https://...github.io/... URL in Chrome on Android.
4. Wait for the page to load once, then use Chrome menu > Install app (or Add to Home screen).
5. Open the installed app once while online; service worker caches the app for offline use.

All app code is local; there are no external JS/CSS dependencies.
Progress is saved in this browser's local storage. Use Backup > Export JSON regularly.
The in-app reminder checks while the app is open; it is not a guaranteed background alarm.
