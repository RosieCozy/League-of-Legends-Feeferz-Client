<p align="center">
  <img src="assets/icon.png" width="96" alt="Feeferz Client">
</p>

<h1 align="center">Feeferz Client</h1>

<p align="center">
  A fast, lightweight League of Legends and TFT companion for Windows.<br>
  Builds, counters, tier lists, items, TFT comp guides, player profiles, the store and a minimal in-game overlay in one app.
</p>

<p align="center">
  <a href="https://github.com/RosieCozy/League-of-Legends-Feeferz-Client/releases/latest"><img src="https://img.shields.io/github/v/release/RosieCozy/League-of-Legends-Feeferz-Client?label=download&color=4b4b54" alt="Latest release"></a>
  <a href="https://github.com/RosieCozy/League-of-Legends-Feeferz-Client/releases"><img src="https://img.shields.io/github/downloads/RosieCozy/League-of-Legends-Feeferz-Client/total?color=4b4b54" alt="Downloads"></a>
  <img src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-4b4b54" alt="Windows 10 and 11">
</p>

<p align="center">
  <img src="docs/screenshots/champion.png" width="900" alt="Champion build page">
</p>

## Download

1. Grab **`FeeferzClient.exe`** from the [latest release](https://github.com/RosieCozy/League-of-Legends-Feeferz-Client/releases/latest).
2. Run it. No installer and nothing else to install.
3. Set League to **Borderless** window mode so the overlay can show above the game.

The app updates itself when a new release is out. It waits until you're out of champ select or a game.

## Features

### Champ select, loading screen and in game
- Predicts your lane opponent as enemies lock in, with counter picks, your matchup win rate and the rune page that wins it.
- Runes and item sets import in one click. Imported rune pages are temporary: your own pages are never cluttered, and a page borrowed for the import is put back after the game.
- Loading screen: rank, win rate and champion stats for all 10 players, with flags for one-tricks, streaks, premades and players new to their champion.
- In game: your build against your lane opponent, the next item to buy and situational items based on the enemy team.
- A build for the enemy team you're facing: what players change into a mostly AP or mostly AD team.
- Click any player in champ select or in game to open their profile.
- A minimal, click-through overlay that never steals focus, plus an optional CS tracker for you and your lane opponent. Both adapt to ARAM and Arena. Turn the overlay on or off from the top bar.
- Optional auto-accept for queue pops.

### Builds and tier list
<img src="docs/screenshots/tier-list.png" width="900" alt="Tier list">

- Every champion opens on its best win rate build for the rank you pick, with tabs for the most played and off-meta builds players really run, runes, item sets, matchups, one-tricks and a guide.
- Runes and item sets import in one click, and are cleared from the client afterwards so nothing piles up.
- The build into any opponent.
- Lane-specific tier and stats, every lane the champion is played in, and good/bad matchups.
- Ranked, ARAM, ARAM: Mayhem and Arena builds.
- A tier list per lane with win, pick and ban rates, and an off-meta filter.

### Items
- Every item on the Rift with its gold cost, stats and full description, searchable and sortable by type or stat.
- Popular items: what's built most, the share of champions building it and the champions doing best with it.

### TFT comps
<img src="docs/screenshots/tft-guide.png" width="900" alt="TFT comp guide">

- Current meta comps with tier, average placement, top 4, win and pick rates, filtered by play style.
- A full guide for each comp: final board, traits, variations, economy plan stage by stage, tips, builds for every carry and item priority.
- Section links at the top of each guide, and a one-click team code for TFT's Team Planner.

### Player profiles
- Search any Riot ID. Your friends list and recent teammates show up first, with live in-game status.
- Profiles refresh as soon as you open them, and are split into tabs instead of one long page.
- Ranks, season records, champion mastery, recent form at a glance and the last games with a grade and tags for each.
- Match details for any game: both teams, every player's build, runes and spells, damage, objectives and bans.
- Insights that compare you with players in your role at your rank.
- Premades from recent games, and a flag when someone is new to the champion they're playing.

### League Shop
<img src="docs/screenshots/shop-sale.png" width="900" alt="League Shop">

- Every skin with its price, the weekly sale, limited and legacy skins, the Sanctum, the Mythic shop with its rotations and time left, wards with prices, your skin shards and your own collection.
- A TFT store with limited-time items, prices and filters for Tacticians, Arenas and Booms.
- RP, Blue Essence, Mythic Essence, Orange Essence and TFT currencies shown just like the client.
- Remembers your account, currencies, shards and shop from the last time League was open, so you can browse it with League closed.

### More
- League patch notes for the last year with your most played champions first, plus the app's own patch notes, both by month.
- Dark and light mode.
- A short welcome tour for new users and a What's new tour after each update, both optional.
- 12 or 24-hour time, close to tray or exit, and back/forward with the mouse side buttons.
- Light on older PCs: images download once, heavy sections load only when opened, and the app slows its polling down when minimized.

## Screenshots

| | |
| --- | --- |
| <img src="docs/screenshots/builds.png" alt="Champion grid"> | <img src="docs/screenshots/tft-comps.png" alt="TFT comps"> |
| <img src="docs/screenshots/items.png" alt="Items"> | <img src="docs/screenshots/items-popular.png" alt="Popular items"> |
| <img src="docs/screenshots/shop-mythic.png" alt="Mythic shop"> | <img src="docs/screenshots/shop-sanctum.png" alt="Sanctum"> |
| <img src="docs/screenshots/shop-tft.png" alt="TFT store"> | <img src="docs/screenshots/patch-notes.png" alt="Patch notes"> |

## Is it safe?

Feeferz Client only uses the interfaces Riot provides on your own PC: the League client's local API (champ select, runes, store) and the Live Client Data API (your in-game items). It doesn't read or change game memory, inject anything or touch game files. No account login or API key is needed.

Enemy ability and summoner spell timers are deliberately left out, as Riot's third-party rules don't allow them.

## License

Copyright (c) 2026 Throwsie. All rights reserved.

Feeferz Client and its source code are owned by Throwsie. The code is public to view only. You may download and use the released app for personal use, but you may not copy, modify, redistribute, sell, re-upload or publish this code or the app, in whole or in part, or make derivative works from it, without written permission. See [LICENSE](LICENSE).

## Legal

Feeferz Client isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
