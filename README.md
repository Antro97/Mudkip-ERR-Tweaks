# No More Red Particles

## Until further notice, the "No More Red Particles" tweak will not be uploaded since it crashes the game at startup.
Disables the red particles floating around when the Erdtree is burnt for the second time.
- Original mod by clevererraptor6 (https://www.nexusmods.com/eldenring/mods/1559)
- All credit goes to Clever for providing the instructions on how to do this by oneself (https://www.nexusmods.com/eldenring/mods/1559?tab=files&file_id=6074) and to @unko_deso (Discord) for clearing my doubts and providing further help.

### Installation
Extract the archive in the ERR folder, replace the file when asked to.

----------

# Permanent Sacrificial Twig
Permanent effect of Sacrificial Twig; it also works as a counter to the rune loss from Death Blight (the effect spawns the lost runes on the ground and you can immediately retrieve them upon respawning).
- If you have the Erd Tools mod with "pickup_lost_runes" set to 1, the retrieval is automatic.

### Installation
Extract the archive in the ERR folder, replace the file when asked to.

*Not compatible with Scabbards on Back, unless you merge the "regulation.bin" file by yourself using Smithbox.*

### _Changed values_
- ActionButtonParam
  - ID 1000
    - radius = 1000000
    - height = 1000000
    - baseHeightOffset = -700000

- SpEffectParam
  - ID 100620 and 100621
    - cycleOccurrenceSpEffectId = 68

----------

# Scabbards On Back
Scabbards of katanas and straight swords on your back, instead of by your side.

### Installation
Extract the archive in the ERR folder, replace the file when asked to.
- The .csv files are not needed, they are just for merging if you need to.

*Not compatible with Permanent Sacrificial Twig, unless you merge the "regulation.bin" file by yourself using Smithbox.*

### _Changed values_
Check the provided .csv files for katanas and straight swords.
