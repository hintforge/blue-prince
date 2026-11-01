# Blue Prince -- Limitations & Blocked Sources

Sources I found that look useful but couldn't fully fetch -- paywalls, Cloudflare, age gates, video-only content, etc. URLs preserved so the player (or another contributor) can open them in a real browser. This file names no gated game content: where a gap or conflict concerns late-game material it points to the file and section that holds the detail.

## How to read this file
- Each entry: topic, URL, block type, what I could glean, best alternative I did get to.
- Each per-topic file (in `puzzles/`, `items/`, `sections/`) also lists its own blocked sources at the bottom -- the player rarely needs to come hunting here.
- This file is the catch-all for sources that didn't fit a specific topic.

## Block types
- **paywall** -- content gated behind a subscription or article limit
- **cloudflare** -- Cloudflare bot challenge / 403 / 503 from WebFetch
- **video-only** -- YouTube or other video where the answer is shown visually; no readable text equivalent
- **age-gate** -- content blocked behind age verification
- **cookie-wall** -- popup or consent flow that broke the fetch
- **search-snippet-only** -- search engine returned a snippet but the page itself wasn't reachable
- **dead-link** -- URL was in another source but no longer resolves

- **robots-restriction** -- the external research runtime reports a robots access restriction
- **terms-restriction** -- a stated retrieval restriction was reported; preserve the actual evidence
- **javascript-dependent** -- useful content requires page execution the available tool did not perform
- **login-required** -- a signed-in session is required
- **access-not-checked** -- no content/access check was performed; never call this robots-blocked

## Companion tools

For every useful map, tracker, database or completion tool supplied, recalled or found:

- Name and URL if verified (otherwise mark unknown/unverified)
- Apparent coverage, evidence for it, and uncertainty; unread coverage is not confirmed game data
- Reason not read, access-check result, policy evidence if available, and check date
- How a person could use it, best readable alternative, and wider-spoiler warning where relevant

Merge repeated URLs with dated evidence retained. Read tools can also be recorded here when they offer a useful location fallback. Record an honest empty statement when no candidates were found; do not imply exhaustive discovery.

Candidates (Stage 0 search 2026-10-31, merged with the P1 and P2 research results of 2026-10-31; discovery is limited and an absence of results does not prove no tool exists). No dedicated interactive map or collectible tracker was found in any pass; the P1 and P2 searches returned wikis, guides and news only (P2 ran few searches for one, so this does not prove none exists).

