# Blue Prince -- Mechanics Reference

**status:** research-integrated
**last_reconciled:** 2026-11-01

Core rules of the shifting manor, steps, resources and the late-game structure, from the Stage 0 pass and the P1 and P2 research results (2026-10-31). Source numbers in brackets (for example [24]) are listed in `## Sources` at the end; claims whose `_source:` line says P2 use the P2 numbering listed in `## Sources (P2)`. Room lists are in `sections/rooms.md`, items in `items/`, puzzles in `puzzles/`. The unlock chains P2 researched are in `items/upgrades.md` and the files of `puzzles/`.

## Room drafting and the shifting manor

> **Cross-system dependency** -- see `dependencies.md` DEP-021.

The manor's layout is rebuilt each day. The house is a grid of 45 room slots: 5 columns by 9 rows (ranks), Rank 1 at the south and Rank 9 at the north. The leftmost and rightmost columns are the West and East Wings.
_source: P1 research 2026-10-31 refs [5][24][36] · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 3 sources, 1 languages]

The Entrance Hall is always in the middle of Rank 1.
_source: P1 research 2026-10-31 refs [5][24] · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 2 sources, 1 languages]

A sealed room, the Antechamber, is always in the middle of Rank 9 and starts sealed.
_source: P1 research 2026-10-31 refs [5][24] · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Confirmed: 2 sources, 1 languages]

Drafting: open an unexplored door and three floorplans are drawn from the draft pool; pick one and it is built behind the door; you cannot back out. The first plan offered is always free; plans 2 and 3 may cost gems (1-5), and a plan you cannot pay for cannot be picked. A drafted room is rotated so one of its doors meets the door you came through; doors that do not line up leave blocked doors. Doors on the outer edge of the grid cannot be drafted through.
_source: P1 research 2026-10-31 refs [5][24][36] · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 3 sources, 1 languages]

A dead end is a room with only one doorway; extra doorways, even blocked ones, disqualify a room from counting as one. Day 1's first draft is always a Bedroom, a Closet and a Hallway.
_source: P1 research 2026-10-31 refs [24][36][38] · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Single source -- verify · class:community-wiki]

Redraws: an Ivory Die gives one redraw (you must be able to afford all three offered plans to use one). Plans normally appear once per day. A custom seed of up to 8 digits can be typed on the New Game screen; the three offered plans, extra items in rooms (rolled each time a room is drafted) and the orientation when more than one fits are random.
_source: P1 research 2026-10-31 refs [24] · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Single source -- verify · class:community-wiki]

Locked doors cost 1 key and never appear in Ranks 1-2; the lock chance grows with rank (it reaches certainty at Rank 9). A Lock Pick is one tool that can open a lock instead of a key. Rarity (how often a floorplan is drawn) has four bands, Commonplace / Normal / Uncommon / Rare; rarer plans come more often the further north you draft. Rarity is not rank (see "Terms that look alike").
_source: P1 research 2026-10-31 refs [24][38] · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Single source -- verify · class:community-wiki]

Rank 3's lock chance is given as 70 percent for one random position per day and Rank 9's as 130 percent (always). The wiki lists exact rarity percentages per rank; for example Rank 9 on days 1-5 is 86 / 9 / 4 / 1 percent across the four bands, and the odds change from day 6 and from day 25. Reinforced security doors are a separate kind of door: one Keycard opens every powered security door that day and is not consumed. Foyer-type Hallway rooms make Hallway doors always unlocked. Whether a Lock Pick gets one attempt or retries is disputed (one wiki says one attempt per lock; a Reddit tips post and its replies disagree).
_source: P1 research 2026-10-31 refs [24][51] · capture: web_fetch · confidence: low · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Contradicted across sources -- see notes]

Room colors (types): violet Bedroom (steps), orange Hallway (many doors), green Green Room (gems, dig spots), golden-yellow Shop (coins), red Red Room (powerful at a cost), blue Blueprint (the default type). A multicolor plan counts as every color it shows. Subtype symbols: compass = Drafting, gear = Mechanical, clock = Tomorrow, jigsaw = Puzzle, open door = entry effect, clover = luck.
_source: P1 research 2026-10-31 refs [2][24][38][47] · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 3 sources, 1 languages]

Higher-ranked rooms (determined by grid row) are described as having harder puzzles and better rewards.
_source: https://en.wikipedia.org/wiki/Blue_Prince · capture: web_fetch · contributor: setup-wizard Stage 0 · confidence: medium · last-verified: 2026-10-31 · enemy-tier: 0 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:editorial-en]

The wiki.gg Room Directory lists 8 rooms per colored group, while the Fextralife wiki counts Bedroom 18, Hallway 16, Green 23, Shop 9, Red 13 because it includes multicolor and added rooms. The two count different sets and neither is wrong; the same room can have different names on the two wikis (see `limitations.md`).
_source: P1 research 2026-10-31 refs [2][24] · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Contradicted across sources -- see notes]

Early-game restrictions: on days 1-3 the first draw of each day is limited to free plans; the Study is never offered on days 1-2; the Library is usually not offered on days 1-4; Her Ladyship's Chamber is not offered on days 1-11; the Gallery is not offered on days 1-45 and not from day 363; the Chamber of Mirrors becomes Normal on 8 percent of days from day 10. Plans normally appear once per day; exceptions are the Chamber of Mirrors (duplicates) and room additions from the Schoolhouse or Studio. Repellent removes the room you stand in from the pool for a week.
_source: P1 research 2026-10-31 refs [26][46] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:community-wiki]

One more exception to the once-per-day rule: the Tunnel always draws a Tunnel.
_source: P1 research 2026-10-31 refs [26][46] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Single source -- verify · class:community-wiki]

