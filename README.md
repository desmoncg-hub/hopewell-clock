# Hopewell High School Daily Clock

A web version of the daily date-and-time slide. The page shows the current time (12-hour, AM/PM), the long date, and the short date, and updates itself from the Chromebox clock. Nothing needs to be typed or changed day to day.

Live page: https://desmoncg-hub.github.io/hopewell-clock/

## Publish on GitHub Pages (one time)

1. On GitHub, create a new **public** repository named `hopewell-clock`.
2. Choose **Add file > Upload files**, drag in `index.html`, `README.md`, and the whole `assets` folder, then click **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment," set Source to **Deploy from a branch**, Branch to **main**, folder to **/ (root)**, then click **Save**.
4. Wait a minute or two, then open https://desmoncg-hub.github.io/hopewell-clock/

## Set up the Chromebox (one time)

1. Open Chrome **Settings > On startup > Open a specific page or set of pages**, and add the page address.
2. Open the page and press the **full-screen key** (top row, the rectangle with arrows) to hide the browser bars.
3. If the startup setting is locked by the district, bookmark the page on the bookmarks bar instead and click it each morning.

## Notes

- The page keeps the screen awake while it is open.
- The bubble animations start hidden, like the slide. Each click or tap on the board steps through the same click order the slide used. The click after the last one clears them.
- The mouse pointer hides after 3 seconds without movement.
- Chromeboxes don't have the Impact font, so the title uses Anton (bundled in `assets`, SIL Open Font License), which looks almost identical. On a computer that has Impact, the page uses Impact.

## Files

- `index.html` - the page
- `assets/mascot.png` - Titan mascot from the original slide
- `assets/sparkle.gif` - bubble animation from the original slide
- `assets/anton.woff2` - title font
