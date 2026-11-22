# fiesta nether

This is FiestaSMP's Nether save from 2026-11-21. The Overworld and End are in [world](https://github.com/open-fiestasmp/world) and [world-the-end](https://github.com/open-fiestasmp/world-the-end).

It's about 18.6 GB of world files before extraction. Leave extra space for the download and extracted copy. Use Java Edition and the same Minecraft/Paper version as the matching Overworld.

## download

Open [Releases](https://github.com/open-fiestasmp/world-nether/releases), choose `snapshot-2026-11-22`, then download **Source code (zip)**. Extract it. The folder with `level.dat` at its top level is the Paper Nether world folder. Inside it, `DIM-1` holds the dimension data. `README.md` is just this guide and can be removed after you read it.

## use it on a Paper server

1. Stop the server fully and back up `world`, `world_nether` and `world_the_end` first.
2. Download the matching `snapshot-2026-11-22` from [world](https://github.com/open-fiestasmp/world) and [world-the-end](https://github.com/open-fiestasmp/world-the-end) too. Don't mix snapshots from different dates.
3. Extract this archive and put its folder beside the other world folders. Name it `world_nether`; keep the files inside it, including `level.dat` and `DIM-1`.
4. Start the same Paper/Minecraft version the saves came from. Check the console before players join.

For a normal Paper layout, the sibling folders are `world`, `world_nether` and `world_the_end`, with `level-name=world` in `server.properties`. If your server uses custom world names or a world manager plugin, match its config instead.

## use the Nether in single-player

1. Start with the matching Overworld save from [world](https://github.com/open-fiestasmp/world) and make a backup copy.
2. From this archive, copy only the `DIM-1` folder into the root of that Overworld save, beside `level.dat` and `region`. The target path should be `saves/FiestaSMP/DIM-1`.
3. Don't copy this archive's `level.dat` over the Overworld's. Open the save with the matching Java version.

## extra files

`DIM-1/.world-tier/access` has region access-time markers. Minecraft doesn't need them to load the Nether; keep them if you want that history. This repo is world data only, not server plugins or config.

This is a community backup from FiestaSMP. We aren't Mojang or Microsoft, and this doesn't include or grant a Minecraft license.

Backed up and uploaded using Fiesta tools by `gautam652`.