More day-based draft rules from the same Fextralife Progression page (P2 reached it again; it is the same publication as P1 reference [26], so it adds facts but not a second source): on days 1-2 the Closet never holds the Silver Key, Sledge Hammer, Compass, Lucky Rabbit's Foot or Metal Detector, and the Magnifying Glass is never placed in a room on day 1; on days 1-2 the Master Bedroom and Drafting Studio are usually not offered (95 percent of days); on days 3-7 the Study is Rare. From day 2 the Utility Closet is Commonplace until the West Gate is opened; from day 3 the third floorplan of a draft often turns out to be the Garage once a day; from day 7 the Foundation is Uncommon once Rank 4 is entered (Normal from day 21); from day 17 either the Boiler Room (60 percent) or the Workshop (40 percent) is Normal each day; from day 20 the Library is Normal. Dated events: days 12-16 the Commissary is closed (a red memo); days 20 and 21 hold the Annual Maid's Day Sale (up to 50 percent off). From day 46 the Gallery can be offered (the P1 sentence above says not before day 46).
_source: P2 research 2026-10-31 refs [19] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:community-wiki]

Drafting three rooms within 30 seconds at the start of a run puts the game in a "V mode" (datamined) in which some early-day restrictions are lifted (for example the Tomb can be offered on the very first draft); drafting slowly locks in a beginner difficulty. One TrueTrophies page; no second source found.
_source: P2 research 2026-10-31 refs [1] · capture: browser_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:editorial-en]

The Foundation: once drafted it returns every morning on the same tile. Patch 1.5 made it appear less often on Ranks 2 and 3, and using Repellent before 7 days have passed cannot add it to the pool.
_source: P1 research 2026-10-31 refs [1][26] · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression · missable: no_ [Confirmed: 2 sources, 1 languages]

The daily Dining Room five-day menu cycle and the permanent unlock lists (Studio picks, estate upgrades, rarity changes, upgrade disks, allowance, stars) are the things that do not reset between days; see `items/upgrades.md`.
_source: P1 research 2026-10-31 refs [24][26] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:community-wiki]

Fextralife's wording for a date-bound event: a Christmas tree appears in the Boudoir on days 49, 414, 779, 1144 and 1509; per P2 it holds 2 Ivory Dice and gifts (same Fextralife page).
_source: P1 research 2026-10-31 refs [26] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: easter-egg · spoiler: progression · missable: yes_ [Single source -- verify · class:community-wiki]

## Terms that look alike

> **Cross-system dependency** -- see `dependencies.md` DEP-001.

Shared-name and look-alike pairs found by P1; keep the two sides of each pair separate. Each row hides or shows on its own `tier` value.
_source: P1 research 2026-10-31 refs [24] · capture: derived · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

| Pair | Side A | Side B | Rule | tier |
|---|---|---|---|---|
| Rank versus rarity | Rank is a row of the 9-row grid (Rank 1 south to Rank 9 north) | Rarity is how often a floorplan is drawn (Commonplace / Normal / Uncommon / Rare) | Never call rarity a "tier" without saying so | none |
| Blueprint (menu), Blueprint (room type), Blackprint | The house map and inventory menu, and the roll picked up in the Entrance Hall | The default blue floorplan type; Blackprint is a separate type of ancient floorplan with no colored border | Three different things; wiki.gg also calls the Room Directory's first pages "Blueprints" | none |
| Room Directory versus Mount Holly Directory | The in-game list of every drafted room (open with R or the system menu) | The "Mount Holly Directory" named in an achievement text is the same in-game Directory, not a wiki page | One in-game menu | none |
| Minor keys versus named special keys | Minor keys are a HUD resource, 1 per locked door, reset daily | The Special Keys group on wiki.gg; a Keycard opens security doors, not locked doors | Do not merge; the wikis list some keys under two groups | none |
| Master Bedroom versus Master Key | A Bedroom that exists only in the East Wing | A special key listed as a Showroom item | Different things | none |
| Study versus Study Safe | A Drafting room (gems to redraw) | A safe inside it | Different things | none |
| West Wing Hall, East Wing Hall versus the Wings | Rooms that can only be drafted in one Wing | The Wings are the outer columns of the grid | Rooms versus columns | none |
| Dormitory | A Bedroom-colored room unlocked through the Drafting Studio | none | Counted as a Studio addition and as a Bedroom | progression |
| Guest Bedroom variants | Guest Bedroom | Fextralife also lists "Guess Bedroom" and "Quest Bedroom" among not-listed Bedrooms | Treat as unverified variants | progression |
| Grounds versus house look-alike names | Grounds areas such as the Campsite and the Drive Tunnel | House rooms with similar names (Courtyard, Patio, Terrace, Veranda, the Tunnel floorplan) | The Tunnel floorplan in the house is not the Drive Tunnel on the grounds | late-game |
| Trophy Room versus Trophy Case versus trophies | Trophy Room is a house room | Trophy Case is the display in it; "trophy" is the brass achievement object | Same word, three uses | progression |
| The five "8"s | Room 8, a puzzle room reached through a locked door on Rank 8 | Key 8, Trophy 8, an Office envelope, the eight Outer Rooms | Five unrelated "8"s | late-game |
| Cloister family and the Tomb | Cloister is an ordinary Green Room | Other "Cloister of ..." rooms are different rooms; the Tomb room is not the Catacombs below it | Different rooms despite the shared stem | late-game |
| Room versus organisation | The Foundation is a permanent room with an elevator to the underground | The organisation that inherits the estate if the goal is not found | Different things | story |
| The three "46"s | The real objective room north of the Antechamber | The model house's own room, and the door on the Antechamber's north side | Three referents | story |

_source: P1 research 2026-10-31 refs [2][3][24][26][35][36][37][38][46][47] · capture: web_fetch · confidence: medium · enemy-tier: 3 · puzzle-tier: 3 · category: mainline · spoiler: story_ [Single source -- verify · class:community-wiki]

