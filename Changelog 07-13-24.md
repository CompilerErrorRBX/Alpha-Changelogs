# :bookmark_tabs:  Changelog 07/13/2024 - 07/19/2024
## :green_circle: Status `Released`

## :speech_balloon: Patch Notes
Mainly focused on fixing bugs in this patch. While fixing some camera issues, we took the opportunity to add a free-look option to the system.

Some notable bugs that were fixed include camera clipping, bunker ground loot not spawning, and some game breaking server-wide bugs.

________

## 🇺🇸 Added More Skins to Patriotic Skin Bundle
- Added `M82A1` Patriotic Skin
- Added `MRAD` Patriotic Skin
- Added `AWM` Patriotic Skin
- Added `Welding Mask` Patriotic Skin

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Added Free-Looking
- Ability to look around while running in a fixed direction.
- Default Keybind set to `Left Alt`

### :arrow_up_small: `Improvement` Reworked gun system camera
- Significantly improved camera occlusion. Should prevent users from seeing through walls when pushing their camera up againts it.
- Improved behavior of the third person camera when its near the character head. No longer resulting in two weapons being rendered.
- Improved client performance a bit as well, likely more noticable on high-end hardware.

________

## :balance_scale: Changes

### :exclamation: `Change` Changed Push-To-Talk keybind to `I` from `Left Alt`

________

## :bug: Bugfixes
- Fixed a bug which broke player initialization on some servers.
- Fixed a bug which prevented arrows from being retrievable after firing them.
- Fixed a bug which could prevent certain ground items from respawning in certain cases.
- Fixed a bug which caused cars to explode and get launched into to space in a certain case (hopefully 🤞)
- Fixed a bug which caused the inventories of items inside of a backpack to be wiped when rejoining.
- Fixed a bug which caused an issue during loading player equipment in some cases which would prevent many (or all) items from loading.
- Fixed a bug which caused zombies to spawn an empty loot bag sometimes.
- Fixed a bug which drew two gun models when the third person camera got close to the head.
- Fixed a bug which incorrectly oriented weapons in certain spawning situations.
- Fixed a bug which allowed players to see through walls by butting their camera up against them.
- Fixed a bug which allowed players to unbind essential controls, which made it impossible for them to play the game.
