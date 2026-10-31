# Haruko Poker

A pocket rules reference for poker nights, made to be passed around the table on a phone.

- **Hand rankings** with card examples and tie-break rules
- **Texas Hold'em**: how a hand goes, step by step
- **Blinds & betting**: small/big blind, check/bet/call/raise/fold, limits, side pots, a home-game chip setup
- **Quick answers** to the usual table arguments ("Does a flush beat four of a kind?")
- **Other games**: Omaha, Five Card Draw, Seven Card Stud, wild cards

It's a single static page (`index.html`), no build step. Open it on a phone and use "Add to Home Screen" to get an app icon; it then works offline too.

## Hosting

A GitHub Actions workflow publishes the site to GitHub Pages on every push to `main`.
One-time setup: in the repo go to **Settings → Pages** and set **Source** to **GitHub Actions**.
The site is then at `https://<user>.github.io/poker/`.
