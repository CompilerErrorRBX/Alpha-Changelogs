# :bookmark_tabs:  Changelog 03/08/2024 - xx/xx/xxxx

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes

________

## :gun: New Items

### Reinforced Armor Plate
- Naturally spawns - Military areas.
- Used to repair vests.
- Repairs 50 durability (2x required to fully repair tier 2 vest), 1x use
- Stackable to 4x, weighs 2.5kg.

### Makeshift Armor Plate
- Crafted
- Used to repair vests.
- Repairs 10% durability.
- Repairs 20 durability (5x required to fully repair tier 2 vest), 1x use
- Stackable to 4x, weighs 2.5kg.

### Makeshift Weapon Repair Kit
- Crafted
- Used to repair weapons.
- Repairs 10% durability.

### Makeshift Satchel
- Crafted
- Small backpack.

### Sponge
- Naturally spawns - Residential and Industrial areas
- Crafting Resource.

### Glue Bottle
- Naturally spawns - Residential and Industrial areas, Craftable.
- Crafting Resource.
________

## :thread: New Crafting Recipes

### Makeshift Armor Plate
- 1x `Advanced Composite Fiber`
- 25x `Scrap Metal`

### Makeshift Weapon Repair Kit
- 3x `Composite Fiber`
- 10x `Scrap Metal`
- 2x `Spring`
- 1x `Sponge`
- 2x `Scrap Glass`

### Changed Duct Tape Recipe
- Reduced `Scrap Cloth` requirement (from 5x -> 2x)
- Removed `Sap` requirement
- Added 2x `Scrap Plastic` requirement
- Added 1x `Glue Bottle` requirement

### Disabled Medium Backpack Recipe

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Added Proximity Voice Chat Support
- Toggle Voice Chat via Keybind (`Left Alt` on Keyboard, unbound on controllers).
- Zombies react to your voice.

### :white_check_mark: `Feature` Added Primary/Secondary Weapon Swapping
- Drag and drop an a primary/secondary weapon into another weapon slot to swap them.

### :arrow_up_small: `Improvement` Fixed a critical memory leak.
- Also causing a performance leak.

### :arrow_up_small: `Improvement` Partial rewrite of zombie logic.

________

## :balance_scale: Changes

### :exclamation: `Change` *CRITICAL CHANGE* Increased chance of a `Leg Break` when shot in the legs (from `damage / 4` to `damage`)
- `MRAD` should break a leg about 56% of the time, `AR-15` is about 15.4%.

### :exclamation: `Change` Reduced item durability degradation on death (from 25% -> 20%)

### :exclamation: `Change` Reduced spawn rates of residential spawns
- Should reduce the frequency of finding food in cabinets.

### :exclamation: `Change` Buffed Dumpsters
- Added all scrap items to dumpster spawns.
- Increased max quantity of each item.

### :exclamation: `Change` Shotguns now have a Headshot multiplier
> Previously, a headshot with a shotgun did the same damage as a torso shot. If a player shot another player in the head who had a tier 2 helmet, they would deal only about 55 damage with the Remington pump shotgun. This change should put that closer to 90 damage.
________

## :bug: Bugfixes
- Fixed a bug where zombies could attack several times rapidly.
- Fixed a bug where being radiated didn't cause passive health drain.
