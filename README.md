# Tiktok Game store

The game list that **Tiktok Game** (by CONNOR KURD) reads: `catalog.json`.

- `games[]` - every game in the in-app Store (cover, version, download). The download is a zip with `game.json` at
  its root; the program reads that file to build the gift setup, so a new game needs no program update.
- Bump a game's `version` (and upload the new zip as a release asset) to make every player update before playing.
- `app` - the newest Tiktok Game program; a higher `version` makes every copy update itself.
