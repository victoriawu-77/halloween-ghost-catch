# Catch the Ghosts

A cute Halloween mini-game: tap floating ghosts, dodge pumpkin bombs, and chain combos before the clock runs out.

## Play locally

Open `index.html` in any modern browser (Chrome, Safari, Firefox). No build step, no install.

```bash
# optional local server
python3 -m http.server 8080 --directory .
# then visit http://localhost:8080
```

## Play online

Once deployed to GitHub Pages:

**https://victoriawu-77.github.io/halloween-ghost-catch/**

## How to play

- **60 seconds** per round
- **Ghost** → +10 points
- **Golden ghost** (glowing) → +30 points
- **Pumpkin bomb** → −15 points if tapped
- Catch ghosts within ~1.2s of each other to build a **combo multiplier**

## Stack

Single static `index.html` (inline CSS + JS). No frameworks, no CDN dependencies.

## License

Made for fun. Share freely.
