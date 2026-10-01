# Veluxe Stay — Rivergate Guest Guide

## What's in here
- `index.html` — the full guest guide (self-contained, images already embedded as base64, so this one file is all GitHub Pages needs)
- `images/` — logo lockups and icon crops shared with the SOHO guide, plus `qr_rivergate.png` (QR to rivergate.veluxestay.com, VS mark + "RVG" label, verified to scan)
- `CNAME` — points GitHub Pages at `rivergate.veluxestay.com`

## Deploy status
Published at https://rivergate.veluxestay.com through the `veluxegroupvn/rivergate-guide` GitHub repository, using `main` and the repository root.

The navigation redesign dated 2026-10-01 is included in main. GitHub Pages publishes changes automatically after a successful push.

## To edit
Open `index.html`, search for `const CONFIG` near the bottom. wifiName, hostPhone,
checkIn/checkOut, and the exchange/spa links all live there. Everything else is
plain HTML further up the file, organized by <section id="..."> blocks.

## What's still unverified (check before going live)
- **Exchange links (fx1/fx2) and spa link** in CONFIG are still the same SOHO ones (near 100 Cô Giang, District 1). Not confirmed to be convenient from Rivergate (District 4) — may need Rivergate-specific ones.
- **Pharmacy/doctor section** (`CarePlus International Clinic`) kept as-is from SOHO — a citywide chain, but distance from Rivergate not re-verified.
- **Rubbish room** is described as "usually down the hallway... confirmed in your check-in message" — only works if that's actually true for every unit's check-in message.
- **SIM card shop (VNPT near the Honda dealer)** and **ATM withdrawal limit (~2M VND)** are from memory, not verified on the ground.
- **Door lock codes** are per-unit and change; deliberately left out of this guide (guests get them via check-in message, not the public guide).
- Food/shopping picks pulled from Tony's Airbnb guidebook and Grab order history — addresses were found via web search, not independently walked/verified.
- **Poke Saigon** — conflicting signals on whether it's still open (HappyCow says closed, other listings from 2026 say active). Confirm before relying on it.

All travel times (attractions, malls, supermarkets, restaurants, gyms) were checked against live Google Maps driving/walking directions from the Rivergate address, not just estimated.

## Source of truth for fees
Fees follow the internal SOP (Google Doc), not the printed card, where the two
ever disagree. Same policy as the SOHO guide — not re-verified for Rivergate specifically.

## Still to build
- Printed card redesign to match the SOP's late check-out numbers

## Navigation redesign, 2026-10-01

The opening shows WiFi, the driver address, stay times and host contact. A sticky “Find something” menu replaces the 13 card contents grid. Six groups provide short descriptions and direct links to individual answers. Links open the relevant accordion automatically, including when a guest opens a URL with a fragment. Escape closes the menu.

Luggage has its own answer and retains the property's existing policy. Rubbish photos are preserved and shown on request. Nearby food and Grab delivery appear first in the food section. Attraction and mall durations explicitly say “by car”. All other local durations retain each building's own starting point.

Browser validation covers all three guides at widths of 320, 390, 430, 768 and 1280 pixels, all 29 unique menu destinations, keyboard dismissal, copy buttons, photo preservation and existing extras and late check out prices.

Rivergate retains its 15 minute walking labels for Phở SOL and Eatlah. The separate Google Maps checks showed 14 and 13 minutes on the shortest routes, with 15 minute alternatives. Tresor's shorter times are not shared with this guide.
