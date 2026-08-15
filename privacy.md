---
permalink: /privacy/
---

# Global Sitrep – Privacy Policy

_Last updated: 13 August 2026_

**Global Sitrep collects nothing about you, and there is no server behind it.**

That second half is unusual enough to be worth explaining properly, because it has one consequence
you should know about before you decide to trust the app.

## There is no backend

Most apps like this route their data through the developer's own servers. Global Sitrep does not
have any servers. Your phone talks **directly** to each public data provider.

That is good for you in the obvious way: there is no account, nothing to breach, and no company in
the middle building a profile of what you look at. Nobody, including the developer, can see which
countries you check or which panels you open, because that information never leaves your device.

**The consequence, stated plainly:** when your phone requests data from a provider, that provider
sees a request coming from your IP address, the same as if you had opened their website in Safari.
Each provider's own privacy policy governs what they do with that. The app cannot hide this, and an
app that did hide it would be one with a server in the middle, logging your requests instead.

The providers your device may contact are the U.S. Geological Survey, GDACS, NASA EONET, NASA
FIRMS, The GDELT Project (including its bulk exports, which are hosted on Google Cloud Storage),
the World Health Organization, abuse.ch, GitHub and the jsDelivr CDN (for the UCDP data mirror),
the Humanitarian Data Exchange, UNHCR, the U.S. State Department, Open-Meteo, Yahoo Finance, IMF
PortWatch, Polymarket, pizzint.watch, the World Bank, ReliefWeb, Windy.com, ACLED, the OpenSky
Network and Wikimedia Commons. Apple Maps draws the map itself and is covered by Apple's privacy
policy.

## What is stored, and where

Everything the app remembers stays on your device:

- A cache of the events it has already downloaded, so it opens instantly and does not re-fetch on
  every launch
- Your dashboard layout: which panels you have, their order and their sizes
- Your filters, time window, enabled map layers, map style and chosen region
- Which news categories and live channels you have enabled, and any channels you have added
- Whether the live news panel is collapsed or muted
- Your active mission workspace, if you use one
- Your unit preference, your live-flights settings, and whether the map legend is expanded
- A cache of aircraft type photographs and of World Bank country indicators, so the same thing is
  not looked up twice
- A count of how many times you have tipped, so the app can say thank you

None of it is transmitted anywhere. There is no account and no sign-in. Deleting the app deletes
all of it.

## Optional API keys

Five sources ask you to register with them directly: NASA FIRMS, ACLED, ReliefWeb, Windy.com and
the OpenSky Network. The app works without any of them.

If you add one, the key is stored in the **iOS Keychain** on your device. It is sent only to the
provider it belongs to, as part of a normal request to them, and nowhere else. It is never sent to
the developer, because there is nowhere to send it.

## Location

Location is **optional** and off unless you grant it. If you do, it is used for one thing: drawing
your position on the map so you can see what is near you. It is never transmitted, never stored,
and never attached to any request. Decline it and every other feature works identically.

## Live flights

The flights layer is **off** unless you turn it on. When it is on, the app asks the OpenSky
Network what is flying over the area of the map you are currently looking at, which means the
coordinates of that area are sent to them as part of the request.

That is not your location, and the app never sends your location to anyone. But a map you have
centred on yourself does imply roughly where you are, so it is worth saying plainly rather than
leaving you to infer it. The app states this on the screen where you enable the layer, too. Turn
the layer off and nothing about the map is transmitted.

Aircraft types come from a fixed snapshot of OpenSky's aircraft database that ships inside the
app, so looking one up sends nothing. Aircraft photographs are fetched from Wikimedia Commons by
aircraft type — never by which aircraft you tapped.

## Live television

The live news channels play video from third parties, either YouTube or a broadcaster's own stream.
Watching a channel means your device contacts **them**, and YouTube in particular has its own
privacy policy and may set cookies in the embedded player. Nothing plays until you choose a
channel: there is no autoplay, and the sound starts muted, deliberately.

## What Global Sitrep does not do

- No analytics or crash-reporting SDKs
- No advertising, and no advertising identifiers
- No tracking across apps or websites
- No accounts, no sign-in, no email address collected
- Nothing sold or shared, because nothing is collected

## Tips

The tip jar uses Apple's standard in-app purchase system. Tips are optional, unlock nothing, and
are handled entirely by Apple. Global Sitrep never sees your payment details.

## Children

Global Sitrep collects no data from anyone, including children under 13. Note that the app reports
on armed conflict and disasters, including casualty figures, and is rated accordingly.

## Not for operational use

This is worth repeating here as well as in the app. Global Sitrep aggregates public data for
general awareness. Do not rely on it for emergency response, travel safety, or any decision where
being wrong matters. Some sources are automated and produce false positives; some lag by days or
weeks.

## Changes

Any change to this policy will appear on this page with a new date above.

## Contact

drdjcannon@gmail.com

---

[Back to Global Sitrep](../) · [Support](../support/)