## Steps

> **Cross-system dependency** -- see `dependencies.md` DEP-034.

Each day starts with 50 steps in the standard mode. Entering any room costs 1 step, including rooms you already visited; steps never drop below 0, and at 0 the day ends where you are. Steps are restored by eating food (apple 2, banana 3, orange 5, cupcake 10) and by entering Bedrooms (+2 per entry). Call It a Day from the system menu or the Blueprint menu also ends the run. When the day ends, the player is returned outside and loses what was collected that run.
_source: P1 research 2026-10-31 refs [5][24] · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 2 sources, 1 languages]

More step sources and sinks: the Guest Bedroom (+10 on first visit), the Master Bedroom (+1 per room in the house on first visit; and +10 tomorrow at day end), the Sauna (+20 tomorrow), the Apple Orchard (+20 every day, permanent); the Gymnasium costs 2 steps per entry while its lights are on, the Weight Room halves your steps once, and Her Ladyship's Chamber costs 10 tomorrow at day end.
_source: P1 research 2026-10-31 refs [24][26][27] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:community-wiki]

Rooms with a clock symbol pay on the next day: the Clock Tower (1 key per such room drafted today), the Morning Room (2 gems), the Sauna (+20 steps), the Freezer (frozen coins and gems return). Day-end rooms: the Master Bedroom (+10 steps tomorrow), the Servant's Quarters (steps halved, 1 Ivory Die), Her Ladyship's Chamber (-10 steps, +1 star).
_source: P1 research 2026-10-31 refs [26] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:community-wiki]

One more day-end room: the Planetarium (+2 stars).
_source: P1 research 2026-10-31 refs [26] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Single source -- verify · class:community-wiki]

A Furnace or Sauna entered after freezing accounts can unfreeze them; go back into the Freezer before the day ends. Latest safe point: before ending the day.
_source: P1 research 2026-10-31 refs [26] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression · missable: yes_ [Single source -- verify · class:community-wiki]

## Resources and key items

The HUD tracks coins, gems, keys and ivory dice; food only adds steps. P1's resource table:

| Resource | Used for | Carries over | tier |
|---|---|---|---|
| Steps | Entering rooms | no | none |
| Gems | Special floorplans (0-5) | no (unless frozen) | none |
| Keys | Locked doors and lockers (1 each) | no | none |
| Coins (gold) | Shops | no (unless frozen) | none |
| Ivory Dice | Redrawing plans | the source says "not confirmed" | none |
| Stars | Constellations (daily effects) | yes | progression |

_source: P1 research 2026-10-31 refs [24] · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Single source -- verify · class:community-wiki]

The wiki's Items page groups "Resource Items" as Coins, Gems, Keys, Food, Ivory Dice and Allowance Token; exact rules for each beyond the table above are in `items/`.
_source: https://blueprince.wiki.gg/wiki/Items · capture: web_fetch · contributor: setup-wizard Stage 0 · confidence: medium · last-verified: 2026-10-31 · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Single source -- verify · class:community-wiki]

Digging needs a Shovel (or a built contraption that digs); each pile can be dug once, and with a Shovel about 6 in 10 digs find something useful. A Rabbit's Foot raises the chance of extra items.
_source: P1 research 2026-10-31 refs [24] · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Single source -- verify · class:community-wiki]

From day 16 a dig can turn up a torn scrap with a contraption idea you have not built (patch 1.6 says the scrap only appears in a save where that contraption is unbuilt).
_source: P1 research 2026-10-31 refs [1][26] · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Confirmed: 2 sources, 1 languages]

## Stars and constellations

Each star count unlocks a constellation (a daily effect): 1 star North Star (1 coin); 2 The Twins (2 trunks at the Entrance); 3 The Slice (3 steps); 4 Diamondus Minor (1 gem); 5 The Southern Cross (4 exit rooms more common); 7 Farmer's Apple (apples +5 steps); 8 Clavis (1 key); 11 Diamondus Major (5 gems); 12 Draxus (dead ends more common); 15 The Sail (the page text is cut off after this entry, so later constellations are a gap). The Observatory is where they are used.
_source: P2 research 2026-10-31 refs [9] · capture: browser_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:editorial-en]

## Terminals

> **Cross-system dependency** -- see `dependencies.md` DEP-023.
> **Cross-system dependency** -- see `dependencies.md` DEP-035.

Terminals sit in several rooms and all of them accept Upgrade Disks. Office terminal: spread coins, payroll. Security terminal: the security-door level (Low or High), unlock on power loss, order an item to the Commissary, and a Keycard System menu with Offline Mode Unlocked. Shelter terminal: a radiation level; above 12 all doors unlock (this needs 5-6 experiment triggers). Laboratory terminal: a daily experiment. The Security terminal and the Utility Closet breaker "Keycard Entry System" are also the two ways TrueTrophies gives to fill every house slot (Security terminal set to High with a keycard, or the breaker off with Offline Mode Unlocked).
_source: P2 research 2026-10-31 refs [9][14] · capture: browser_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:editorial-en]

The Full House goal needs all 43 slots filled in one day (42 if the Foundation is already built), per TrueAchievements. P1's sources say every open slot of the 45-slot house; 43 equals 45 less the always-present Entrance Hall and Antechamber (the guide's own arithmetic, not a source statement).
_source: P2 research 2026-10-31 refs [14] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression · achievement: full_house_trophy · achievement-hidden: no · trigger_type: mastery · missable: no_ [Single source -- verify · class:editorial-en]

## Soft-locks, dead ends and patch fixes

> **Cross-system dependency** -- see `dependencies.md` DEP-025.
> **Cross-system dependency** -- see `dependencies.md` DEP-035.

