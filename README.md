# Sandrock Trainer

A quest-aware trainer for **My Time at Sandrock** (single-player). It runs as a BepInEx plugin that hosts a local control panel — toggles, item/currency tools, teleport, and a full quest browser — without the grind of traversal.

> **Single-player only.** The multiplayer client's launch integrity check rejects the mod; don't install it there.

## Features
- **God mode / infinite stamina / infinite endurance / freeze time of day / move-speed multiplier**
- **Gold & currencies**, **give any item** (with grade), **NPC relationships**
- **Teleport** — to your quest objective, to named locations (fast-travel points, ruins, Moisture Farm...), or to **any point on the game's map** (dungeons, shops, NPCs, fishing spots) with real coordinates
- **Quest catalog** — browse every named quest and **Start or Finish** any of it (back up your save first)

## Install

**Easy (recommended):** download **`Sandrock-Trainer-0.1.0-setup.exe`** from the [latest release](../../releases), run it, and on the **Setup** tab click **Install / Update** — it finds the game and sets up BepInEx + the plugin for you. Then launch My Time at Sandrock in single-player and open the trainer.

**Manual:** download `sandrock-trainer-v0.1.0.zip` from the [release](../../releases), install **BepInEx 5.4.x (x64)** ([for MTAS](https://www.nexusmods.com/mytimeatsandrock/mods/129)), extract the `SandrockTrainer` folder into `<game>\BepInEx\plugins\`, launch single-player, and open **http://localhost:17600** in any browser.

## Compatibility
Built against Steam build **18623106** (June 2026). A game update may require a rebuilt plugin.

## License / credits
Original mod code; references the game's API via BepInEx. Not affiliated with Pathea Games.
