![Alt text](([https://example.com/image.png](https://i.pinimg.com/736x/22/a2/67/22a267699325a8e7b579c0265a5e6920.jpg))
# Palworld MOB IDs for Admin Commands

This repository contains a reference list of **MOB IDs** used in **Palworld**.  
These IDs are required when using the `!spawn PalAsset Level` command with the [Admin Commands Mod](https://www.curseforge.com/palworld/lua-code-mods/admin-commands).

---

## Purpose

The goal of this repository is to make it easier for server admins to quickly find the correct MOB IDs when spawning creatures in Palworld using the mod.

---

## Installation & Requirements

1. Download and install the latest experimental version of **UE4SS**.  
2. Download the Admin Commands mod and extract it into: Pal/Binaries/Win64/ue4ss/Mods
3. Log in as admin using `/adminpassword`.  
4. Type `!help` in chat to see available commands.  

---

## Usage

With the Admin Commands Mod installed, you can spawn creatures using the following syntax:

- **PalAsset** → The internal asset ID of the Pal (see `mobs_palworld.txt`).  
- **Level** → The level you want the Pal to spawn at.  

---

## Examples

Spawn **GrizzBolt** at level 50:
!spawn ElecPanda 50

---

## Contents

- `mobs_palworld.txt` → A text file containing all MOB IDs aligned with their in-game names.  
- Reference table for quick lookup when spawning creatures.  

---

## Notes

- Some IDs are internal placeholders and may not correspond to a valid Pal in-game.  
- Always ensure you are using the correct mod version compatible with your Palworld build.  
- The list will evolve as new Pals are added to the game.  

---

## Credits

- Mod created by [Kozejin](https://www.curseforge.com/palworld/lua-code-mods/admin-commands).  
- Community contributions for MOB ID mapping.  

---

Happy spawning!

