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
- **Pause** freezes the clock, the ghosts, and new spawns. **Resume** continues the same round
- **Quit** leaves the round and returns to the start screen. The score is not saved. Switching away from the tab pauses the round too

## Sound

Music and effects are synthesized in the browser with the Web Audio API. There are no audio files and no CDN. An original spooky loop (minor lead, plucky bass, theremin-style glide, a soft ghostly swell, and a bell accent) starts when you press **Play**. Pausing the game pauses the music. The speaker button mutes or unmutes, and that choice is remembered on this device. Effects cover catches, golden ghosts, pumpkin bombs, combos, game over, and button taps.

## Leaderboard

High scores stay in this browser only (`localStorage`). Nothing is uploaded.

After a round, if your score reaches the top 10, save a name or skip. Names can be up to 16 characters; the default is Ghost Hunter. **Play Again** is always available, including before you save. Open **Leaderboard** from the start screen or the results screen. Each row shows rank, name, score, best combo, and date.

## Stack

Single static `index.html` (inline CSS + JS). No frameworks, no CDN dependencies, no build step.

## License

Made for fun. Share freely.
