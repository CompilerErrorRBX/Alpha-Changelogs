# :bookmark_tabs:  Changelog xx/xx/xxxx - xx/xx/xxxx

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes

________

## :gun: New Items

### `Gear Airdrop` 🪂
> The `Gear Airdrop` contains high tier gear and consumables to get you ready for the fight fast to quickly donate dank loot to superior players.

- (Black/Red) Beret (1x)
- (Black/Tan) Boots (1x)
- (Black/Green) Mask (1x)
- (Black/Green) Tactical Pants (1x)
- (Black/Green) Tactical Shirt (1x)
- Duffle Bag (1x)
- Night Vision Tier 2 (1x)
- Energy Drink (1x)
- Tactical Bacon (1-3x)
- MRE (1-2x)

### `Hazmat Airdrop` 🪂
> The `Hazmat Airdrop` contains the necessary equipment to enter radioactive zones.

- Hazmat Shirt (1x)
- Hazmat Pants (1x)
- Gas Mask (1x)
- Energy Drink (1x)
- Tactical Bacon (1-3x)
- MRE (1-2x)

________

## :thread: New Crafting Recipes

### Makeshift SMG Adjustment
- Reduced `Composite Fiber` requirement (from 2x -> 1x)
- Reduced `Scrap Metal` requirement (from 50x -> 20x)
- Reduced `Spring` requirement (from 3x -> 2x)
- Added `Scrap Plastic` requirement (7x)

### Makeshift Sniper Adjustment
- Reduced `Composite Fiber` requirement (from 3x -> 2x)
- Reduced `Scrap Metal` requirement (from 75x -> 35x)
- Removed `Spring` requirement (from 1x -> 0x)
- Added `Scrap Plastic` requirement (5x)

### Makeshift Armor Plate Adjustment
- Removed requirement for `Advanced Composite Fiber` (from 1x -> 0x)
- Added requirement for `Composite Fiber` (2x)

### Press Vest Adjustment
- Removed requirement for `Composite Fiber` (from 4x -> 0x)
- Removed requirement for `Scrap Metal` (from 35x -> 0x)
- Added requirement for `Makeshift Armor Plate` (2x)

### Healing Salve Adjustment
- Reduced `Scrap Cloth` requirement (from 6x -> 2x)
- Reduced `Sap` requirement (from 3x -> 2x)

### Saline Solution Adjustment
- Increased quantity (from 1x -> 4x)

### Small Medkit Adjustment
- Removed requirement for `Healing Salve` (from 8x -> 0x)
- Added requirement for `Dressed Bandage` (2x)

### Large Medkit Adjustment
- Removed requirement for `Dressed Bandage` (from 4x -> 0x)
- Added requirement for `Small Medkit` (2x)

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Durability items can be combined.
- *Some* items with durability can now be combined.
- Combinable items: `Water Purification Tablets`, `Makeshift Weapon Repair Kit`, `Weapon Repair Kit`, `9V Battery`.

### :white_check_mark: `Feature` All Weapons are Scrappable
> Eventually we plan to create weapon receiver items for higher tier weapon crafting.
- Any weapon can be reduced to basic scrap items.

### :arrow_up_small: `Improvement` Status effects are applied after spawning.
> Previously, we applied status effects immediately as they loaded in. This caused players to occasionally die in the spawn box.
> This improvement moves the application of these status effects to AFTER you press the spawn button.

### :arrow_up_small: `Improvement` Grenade improvements
> We'll add the ability to "cook" a grenade in the near future.
- Grenades roll much less now.
- Increased drop on the throw a bit to make the throw more predictable.

________

## :balance_scale: Changes

### :exclamation: `Change` `Water Purification Tablets` Changes
- Reduced use time (from 7s -> 4s)

### :exclamation: `Change` `Makeshift SMG` Attachments
- Added muzzle attachment

### :exclamation: `Change` Medical Item Spawn Rate Changes
> We'd like to push the meta here more towards controling areas like the hospital, and crafting medical items.
> With the changes to medical item crafting requirements, we feel this change should help with that.
- Reduced frequency of medical item spawns across the map, outside of areas specifically designated as medical POI (hospital, infirmaries, etc).
- Increased frequency of medical item spawwns within areas specifically designated as medical POI (hospital, infirmaries, etc).

### :exclamation: `Change` Weapon Spawn Rate Changes
> Again, attempting to make entice players more towards scavenging and crafting, we're reducing the rate that weapons spawn across the map.
> With the changes to the makeshift weapon crafting recipes, we believe this change should help push players to use crafted weapons more.
- Reduced frequency of medical item spawns across the map, outside of areas specifically designated as medical POI (hospital, infirmaries, etc).

________

## :bug: Bugfixes
- Fixed a bug which prevented the `Weapons` filter in the crafting menu from showing weapons.
- Fixed a bug which caused grenades to fail to throw frequently.
- Fixed a bug which prevented players from pinging into POIs sometimes.
- Fixed a bug which prevented players from shooting through fences and other similar materials.
- Fixed a bug where your character would appear to be standing when it was actually crouched.
- Hopefully fixed a bug which prevented certain interactions from being accessible (🤞)
- Hopefully fixed a bug which caused console users to accidentally scrap items due to their item context menu popping up when it shouldn't.

