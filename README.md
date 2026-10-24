# Binder Tracker: Yu-Gi-Oh! images

Yu-Gi-Oh! card images for [Binder Tracker](https://bindertracker.co.uk/), served at `https://img.bindertracker.co.uk/` by GitHub Pages.

- `yugioh/<id>/low.webp` (210×306) and `yugioh/<id>/high.webp` (421×614): one image per Yu-Gi-Oh! card artwork, shared by every printing that uses it. `<id>` is the artwork's YGOPRODeck image id.

The files are made by `npm run images -- --game yugioh` in the Binder Tracker repository, from the card scans on [YGOPRODeck](https://ygoprodeck.com/). Each scan is downloaded once and re-encoded to WebP. Don't regenerate images that are already here: every change adds a full copy to the git history, and a GitHub Pages site can be at most 1 GB.

Yu-Gi-Oh! and all card images © Studio Dice/SHUEISHA, TV TOKYO, KONAMI. This repository isn't affiliated with, endorsed, sponsored or approved by Konami Digital Entertainment, Studio Dice or Shueisha. The images aren't licensed here: they're shown only to identify cards in a free collection checklist.

The site sets no cookies and runs no tracking. GitHub Pages serves the files, so GitHub sees visitors' IP addresses, like any web host.