Design note: this section holds the risks and the "not missable" findings; `sections/missables.md` is the aggregate of every claim tagged missable, and the two are meant to stay separate.

Runs full of dead ends, or with no keys left to progress, happen through randomness and the only recovery named is starting again the next day.
_source: P2 research 2026-10-31 refs [1] · capture: browser_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Single source -- verify · class:editorial-en]

The Foundation, if drafted where its back cannot be reached, is wasted for that day. The Archives hides one of the three draft options for the rest of the run ("avoid the Archives"); building the Freezer without the Furnace first risks locking gems and ending a run; the Furnace raises Red Room odds. An Upgrade Disk can be lost if no Office can be drafted to reach a terminal.
_source: P2 research 2026-10-31 refs [1][4][14] · capture: browser_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:editorial-en]

Missable items: none found in the pages P2 read. No TrueTrophies, TrueAchievements, Fextralife or wiki.gg page read calls any item permanently missable; community fresh-save and import reports (Reddit) were not read, so "none found" covers those pages only.
_source: P2 research 2026-10-31 refs [4][13][15][19][23] · capture: browser_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression · missable: no_ [Single source -- verify · class:editorial-en]

An input problem from April 2025 (before remapping existed), in a late underground area: on an AZERTY keyboard the Basement Jacklift carts could not be pushed with Z; W or the arrow keys push them (W and S push and pull the carts). A Steam user reported two ruined runs, and the Steam-forum developer account said W instead of Z allows pushing and that the report was passed to the team. Patch 1.7 added keyboard remapping.
_source: P2 research 2026-10-31 refs [7][8][20] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Single source -- verify · class:forum]

Fixed risks: patch 1.7 (console update 2.002) added safety checks against reported soft locks in the UI system, and the console notes list a fix for a phantom Upgrade Disk and for terminal-access issues. Two news pages (Nintendo Everything, MP1st) describe the 1.7 / 2.002 notes, both through page summaries rather than page text.
_source: P2 research 2026-10-31 refs [17][18] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Confirmed: 2 sources, 1 languages]

## Daily reset, carry-over and saves

Each day the drafted rooms, inventory, steps (back to 50), gems, keys and coins reset, and floorplans added for the day leave the pool. Saves: 4 slots, saved at the end of each day (Save & Continue / Save & Quit); a manual "restore from backup" exists (patch 1.6) and the Profiles menu can restore all four slots.
_source: P1 research 2026-10-31 refs [1][5][24][26] · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 4 sources, 1 languages]

Carried over: stars, permanent changes (see `items/upgrades.md`), allowance, trophies, and the Directory records; coins and gems frozen in the Freezer come back next day; the Moon Pendant lets 2 items carry over. The Entrance Letter sets three ground rules: no outside tools, nothing found may leave the estate, no overnight stay.
_source: P1 research 2026-10-31 refs [24][26] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:community-wiki]

Some permanent items and upgrades (extra steps, gems or coins) carry over between runs; the full list and how each is obtained are in `items/upgrades.md`.
_source: https://en.wikipedia.org/wiki/Blue_Prince · capture: web_fetch · contributor: setup-wizard Stage 0 · confidence: medium · last-verified: 2026-10-31 · enemy-tier: 0 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:editorial-en]

## The goal

The store description presents finding the rumored Room 46 as the goal; failing within a day means starting over the next day.
_source: https://store.steampowered.com/app/1569580/Blue_Prince/ ; https://en.wikipedia.org/wiki/Blue_Prince · capture: web_fetch · contributor: setup-wizard Stage 0 · confidence: high · last-verified: 2026-10-31 · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 2 sources, 1 languages]

## Optional goals that point at earlier rooms (progression)

> **Cross-system dependency** -- see `dependencies.md` DEP-010.
> **Cross-system dependency** -- see `dependencies.md` DEP-018.
> **Cross-system dependency** -- see `dependencies.md` DEP-023.

Draft a room in every open slot of the 45-slot house in one day; start toward the bottom-right corners, avoid dead ends, and extra steps help (the Sauna). Not missable.
_source: P1 research 2026-10-31 refs [41][42][43][44] · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression · achievement: full_house_trophy · achievement-hidden: no · trigger_type: mastery · missable: no_ [Confirmed: 4 sources, 1 languages]

Complete the in-game Directory (about 110 rooms; each must be drafted; some sit behind puzzles, Studio picks, found floorplans or outer rooms). A patch 1.7 bug could fail to award the trophy; it waits in the Entrance Hall if completed (patch 1.7.1).
_source: P1 research 2026-10-31 refs [1][25][41][42][43][49] · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression · achievement: explorers_trophy · achievement-hidden: no · trigger_type: collection · missable: no_ [Confirmed: 5 sources, 1 languages]

Draft 20 dead ends in a single day; the prize arrives mailed (a Mail Room package with 200 gold) days later alongside the "Drafting Strategy Sweepstakes" prize, which is the same event seen from the other end. The Draxus constellation (12+ stars) and the Chamber of Mirrors' duplicates help.
_source: P1 research 2026-10-31 refs [41][42][43][44] · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: trophy_of_drafting · achievement-hidden: yes · trigger_type: mastery · missable: no_ [Confirmed: 4 sources, 1 languages]

P2 (TrueAchievements walkthrough page 5, reference [14]): the Outer Room counts as a dead end and the Bunk Room as 2; the trophy is collected from the next day's Mail Room, whereas P1's guides say it arrives by mail days later. The delivery timing is unreconciled.
_source: P2 research 2026-10-31 refs [14] · capture: web_fetch · confidence: low · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: trophy_of_drafting · achievement-hidden: yes · trigger_type: mastery · missable: no_ [Contradicted across sources -- see notes]

