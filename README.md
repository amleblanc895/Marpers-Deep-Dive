# Marper's Deep Dive

Marper falls through five shafts with jet sneakers, stomping and blasting enemies to collect the five torn pages of a treasure map, then climbs back up in Climb Mode. Everything (code, art, music, fonts) is inside `index.html`.

## Put it online with GitHub Pages

1. Sign in at github.com and create a new **Public** repository (for example `marpers-deep-dive`).
2. **Add file → Upload files**, drop in every file from this folder, then **Commit changes**.
3. **Settings → Pages**: Source **Deploy from a branch**, branch **main**, folder **/ (root)**, **Save**.
4. After a minute or two the game is at `https://YOUR-USERNAME.github.io/marpers-deep-dive/`.

## Install it on a phone

- **iPhone (Safari):** open the link, tap **Share → Add to Home Screen**.
- **Android (Chrome):** open the link, tap **⋮ → Add to Home screen** (or **Install app**).

It opens full-screen from its own icon and keeps working offline after the first visit.

## Updating

Upload the new `index.html` over the old one (same name). The update appears the next time the game is opened with an internet connection.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole game |
| `manifest.json` | Name, icon and colors used when installed to a home screen |
| `sw.js` | Offline support |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `favicon-32.png` | App icons |
| `FONTS-LICENSE.txt` | License for the two fonts built into the game (SIL Open Font License) |
