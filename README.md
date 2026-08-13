# AKINO's Survival Optimization

A curated survival-focused Minecraft modpack for **Minecraft 1.21.1** built on **NeoForge 21.1.244**, tuned for a rich, optimized single-player survival experience.

## Requirements

| Item      | Requirement                          |
|-----------|--------------------------------------|
| Minecraft | 1.21.1                               |
| Loader    | NeoForge 21.1.244                    |
| Java      | 21 or newer                          |
| RAM       | 4 GB+ (6 GB recommended)             |
| Launcher  | CurseForge, Prism, ATLauncher, etc.  |

## Highlights

- **Exploration & Dimensions** – The Aether, Deeper and Darker, Ender'scape, Oh The Biomes We've Gone, and more.
- **Content & Combat** – Iron's Spells 'n Spellbooks, Better Combat, Simply Swords, block-based bosses, Aquaculture fishing.
- **Crafting & Building** – Create, Farmer's Delight, Supplementaries, Macaw's bridges/doors/furniture/windows/fences.
- **Storage & Utility** – Sophisticated Storage + Backpacks, Waystones, Carry On, Nature's Compass, Trade Cycling.
- **Performance** – Sodium, Lithium, FerriteCore, ModernFix, Iris (shaders), Sound Physics Remastered.
- **Immersion** – Touhou Little Maid companions, AmbientSounds, fresh animations (Fresh Animations / Better Leaves / Stay True).

## Installation

1. Install a compatible launcher (e.g. CurseForge).
2. Download this modpack (as an archive or via the launcher's "Import" feature using `minecraftinstance.json`).
3. Launch with **Java 21+** and at least **4 GB** of allocated RAM.
4. (Optional) Enable any of the included shaderpacks or resource packs from the in-game options.

## Included Resource Packs

- Better Leaves 9.5
- Fresh Animations 1.10.4
- Stay True 1.21
- Dramatic Skys (demo)

## Included Shaderpacks

- Bliss 2.1.2 (Chocapic13 edit)
- Complementary Unbound r5.8.1
- Photon v1.3b

## Directory Structure

```
config/            Mod configuration files
defaultconfigs/    Server-style default configs (used on world creation)
datapacks/         Custom data packs (e.g. skill reset, maid compatibility)
global_packs/      Global required/optional data & resource packs
mods/              All mod JARs
resourcepacks/     Resource packs shipped with the pack
shaderpacks/       Shader packs shipped with the pack
tlm_custom_pack/   Touhou Little Maid custom maid/resource pack
xaero/             Xaero's map settings & waypoints
```

## Notes

- World saves (`saves/`) and machine-specific files (logs, caches, `user-prefs.json`) are intentionally **excluded** from this repository via `.gitignore`.
- The repository may exceed GitHub's 50 MB per-file recommendation for large mod JARs; files stay under the 100 MB hard limit, so they are committed directly.

## License

The modpack configuration is provided as-is. Individual mods, resource packs, and shaderpacks retain their own licenses; refer to each mod's CurseForge/Modrinth page for redistribution terms.
