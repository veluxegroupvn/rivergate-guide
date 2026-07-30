# Veluxe Stay — Rivergate Guest Guide

## What's in here
- `index.html` — the full guest guide (self-contained, images already embedded as base64, so this one file is all GitHub Pages needs)
- `images/` — logo lockups and icon crops shared with the SOHO guide, plus `qr_rivergate.png` (QR to rivergate.veluxestay.com, VS mark + "RVG" label, verified to scan)
- `CNAME` — points GitHub Pages at `rivergate.veluxestay.com`

## Deploy status
Repo created and pushed. Still needed on the GitHub/DNS side:
1. Settings → Pages → Deploy from main / root
2. Settings → Pages → confirm custom domain is `rivergate.veluxestay.com` (should auto-fill from the CNAME file)
3. GoDaddy DNS → CNAME record: Name `rivergate`, Value `veluxegroupvn.github.io`
4. Once the cert provisions, check "Enforce HTTPS" in Settings → Pages

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
- Tresor guide (copy this file, edit CONFIG + the two BUILDING-SPECIFIC blocks)
- Printed card redesign to match the SOP's late check-out numbers
