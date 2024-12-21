# :bookmark_tabs:  Changelog 03/01/2024 - 03/08/2024

## :green_circle: Status `Released`

## :speech_balloon: Patch Notes
This week we wanted to spend some time on improving new user experience. We added a contextual hotkey bar to notify new players of their available controls.
We definitely want to do more to improve new player experience but we believe this is a helpful first step!

We also wanted to improve the experience of crafting makeshift weapons. One of the biggest pain points was in the need for a camp axe. To address this,
we added the new `Makeshift Axe. Players can craft a makeshift axe with relative ease, and it doubles as an effective melee weapon.
Some other pain points in makeshift crafting was in the excessively expensive recipes. We've reduced recipe item requirements significantly.
We believe these changes make these a much more viable option.

We've also made some significant changes to how items are affected by player death. This should help to create more scarcity, and increase the usefulness of repair kits.
We have yet to create an item to repair melee weapons, but we suspect this is a non-issue for the moment.

We've also fixed several outstanding bugs.

________

## :gun: New Items

### `AWM`
- .50 BMG Sniper rifle.
- Spawns where `MRAD` spawns.
- (Yes, we know this gun does not have a .50 BMG barreled action IRL.)

### `Makeshift Axe`
- Chops trees.
- Melee.


________

## :thread: New Crafting Recipes

### `Makeshift Axe` Recipe
- 20x `Scrap Metal`.
- 2x `Duct Tape`.

### Changes to `Makeshift SMG` Recipe
- Reduced `Scrap Metal` (from 150 -> 50).
- Removed `Duct Tape` ingredient.
- Reduced `Springs` (from 10 -> 3).
- Reduced `Composite Fiber` (from 4 -> 2).
- Reduced `Chopped Logs` (from 5 -> 4).

### Changes to `Makeshift Sniper` Recipe
- Reduced `Scrap Metal` (from 200 -> 75).
- Removed `Duct Tape` ingredient.
- Reduced `Springs` (from 4 -> 1).

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Item Durability Changes.
- Upon death, all items with durability are reduced by 25%.

### :white_check_mark: `Feature` Contextual Keybind UI
- Added a UI to show all active keybinds based on current context.

### :white_check_mark: `Feature` Bunker Loot Changes
- Buffed bunker loot spawns.
- Loot now only spawns when a player opens the hatch.

### :arrow_up_small: `Improvement` Fixed a large memory leak with ground items.

### :arrow_up_small: `Improvement` Improved the behavior of entering and exiting a ladder.

### :arrow_up_small: `Improvement` Technical Improvements
- When climbing, character rotation is now locked to ladder direction.
- Fixed feet angles in character animations

________

## :balance_scale: Changes

### :exclamation: `Change` Reduced range of melee weapons across the board.

### :exclamation: `Change` Reduced melee weapon durability by 50% across the board.

### :exclamation: `Change` Melee item damage reductions:
- `Camp Axe`, `Crowbar`, `Shovel`.

### :exclamation: `Change` Doubled `Makeshift SMG` durability (from 100 -> 200).

### :exclamation: `Change` Drink changes
- `Dirty Water` now gives 25 thirst (20 -> 25)
- `Energy Drink` now gives 20 thirst (5 -> 20)
- `Cola` now gives 20 thirst (25 -> 20)

### :exclamation: `Change` Reduced the use time on `Bandage`
- Reduced time to apply normal bandages (3s -> 2s).

### :exclamation: `Change` Reduced spawn rate of weapons across the map.
- Large reduction in spawn rate of weapons in beds, satchels and briefcases.
- Reduced amount of sniper spawn chances in the map.
- General reduction in spawn rates across all weapon spawns in the map.

### :exclamation: `Change` Reduced most primary/secondary item durability (from 500 -> 400).

### :exclamation: `Change` Reduced most sidearm item durability (from 500 -> 200).

### :exclamation: `Change` Reduced spawn rate of weapon repair kits.

### :exclamation: `Change` `Duct Tape` item changes
- Increased carry capacity (from 4 -> 12).
- Decreased weight (from 0.35kg -> 0.3kg).
- Can now be used to repair Hazmat clothing.
  
________

## :bug: Bugfixes
- Fixed a bug which allowed players to pick up items while they were dead.
- Fixed a bug which caused an item count desync in the crafting system when a player died.
- Fixed a bug where players were teleporting vertically in some situations.
- Fixed a bug where using an item was stuck on the item until the player dropped it from their inventory.
- Fixed a bug where players could not cancel item consumption.
