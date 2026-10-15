# bay-area-shine-app-updates

Web bundles for the Bay Area Shine test apps (live updates). Public by design: it holds only built web apps with made-up demo data, never keys or real customer data.

- `customer/manifest.json`, `crew/manifest.json` — what the apps read on launch
- `<app>/bundles/<version>.zip` — the bundles (newest 5 kept)

Published by the app team with `npm run live:publish`; nothing here is for people.
