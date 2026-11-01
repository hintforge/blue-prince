# Blue Prince -- Achievements

**status:** research-integrated <!-- scaffold | research-integrated | live-observed | reconciled -->
**last_reconciled:** 2026-10-31
**stub_source:** Steam (names and hidden flags as reproduced by VGTimes and Destructoid at Stage 0)
**stub_fetched:** 2026-10-31
**stub_count:** 16
**recount:** re-run at the P2 ingestion (2026-10-31): Steam global-achievements page, partial -- 5 of 16 names seen (the page states 16 achievements, 5 visible and 11 hidden, and names only the 5; fetched 2026-10-31); Xbox/Windows list on TrueAchievements, full -- 16 of 16 names seen (fetched again 2026-10-31 through a headless browser, verdict ok; page states 16 achievements worth 1,000 Gamerscore); PlayStation list (17 trophies, one extra platinum) was read by the P1 research on 2026-10-31 and not re-fetched; P2 saw the PlayStation platinum name only on a TrueTrophies page
**coverage:** 16 of 16 resolved at paragraph level from guides and wikis; name set verified against the live Xbox/Windows list (16 of 16) and partially against Steam (5 of 16); the completeness check was re-run at P2

This file is the corpus's single source of truth for "what achievements does this game have, and what do I need to do for each one." The reader treats it as authoritative for trigger conditions, point-of-no-return windows and missability. Hidden achievements (`hidden: yes`) keep their name here but the reader gates the heading until the dials allow it. Triggers are paraphrased, never the platform's description text. All 16 triggers come from guides and wikis dated 2025-04 or later (one undated); only the 5 non-hidden achievements have public Steam conditions, so version changes after patch 1.6 may not be reflected. Each entry's tiers are the strictest of its name and its trigger.

Platform differences (PS5 and Xbox lists, as read by P1): the Xbox/Windows list has the same 16 names worth 1,000 Gamerscore. The PlayStation 5 list has 17 trophies (8 silver, 8 gold, 1 platinum): the same 16 names plus a platinum, "Case Closed", for completing the Trophy Case; on that list the case-completing trophy's description reads "Collect all 16 trophies" instead. The Switch 2 list was not found.
_source: P1 research 2026-10-31 refs [49][50] · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_ [Single source -- verify · class:editorial-en]

## Progression

### Inheritance Trophy

- **id:** inheritance_trophy
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Reach the goal room; every player who finishes gets it.
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none beyond reaching the goal room
- **vector-binding:** `mechanics.md` section "Rules that apply late in the game (late-game)"
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [37][41][42][43]; Steam public conditions exist for this one (page [25])
- **notes:** Delivered to the Entrance Hall the morning after. Confirmed: 4 sources.

## Branch

### Dare Bird Trophy

- **id:** dare_bird_trophy
- **hidden:** yes
- **trigger_type:** branch
- **genre:** roguelike
- **trigger:** Reach the goal room in the dare challenge mode after four dares are revealed and none is broken.
- **missable:** yes (breaking any dare on that save)
- **ponr-window:** until the first dare is broken on that save; then start a new save in the mode
- **prereqs:** the mode is unlocked after the first arrival at the goal room, bought in the Gift Shop; a new save is started in the mode (P2: it begins with no floorplans, tokens or permanent upgrades, and needs at least 4 dares active)
- **vector-binding:** `mechanics.md` section "Other late-game rules (late-game)"
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [28][41][42][43]; P2 research 2026-10-31 refs [11][15]
- **notes:** Non-default mode choice, so branch rather than mastery. Confirmed: 4 sources. P2 adds that up to 8 dares can be active and that the dare list's size (24 or 28) is unreconciled.

### Cursed Trophy

- **id:** cursed_trophy
- **hidden:** yes
- **trigger_type:** branch
- **genre:** roguelike
- **trigger:** Reach the goal room in the cursed challenge mode (13 steps a day).
- **missable:** no (a new save is needed)
- **ponr-window:** n/a
- **prereqs:** unlocking the mode; P2 reads the guides' two unlock descriptions as one chain with two routes to the Gift Shop's coffer
- **vector-binding:** `mechanics.md` section "Other late-game rules (late-game)"
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [41][42][43][45][56]; P2 research 2026-10-31 refs [3][15]
- **notes:** The trigger is confirmed by 3 sources. The unlock-item disagreement is resolved in P2 at medium confidence (two pages of one publisher network; the earlier guide was not re-read), see `limitations.md`.

## Mastery

### Day One Trophy

