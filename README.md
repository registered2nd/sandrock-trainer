# Sandrock Trainer

A quest-aware trainer for **My Time at Sandrock** (single-player). It runs as a BepInEx plugin that hosts a local control panel — toggles, item/currency tools, teleport, and a full quest browser — without the grind of traversal.

> **Single-player only.** The multiplayer client's launch integrity check rejects the mod; don't install it there.

## Features
- **God mode / infinite stamina / infinite endurance / freeze time of day / move-speed multiplier**
- **Gold & currencies**, **give any item** (with grade), **NPC relationships**
- **Teleport** — to your quest objective, to named locations (fast-travel points, ruins, Moisture Farm…), or to **any point on the game's map** (dungeons, shops, NPCs, fishing spots) with real coordinates
- **Quest catalog** — browse every named quest and **Start or Finish** any of it (back up your save first)

## Install
1. Install **BepInEx 5.4.x (x64)** into your game folder ([BepInEx for MTAS](https://www.nexusmods.com/mytimeatsandrock/mods/129)), launch the game once, then quit.
2. Download the latest [release](../../releases) and extract the `SandrockTrainer` folder into `<game>\BepInEx\plugins\`.
3. Launch single-player and open **http://localhost:17600** in any browser (or use the desktop app).

## Compatibility
Built against Steam build **18623106** (June 2026). A game update may require a rebuilt plugin.

## License / credits
Original mod code; references the game's API via BepInEx. Not affiliated with Pathea Games.
