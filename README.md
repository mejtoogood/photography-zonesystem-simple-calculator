# Zone Meter

Single-page, installable, offline-capable zone-system exposure calculator.

## Use

Select a metered shutter speed, adjust aperture and ISO, and tap the zone where that metered tone should be placed. Swipe vertically on the EV or Exposure tape to move the metered placement between zones. Zone V remains outlined. The Exposure tape shows shutter speed and aperture separated by a hyphen. Settings are saved locally.

## GitHub Pages

In **Settings → Pages → Build and deployment**, select **GitHub Actions** as the source. The workflow `.github/workflows/pages.yml` then publishes the site on changes to `main`.

Expected site URL: https://mejtoogood.github.io/photography-zonesystem-simple-calculator/

For local testing: `python3 -m http.server 8000`. On iOS, open the deployed HTTPS site in Safari and use Share → Add to Home Screen.
