---
permalink: /support/
---

# Global Sitrep – Support

Global Sitrep is a live global risk dashboard: earthquakes, disasters, armed conflict, disease
outbreaks, displacement, climate anomalies, markets, shipping chokepoints and news, on one screen.
It has no account and no server of its own.

## Getting started

- The app opens on the **map**. Pins are live events; the country shading is a risk score, not an
  event count. Tap a pin or a country for detail.
- The **dashboard** is yours to arrange. Add, remove, reorder and resize panels from the arrange
  page. Your layout is saved.
- The **time window** at the top changes what "live" means. Note that standing conflict zones and
  the historical conflict record deliberately ignore it, because a four-year war produces no events
  in a 24-hour window.
- **Alerts** collects what the app thinks is worth your attention right now.

## Common questions

**Do I need an account, or to pay for anything?**
No. There is no account, no sign-in, and no paywall. Every panel, layer and source is included.
There is an optional tip jar that unlocks nothing.

**Do I need an API key?**
No. Most sources need nothing at all. Four of them (NASA FIRMS, ACLED, ReliefWeb, Windy.com) ask
you to register with them directly, and Settings has a page explaining each with a signup link. The
app works fine without them; those specific layers just stay empty and say so.

**Why does a source say "Needs a key" or "Failed"?**
Settings lists every source with its state, and the reason if it failed. A source that returns
nothing will tell you it returned nothing, rather than looking the same as one that is broken. If
something reads "Failed", it is usually the provider being temporarily unavailable.

**Why is a conflict event in an odd place, or obviously not conflict?**
Some of the conflict wire comes from GDELT, which codes events automatically from news text. That
is fast but it makes mistakes, particularly with figures of speech. The app restricts these to
twenty active conflict countries for exactly this reason. Verified historical conflict records come
from UCDP instead, and death tolls from the Humanitarian Data Exchange.

**Why do the numbers differ between two panels?**
Usually because they are counting different things on purpose: a live window versus a standing
record, or an exact severity band versus everything above it. Tap a panel for its detail view,
which states what it is measuring.

**Some data looks out of date.**
Some of it is, legitimately. Shipping transit volumes land about two weeks in arrears, conflict
records lag by around a month, and displacement figures are annual. The app shows the date the
data is actually for rather than the time it fetched it.

**Does it work offline?**
It opens and shows you the last data it had, which is cached on your device. New data needs a
connection.

**Live TV does not start playing.**
By design. Nothing autoplays and the sound starts muted, because a dashboard that begins blaring
cable news when you open it is hostile and expensive on cellular. Pick a channel and unmute it.

**How do I use less cellular data?**
Fetches are throttled by how often each source actually publishes, so the app does not poll
needlessly. The heaviest thing by far is live TV, so leave it closed on cellular.

## Not for operational use

Global Sitrep aggregates public data for general awareness. Do not rely on it for emergency
response, travel safety, or any decision where being wrong matters.

## Reporting a problem

Email **drdjcannon@gmail.com**. Useful things to include: what you were looking at, which source or
panel, what you expected, and a screenshot. If it is a wrong figure, the source name and the number
you saw are the two most helpful details.

---

[Back to Global Sitrep](../) · [Privacy policy](../privacy/)
