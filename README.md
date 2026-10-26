# Ultimate Draft 27

An original offline-first football card game prototype. Player names, clubs and ratings are fictional; no official football league or club assets are included.

## Features
- Open packs using in-game coins and add cards to your collection
- Build a squad in a 4-3-3 formation by choosing owned cards
- Create a draft from random choices and claim drafted players
- Offline transfer market: buy listed players and sell cards from your collection
- Saves coins, collection and squad locally on the device
- Android APK built automatically by GitHub Actions

## Build on Android phone only
1. Download this ZIP and extract it using your phone's Files app.
2. Upload the extracted project files to a GitHub repository (keep the `.github/workflows/build-apk.yml` path).
3. Open the repository on GitHub, select **Actions**, and enable workflows if asked.
4. Open **Build Ultimate Draft 27 APK** and tap **Run workflow**. Alternatively, pushing the files to `main` starts a build automatically.
5. When the run finishes with a green tick, open that run, scroll to **Artifacts**, and download `Ultimate-Draft-27-debug-apk`.
6. Extract the downloaded artifact ZIP to get `app-debug.apk`. Tap the APK to install. Android may ask you to allow installs from your browser or Files app.

## If using an existing repository
Upload/replace the files from this project in the repository root. Do not upload the outer folder as an extra nested folder: `package.json`, `capacitor.config.json`, `www/`, and `.github/` should be at the repository root.

This is a playable prototype, not a finished commercial release. The APK from Actions is a debug build; a signed release build and privacy/store compliance are separate steps.
