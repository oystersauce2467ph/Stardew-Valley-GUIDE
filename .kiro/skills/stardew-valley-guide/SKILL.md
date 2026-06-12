---
name: stardew-valley-guide
description: >
  Use this skill whenever working on the Stardew-Valley-GUIDE project — writing
  or editing guide content, answering Stardew Valley gameplay questions, building
  features for the guide, or recalling project decisions. It bundles reusable game
  knowledge, project conventions, and pointers to the running memory log so context
  carries across sessions.
---

# Stardew Valley Guide Skill

This skill is the shared knowledge base for the **Stardew-Valley-GUIDE** project. It
exists so that every session starts with the same context instead of relearning the
project from scratch.

## When to use this skill

- Writing, editing, or organizing guide content (crops, villagers, fishing, mining, etc.)
- Answering gameplay questions about Stardew Valley
- Adding features or structure to the guide repository
- Recalling earlier decisions, preferences, or conventions for this project

> For the running log of what we have discussed and decided, see the companion
> **`AGENT.md`** file at the repository root (the "Memory & Chat History Log" section).
> Read it at the start of a session and append to it at the end.

## Current game version

- Track guidance against **Stardew Valley 1.6.15** (PC, Dec 2024) and **1.6.15.1**
  (Xbox / PlayStation / Switch, Feb 2025) — the current latest release.

## Project conventions

- **Repository:** `oystersauce2467ph/Stardew-Valley-GUIDE`
- **Format:** Markdown-first. Keep content readable on GitHub without extra tooling.
- **Tone:** Friendly, beginner-welcoming, spoiler-aware (flag late-game spoilers).
- **Structure:** Prefer one topic per file, linked from a top-level index/README.
- **Accuracy:** Stardew Valley is patched over time — note the game version a tip
  applies to when behavior is version-specific. Verify facts against the official
  [Stardew Valley Wiki](https://stardewvalleywiki.com/) (its MediaWiki API at
  `https://stardewvalleywiki.com/mediawiki/api.php` returns clean wikitext).

## Guide contents (what exists so far)

- **[`RELATIONSHIPS.md`](../../../RELATIONSHIPS.md)** — the Relationships & Gifting
  beginner manual: friendship mechanics, point values, romance/marriage, universal
  gift tastes, complete per-character Loves/Likes/Dislikes/Hates for all 34 giftable
  villagers, a "best easy loved gift" cheat sheet, and a birthday calendar.
- **[`FASTEST-COMPLETION.md`](../../../FASTEST-COMPLETION.md)** — the fastest route to
  finish the game (Community Center, Grandpa's 4 candles, Perfection 100%), a
  season-by-season plan from Spring Y1, tool-upgrade order, and skills ranked
  easiest→hardest with needed-vs-optional notes.

## Suggested guide structure

A guide repo like this usually organizes well into sections such as:

| Section | Covers |
| --- | --- |
| Getting Started | Controls, first day, early goals |
| Farming | Crops by season, profit, sprinklers, greenhouse |
| Villagers & Gifts | Loved/liked gifts, schedules, heart events, marriage |
| Fishing | Fish by season/location/weather, tackle, legendary fish |
| Mining & Combat | Mine levels, Skull Cavern, ore, weapons, rings |
| Foraging | Seasonal forageables, the Community Center bundles |
| Community Center | Bundle checklists and rewards |
| Cooking | Recipes, ingredients, buffs |
| Money-Making | Best per-season strategies, artisan goods |
| Calendar | Birthdays, festivals, seasonal deadlines |

## Core game knowledge (quick reference)

- **Seasons:** Spring, Summer, Fall, Winter — 28 days each. Most crops die when the
  season changes (greenhouse and Ginger Island are exceptions).
- **Energy & time:** Days run from 6:00 AM to 2:00 AM. Passing out costs money/energy.
- **Community Center vs. JojaMart:** Two mutually exclusive progression paths.
- **Skills:** Farming, Mining, Foraging, Fishing, Combat — each needs 15,000 total XP
  for level 10, with profession choices at level 5 and level 10. Difficulty to max,
  easiest→hardest: Foraging, Farming, Mining, Combat, Fishing. All five are
  **required** for Perfection (the "Farmer Level" category); none is needed merely to
  beat the Community Center or get Grandpa's 4 candles.
- **Tool upgrades (Blacksmith, 2 days each, in order):** Copper 2,000g+5 Copper Bars,
  Steel 5,000g+5 Iron Bars, Gold 10,000g+5 Gold Bars, Iridium 25,000g+5 Iridium Bars.
  Upgradeable: Pickaxe, Axe, Hoe, Watering Can, Trash Can, Pan. Recommended order:
  Pickaxe → Hoe → Axe → Watering Can (upgrade in **Winter** to avoid killing crops).
  Fishing rods come from Willy (Bamboo 500g, Fiberglass 1,800g/Lv2, Iridium 7,500g/Lv6).
  **Mastery** (1.6, unlocked at Lv10 in all skills) grants the Iridium Scythe and
  Advanced Iridium Rod — optional for Perfection but powerful.
- **Completion milestones:** Community Center (Greenhouse, Desert bus, minecarts) →
  Grandpa's Evaluation (12+ pts = 4 candles; re-check with a Diamond) → **Perfection
  100%** (averaged across 11 categories incl. ship 154 items, cook 81, craft 149,
  catch 72 fish, 7 Stardrops, 130 Golden Walnuts, 12 monster goals, all skills Lv10,
  4 Obelisks, the 10,000,000g Gold Clock, max hearts with all 34 villagers). Full
  walkthrough lives in [`FASTEST-COMPLETION.md`](../../../FASTEST-COMPLETION.md).
- **Relationships:** 250 friendship points = 1 heart. Most villagers cap at 10
  hearts; a spouse/roommate reaches 14. Gift point values: **Love +80, Like +45,
  Neutral +20, Dislike −20, Hate −40**. Birthdays multiply gifts ×8 (Winter Star ×5,
  the *Friendship 101* book ×1.1; silver/gold/iridium quality add +10/+25/+50% to
  loves & likes). You may give 2 gifts per villager per week (plus a birthday gift),
  talk daily (+20), and complete delivery quests (+150). Decay is −2/day until a
  meter is full; spouses always decay. **Romance:** reach 8 hearts → give a Bouquet
  (800g, Pierre's) to date → 10 hearts → Mermaid's Pendant (5,000g, Old Mariner on
  rainy beach days) to marry; Krobus can be a roommate instead. Full details and
  per-character gift tables live in [`RELATIONSHIPS.md`](../../../RELATIONSHIPS.md).

## How to keep this skill useful

When something new and reusable is learned about the game or the project's
conventions, add it here. When it is a one-time decision or conversational context,
record it in `AGENT.md` instead. Knowledge that should outlive a single chat goes in
this skill; the narrative of *what happened* goes in the agent memory log.
