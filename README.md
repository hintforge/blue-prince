# Blue Prince — Hintforge Companion

![Blue Prince companion status — coverage, how current it is, and spoiler control](assets/readme-status-card.svg)

A spoiler-controlled hint companion for **Blue Prince**, Dogubomb's puzzle adventure where you draft the rooms of a changing manor one door at a time and try to reach a room no one can find. Built in the [Hintforge](https://github.com/hintforge/builder) format: a loyal sidekick that answers only from these guide files — never from guesswork — at the spoiler level you set.

## Use it

You need a Hintforge reader running in Claude Code, Codex, or OpenClaw. Point it at this repo:

> Load the Blue Prince guide from github.com/hintforge/blue-prince

Then just ask — *"what does this room do," "how do drafting odds work," "give me a small nudge on this puzzle."* Runtime setup lives in [`hintforge/reader`](https://github.com/hintforge/reader).

## Spoilers

Blue Prince is a game of discovery, and almost everything worth knowing is something you are meant to find. The puzzle dial starts at zero: the companion says nothing about a puzzle until you ask, and each ask climbs one small hint at a time, with the answer only at the top. Late rooms, the story and the deeper secrets stay out of answers until you raise the dials. Every fact carries its source and says how sure it is, and where the sources disagree or say nothing, the guide says so instead of guessing.

## What's inside

A structured Markdown corpus — how drafting, the daily run and the manor's resources work, a room lookup, permanent upgrades and items, puzzles with step-by-step hint ladders, the dependencies between unlocks, things you can miss, settings, controls for each platform (PC, PS5, Xbox Series and Switch 2; the console button layouts are still a gap), and all 16 achievements. The companion reads and writes only the files you control.
