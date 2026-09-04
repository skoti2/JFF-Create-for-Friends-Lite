# JFF Create for Friends Lite - Server bootstrap data

Dedicated-server metadata for **JFF Create for Friends Lite 0.0.1 FIX5**.

- Minecraft: 1.21.1
- NeoForge: 21.1.248
- Client source list: `modliste(2).txt` (382 JARs)
- Dedicated-server manifest entries: 334

Files:
- `server-manifest.json` - CurseForge project/file IDs installed by the server bootstrap.
- `server-overrides.zip` - server configs and KubeJS overrides inherited from the proven Full-pack base, with obvious removed-mod configs pruned.
- `server-exclusions.txt` - client-only and removed Lite mods that must not be installed on the dedicated server.
- `DEPENDENCY-CHECK.txt` - important client dependency combinations to verify before publishing.

Minecraft 1.21.1 / NeoForge 21.1.248.


## FIX5 changes

- Removed `upgraded-iron-chests-1.4.jar` from the server manifest and added it to server exclusions.
- Removed its two config files from `server-overrides.zip`.
- Added Create: Metallurgy 1.0.3.
- Added Create: Simulated Thrusters 1.1.1.
- Added Create: Coasters Simulated 0.1.5.
- Added Create: Treadmill 1.13.

## FIX6 server mod update

Added to the dedicated-server manifest:

- `jei-1.21.1-neoforge-19.50.0.414.jar` — CurseForge project 238222, file 8759217
- `ae2jeiintegration-1.2.1.jar` — CurseForge project 1074338, file 7727898
- `createcobblestone-1.5.0+neoforge-1.21.1-153.jar` — CurseForge project 1023532, file 8763220

`jei` was removed from `server-exclusions.txt`. JEI addons such as FTB JEI Extras remain excluded unless they are specifically required server-side.
