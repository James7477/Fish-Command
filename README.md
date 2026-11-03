# Fish Command — Angler Edition 🎣

**V1 Beta — web application**

A separate fishing companion app built using the user experience ideas from Buck Command — Guardian Edition. Buck Command is a different repository and is unchanged.

## What works in this beta
- First-run registration screen, welcome/splash screen, and freshwater / inshore / offshore fishing choice
- Interactive mapping and searching, with available NOAA nautical layers
- Fishing Almanac, current weather, NOAA tides for supported coastal stations
- Alabama waterway and species information; fish habitats and bait tips
- Fishing spot pins, catch journal, and trip planning
- Directions link for road-access points; feedback and future features

## Important beta limitations
- **Registration is local to the device/browser.** No registration is sent to an owner's dashboard or shared database yet. A securely authenticated backend, privacy notice, and appropriate data retention controls must be built before collecting names, emails, or phone numbers centrally.
- Feedback is **not yet submitted** to an owner database; the interface provides local/copy functionality until a secure endpoint is connected.
- Maps, tide predictions, and weather require an internet connection; coverage and accuracy vary. Nautical overlays are for planning only and are **not a certified navigation system**.
- Solunar fishing activity periods are traditional estimates, not guaranteed catch predictions.
- Mobile GPS needs HTTPS, browser permission, and location services; GPS may be unavailable or inaccurate.
- Do not rely on this beta as an emergency response, marine navigation, or life-safety system.

## Publish with GitHub Pages
1. On the GitHub repository, open **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose **main** and **/(root)**, then click **Save**.
4. When GitHub Pages reports the site as published, the address should be `https://james7477.github.io/Fish-Command/`.
5. If a phone shows an older version, reload or open `https://james7477.github.io/Fish-Command/index.html?v=1`.

## Next development
1. Secure owner-accessible registration/feedback storage, consent and account recovery.
2. Stronger location selection, favorites and saved spots across devices.
3. More state-specific fish guides, regulations, public access and boat ramps.
4. Additional NOAA/USGS data integrations; licensing review for commercial map datasets.
5. Tested offline options and improved marine/angler safety features.

© Fish Command beta project. Map and data providers retain their own rights and license terms.
