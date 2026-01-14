#  Dungeons & Dragons: Wood Elf Add-on

![Version](https://img.shields.io/badge/Version-v0.0.1_Alpha-green) ![Bedrock](https://img.shields.io/badge/Platform-Bedrock_Edition-blue)

**Welcome to the official repository for the D&D Wood Elf Add-on!** This project brings the fantasy world of Dungeons & Dragons to Minecraft Bedrock Edition, starting with the elusive and deadly Wood Elf.

---

##  Features

###  New Entity: The Wood Elf
A fully custom-modeled entity that spawns in your world.
* **Health:** 20 (Matches Player Health)
* **Behavior:** Neutral/Defensive. Will fight monsters to protect the area.
* **Combat:** specialized **Archer AI**. Keeps distance and uses a custom modeled bow.

###  Custom Animations
Fluid movements created in Blockbench to bring the Elf to life:
* **Idle:** Breathing and looking around.
* **Walk:** Natural movement when patrolling.
* **Attack:** Draws bow and fires arrows.
* **Death:** Dramatic collapse animation.

###  Loot Table
Defeating a Wood Elf (or trading, coming in v0.2) yields special rewards:
* **Elven Bread & More!** 
* *More items coming in future updates...*

---

##  Installation Guide

1.  Go to the **[Releases]** tab on the right side of this page.
2.  Download the latest `.mcaddon` file (e.g., `Wood_Elf_v0.0.1.mcaddon`).
3.  **Double-click** the file to open Minecraft.
4.  The game will automatically import the **Behavior Pack** and **Resource Pack**.
5.  Create a new world (or edit an existing one) and activate both packs in the settings!

> **Note:** Ensure "Experimental Gameplay" is enabled if you are using advanced features, though this version is designed to work with standard settings.

---

##  For Developers / Source Code

This repository contains the raw source code compatible with **bridge. v2**.

### Folder Structure
* `BP/` - Behavior Pack (Logic, Loot Tables, Entities)
* `RP/` - Resource Pack (Textures, Models, Animations, Sounds)
* `Skin Pack/` - Bonus custom skins.

### Compiling
To build this project yourself:
1.  Clone this repository.
2.  Open the folder in **bridge. v2**.
3.  Press **Export** to generate the `.mcaddon`.

---

## Credits & License

* **Model & Textures:** Created using [Blockbench](https://www.blockbench.net/).
* **Code & Logic:** Built using [bridge.](https://bridge-core.app/).
* **Created by:** [Draco12191712 (Vivaan Bobade)]
