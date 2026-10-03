# Min-Max Tracker — v2

A free, installable Progressive Web App (PWA) for the 12-week Min-Max program.

## v2 additions
- Pause / Resume workout
- Reset unfinished workout without saving it
- Workout timer freezes while paused
- Rest timer presets: 1, 2, 3, 4, and 5 minutes
- +30 seconds button to extend an active rest timer
- Program Guide / Info page
- RIR definitions
- Intensity-technique definitions
- Program abbreviations
- Progression and rest guidance

## Files
- `index.html` — app entry point
- `style.css` — responsive iPhone/desktop styling
- `app.js` — program data and app logic
- `manifest.webmanifest` — installable-app metadata
- `sw.js` — offline caching
- `icon-*.png` — app icons

## GitHub Pages
1. Create a public GitHub repository, e.g. `min-max-tracker`.
2. Upload every file in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`.
6. Save and wait for GitHub Pages to publish.

## iPhone
Open the GitHub Pages URL in Safari → Share → Add to Home Screen → enable Open as Web App → Add.

## Desktop
Open the same URL in Edge or Chrome and use the browser's **Install this site as an app** option.

## Data
Workout history is stored locally in the browser/device. Use **Backup Data** periodically. Use **Restore Data** to recover a backup JSON file.


## v3 updates
- Added a prominent INFO / LOOKUP button inside active workouts.
- Added searchable quick-reference lookup for acronyms, RIR, ROM, progression, rest and Block 2 intensity techniques.
- Added the instructional YouTube demo link from the source PDF to every programmed exercise.
- Updated service-worker cache version so the new app assets can replace the prior cached version.
