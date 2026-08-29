# Guadalajara → Coimbatore — Diwali 2026

A single-file travel companion for the Guadalajara-to-Coimbatore trip around Diwali 2026 — countdown, weather delta, logistics, gift list, and a category-tabbed packing checklist, all in one page.

## Description

This is a no-build, single-file HTML app for planning an extended trip from Guadalajara, Mexico to Coimbatore, India around Diwali (November 8, 2026). It brings together the scattered pieces of trip prep — flight countdown, voltage/plug logistics, weather differences between the two cities, a family gift list, and a packing checklist — into one page instead of a handful of notes apps.

The visual identity follows the botanical-dark aesthetic used across other builds in this series: deep green background, parchment text, Fraunces serif for display type, Inter for UI, IBM Plex Mono for data and dates. A dotted "journey thread" runs down the page connecting each section, echoing the route the trip itself takes.

Checklist progress, the gift list, and the departure date all persist automatically using the artifact's built-in storage — no backend, no account, no setup.

## Visuals

- **Hero** — live countdown to Diwali, plus a second countdown that activates once a departure date is set
- **Weather delta** — side-by-side climate comparison, Guadalajara (dry season) vs. Coimbatore (post-monsoon)
- **Logistics** — voltage/plug comparison (127V Type A/B vs. 230V Type C/D/M) and a checklist for visa, flights, SIM, converter, and insurance
- **Gifts for family** — an editable table of names and gift ideas, with a checkbox per row
- **Packing checklist** — tabbed by category (documents, electronics, clothing, festival, toiletries, misc) with a live progress bar

## Installation

No installation needed. It's a single self-contained HTML file — open it directly in a browser, or run it as a Claude artifact where the storage API is available.

If running it outside of an artifact-capable environment, note that the persistence layer (`window.storage`) won't exist — the checklist and gift list will still work for the session but won't save between visits unless that API is present.

## Usage

1. Open the file.
2. Set a departure date in the field below the countdowns — the second countdown activates automatically.
3. Check off logistics items as they're sorted (visa, flights, SIM, etc.).
4. Add a row per person under **Gifts for family** using the "+ add person" button; edit name and gift idea inline; remove a row with the × button.
5. Switch between packing categories using the tabs, and check off items as they're packed. The progress bar reflects the total across all categories.

Everything autosaves a moment after each edit — no save button required.

## Support

This is a personal single-file build, not a maintained package — no support channel. For changes or a new section, describe what's needed and a new version can be generated.

## Roadmap

Ideas for a future pass, not yet built:
- Editable weather figures (currently seeded with typical early-November ranges for both cities)
- Optional additional family members pre-seeded beyond the one default row
- A print/export view for offline reference while traveling

## Contributing

Personal project — not open for external contributions. Feedback and change requests are welcome directly.

## Authors and acknowledgment

Built for Soundarya's Guadalajara–Coimbatore trip, part of the ongoing series of single-file cross-cultural builds (Suvadi, Rasam vs. Salsa, The Nine-Hour Overlap).

## License

Personal-use project. No license currently applied.

## Project status

Active — first working version complete; weather figures and family gift list to be finalized closer to travel dates.
