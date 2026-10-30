MyCycle - installable web app (Chrome)
=======================================
Files: index.html, manifest.json, sw.js, icons/ (keep them together in one folder).

1. Put the folder on the web (free static hosting works, for example Netlify Drop or GitHub Pages).
   Upload the CONTENTS of this folder so index.html sits at the top of your site.
   The address must start with https:// (Bluetooth only works on secure pages).
2. On your Samsung phone or tablet open that address in Chrome.
3. Chrome menu (three dots) > "Install app" (or "Add to Home screen"). MyCycle then opens in its own window
   with your icon, no browser bars. It also works offline after the first visit.
4. Open the app, tap the Bluetooth button and pair your bike and heart rate strap.

Updating: upload the new files over the old ones, then open the app while online. The "Build" number under
the title tells you which version you are running.

Your data (layouts, workouts, zones, FTP) is stored on the device only.

Not possible in a Chrome web app: floating over another app with a see-through background, and lowering other
audio while a cue plays. Those need a native Android app.