Draft the Schoolhouse (an outer room that adds eight Classroom plans), draft the Classroom from the Drafting Studio, then draft all Classrooms to open the final exam and ace it (one source says 100 percent); answers are locked in. The question count is disputed: the P1 guides say 40 questions, while P2's TrueTrophies and TrueAchievements pages (one publisher network) say 46 (46 of 46 is an A+, 45 of 46 an A, and an A or A+ gives the trophy). The exam's rules and answer list are in `puzzles/final_exam.md`.
_source: P1 research 2026-10-31 refs [41][42][43][45] and P2 research 2026-10-31 refs [10][14] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: diploma_trophy · achievement-hidden: yes · trigger_type: mastery · missable: no_ [Contradicted across sources -- see notes]

## Rules that apply late in the game (late-game)

> **Cross-system dependency** -- see `dependencies.md` DEP-004.
> **Cross-system dependency** -- see `dependencies.md` DEP-009.
> **Cross-system dependency** -- see `dependencies.md` DEP-012.
> **Cross-system dependency** -- see `dependencies.md` DEP-017.
> **Cross-system dependency** -- see `dependencies.md` DEP-019.
> **Cross-system dependency** -- see `dependencies.md` DEP-027.
> **Cross-system dependency** -- see `dependencies.md` DEP-028.
> **Cross-system dependency** -- see `dependencies.md` DEP-031.
> **Cross-system dependency** -- see `dependencies.md` DEP-032.

Shop stock and prices: `items/support_items.md` section "Shops".

After the first click on the door marked 46 the ending film and credits play (skippable) and the day summary appears; the next morning a trophy and a letter wait in the Entrance Hall, and the door then opens into the room itself. Reaching it is an achievement trigger and is not missable.
_source: P1 research 2026-10-31 refs [37][41][42][43] · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: inheritance_trophy · achievement-hidden: no · trigger_type: progression · missable: no_ [Confirmed: 4 sources, 1 languages]

Changes after the first arrival: the Gift Shop joins the draft pool; a Major key can be a Safe Deposit Key when the Vault is drafted; a Sanctum Key can appear in the Music Room; dartboard prizes improve (20 percent chance of the Secret Garden Key); the Bookshop appears often in the Library's third slot with the Hall Pass; Key 8 and a Safe Deposit Key can appear in the Lost & Found after day 364.
_source: P1 research 2026-10-31 refs [37] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Single source -- verify · class:community-wiki]

Eight Sanctum Keys open eight doors in the Inner Sanctum; the first key is earned by reaching the goal room a second time after the credits (the key sites: the goal room, the Safe House underground, the Clock Tower's grandfather-clock drawer when all eight clocks are right, a trunk in the Reservoir underground, the Throne Room, Vault box 370 or the Watch Tower, the Mechanarium, the Music Room after the first arrival). Each of the eight realm sigils unlocks when four traits (color, society, travel, weather) are right; the book Realm & Rune (50 gold at the Bookshop) explains reading them. Unlocking all eight sigils gives the trophy, which spawns in the Inner Sanctum foyer. The rule for reading a sigil's four traits is not reproduced by any source read; P2's text descriptions of the eight sigils and its list of the eight key sites are in `puzzles/sanctum_keys.md`.
_source: P1 research 2026-10-31 refs [37][41][43] · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: trophy_of_sigils · achievement-hidden: yes · trigger_type: collection · missable: no_ [Confirmed: 3 sources, 1 languages]

The trophy case: completing the Trophy Case in the Trophy Room with the other 15 trophies awards the last trophy. Challenge-mode and fastest-run trophies need separate saves, which are merged into the main save through the admin function of a terminal in the Blackbridge Grotto (the passwords are in `puzzles/secret_puzzles.md`).
_source: P1 research 2026-10-31 refs [25][41][42][43][45] · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: trophy_of_trophies · achievement-hidden: no · trigger_type: collection · missable: no_ [Confirmed: 5 sources, 1 languages]

Late-game random-number tools: the Observatory 50-star reroll (a star per reroll), the red crown from the Closed Exhibit (a redraw if no red room is present), the Conservatory's and the Gear Wrench's rarity changes, the Chamber of Mirrors' duplicates, and the Knight chess power's Armory (The Axe frees a room's gem cost permanently).
_source: P1 research 2026-10-31 refs [26][48][53] · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Confirmed: 3 sources, 1 languages]

The Wikipedia article states the post-game contains puzzles that, as of November 2025, the community had not solved. Reddit's three-layer reading of the game puts permanent upgrades and the goal room first, the Sigils and other trophies second, and the secrets beyond (ending at two sealed doors) third, and says everything past about step 13 gives no trophy or recognition.
_source: P1 research 2026-10-31 refs [5][53] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Single source -- verify · class:forum]

## Late-game story content (story)

Inside the goal room: the Crown of the Blueprints, the first Sanctum Key, a note with a rhyme hinting at the eight keys, a framed world map that reveals the Deed and the Will when solved; a desk drawer holds a ransom note. The will says that if Simon fails the estate goes to the Orindian Heritage Foundation and the house is sealed.
_source: P1 research 2026-10-31 refs [37] · capture: web_fetch · confidence: medium · enemy-tier: 3 · puzzle-tier: 3 · category: lore · spoiler: story_ [Single source -- verify · class:community-wiki]

