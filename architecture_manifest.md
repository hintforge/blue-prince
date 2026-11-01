# Blue Prince -- Architecture manifest

**status:** research-integrated
**last_reconciled:** 2026-10-31
**research_run:** P1 ingested 2026-10-31; P2 ingested 2026-10-31

`nav/` was intentionally skipped for this guide (game-type `procedural`, localization-mechanism class `none`: the manor's layout is rebuilt each day, so no stable zone graph exists). This root file carries the manifest and the vector list the reader reads at session start.

## Hintforge manifest

```
corpus-core-version: 6
game-version: "latest as of 2026-10-31"
game-version-platform: "PC (Windows/macOS), PS5, Xbox Series X|S, Switch 2"
game-version-as-of: 2026-10-31
vector-extensions: puzzles
```

## Vector extensions

- `puzzles/` -- discrete puzzle files with hint ladders, indexed by `puzzles/index.md`

## Structural notes

**Game-type label:** procedural (confirmed by P1 from three sources: Wikipedia, the Fextralife Game Mechanics page and the Steam description).
**Localization-mechanism class:** none (confirmed by P1). A per-day Blueprint map of the current house exists in the game, but there is no stable map.
**Source-language set:** English (the game ships English-only: Steam page, Wikipedia citing Polygon, VGTimes). Developer: Dogubomb, based in Hollywood, California, United States (publisher page, single source); publisher Raw Fury. Non-English coverage verified from pages read: Spanish, Russian, Chinese, French, and Polish (P2 read one Playnews guide; its text reads as a translation of a French original, so its claims count as single-source; nothing was found on gry-online.pl). German, Portuguese, Japanese and Korean: no page read.
**DLC:** none found beyond "Blue Prince - The Original Soundtrack" (Steam page and Wikipedia; out of scope until P3, which was skipped at setup).
**Where the structure lives:** the grid, fixed rooms, drafting rules and run structure are in `mechanics.md`; the room lookup is `sections/rooms.md`; the permanent unlocks and their chains are in `items/upgrades.md`; the optional-content registry is the Studio additions, found floorplans and Outer Rooms in `sections/rooms.md` and `items/upgrades.md`.

No zone graph, support topology or locks-and-keys table is scaffolded. The unlock-dependency table P2 returned (partial) is distributed across `items/upgrades.md`, `mechanics.md` and the files of `puzzles/`; its gaps are listed in `limitations.md`.

The version facts P1 found (latest PC patch 1.7.3 on 2026-09-16; console update numbering 2.001 to 2.003; patch 1.10 announced and not shipped) are recorded as claims in `mechanics.md` section "Versions and platforms"; the manifest fields above were not changed by ingestion.
