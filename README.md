# Shlake Boom Boom - שלקה בום בום

Original block-puzzle game (Block Blast style): 8x8 board, drag-and-drop pieces, row/column clears, combos, high score, sounds. Hebrew RTL UI.

## Play / Install (PWA)
Open the GitHub Pages site and use "Add to Home Screen" on Android to install it as an app. Works offline after first load (service worker).

## Structure
- `index.html` - the full standalone game (vanilla JS, no build step). This is what GitHub Pages serves and what can be wrapped into an Android APK/AAB later (Capacitor / TWA).
- `manifest.webmanifest`, `sw.js`, `icon-*.png` - PWA install support.
- `react-source/` - the original React + TypeScript source of the same game.
- `hero-art.png` - original key art.

All art is original, generated for this project. No assets from any existing game.
