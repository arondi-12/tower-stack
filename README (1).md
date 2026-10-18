# Tower Stack

A one-tap stacking game for [start.ng](https://start.ng). Drop each sliding block onto the tower. Any overhang is sliced off, so the tower gets narrower until you miss. Line blocks up exactly for a perfect drop and keep your width.

**Play it:** https://tower-stack.start.ng

## How to play

- Tap, click, or press **Space** to drop the block.
- Each floor you land adds 1 to your score.
- A near-exact drop counts as a **perfect** and keeps the block full width.
- The blocks speed up as the tower grows.
- If a block misses the tower completely, the run ends.

## start.ng features

- **Your character:** the game shows your start.ng profile card (face, character name and account). Guests are shown as "Guest" with a Sign in button.
- **Leaderboard:** signed-in players have their best run saved. Players are ranked by **Floors**, with **Perfect drops** as the tiebreaker.

## Project files

| File | Purpose |
| --- | --- |
| `index.html` | The whole game: HTML, CSS and JavaScript, with no build step |
| `startng.json` | Declares the leaderboard columns (`floors`, `perfects`) |
| `cover.png` | The 16:10 cover picture shown on start.ng |

## Run it locally

Open `index.html` in a browser. The game plays without a player, but sign-in, profile card and leaderboard only work when it's live on start.ng.

## Updating

Push changes to the `main` branch. start.ng checks the repo and updates the live game automatically.