The Throne of the Blue Prince: the Throne Room floorplan from the Orindian Ruins on the grounds, the Crown from the goal room, the Cursed Effigy from the Shrine trunk (break it with the Morning Star, a Sledge Hammer or a Power Hammer; it curses you for 2 days), the Royal Scepter set to Blueprints (from the Treasure Trove); entering the Throne Room plays a cutscene, then it becomes a Blueprint room, and 8 Blueprint rooms in a row unlock the "Seal Unlocked" state permanently. The Atelier (through the Secret Passage from the outer door, watered with still water from the Watering Can) holds a model house whose own Room 46 holds a book. Books: one in the Nursery and Master Bedroom, a draft in a Catacomb stone pillar, another draft in a blue box in Room 8 of the Drive Tunnel.
_source: P1 research 2026-10-31 refs [36][37] · capture: web_fetch · confidence: medium · enemy-tier: 3 · puzzle-tier: 3 · category: lore · spoiler: story_ [Single source -- verify · class:community-wiki]

## Other late-game rules (late-game)

> **Cross-system dependency** -- see `dependencies.md` DEP-012.
> **Cross-system dependency** -- see `dependencies.md` DEP-013.
> **Cross-system dependency** -- see `dependencies.md` DEP-014.
> **Cross-system dependency** -- see `dependencies.md` DEP-015.
> **Cross-system dependency** -- see `dependencies.md` DEP-016.
> **Cross-system dependency** -- see `dependencies.md` DEP-033.

Bequest Mode is the standard mode, 50 steps per day. Other modes are unlocked after the first arrival at the goal room and chosen when starting a new save.
_source: P1 research 2026-10-31 refs [24][26][28][41] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Single source -- verify · class:community-wiki]

Dare Mode: unlocked by buying the Swim Bird Plushie in the Mount Holly Gift Shop (110 coins); a Dare Letter appears in the Entrance Hall, one new dare is added each day until four (or up to eight in the longer letter) are revealed, and breaking any one fails the challenge. The trophy needs the goal room to be reached after four dares are revealed and none broken; breaking a dare means starting a new save in Dare Mode. The wiki lists 24 dares in exact wording (examples: never touch the center door in the Entrance Hall; always pick the first floorplan in the Entrance Hall; always have at least 20 steps; never draft Den again; end each day with 0 keys, 0 gems and 0 coins).
_source: P1 research 2026-10-31 refs [28][41][42][43] · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: dare_bird_trophy · achievement-hidden: yes · trigger_type: branch · genre: roguelike · missable: yes_ [Confirmed: 4 sources, 1 languages]

Dare Mode details from P2 (TrueTrophies and TrueAchievements, one publisher network): reach the goal room once, build the Mount Holly Gift Shop (available only after that), buy the Swim Bird Plushie for 110 gold, choose Call it a Day, then Save and Quit and pick Dare Mode on a new save. At least 4 dares must be active (day 4, or a Laboratory experiment for extra dares early); dares accumulate to a maximum of 8; breaking one loses the day, which restarts with the same dares; the goal room cannot be reached before four dares. A new save starts with no floorplans, Allowance tokens or permanent upgrades. One row says "no puzzle first" is needed before buying the plushie, while the other needs the goal room reached first; the wording is not reconciled.
_source: P2 research 2026-10-31 refs [11][15] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: dare_bird_trophy · achievement-hidden: yes · trigger_type: branch · genre: roguelike · missable: yes_ [Single source -- verify · class:editorial-en]

The Dare list as one TrueTrophies walkthrough gives it (it says it lists 28 Dares but "could not find a complete list", and this result's row names 24, which is also the count on P1's Fextralife page; none verified against the game): leave the Mt. Holly Blueprint on the Entrance Hall table; never draft all 5 rooms in a rank; open each locked trunk each day (the Garage trunk counts); spend 30 seconds in the Lavatory each day; draft six different room colours per day; always draft a Red Room when one is drawn; end each day with 0 keys, 0 gems and 0 coins; never enter a room more than 3 times; never exit via the Entrance Hall; carry no more than two special items; never ride elevators (the Foundation, the Chamber of Mirrors, the Gas Elevator); never eat fruit; never draft from a south-facing door; make exactly 1 purchase or trade in each shop drafted; end each day with at least 1 gem; draft the most expensive floorplan when you have 3 or more gems; always have at least 20 steps; press only the correct numbers in the Billiard Room; use at most one switch or button per Utility Closet; open an empty box in each Parlor; never step in the Pool; never touch the Entrance Hall centre door; never draft the Den again; always pick the first floorplan when drafting in the Entrance Hall. In the author's own run the Den and the Aquarium were instant-loss rooms.
_source: P2 research 2026-10-31 refs [11] · capture: browser_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: dare_bird_trophy · achievement-hidden: yes · trigger_type: branch · genre: roguelike · missable: yes_ [Single source -- verify · class:editorial-en]

Curse Mode: starts each day cursed with 13 steps; the Apple Orchard gives no benefit in it. Unlock chain (three guides agree, plus a fourth): draft the Shrine Outer Room and donate gold then take it back (it becomes cursed); buy a small red box for 13 gold at the Gift Shop; break it with a Sledgehammer at the Shrine statue; pick up the Effigy, which unlocks the mode and curses the player for 2 days on that save. The trophy needs the goal room reached in this mode on a new save.
_source: P1 research 2026-10-31 refs [41][42][43][45][56] and P2 research 2026-10-31 refs [3][15] · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: cursed_trophy · achievement-hidden: yes · trigger_type: branch · genre: roguelike · missable: no_ [Confirmed: 4 sources, 1 languages]

How the Gift Shop comes to sell the red box (the Cursed Coffer, 13 gold) has two routes in the sources. Stealing coins from the Shrine to gain the Cursed effect puts the coffer on sale (P1's guides and P2's TrueTrophies). The other route is a book: the Bookshop (only buildable from the Library; rare) sells "The Curse of Black Bridge" for 40 gold; the next day the Library is built and the book requested with the document on the table; the day after it is read. P1's TheGamer guide named the 40-gold Bookshop item as the unlock; P2's TrueTrophies and TrueAchievements describe that book as a step inside the same chain, not a competing item. That resolves P1's disagreement only on the evidence of two pages from one publisher network and without re-reading TheGamer, so the resolution is medium confidence.
_source: P1 research 2026-10-31 refs [45] and P2 research 2026-10-31 refs [3][15] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Confirmed: 2 sources, 1 languages]

