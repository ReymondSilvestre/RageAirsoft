R.A.G.E Airsoft Mission Simulation — Offline PWA

DEPLOY TO VERCEL
1. Extract this ZIP.
2. Upload the contents of this folder to a GitHub repository (index.html must be at the repository root).
3. Import that repository into Vercel and deploy.
4. Open the HTTPS Vercel URL while online.
5. Wait a few seconds for the service worker to install and cache the app.
6. On supported browsers, use Install App / Add to Home Screen.

OFFLINE USE
- Open the deployed app once while connected to the internet.
- After it has cached successfully, disconnect from the internet and reopen it.
- The self-contained game interface and its built-in JavaScript should load offline.

NOTES
- This is offline support for the game shell. The app does not currently sync game results to Firebase or another cloud database.
- Any music selected by the user is a local file selection and must be selected again if the browser session/device does not retain it.
- Browser support for installing PWAs varies. Service workers require HTTPS (Vercel provides HTTPS).
- When updating the website, deploy the new files and reload the app while online to receive the update.
