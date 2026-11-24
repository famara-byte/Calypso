# Calypso Bar and Restaurant — Website

Demo website for **Calypso Bar and Restaurant**, Cape Point, Bakau, The Gambia — a garden restaurant and bar beside a wildlife lagoon, next to the Ocean Bay Hotel.

## What's here

- `index.html` — the complete single-page website: photo slideshow hero, Eat & Drink menu with pictured dishes and ingredients, the lagoon and crocodile story, live music and events, Google Reviews section, opening hours and a Reserve a Table form.
- `assets/` — the site's photos (venue, lagoon, dishes and drinks).
- `space.json` / `AGENTS.md` — original build metadata and notes.

## Status

Demo version. Menu prices are sample estimates, to be replaced with Calypso's real menu card before the site is promoted as final.

## The business

- Calypso Bar and Restaurant, Cape Point, Bakau, The Gambia
- Est. 1988 · Wildlife lagoon with daily crocodile feeding at 4pm
- Phone: +220 335 7788

## Ordering system (demo)
- `menu.html` — guest menu with table ordering, bill and demo payment; add `?t=N` for the table number (QR codes per table). After payment, guests are asked for a star review.
- `kitchen.html` — live kitchen board: New → Preparing → Ready → Served.
- `pos.html` — cashier POS: bills by table, take payment & close, today summary, latest reviews.
The three screens sync live in the same browser (localStorage) for demonstration; production multi-device use needs a cloud backend.