Curse Mode penalties (P2, two pages of one network): each day starts with 13 steps; a Bedroom costs 1 step, a Hallway 1 key, a Green Room 1 gem, a Shop 1 coin, a Red Room one of each; multicolour rooms apply per colour (the Aquarium loses two of everything); the Orchard is burned down (no +20 steps); the Shrine is caved in or blocked by debris if drafted (no Blessing of the Monk; no Royal Scepter that way, though the chess puzzle gives the same effect). Still possible in the mode: Upgrade Disks, stars, Allowance Tokens and all other permanent upgrades. The two pages word the Shrine penalty differently.
_source: P2 research 2026-10-31 refs [3][15] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Single source -- verify · class:editorial-en]

Reach the goal room within day 1 of a fresh save (practically needs early luck with the Foundation or Secret Garden; missable the moment day 1 ends on that save, restart if the Foundation does not appear).
_source: P1 research 2026-10-31 refs [37][41][42][43] · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: day_one_trophy · achievement-hidden: yes · trigger_type: mastery · missable: yes_ [Confirmed: 4 sources, 1 languages]

Reach the goal room in under one real hour from the start of a fresh save (the limit is real time, not in-game time; where the hour starts is disputed in the next paragraph); missable once an hour has passed on that save.
_source: P1 research 2026-10-31 refs [37][41][43] and P2 research 2026-10-31 refs [1][12][21] · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: trophy_of_speed · achievement-hidden: yes · trigger_type: mastery · missable: yes_ [Confirmed: 5 sources, 1 languages]

Where the hour starts is disputed. A Steam thread (P2) says it is one hour of real time from the start of Day 1, not in-game time and not necessarily the start of one run (a 40-minute trip with the in-game clock at 8:40 gave nothing); TrueAchievements says one hour of real time; TrueTrophies says Day One takes about 30 minutes and failing the hour means doing it again; one poster in the Steam thread disagrees about "an hour of a single run". P1's patch 1.7.3 note says the timer does not start until the player begins moving on day one. The start point and the meaning of a single run are unresolved.
_source: P1 research 2026-10-31 refs [1] and P2 research 2026-10-31 refs [1][12][21] · capture: web_fetch · confidence: low · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: trophy_of_speed · achievement-hidden: yes · trigger_type: mastery · missable: yes_ [Contradicted across sources -- see notes]

Day One and 1 Hour route notes (P2, TrueTrophies page 8): a Day One run is about 30 minutes and the Trophy of Speed run is the same attempt under an hour; the trophies are collected on the Entrance table the next day. Make a copy of the save after the first permanent unlocks so repeated failed Day One attempts start from a stocked save, and do not delete the main save. The special start state: drafting 3 rooms within 30 seconds puts the game in the "V mode" described under the early-game rules, in which some early restrictions are lifted. The levers that open the way to the goal room have their own routes (`puzzles/antechamber_levers.md`).
_source: P2 research 2026-10-31 refs [1] · capture: browser_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game · achievement: day_one_trophy · achievement-hidden: yes · trigger_type: mastery · missable: yes_ [Single source -- verify · class:editorial-en]

Patch 1.7.3 notes on the challenge modes: a Dare Mode bug that sometimes failed a red-rooms dare when using the Secret Garden Key or a similar special key (or a berry) while drafting was fixed; the "been cursed" flag now sets correctly; the in-game timer used by the dare, curse and speed challenges no longer starts until the player begins moving on day one.
_source: P1 research 2026-10-31 refs [1] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Single source -- verify · class:official-pr]

Challenge-mode saves (P2, TrueTrophies and TrueAchievements: one publisher network): the challenge modes are played in separate save slots; the challenge trophy is collected on the Entrance table the next day, then the main save is loaded and the trophy imported through the Administrator Terminal in the Blackbridge Grotto. A new save offers Dare or Curse once unlocked, each starting with no floorplans, Allowance tokens or permanent upgrades. The profile holds only 4 saves ("you may have to eventually delete one"), so trophies must be imported before a save is deleted; the Profiles menu can restore all four slots from a backup, overwriting all four. The Platinum needs all trophies on the main save. P2's console notes also mention a fix for challenge-save loading in Bequest mode (details unreadable). One of the page counts says "3 sources"; two of those pages are TrueAchievements.
_source: P2 research 2026-10-31 refs [1][3][12][15][17][19] · capture: web_fetch · confidence: medium · enemy-tier: 2 · puzzle-tier: 2 · category: mainline · spoiler: late-game_ [Single source -- verify · class:editorial-en]

## Versions and platforms

Latest PC patch confirmed: 1.7.3 on 2026-09-16 (Steam, the developer's X post, wiki.gg, Fextralife's update history and Steam's news feed agree). No 1.8 or 1.9 post exists; patch 1.10 was announced (Kotaku, 2026-04-29: a final update adding the missing arcade game Digiblocks, a cat, more cinematics and a few other things) and had not shipped as of 2026-10-21 per Fextralife (2026-10-08 per Steam's feed).
_source: P1 research 2026-10-31 refs [1][7][8][9][10] · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 4 sources, 1 languages]

Console numbering: PC 1.7 = console update 2.002 (2026-05-06, PS5), PC 1.7.1 = 2.003 (2026-05-19, PS5 and Xbox), PC 1.6 = 2.001 (2025-10-22); consoles lagged PC by roughly a week for 1.7 and 1.7.1 and about three weeks for 1.6. Console builds of 1.7.2 and 1.7.3 and the Switch 2 version number were not found (the developer's 2026-09-16 post says console rollout "soon").
_source: P1 research 2026-10-31 refs [1][9][11][12][63] · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 3 sources, 1 languages]

