# Reef Rush — public website

GitHub Pages site for the App Store listing: https://norfork37.github.io/reefrush/

- Landing page: `/index.html`
- Privacy Policy (App Store Connect → Privacy Policy URL): `/privacy.html`
- Support (App Store Connect → Support URL): `/support.html`

The privacy policy describes the ad-supported 4.x releases (4.1 and 4.2): Google AdMob, consent and App Tracking Transparency choices, the Remove Ads purchase, Game Center and iCloud, and nearby multiplayer.

## app-ads.txt

AdMob only reads `app-ads.txt` from the **root of the domain** in the App Store Marketing URL, so it cannot live in this project site (`/reefrush/`). Publish it from a separate `norfork37.github.io` repository so it appears at `https://norfork37.github.io/app-ads.txt`, and set the Marketing URL to `https://norfork37.github.io/`.

Contact: norfork37@gmail.com