| Tool | Type and apparent coverage | Read state and check (2026-10-31) | How to use it; wider-spoiler warning |
|---|---|---|---|
| Blue Prince Wiki (wiki.gg), https://blueprince.wiki.gg/ | Community wiki, 461 articles per its own main page (page last edited 2025-04-12, so the count may be stale) | Read: Room Directory, Items, patch notes (Patch_1.7 address), main page; P2 also read the Shrine page (edited 2026-09-17; its tables were folded) and found its Controls page an empty 404 (2026-10-31). The Patch_notes address returned 404 on WebFetch and camoufox-fetch. Not read: Documents, Puzzles categories, a book-volume list (folded), Room Directory and Items again in P2 | Room Directory and Puzzles pages spoil room contents and solutions |
| Blue Prince Wiki (Fextralife), https://blueprince.wiki.fextralife.com/ | Community wiki, "110 rooms, 70 items, 16 achievements, 231 total pages" on its home page; the most current wiki found (edits to 2026-10-22) | Read: many pages (mechanics, progression, upgrades, puzzles, locations, rooms, room types, shops, glossary, achievements, update history). Folded "spoiler" blocks hid text on the Progression and Game Mechanics pages (several topic blocks). P2 read Progression again (edited 2026-10-22): the folded blocks stayed hidden (the "Show 28 more" list under permanent unlocks and several topic blocks), and its Controls page is an empty 404 | Locations, Endings and Puzzles pages spoil late-game content |
| TrueTrophies (PS5) / TrueAchievements (Xbox) | Trophy and achievement lists plus a 14-page walkthrough | Read: both lists, walkthrough page 2 of each, and the Xbox list again by camoufox-fetch in this ingestion (verdict ok). Not read in P1 (budget, not blocked): TrueTrophies walkthrough pages 3-14 and TrueAchievements pages 3-8. P2 read TrueTrophies pages 2, 3, 4, 6, 7, 8, 11, 12, 13 and 14 (WebFetch gave 403; camoufox-fetch verdict ok) and TrueAchievements pages 2, 4, 5 and 7. Still not read: TrueTrophies pages 5, 9 (Items) and 10 (Room Directory); TrueAchievements pages 3, 6 (a trophy walkthrough) and 8 (a Directory checklist). The copies of TrueTrophies walkthrough pages 12 and 13 and of the www.truetrophies.com page 2 were truncated, and click-to-reveal solution blocks and puzzle-solution images on TrueAchievements and TrueTrophies could not be read. TrueTrophies and TrueAchievements are one publisher network | The best readable location inventory found; wide spoilers |
| In-game Room Directory and Mount Holly Records / Scrapbook in the Library | In-game completion tracker | Described by [2][26]; not independently observed | In-game only |
| Reddit progress-route guides (r/BluePrince) | Community "tracker" of unlock order, not a tool | Read three posts (first 8-15 comments each) | One is flagged late-game and story throughout |
| Nexus Mods developer-menu mod, https://www.nexusmods.com/blueprince/mods/30 | Datamining and modding aid exposing a developer overlay (MelonLoader) | Read the mod page only in P1; not reopened in P2 | Spawns any room or item: wide spoilers; it can change saves; not a map or tracker |
| ShortcutPosters controls page, https://shortcutposters.com/games/blue-prince/ | Keybind reference, unofficial | Read | Controls only |
| Spottis controls page, https://www.spottis.com/games/blue-prince-controls/ | Controls table, undated, low reliability | Read (truncated at 12,000 of 17,243 characters); not reopened in P2 | Controls only |
| Thunderstore mod "BluePrinceNotes", https://thunderstore.io/c/blue-prince/p/red_socket/BluePrinceNotes/ | A notes mod (datamining class); coverage unknown | Found by P2 in search; not opened (2026-10-31); access not checked | Mods can spoil far beyond a player's dials (the Nexus row above is the other mod) |
| TrueTrophies page links: a datamined puzzle answer sheet, a solver and puzzle maps (images) | Solvers and answer sheets named on a TrueTrophies page | Seen as links in P2; not followed | Puzzle solutions; wide spoilers |
| Playnews (https://www.playnews.gg/), VGTimes (https://vgtimes.ru/) | A Polish-language guide site (reads as a translation of a French original) and a Russian guide site | P2 read one Playnews puzzle guide and one VGTimes answers page (the VGTimes text was cut off in its last section). WebFetch gave 403 for Playnews; camoufox-fetch verdict ok. A second Playnews guide (the dated 2026-10-14 one) was seen in links and not opened | Guides; the answers page spoils solutions |

## Entries

### Blue Prince Wiki and Fextralife -- controls pages
- Source: https://blueprince.wiki.gg/wiki/Controls and the Fextralife Controls page
- Block type: dead-link (HTTP 404 on both tools, 2026-10-31)
- What I could glean before the block: nothing.
- Best alternative I did get to: the Patch 1.7 page (remapping added), two third-party control tables (see `controls.md`).

### YouTube "Blue Prince: PC Settings Overview"
- Source: https://www.youtube.com/watch?v=K8uqmFNj7zs
- Block type: dead-link (the video is unavailable: "This video isn't available anymore"; camoufox-fetch verdict thin)
- Best alternative I did get to: the Accessibility pages listed in `settings.md`. No video transcript exists for settings, and no speedrun-route video was readable for any topic.

### Steam Community controls thread
- Source: https://steamcommunity.com/app/1569580/discussions/0/599650036410778058
- Block type: access-not-checked (no access check and no search snippet is recorded for this thread in either research result; a second, readable thread on keybinds was read: https://steamcommunity.com/app/1569580/discussions/0/599650563430304613/)

### Pages seen as search results only (not opened by P1)
- gamespot.com and screenrant.com trophy guides; mp1st.com early console update pages (1.003 to 1.011); rutab.net (Russian review roundup); lootlevelchill.com, deltiasgaming.com, gameluster.com, sportskeeda.com and dexerto.com English tips and room lists; four Steam Community threads (snippets only); the developer's other X posts and Bluesky posts (settings screenshots). Access check: not checked. Each could add triangulation; none supplies confirmed facts.
- Polish-language sources: none found in P1's two searches (gry-online.pl named in the brief); P2's retry found and read a Polish guide site (Playnews, below) and still found nothing on gry-online.pl.

### Sportskeeda / Deltia's Gaming -- controller versus mouse
- Block type: javascript-dependent (direct fetch returned HTTP 405 and both pages were then read through a headless browser, 2026-10-31; no Cloudflare challenge, 403 or 503 is recorded, and the cause of the 405 is not recorded). Everything was recovered.

### TrueTrophies and Playnews -- walkthrough and guide pages (P2)
- Source: https://i2.truetrophies.com/game/Blue-Prince/walkthrough/ pages 2-14; Playnews (https://www.playnews.gg/), one Polish-language puzzle guide (its page address is not listed here)
- Block type: cloudflare (WebFetch returned 403 for both sites, 2026-10-31); read through camoufox-fetch with verdict ok. Everything on the pages read was recovered, except where a copy was truncated or its solutions are images.

### Pages seen as search results or links only (not opened by P2)
- Insider Gaming and Shacknews Switch 2 launch pages (P1 read them; P2 did not reopen them); deltiasgaming.com controller page (P1 read it); gamerblurb.com controls and item guides; selphie1999gaming.com and deltiasgaming.com item lists; rutab.net answer list (Russian); postmode.org guides hub (it would settle two open gaps); pcgamesn.com and siliconera.com puzzle solutions (second sources for one solution); YouTube puzzle videos in English, French, Spanish and Portuguese (one opened, no transcript); a second Steam thread on one open question; r/BluePrince threads on threshold questions, save reports and soft-locks (no Reddit URL surfaced in P2's searches, none read). Access check: surfaced in search 2026-10-31, not opened. An unread source supplies no confirmed unlock conditions.
- speedrun.com: a search found no Blue Prince leaderboard or route notes; several generic speedrun pages surfaced and were not read. gry-online.pl: a search found no Blue Prince guide on it (2026-10-31).
- German, French, Portuguese, Japanese and Korean pages: none read by P2.

## Research gaps carried forward (details live in the file named)

- Controls (still open after P2): default bindings for PlayStation (DualSense), Xbox, Switch 2 (handheld, docked and Joy-Con 2 mouse mode), a Steam Deck gamepad map and verified PC keyboard and mouse defaults (`controls.md`); also whether each console has its own Remapping entry. Settings: exact tab names, every option's range and default, and the graphics, audio, subtitle and language lists (`settings.md`).
- Unlock chains the research marks incomplete or unlocated after P2: several collectible locations, one carry limit, an inventory count, a repeat rule, one puzzle's location and a few other links and traits are not covered (details in the files named); folded blocks about late-game content stayed unreadable. See `items/upgrades.md`, `puzzles/` and `mechanics.md`.
- Late-game material: P2 added late-game detail (kept at its tiers in `puzzles/`); one late-game reading rule is still not reproduced by any source.
- Per-room details for all 110 rooms and the "not listed" room variants: not researched. The upgrade list is now in `items/upgrades.md`.
- The 1.10 patch contents and the Switch 2 / console builds of 1.7.2 and 1.7.3: not found (`mechanics.md` "Versions and platforms").
- Video transcripts and speedrun routes: none read (P2 reached one video page that exposed only a caption line and a description); no speedrun.com content found.
- Not read in P2: German, French, Portuguese, Japanese and Korean pages; the VGTimes guide bodies beyond the answers page; Reddit save reports.

## Unresolved conflicts between sources (both values are kept in the file named)

| Topic | Where | Status |
|---|---|---|
| What the stroll button does on consoles (one third-party table against the developer's own notes) | `controls.md` | Developer notes treated as authoritative; the table is marked low reliability. P2 (four sites) shows the third-party "run" wording and the developer's "stroll" name the same faster speed; the table's claim that stroll slows movement stays contradicted |
| Lock Pick retries (one wiki says one attempt per lock; a Reddit tips post and replies disagree) | `items/support_items.md` | Both kept; unresolved. P2's pages say neither |
| A set of thresholds that a 2025 Reddit post and the wiki page give differently (patch 1.7.3 swapped two amounts) | `items/builds.md` | Both kept. P2's TrueTrophies table gives the same costs the Reddit post quotes and the low end of the wiki ranges, so the mismatch may be ranges against single costs (the guide's own comparison); whether the table's two swapped amounts pre-date patch 1.7.3 is unknown |
| The same room is named two ways on two wikis | `mechanics.md` | Naming difference, same room |
| Room counts per color (one wiki lists 8 per group, the other counts multicolor and added rooms) | `mechanics.md` | Different sets, neither wrong |
| Dead-end advice (some players say to draft them early, common fear says avoid) | `items/builds.md` | Style disagreement, not a fact conflict |
| A prerequisite that one guide words differently from three others, for a late-game feature | `mechanics.md` late-game section | Resolved by P2 at medium confidence: the odd one out is a step in the same chain (two pages of one publisher network; that guide was not re-read) |
| Which values are listed for one late-game entry (sources differ) | `puzzles/secret_puzzles.md` | Not necessarily exclusive; all values kept; the P2 explanation is unverified |
| Differences in a few late-game entries between three sites (P2) | `puzzles/safes_and_codes.md` | Possibly differences already listed by P1's sources; both kept; unresolved |
| Two route descriptions for one permanent addition | `items/upgrades.md` | Both kept; unresolved |
| Two route descriptions for one estate location (P1 against P2) | `items/upgrades.md` | Both kept; may be two routes; unresolved |
| Three accounts of the contents of one late-game location (P1, TrueTrophies, TrueAchievements) | `puzzles/secret_puzzles.md` | Three accounts kept; unresolved |
| A count that two groups of sources give differently, for one late-game activity (P1 guides against two P2 pages from one publisher network) | `mechanics.md`, `puzzles/final_exam.md` | Both kept; one side is a single publisher network; unresolved |
| The conditions of one late-game goal | `mechanics.md` | A forum thread, TrueTrophies, TrueAchievements and a P1 patch note differ; all kept; unresolved |
| A list size that a walkthrough states differently from its own row and from P1's wiki, and the unlock wording for one late-game option | `mechanics.md` | Both kept; unresolved |
| A delivery timing that sources give two ways, for one late-game reward | `mechanics.md` | Both kept; unresolved |
| The order of steps on one late-game route, and which of two routes reaches one destination | `puzzles/chess_puzzle.md` | Two orders and two routes kept; unresolved |
| A numeric threshold in one late-game chain against the table that lists it | `puzzles/chess_puzzle.md`, `mechanics.md` | Both kept; unexplained |
| A naming difference inside one source, for one late-game item | `puzzles/chess_puzzle.md` | Treated as a naming difference inside one source; unverified |
| A count that sources give differently for one late-game feature (one figure comes from a guide title that was not opened) | `puzzles/antechamber_levers.md` | Both kept; unresolved |
| Where one late-game reward appears (two accounts), and whether two P1 names match P2's | `puzzles/sanctum_keys.md` | Both kept; unresolved |
| A figure that P1 and P2 give differently for one late-game feature | `puzzles/machinery.md` | Both kept; the two may describe different parts |
| Which rule framing one puzzle uses (two framings are given) | `puzzles/parlor_three_boxes.md` | Both kept; unresolved |
| Whether two descriptions (P1 and P2) are of the same puzzle | `puzzles/utility_closet_vac.md` | Left unresolved by the result |
| A price floor that P1 and P2 give differently | `items/support_items.md` | Both kept; unresolved |
| Two descriptions (P1's and P2's) of one puzzle's settings | `puzzles/machinery.md` | Both kept; not reconciled |
| A count of one kind of reward site that P1 and P2 give differently | `puzzles/mora_jai_boxes.md`, `items/upgrades.md` | Inventory incomplete in both; unresolved |

## Always-blocked categories

- **Per-day randomized content.** The manor's layout changes every day and each new room is drafted from three random floor plans (https://en.wikipedia.org/wiki/Blue_Prince, read 2026-10-31); a text guide can describe the rules, never a specific day's layout. Extra items in a room are rolled each time it is drafted.
- **Visual-only puzzles.** Some solutions are described only in words by the guides read, and several solution pages are images or click-to-reveal blocks that no tool read. One late-game rule is not reproduced by any source; one answer list is held at a high tier in `puzzles/`.
