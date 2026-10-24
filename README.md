# The Titanic Game

A browser game designed by Asa (age 6).

The Titanic is about to hit an iceberg. You start at the very bottom of the ship. Find the key, unlock the gate to the lifeboats, and get in a lifeboat before the water touches you. There are no points. You either survive or you don't.

## How to play

Open `index.html` in any modern browser. There's nothing to install or build.

| Action | Keyboard | Touch |
| --- | --- | --- |
| Walk | ← → (or A / D) | ◀ ▶ buttons |
| Climb ladders | ↑ ↓ (or W / S) | ▲ ▼ buttons |
| Search a suitcase, crate or trunk | Space (or E / Enter) | 🔍 button |

## The rules

- **You start in the Boiler Room.** Climb up through the 3rd Class cabins, the hallways and the ballroom to reach the Boat Deck.
- **The richer you are, the higher your class.** Coins (worth 1) and money bags (worth 3) are scattered around the ship and hidden in luggage.
  - 5 coins makes you **2nd Class** and opens the 2nd Class Lounge.
  - 12 coins makes you **1st Class** and opens the 1st Class Ballroom.
  - Your outfit changes as you move up: flat cap, then bowler hat, then top hat.
- **The lifeboat gate is locked.** You need the key to open it.
- **The iceberg hits at a random time.** The lookout rings a bell just before. Once it hits, water starts rising from the bottom of the ship.
- **If the water touches you, you lose.** If you get into a lifeboat first, you survive.

## The better you get, the better the key hides

Every win moves you up a level, and your level is saved in the browser.

| Level | Where the key is |
| --- | --- |
| 1 | Lying out in the open on one of the bottom two decks, sparkling (the mini-map shows where) |
| 2 | Out in the open, anywhere from 3rd Class up to the top hallway |
| 3 | Hidden inside a suitcase, crate or barrel on the lower decks or in a hallway |
| 4 | Hidden in luggage in the 2nd Class Lounge, so you need 5 coins first |
| 5+ | Hidden in luggage in the 1st Class Ballroom, so you need 12 coins first |

From level 2 on, the iceberg also tends to come sooner and the water rises faster, up to a limit. You can go back to level 1 from the title screen.

## For grown-ups

- Sound effects are soft chimes. The speaker button in the top-right corner turns them off.
- It's a single self-contained file: `index.html`, with plain JavaScript and a canvas. The only external resource is the Fredoka font from Google Fonts, and the game still works without it.
- To put it online, enable **GitHub Pages** for this repository (Settings → Pages → deploy from the `main` branch) and share the link.
