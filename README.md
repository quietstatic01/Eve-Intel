# Local Intel

A live intel page for EVE Online: a gate map of the systems around you with kills, traffic, ratting, sov timers and wormholes, your intel channel and location read from EVE's chat logs, watched systems, alerts, and your characters' notifications.

**Open it:** https://quietstatic01.github.io/eve-intel/

Everything runs in your browser from the single `index.html` file. Press **About** on the page for instructions, the version number and the version history.

## EVE login (for character notifications)

1. Create an application at https://developers.eveonline.com with the permission `esi-characters.read_notifications.v1`.
2. Set its callback URL to `https://quietstatic01.github.io/eve-intel/` (the page shows this address under **EVE login** in Alerts and settings).
3. Paste the app's Client ID into the page and press **Log in with EVE**.

## Data

CCP's EVE Swagger Interface and EVE login, zKillboard, and EVE-Scout.
