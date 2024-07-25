# :bookmark_tabs:  Changelog 07/22/2024 - 07/24/2024

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes
We're continuing to work out all of the bugs and unpolished common experiences in the game.

________

## :loudspeaker: Features and Improvements

### :arrow_up_small: `Improvement` Drastically improved container search interactions in unstable ping situations.
> Containers used to fail to open frequently in cases where client ping was unstable. The container interaction now
> accomodates this situation better now. Players should expect far fewer issues with opening containers now.

### :arrow_up_small: `Improvement` Improved logic around overlapping keybinds in some cases.
- Scrapping with F no longer toggles flashlight.

### :arrow_up_small: `Improvement` Improved bleeding particles.
- Blood particles should be far less likely to pass through floors now.

### :arrow_up_small: `Improvement` Improved visiblity of radial menu items for pinging.

________

## :balance_scale: Changes

### :exclamation: `Change` Removed `Watch` and `Defend` Pings
### :exclamation: `Change` Added `Heals` and `Ammo` Pings

### :exclamation: `Change` Reduced rate and quantities of ammo spawns within guns.

________

## :bug: Bugfixes
- Fixed a bug which caused an incorrect weight value being displayed with moving a gun into a different slot.
- Fixed a visual bug which caused the inventories associated with an item to disappear when the item was dropped and picked up quickly.
- Fixed a bug which caused a spashing footstep sound in random places on the map.
- Fixed a bug which made a player characters angle vertically while falling in prone.
- Fixed a bug which allowed an item to belong to multiple inventory slots, allowing for potential item duplication.
- Attempted to fix a bug which causes players to "combat log" while the status effect is not present. 🤞