- **id:** day_one_trophy
- **hidden:** yes
- **trigger_type:** mastery
- **genre:** roguelike
- **trigger:** Reach the goal room within the first day of a fresh save.
- **missable:** yes (per save)
- **ponr-window:** the end of day 1 on that save; restart if the early rooms do not line up
- **prereqs:** a fresh save
- **vector-binding:** `mechanics.md` section "Other late-game rules (late-game)"
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [37][41][42][43]; P2 research 2026-10-31 refs [1]
- **notes:** Practically needs early luck. Confirmed: 4 sources. P2 (TrueTrophies, single source) says a Day One run takes about 30 minutes and advises copying the save after the first permanent unlocks so a failed attempt can be repeated.

### Trophy of Speed

- **id:** trophy_of_speed
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Reach the goal room in under one real hour from the start of a fresh save.
- **missable:** yes (per save; one source says nothing is permanently missable)
- **ponr-window:** one real hour after the save starts
- **prereqs:** a fresh save
- **vector-binding:** `mechanics.md` section "Other late-game rules (late-game)"
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [37][41][43]; P2 research 2026-10-31 refs [1][12][21]
- **notes:** The limit is real time, not in-game time. Confirmed: 5 sources. Where the hour starts and whether it must be a single run is disputed (P2 forum thread against P1's note about when the timer starts); see `limitations.md`.

### Full House Trophy

- **id:** full_house_trophy
- **hidden:** no
- **trigger_type:** mastery
- **trigger:** Fill every open slot of the house with a drafted room within a single day.
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `mechanics.md` section "Optional goals that point at earlier rooms (progression)"; plan in `items/builds.md`
- **enemy-tier:** 1
- **puzzle-tier:** 1
- **spoiler:** progression
- **source:** P1 research 2026-10-31 refs [41][42][43][44]
- **notes:** Public Steam condition exists. Confirmed: 4 sources. P2 (TrueAchievements): 43 slots must be filled (42 if the Foundation is already built), which equals the 45-slot house less the two fixed rooms.

### Trophy of Drafting

- **id:** trophy_of_drafting
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Draft 20 dead ends in a single day.
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `mechanics.md` section "Optional goals that point at earlier rooms (progression)"
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [41][42][43][44]; P2 research 2026-10-31 refs [14]
- **notes:** P1: arrives by mail days later; P2 (TrueAchievements): collected from the next day's Mail Room; the timing is unreconciled. The console lists describe it as winning a sweepstakes, which is the same event. Mastery over threshold because the count is within one day. Confirmed: 4 sources.

### Trophy of Wealth

- **id:** trophy_of_wealth
- **hidden:** no
- **trigger_type:** mastery
- **trigger:** Buy out the whole Showroom and then the final item, needing about 300 coins in one run (P2: 240 to 320, or 120 with a constellation buff).
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `items/support_items.md` section "Shops"
- **enemy-tier:** 1
- **puzzle-tier:** 1
- **spoiler:** progression
- **source:** P1 research 2026-10-31 refs [25][41][42][43][48]
- **notes:** Public Steam condition exists. Mastery over collection because of the single-run coin target. Confirmed: 5 sources.

### Diploma Trophy

- **id:** diploma_trophy
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Draft all the Classrooms and ace the final exam (P1: 40 questions; P2: 46 questions, an A or A+ is needed).
- **missable:** no (answers are locked in once given; retry behavior is not stated)
- **ponr-window:** retry behavior not stated
- **prereqs:** drafting the Schoolhouse and the Classroom
- **vector-binding:** `mechanics.md` section "Optional goals that point at earlier rooms (progression)"
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [41][42][43][45]; P2 research 2026-10-31 refs [10][14]
- **notes:** P1 did not reproduce the exam answers; P2 did, and they are held at the story tier in `puzzles/final_exam.md`. The achievement itself is confirmed by 4 sources; the question count (40 against 46) is contradicted.

## Collection

### Explorer's Trophy

- **id:** explorers_trophy
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Complete the in-game Directory of about 110 rooms.
- **missable:** no (a patch 1.7 bug could fail to award it; it waits in the Entrance Hall)
- **ponr-window:** n/a
- **prereqs:** rooms behind puzzles, Studio picks, found floorplans and outer rooms
- **vector-binding:** `mechanics.md` section "Optional goals that point at earlier rooms (progression)"; room list in `sections/rooms.md`
- **enemy-tier:** 1
- **puzzle-tier:** 1
- **spoiler:** progression
- **source:** P1 research 2026-10-31 refs [1][25][41][42][43][49]; P2 research 2026-10-31 refs [14]
- **notes:** Public Steam condition exists. Confirmed: 5 sources. P2 says some of the rooms it needs sit behind later content; those requirements are held at the late-game tier in the claims carrying this achievement id (`items/support_items.md`, `items/upgrades.md`).

### Trophy of Invention

- **id:** trophy_of_invention
- **hidden:** yes
- **trigger_type:** collection
- **trigger:** Build all eight Workshop contraptions.
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** the items for each recipe
- **vector-binding:** `items/support_items.md` section "Contraption recipes (Workshop)"
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [41][42][43][44]
- **notes:** Duplicates do not count. Confirmed: 4 sources.

### Trophy of Sigils

- **id:** trophy_of_sigils
- **hidden:** yes
- **trigger_type:** collection
- **trigger:** Unlock all eight realm sigils in the Inner Sanctum.
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** reaching the goal room a second time for the first key, then collecting the eight keys
- **vector-binding:** `mechanics.md` section "Rules that apply late in the game (late-game)"
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [37][41][43]; P2 research 2026-10-31 refs [2]
- **notes:** The rule for reading a sigil is still not reproduced; P2's text descriptions of the eight sigils are in `puzzles/sanctum_keys.md`. P2 places the trophy on the Entrance table and P1 in the Inner Sanctum foyer (unreconciled). Confirmed: 3 sources.

### Trophy of Trophies

- **id:** trophy_of_trophies
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Complete the Trophy Case with the other 15 trophies.
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** the other 15 achievements; challenge-mode saves are merged into the main save
- **vector-binding:** `mechanics.md` section "Rules that apply late in the game (late-game)"
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [25][41][42][43][45]; P2 research 2026-10-31 refs [1][15]
- **notes:** Public Steam condition exists. Confirmed: 5 sources. The PlayStation list words this one differently (see Platform differences). P2: the trophies from the challenge saves are imported first, then the Trophy Room (blue, rarer) is drafted and the trophy appears on its table; the PlayStation platinum is named "Case Closed" on a TrueTrophies page.

## Threshold

### Bullseye Trophy

- **id:** bullseye_trophy
- **hidden:** yes
- **trigger_type:** threshold
- **trigger:** Solve 40 dartboard rounds; progress carries across runs.
- **missable:** no
- **ponr-window:** n/a (a wrong throw resets the current series)
- **prereqs:** none
- **vector-binding:** `puzzles/billiard_dartboard.md`
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [35][41][42][43][44]
- **notes:** Confirmed: 5 sources.

### A Logical Trophy

- **id:** a_logical_trophy
- **hidden:** yes
- **trigger_type:** threshold
- **trigger:** Win 40 three-box parlor games.
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** a Wind-Up Key for every box opened
- **vector-binding:** `puzzles/parlor_three_boxes.md`
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [35][41][42][43][44]
- **notes:** Confirmed: 5 sources.

## Discovery

### Trophy 8

- **id:** trophy_8
- **hidden:** yes
- **trigger_type:** discovery
- **trigger:** Solve the room on Rank 8: get the numbered key from the Gallery puzzle, open the locked Rank 8 door, and place the eight statues; the trophy is in the hidden panel.
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** the Gallery puzzle's key, which only works entering Rank 8
- **vector-binding:** `puzzles/room_8_statues.md`
- **enemy-tier:** 2
- **puzzle-tier:** 2
- **spoiler:** late-game
- **source:** P1 research 2026-10-31 refs [35][41][42][43]
- **notes:** Confirmed: 4 sources.

## Sources

- Canonical Steam stats page: https://steamcommunity.com/stats/1569580/achievements (fetched 2026-10-31; shows 5 non-hidden names and the count of 16)
- https://www.trueachievements.com/game/Blue-Prince/achievements (fetched 2026-10-31; 16 names, 1,000 Gamerscore)
- Stage 0: https://vgtimes.ru/games/blue-prince/achievements-and-trophies/steam/ ; https://www.destructoid.com/all-blue-prince-achievements-and-trophies/
- P2 refs (P2 numbering; the references this file uses are listed here): TrueTrophies walkthrough pages [1] 8, [2] 3, [3] 7, [10] 4, [11] 6 (i2.truetrophies.com/game/Blue-Prince/walkthrough/N); TrueAchievements walkthrough pages [12] 2, [14] 5, [15] 7 (www.trueachievements.com/game/Blue-Prince/walkthrough/N); [21] https://steamcommunity.com/app/1569580/discussions/0/599650254291234651
- P1 refs: [25] https://blueprince.wiki.fextralife.com/Achievements ; [49] https://www.trueachievements.com/game/Blue-Prince/achievements ; [50] https://www.truetrophies.com/game/Blue-Prince/trophies ; others as listed in the files named in each entry
