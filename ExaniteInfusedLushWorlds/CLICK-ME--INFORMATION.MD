# Version Info (This is very important)
> This is **not** functional on the latest version. Do not try to use this mod.

# Exanite Infused Lush Worlds

This mod pays tribute to the soon-closing (or if it's past 23 November 2018, *closed*) Sci-Fi MMORPG *WildStar* by Carbine Studios.

As seen in *WildStar*
![The main source of inspiration for this mod](https://i.imgur.com/WjOHwGK.png)

As seen in-game
![The way the mod looks](https://i.imgur.com/R0lW3aP.png)

# Description of the changes it makes to the game

 - The color palette of all worlds flagged as Lush (Any world with extreme plant life, usually "Verdant" or "Flourishing" in planetary descriptions from the scanner) has been replaced with a very gold-heavy palette to replicate locations in WildStar that have extreme amounts of [Exanite](https://wildstar.gamepedia.com/Exanite).
 - The weather of Lush worlds has been reworked to make the boiling rainstorms / humidity a **lot** more rare.
 - Exanite Gemstones (the large hexagonal crystals) now grow from the ground as ambient plants. They can't be mined yet.
 
# Files this edits

 - `METADATA/SIMULATION/SOLARSYSTEM/BIOMES/LUSH/LUSHBIOME.MBIN`
    - Edits weather properties to set the weight of `Humid` to `0.225` and `Clear` to `1`
 - `METADATA/SIMULATION/SOLARSYSTEM/BIOMES/LUSH/LUSHCOLOURPALETTES.MBIN`
    - Edits all colors from the following color categories: `Grass`, `Plant`, `Leaf`, `Wood`, `Dirt`
 - `METADATA/SIMULATION/SOLARSYSTEM/BIOMES/LUSH/LUSHHQCOLOURPALETTE.MBIN`
    - Edits all colors from the following color categories: `Grass`, `Plant`, `Leaf`, `Wood`, `Dirt`
 - `METADATA/SIMULATION/SOLARSYSTEM/BIOMES/LUSH/LUSHHQOBJECTSFULL`
    - Appends `CUSTOMMODELS/EXANITEGEMSTONE` to generation.
 - `METADATA/SIMULATION/SOLARSYSTEM/BIOMES/LUSH/LUSHOBJECTSFULL`
    - Appends `CUSTOMMODELS/EXANITEGEMSTONE` to generation.
 - `METADATA/SIMULATION/SOLARSYSTEM/BIOMES/LUSH/LUSHOBJECTSMID`
    - Appends `CUSTOMMODELS/EXANITEGEMSTONE` to generation.
 - `METADATA/SIMULATION/SOLARSYSTEM/BIOMES/LUSH/LUSHOBJECTSLOW`
    - Appends `CUSTOMMODELS/EXANITEGEMSTONE` to generation.
 - `METADATA/SIMULATION/SOLARSYSTEM/BIOMES/LUSH/LUSHOBJECTSDEAD`
    - Appends `CUSTOMMODELS/EXANITEGEMSTONE` to generation.
