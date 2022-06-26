# pokeemerald Expansion Base

## What is the pokeemerald Expansion Base?

This base aims to combine some of the features I'd like to my pokeemerald base to have for easy access and use.
You are currently on the master branch which should always be a working (at least compileable version of the base)

## What feature branches are included?

- **[RHH's Battle Engine Upgrade](../tree/battle_engine):** Upgrades the battle engine in pokeemerald to newer Generation games' standards. It also adds newer moves and abilities.
- **[RHH's Pokémon Expansion](../tree/pokemon_expansion):** Adds Pokémon from newer Generations and makes them available in the National Dex. It also updates base stats and other Pokémon info.
- **[RHH's Item Expansion](../tree/item_expansion):** Adds items from newer Generations and also updates item effects for field use.
- **[TheXaman's PokedexPlus with a HGSS style](https://www.pokecommunity.com/showthread.php?t=441996):** 
- **[ghoulslash's DexNav & Detector Mode](https://www.pokecommunity.com/showthread.php?t=440571):**
- **[Some of ghoulslash's free_saveblock](https://www.pokecommunity.com/showthread.php?p=10168472#post10168472):** Namely FREE_UNION_ROOM_CHAT, FREE_LINK_BATTLE_RECORDS, FREE_RECORD_MIXING_HALL_RECORDS and APPRENTICE_COUNT set to 1 instead of 4 as well as MAIL_COUNT set to (PARTY_SIZE) instead of (10 + PARTY_SIZE)
- **[Fixes and content from the pret tutorials](https://github.com/pret/pokeemerald/wiki/Tutorials):** 

### Fixes to vanilla code:
- Uncommented bugfixes in config.h
- Surf Dismount Ground Effects
- Fix Snow Weather
- Seeding the RNG properly on startup
- Keep the Camera from Making Waves
- Not showing dex entries until getting the Pokédex
- Improving the WaitForVBlank function
- Better Reflection System

### Removing content:
- Update obedience levels to current standards
- Disabling Union Room check when entering Pokémon Centers

### Features from other generations
- Remove the extra save confirmation
- Allow running indoors
- Trainer Class-Based Poké Balls
- Prompt for reusing Repels
- LGPE-Style Bonus Premier Balls
- Make the keyboard auto-switch to lowercase after the first character

### pokeemerald Miscellaneous
- Speedy Pokecenter Healing
- Battle music changes depending on the map the player is in
- Extra save space with two lines of code
- Enable the Reset RTC Feature
