# Rise of the Hamlets

A 3D hex-board strategy game for 1–4 players that runs in any modern browser. Grow your hamlet into an empire, gather resources, fend off bandits, and outlast your rivals.

**Play it:** https://aenexyz.github.io/Hamlets-Boardgame/

## How to play

Each turn runs through five phases:

1. **Gather:** every peasant collects from the hex it stands on (wheat, wood, stone, gold, or fish from the riverbank), sometimes finding tools, seeds, or a bandit stash.
2. **Move:** units move across the hex board and can attack bandits, rival units, and rival bases.
3. **Combat:** bandits strike back and steal from your stockpile.
4. **Upkeep:** every unit eats 1 food. Unfed units go hungry, and starve if unfed twice.
5. **End:** the next player takes their turn.

**Win** by upgrading your base from Hamlet to Town, City, and finally Empire, or by being the last base standing.

## Features

- Five factions, each with its own hero and hero ability: Hearthfolk, Ironwood Wolfmen, Merfolk, Ashen Orcs, and Stoneheart Dwarves
- 1–4 players on one device, with optional AI opponents
- A river splitting the map, crossable by building bridges, and a bandit lair on an island in the middle
- Farms, barracks, a blacksmith, a wizard tower with magic scrolls, walls, watchtowers, and hidden landmines

## Controls

- **Click or tap** a unit, then a glowing hex to move or a red-highlighted target to attack
- **Drag** to rotate the board, **right-drag / two fingers / WASD** to pan, **scroll / pinch** to zoom
- **B** opens your base menu, **I** opens your inventory, **H** uses your hero's ability, **Z** undoes, **Enter** ends your moves

## Tech

A single `index.html` file using HTML, CSS, and JavaScript, with [Three.js](https://threejs.org/) (loaded from a CDN) for the 3D board. All models are generated in code, so there are no image files.
