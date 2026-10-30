R.A.G.E AIRSOFT OFFLINE PWA
===========================

FILES
- index.html: game with phone-sized responsive layout and fullscreen control
- manifest.json: installable app metadata
- service-worker.js: offline caching
- icons/: your R.A.G.E. logo used for browser favicon, iPhone home-screen icon,
  and Android/PWA installation icon

DEPLOY TO VERCEL
1. Extract this ZIP.
2. Upload the contents of the rage_airsoft_offline folder to your GitHub repository.
   Keep index.html, manifest.json and service-worker.js at the repository root.
3. Import the repository into Vercel and deploy.
4. Open the HTTPS site once while online and wait for it to finish loading.
5. On Android Chrome, use Install app / Add to Home screen.
   On iPhone Safari, tap Share > Add to Home Screen.
6. Open the installed app. The R.A.G.E. logo is used as its app icon.

OFFLINE
The app shell and logo assets are cached after the first successful online visit.
Open the installed app once online before testing airplane mode.

FULLSCREEN
The fullscreen control requests fullscreen where the browser supports it.
Some mobile browsers restrict fullscreen from ordinary web pages. Installing
the PWA to the home screen gives the best app-like display and removes the
normal browser address bar where supported.

PHONE DISPLAY
The game uses the available phone viewport width and height and accounts for
safe areas around notches and home indicators.
