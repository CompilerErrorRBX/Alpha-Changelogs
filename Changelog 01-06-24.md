# :bookmark_tabs:  Changelog xx/xx/xxxx - xx/xx/xxxx

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes

________

## :gun: New Items

### ITEM
- Compass

________

## :thread: New Crafting Recipes

### RECIPE
- DETAILS

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Added location pings
- Creates a ping at the player's mouse position that is shared with the player's squad.

### :white_check_mark: `Feature` Added Compass
- Shows what direction you're facing (in degrees).
- Displays location pings as well.

### :white_check_mark: `Feature` Added zombie staggering
- Zombies are stunned temporarily upon taking damage.

### :arrow_up_small: `Improvement` Player's name is displayed on their grave now.

### :arrow_up_small: `Improvement` Player gear is no longer removed from their ragdoll upon death.

### :arrow_up_small: `Improvement` Reductions to memory usage on the client.

### :arrow_up_small: `Improvement` Improved server memory usage.

### :arrow_up_small: `Improvement` Added indicator to items linked to quick use slots.

### :arrow_up_small: `Improvement` Equipment order on primary/secondary weapons is saved and loaded.

________

## :balance_scale: Changes

### :exclamation: `Change` Satisfied Status Effect Changes
- While hunger and thirst are above 50, gain an extra 0.5 stamina regen per second.

________

## :bug: Bugfixes
- Fixed a bug where no sound was played for other players when a player hit a zombie with a vehicle.
- Fixed a bug where blood splat sounds never played.
- Fixed a bug where most sounds didn't play.
- Fixed a bug where players could not move after rejoining.
- Fixed a bug where players could not interact with almost everything after rejoining.
- Fixed a bug where getting out of a car would sometimes kill the player.
- Fixed a bug where zombies were T-posed sometimes.
- Fixed a bug where bullets didn't hit terrain.
- Fixed a bug where melee didn't hit terrain.
- Fixed a bug where whistle sounds didn't play.
- Fixed a bug where saving data failed due to a bad datatype being stored.
- Fixed a bug where items would craft for free when taking from other inventory sources.
- Fixed a bug where items could be crafted for a single quantity of an item when more was required.
- Fixed a bug where only ammo from a single stack was loaded into a gun (causing an inaccurate ammo in gun display and thus "premature" reload)
- Fixed a bug where quick use slot items would sometimes remove other items in a quick use slot.
- Fixed a bug where items in an inventory were removed when scrapping the item that owned the inventory.
- Fixed a bug where an inventory would be wiped when dropped and picked up in certain cases.