Release dates: Windows, PS5 and Xbox Series X|S 2025-04-10; macOS 2025-09-29 (patch 1.6); Switch 2 2026-03-03, with Patch 1.7 reaching it around 2026-05-21/22. Steam Deck Verified since 2026-06-03. Fextralife also lists a 1.6.1 "Emergency Security Update" (2025-10-08) that wiki.gg's patch page does not.
_source: P1 research 2026-10-31 refs [1][5][8][13][14][15][16] · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 5 sources, 2 languages]

Language and developer: the game ships English-only (Steam, Wikipedia citing Polygon, VGTimes); the developer Dogubomb is based in Hollywood, California, per the publisher's page. Save handling: the PS5 build had a save "rollback" bug (1.4.5) and its save architecture was updated for size limits in 1.7; Steam Cloud is on PC.
_source: P1 research 2026-10-31 refs [1][5][6][9][58][62] · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Confirmed: 4 sources, 2 languages]

## Combat

No combat system or enemies appeared in any page read; the owner states the game has none. Still unverified (the P1 result marks this a hypothesis).
_source: P1 research 2026-10-31 refs [3][37][26][35][48] · capture: web_fetch · confidence: low · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_ [Hypothesis -- unverified]

## Sources

P1 research result numbering (the references this file uses are listed below).

- [1] https://blueprince.wiki.gg/wiki/Patch_1.7 ; [2] https://blueprince.wiki.gg/wiki/Room_Directory ; [3] https://blueprince.wiki.gg/wiki/Items
- [5] https://en.wikipedia.org/wiki/Blue_Prince ; [6] https://store.steampowered.com/app/1569580/Blue_Prince/ ; [7] Steam news feed for app 1569580
- [8] https://blueprince.wiki.fextralife.com/Update_History ; [9] https://x.com/dogubomb/status/2100133069835362398 ; [10] https://kotaku.com/blue-prince-color-blind-accessibility-2000691703
- [11] https://mp1st.com/title-updates-and-patches/blue-prince-accessibility-update-2-002-adds-new-features-fixes ; [12] https://mp1st.com/title-updates-and-patches/blue-prince-update-2-003-released-on-ps5-xbox-series-for-hotfix-1-7-1
- [13] https://nintendowire.com/news/2026/05/20/blue-princes-accessibility-update-will-be-heading-to-switch-2-soon/ ; [14] https://www.nintenderos.com/nintendo-switch-2/nintendo-switch-2-acaba-de-recibir-la-gran-actualizacion-de-accesibilidad-de-blue-prince/ (Spanish)
- [15] https://insider-gaming.com/nintendo-switch-2-gets-blue-prince-today-with-mouse-controls/ ; [16] https://www.shacknews.com/article/148117/blue-prince-nintendo-switch-2-release
- Fextralife pages (blueprince.wiki.fextralife.com): [24] Game_Mechanics ; [25] Achievements ; [26] Progression ; [27] Estate_Upgrades ; [28] Dare_Mode ; [35] Puzzles ; [36] Locations ; [37] Endings ; [38] Glossary ; [46] Rooms ; [47] Room_Types ; [48] Shops
- [41] https://gamerant.com/blue-prince-achievement-guide-get-all-trophies-complete-trophy-walkthrough/ ; [42] https://www.fdaytalk.com/blue-prince-trophy-guide/ ; [43] https://nerdflakes.com/blue-prince-achievement-guide-complete-100-roadmap/ ; [44] https://insider-gaming.com/complete-blue-prince-achievements-list/ ; [45] https://www.thegamer.com/blue-prince-achievement-trophy-guide-tips-unlock/
- [49] https://www.trueachievements.com/game/Blue-Prince/achievements ; [51]-[53] Reddit r/BluePrince threads (2025-04 to 2025-05) ; [56] https://www.truetrophies.com/game/Blue-Prince/walkthrough/2 ; [58] https://vgtimes.ru/guides/124101-kak-ustanovit-russkiy-yazyk-v-blue-prince.html (Russian) ; [62] https://rawfury.com/games/blue-prince ; [63] https://mp1st.com/title-updates-and-patches/blue-prince-new-update-2-001-patch-1-6-console-fixes

## Sources (P2)

P2 research result numbering (the references this file uses are listed below).

- TrueTrophies walkthrough (i2.truetrophies.com/game/Blue-Prince/walkthrough/): [1] page 8 ; [3] page 7 ; [4] page 11 ; [9] page 13 ; [10] page 4 ; [11] page 6
- TrueAchievements walkthrough (www.trueachievements.com/game/Blue-Prince/walkthrough/): [12] page 2 ; [13] page 4 ; [14] page 5 ; [15] page 7
- [7] https://caniplaythat.com/2026/04/29/blue-prince-patch-1-7-introduces-long-awaited-accessibility-features/ ; [8] https://ingamenews.com/games/blue-prince/guides/how-to-configure-motion-color-and-input-accessibility/ ; [17] https://nintendoeverything.com/blue-prince-accessibility-update-out-now-patch-notes-new-features-included/ (page summary) ; [18] https://mp1st.com/title-updates-and-patches/blue-prince-accessibility-update-2-002-adds-new-features-fixes (page summary)
- [19] https://blueprince.wiki.fextralife.com/Progression (edited 2026-10-22; folded blocks not readable) ; [23] https://blueprince.wiki.gg/wiki/Shrine (edited 2026-09-17)
- [20] https://steamcommunity.com/app/1569580/discussions/0/830459290005298028 ; [21] https://steamcommunity.com/app/1569580/discussions/0/599650254291234651
