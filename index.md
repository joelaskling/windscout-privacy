---
title: Windscout Privacy Policy
---

# Windscout — Privacy Policy

**Last updated:** August 12, 2026

Windscout is a wind and weather app, built by Joel Askling. This policy
covers both the iOS and Android apps (`com.joelaskling.windscout`).

## The short version

Windscout has no accounts, no ads, no analytics, and no crash-reporting SDKs, and it
doesn't sell or share your data. It uses your device's location to fetch a wind forecast
and show your position on the on-screen map, and it caches that forecast on your device
so the app still works with no signal. Two outside services are involved in making that
work — Open-Meteo (weather data) and Mapbox (the map) — described below.

## Location

Windscout asks for location access "while using the app" only. It never requests
background/"Always" access, and it never reads your location when the app isn't open.

Your location is used to:

- Request the wind forecast for where you are (sent to Open-Meteo, see below)
- Show your position on the on-screen map, while the app is open and in the foreground
- Work out compass heading, using your device's built-in sensors — this never leaves the device

If you deny or later revoke location access, Windscout will prompt you to grant it again
(with a link to your device's Settings) rather than silently failing. The forecast and
map won't work without it.

## What gets sent off your device, and to whom

**Open-Meteo** (open-meteo.com), for the weather forecast:

- Your coordinates, rounded to roughly 11 meters of precision, are sent with each
  forecast request. There's no account and no API key involved, and nothing ties
  separate requests back to you individually.
- Open-Meteo's infrastructure logs IP addresses for up to 90 days for abuse prevention
  and usage monitoring, then deletes them — standard handling for anyone calling their
  API, not something Windscout adds on top. See
  [Open-Meteo's terms](https://open-meteo.com/en/terms).

**Mapbox** (mapbox.com), for the on-screen map:

- Mapbox's SDK sends its own anonymized telemetry by default: general location,
  altitude and accuracy, a session ID that rotates every 24 hours, and your IP address,
  which Mapbox uses to improve its maps. Mapbox anonymizes this on-device before it
  reaches their servers and doesn't attach it to an advertising or personal identifier.
  See [Mapbox's privacy policy](https://www.mapbox.com/legal/privacy) and their
  [data privacy FAQ](https://www.mapbox.com/legal/legal-faq).

Neither service is used for advertising, and Windscout doesn't send either of them
anything beyond what's needed to answer "what's the forecast/map here."

## What stays on your device

The forecast, once fetched, and your settings (units, clock format) are cached locally
so the app works offline. This local cache is never uploaded anywhere. Uninstalling the
app deletes it — there's no account or server-side copy to also delete, because none
exists.

## What Windscout doesn't do

No accounts or sign-in. No analytics or crash-reporting SDKs. No advertising or
advertising identifiers. No user-generated content. No sale or sharing of your data
beyond the two services above, which exist to provide the forecast and map themselves.

## Children

Windscout isn't directed at children and doesn't knowingly collect data from anyone
under 13 (or the relevant minimum age where you live).

## Changes to this policy

If this policy changes, the "Last updated" date at the top will change with it.

## Contact

Questions about this policy: joel.gaskling@gmail.com
