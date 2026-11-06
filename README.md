# Local Intel

A live intel page for EVE Online: a gate map of the systems around you with kills, traffic, ratting, sov timers and wormholes, your intel channel and location read from EVE's chat logs, watched systems, alerts, and your characters' notifications.

**Open it:** https://quietstatic01.github.io/Eve-Intel/ (the exact address is shown in the repository's Settings → Pages)

Everything runs in your browser from the single `index.html` file. Press **About** on the page for instructions, the version number and the version history.

## EVE login (for character notifications)

1. Create an application at https://developers.eveonline.com with the permission `esi-characters.read_notifications.v1`.
2. Set its callback URL to the page's address, for example `https://quietstatic01.github.io/Eve-Intel/`. Copy it from **EVE login** in Alerts and settings so it matches exactly, including capital letters.
3. Paste the app's Client ID into the page and press **Log in with EVE**.

## Data

CCP's EVE Swagger Interface and EVE login, zKillboard, and EVE-Scout.
