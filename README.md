# The Titanic Game

A browser game designed by Asa (age 6), drawn in a brick-built toy style.

The Titanic is about to hit an iceberg. You start at the very bottom of the ship. Find the key, unlock the gate to the lifeboats, and get in a lifeboat before the water touches you. There are no points. You either survive or you don't.

## How to play

Open `index.html` in any modern browser. There's nothing to install or build.

| Action | Keyboard | Touch |
| --- | --- | --- |
| Walk | ← → (or A / D) | ◀ ▶ buttons |
| Climb ladders | ↑ ↓ (or W / S) | ▲ ▼ buttons |
| Search luggage, or open the shop | Space (or E / Enter) | 🔍 button |
| Full screen | F, or the ⛶ button at the top right | ⛶ button (not on iPhone) |

## The rules

- **You start in the Boiler Room.** Climb up through the 3rd Class cabins, the hallways and the ballroom to reach the Boat Deck.
- **The richer you are, the higher your class.** Coins (worth 1) and money bags (worth 3) are scattered around the ship and hidden in luggage.
  - Collect 5 coins to become **2nd Class** and open the 2nd Class Lounge.
  - Collect 12 coins to become **1st Class** and open the 1st Class Ballroom.
  - Your hat changes as you move up: flat cap, then bowler hat, then top hat.
- **The lifeboat gate is locked.** You need the key to open it.
- **The iceberg hits at a random time.** The lookout rings a bell just before. Once it hits, water rises from the bottom, the ship slowly tips and the lights slowly dim.
- **If the water touches you, you lose.** If you get into a lifeboat first, you survive.

## Extras

- **The shop.** The purser's desk in 3rd Class sells a **life jacket** (4 coins) and **fast shoes** (3 coins, run and climb faster). Spending coins doesn't lower your class, because class counts everything you've collected.
- **Swimming to a lifeboat.** With a life jacket on, you can jump into the sea through the gangway doors on the two lower passenger decks once the iceberg has hit. If the water reaches you, the jacket floats you out instead of you losing. Then the view switches to the open sea from above: swim to a lifeboat before your warmth bar runs out. Icebergs block the way and make you colder if you touch them. Sharks chase you if you swim close, but you can outswim them. More sharks appear at higher levels.
- **The lost puppy.** A puppy is hiding somewhere on the ship. Walk up to it and it follows you. Get it into the lifeboat with you to save it too.
- **Picture hints.** Locked gates show what you still need, like a coin with "3/5". After the iceberg hits, a red arrow over your head reminds you to go up.
- **Guide arrow.** A gold arrow points to the next place to go: coins, then the key, then a lifeboat. It points at ladders when the next place is on another deck.

## The better you get, the harder it gets

Every win moves you up a level. Your level is saved in the browser.

| Level | What changes |
| --- | --- |
| 1 | The key lies out in the open on one of the bottom two decks, and the guide arrow is on. |
| 2 | The key is out in the open on any deck. |
| 3 | The key is hidden in luggage, and passengers walking around slow you down. Luggage holding a key wobbles and twinkles when you're near it on the same deck. |
| 4 | The key is hidden in the 2nd Class Lounge (5 coins), and two lifeboats leave early (about a minute after the iceberg). Red dots on a boat count down to when it leaves. One boat always waits. |
| 5 | The key is hidden in the 1st Class Ballroom (12 coins). |
| 6+ | A locked hatch on the way up needs a silver key, hidden in luggage on the bottom decks. |

From level 2 on, the iceberg comes sooner and the water rises faster, up to level 6. After that, the levels stay the same.

## Make it yours

From the title screen:

- **Pick your player** from six kids.
- **Make it yours:** name the puppy, choose the lifeboat colour, and write a sign that hangs between the funnels on the Boat Deck.

## For grown-ups

The **Grown-ups** button on the title screen has:

- **Slow mode:** the iceberg comes 10 seconds later, the water rises 40% slower, lifeboats wait longer, and sharks and cold are gentler when swimming.
- **Guide arrow:** Auto (levels 1–2 only), Always, or Never.
- **Level:** jump to any level from 1 to 8, or go back to 1.

Other notes:

- Sound effects are soft chimes. The speaker button in the top-right corner turns them off.
- It's a single self-contained file: `index.html`, with plain JavaScript and a canvas. The only external resource is the Fredoka font from Google Fonts, and the game still works without it.
- To put it online, enable **GitHub Pages** for this repository (Settings → Pages → deploy from the `main` branch) and share the link.
