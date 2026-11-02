# Arcade 20 — Game Universe

A mobile-first, offline-capable arcade hub with a premium dark-violet gaming interface inspired by the supplied visual references. Includes a featured hero panel, recent games, discover shelves, category filters, favourites, player profile area, settings, local score storage and a bottom mobile navigation bar.

## Run on the web
Open `index.html` in a browser for a basic preview. For full PWA/service-worker behavior, serve the folder over localhost or HTTPS.

## Android packaging
1. Install Node.js and Android Studio with Android SDK.
2. In this folder run `npm install`.
3. Run `npx cap add android` (first time only).
4. Run `npx cap sync android`.
5. Run `npx cap open android`, then build an APK from Android Studio.

## Notes
- Progress and favourites are stored locally in the browser.
- The app shell is offline-capable after first load when served over HTTPS/localhost.
- The current game engine is a lightweight prototype; several titles share generic mechanics and need dedicated implementations before production release.
- The visual game-cover art currently uses CSS gradients and emoji placeholders, not licensed game artwork.
