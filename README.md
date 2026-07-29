# Veluxe Stay — Rivergate Guest Guide

## What's in here
- `index.html` — the full guest guide (self-contained, images already embedded as base64, so this one file is all GitHub Pages needs)
- `images/` — same logo lockups and icon crops as the SOHO guide (shared brand assets)

## Deploy status
Not yet live, and no repo created yet. Steps needed:
1. Create GitHub repo under the `veluxegroupvn` account (e.g. `rivergate-guide`), upload `index.html`
2. Settings → Pages → Deploy from main / root
3. Settings → Pages → Custom domain → `rivergate.veluxestay.com`
4. GoDaddy DNS → CNAME record: Name `rivergate`, Value `veluxegroupvn.github.io`
5. Add a `CNAME` file to the repo containing `rivergate.veluxestay.com` (same as the SOHO repo)
6. No QR code generated yet for this domain — the SOHO one (`qr_soho.png`) does NOT work here, needs a new one pointed at `rivergate.veluxestay.com`

## To edit
Open `index.html`, search for `const CONFIG` near the bottom. wifiName, hostPhone,
checkIn/checkOut, and the exchange/spa links all live there. Everything else is
plain HTML further up the file, organized by <section id="..."> blocks.

## What's still unverified (check before going live)
- **Exchange links (fx1/fx2) and spa link** in CONFIG are still the same SOHO ones (near 100 Cô Giang, District 1). Not confirmed to be convenient from Rivergate (District 4) — may need Rivergate-specific ones.
- **Travel times** in "Brunch & cafes", "District 1 favourites" and "Vincom Center food court" were bumped up from SOHO's numbers to account for crossing the river (e.g. 6→10 min taxi), but these are estimates, not measured trips.
- **Bùi Viện walk time** (15 min) in the street rail is a rough estimate, not measured.
- **Pharmacy/doctor section** (`CarePlus International Clinic`) kept as-is from SOHO — a citywide chain, but distance from Rivergate not re-verified.
- **Rubbish room** is described as "usually down the hallway... confirmed in your check-in message" — only works if that's actually true for every unit's check-in message.
- **SIM card shop (VNPT near the Honda dealer)** and **ATM (around the block towards McDonald's, ~2M VND limit)** are from memory, not verified on the ground.
- **Door lock codes** are per-unit and change; deliberately left out of this guide (guests get them via check-in message, not the public guide).
- New food/shopping picks (street food, Japanese/Korean, fine dining, Tân Định Market, The Cafe Apartment, Crescent Mall, AEON Nguyễn Văn Linh) were pulled from Tony's Airbnb guidebook — addresses are as given there, not independently re-verified.

## Source of truth for fees
Fees follow the internal SOP (Google Doc), not the printed card, where the two
ever disagree. Same policy as the SOHO guide — not re-verified for Rivergate specifically.

## Still to build
- Tresor guide (copy this file, edit CONFIG + the two BUILDING-SPECIFIC blocks)
- Printed card redesign to match the SOP's late check-out numbers
