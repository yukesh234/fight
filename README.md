# Poké Quest

A fun little browser-based Pokémon fan game. Pick a region, build a team, beat all 8 gyms, then take on the Elite Four and the Champion.

**Play it here:** https://yukesh234.github.io/fight/

No install, no dependencies. It is a single HTML file.

## Features

- **Four regions:** Kanto, Johto, Hoenn and Sinnoh, each with its own 8 gym leaders, Elite Four and Champion
- **Pick your own team** at the start, with unlimited Rare Candies and unlimited cash
- **Mega Evolution:** many of the 32 Pokémon can Mega Evolve once per battle
- **Walkable town map:** move with WASD or the arrow keys (or the on-screen D-pad on phones) and step onto a door to enter
- **Turn-based battles:** type matchups, same-type bonuses, speed order, status effects (sleep, paralysis, burn, poison), a Bag and switching
- **"About to send out" prompt:** the game asks if you want to switch Pokémon between the opponent's Pokémon
- **Wild grass and catching** with Poké Balls
- **Poké Mart, Pokédex and badge case**
- **Day and night** on the map, based on your clock
- **Sound effects and a chiptune loop**
- **Auto-save** in your browser, and the game resumes where you left off
- **Mobile friendly**

## Controls

| Action | Keys | Touch |
| --- | --- | --- |
| Walk | WASD / arrow keys | On-screen D-pad |
| Enter a building | Walk up to its door | Walk up to its door, or tap the building |
| Everything else | Click | Tap |

## Optional: real sprites (local use only)

By default the Pokémon and trainers are simple drawn shapes. If you run the game from your own computer, it will load images from these folders next to the HTML file:

- `sprites/<pokemon>.png`, for example `charizard.png`, with Mega forms as `charizard-mega.png`
- `sprites/trainers/<name>.png`, for example `brock.png` or `ltsurge.png`

Anything missing falls back to the drawn version. Sprite images are not included in this repository.

## Run locally

Download the HTML file and open it in your browser.

## Notes

- Progress is saved per browser, so the hosted version and a local copy keep separate saves.
- The battle system is a simplified take on the original games.

## Disclaimer

This is an unofficial, non-commercial fan project made for fun and learning. Pokémon and all related names and characters are trademarks of Nintendo, Game Freak and Creatures Inc. This project is not affiliated with or endorsed by them.
