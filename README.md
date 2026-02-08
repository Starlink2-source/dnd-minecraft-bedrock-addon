# D&D Add-on

![Version](https://img.shields.io/badge/Version-v0.1.0-blue) ![Bedrock](https://img.shields.io/badge/Minecraft-1.21.130-green) ![Platform](https://img.shields.io/badge/Platform-Bedrock_Edition-blue)

**Welcome to the V0.1.0 release of the D&D Add-on!** This project brings the fantasy world of Dungeons & Dragons to Minecraft Bedrock Edition, featuring custom entities, specialized equipment, and advanced animations.

---

## Features

### New Entity: The Wood Elf
A high-fidelity custom entity with specialized Archer AI.
* **Health:** 20 HP.
* **Behavior:** Defensive/Neutral. Will actively hunt monsters (Zombies, Skeletons, etc.) within a 16-block radius.
* **Combat:** Uses a custom-modeled bow. Keeps distance from targets to fire arrows.
* **Animations:** Fully scripted transitions for **Idle, Walk, Attack (Bow Draw), Hurt, and Death**.

### New Gear: Bark Armor Set
The first of many forest-themed equipment sets.
* **Includes:** Bark Helmet, Chestplate, Leggings, and Boots.
* **Optimized Rendering:** Uses custom Molang scripts to prevent leg-to-chest texture stretching.

### New Item: Elven Leaf Bread
A unique food source dropped by Wood Elves.
* **Texture:** Custom leaf-wrapped bread model.
* **Usage:** Essential survival food for forest travelers.

---

## V0.1.0 Technical Fixes
* **Schema 1.21.130:** All entity and item components updated to the latest Bedrock standards.
* **Animation Priority:** Death and Attack animations now correctly override vanilla behaviors using a prioritized State Machine.
* **Armor Components:** Migrated from deprecated `minecraft:armor` to the modern `minecraft:wearable` and `minecraft:protection` system.
* **Flattened Structure:** Optimized file paths to resolve "Missing Texture" (checkerboard) and "Sliding Animation" bugs.

---

## Installation Guide

1. Navigate to the **[Releases]** tab.
2. Download `D&D_Mod_V0.1.0.mcaddon`.
3. **Double-click** the file to launch Minecraft and begin the auto-import.
4. In your World Settings, activate both the **Resource Pack** and **Behavior Pack**.

> **Note:** For the best experience, ensure the Resource Pack is active and placed at the top of your stack.

---

## For Developers (bridge. v2)

This project is fully compatible with **bridge. v2**.

### Directory Layout
* `BP/` - Behavior Pack (Logic, Loot Tables, Entity Definitions).
* `RP/` - Resource Pack (Textures, Geometry, Animations, Render Controllers).

### Building from Source
1. Clone the repository.
2. Open the project in **bridge. v2**.
3. Use the **Export** function to generate a fresh `.mcaddon`.

---

## Credits & License

* **Model & Textures:** Created using [Blockbench](https://www.blockbench.net/).
* **Code & Logic:** Built using [bridge.](https://bridge-core.app/).
* **Created by:** [Draco12191712 (Vivaan Bobade)]
