# Haruku Poker

A pocket rules reference for poker nights, made to be passed around the table on a phone.

- **What beats what**: all 10 hands as a ladder, plus a "hand duel" to settle which of two hands wins
- **Texas Hold'em**: an interactive walkthrough of one hand on a little table
- **Blinds & betting**: small/big blind, check/bet/call/raise/fold, limits, side pots, a home-game chip setup
- **Settle it**: quick yes/no answers to the usual table arguments
- **Other games**: Omaha, Five Card Draw, Seven Card Stud, wild cards

It's a single static page (`index.html`), no build step. Open it on a phone and use "Add to Home Screen" to get an app icon; it then works offline too.

## Hosting

A GitHub Actions workflow publishes the site to GitHub Pages on every push to `main`.
One-time setup: in the repo go to **Settings → Pages** and set **Source** to **GitHub Actions**.
The site is then at `https://<user>.github.io/poker/`.
