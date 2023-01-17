# :bookmark_tabs:  Changelog 12/09/2022 - 01/XX/2023

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes

________

## :star2: New Crafting Recipes
- Added crafting recipes for all ammo types.

## :star2: New Items
- Added Metal Scrap.
  > Can be obtained by scrapping empty cans for now.

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Guns No Longer Break
> When a gun reaches 0 durability it would break. This is no longer the case. Now, instead, they will become non-functional and the player can fix them with a weapon repair kit.

### :white_check_mark: `Feature` Small Trees are Gatherable
> By interacting with the small trees on the map you can obtain sticks from them.

### :white_check_mark: `Feature` Added Generic Eating Animation

### :white_check_mark: `Feature` Added Tactical Zombie
> Extremely rare spawn, but always has very good loot on it.

### :arrow_up_small: `Improvement` Impoved Crafting UI
- Crafting UI better shows what items can be crafted and can't be crafted.
- Craft max button is functional.
- Craft filtering is functional.
- Recipes that yield a quantity greater than 1 now show how many items they make. (TODO)
- Items in your vicinity can now be used in crafting recipes. (TODO)

### :arrow_up_small: `Improvement` Inventory Keybind
> When rebinding the inventory key, occasionally players would have an issue where typing could open the inventory.

### :arrow_up_small: `Improvement` Improved NPC Stimulus Performance
> More to do here still, but this is a step in the right direction.

### :arrow_up_small: `Improvement` Reduced Spawn Rate of Weapon Attachments

________

## :balance_scale: Changes

### :exclamation: `Change` Items are less likely to spawn in larger quantities now
- Added an exponential modifier to item quantities, so a max quantity spawn is exponentially less likely than a minimum spawn.

### :exclamation: `Change` Removed Motorcycle From Vehicle Spawn Pool (Temporary)

________

## :bug: Bugfixes
- Fixed a bug where melee did no damage.
- Fixed several bugs with squad tags 🤞.
- Fixed a bug where NPCs didn't respawn when they fell off the map.
- Fixed a bug where some NPC information wasn't cleaned up when they died.
- Fixed a bug where player equipment was not unloaded when they got too far away to be rendered.
- Fixed a bug where zombies would sometimes be invisible (I think, please let us know if you still experience this)
