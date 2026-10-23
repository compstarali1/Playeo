# Ally Player

A dark, frosted-glass photo and video viewer. Files stay on your device and are only read when you open them.

## Features
- Open a folder (desktop) or add files (phone and desktop)
- All / Images / Videos tabs with counts
- Video thumbnails in the grid and as the poster when a video is selected
- Play/pause, ⏮ / ⏭ previous and next, −10 / +10 skip, seek bar, 1× speed cycle
- Next video plays automatically when one finishes
- In fullscreen, controls fade out while playing and return on movement or tap
- Rotate (⟲ ⟳ and Rotate), Fit 16:9 / Stretch, fullscreen
- Keyboard: Space play · ← → navigate · M mute · E expand · F fullscreen · R rotate · S stretch

## Publish on GitHub Pages
1. Create a new repo (e.g. `Playo` or `ally-player`) and upload every file in this folder, keeping the folder structure.
2. Go to **Settings → Pages**, set Source to **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
3. Your app will be live at `https://<your-username>.github.io/<repo-name>/`.

## Build the Android APK
1. Open **https://www.pwabuilder.com**, paste your GitHub Pages URL, and click **Start**.
2. Check that the Manifest and Service Worker sections pass.
3. Click **Package for stores → Android**, keep the defaults, and set the package ID (for example `com.ally.player`).
4. Download the ZIP. It contains an `.apk` you can install directly and an `.aab` for Google Play.

## Notes
- "Open folder" works on desktop browsers. On Android, use "Add files".
- Replace `icons/icon-192.png` and `icons/icon-512.png` with your own artwork at the same sizes to change the app icon.
