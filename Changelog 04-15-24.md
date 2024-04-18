# :bookmark_tabs:  Changelog 04/15/2024 - xx/xx/xxxx

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes

________

## :gun: New Items

### ITEM
- DETAILS

________

## :thread: New Crafting Recipes

### RECIPE
- DETAILS

________

## :loudspeaker: Features and Improvements


### :white_check_mark: `Feature` FEATURE

### :arrow_up_small: `Improvement` Character movement and collision improvements
- Improved how characters behave when walking off a ledge.
- Improved how characters behave on slopwed terrain in general.
- Improved collisions when walking off of a sloped ledge.

### :arrow_up_small: `Improvement` Minor server performance improvements
- Cleaned up some looping code to make it run more efficiently, should provide some smoother frames on the server.

________

## :balance_scale: Changes

### :exclamation: `Change` Removed viewbobbing while moving.

### :exclamation: `Change` Reduced spawn rate of MRAD and AWM (from 0.5% each -> 0.125% each)

________

## :bug: Bugfixes
- Fixed a bug which made grenades do no damage to players.
- Fixed a bug where stimulus objects weren't properly cleaned up.
- Fixed a bug where weapons in the cabins would be placed on the floor when they shouldn't be.
- Fixed a bug where players would fall through a floor when going prone in some cases.
- Fixed a bug where some guns had an incorrect name on the death screen.
- Fixed a bug where players could respawn on their dead body by leaving and rejoining without respawning.
- Believe we fixed a bug where sprinting would stop randomly (🤞)

## Known Issues
- Occasional desync in crouch-to-stand behavior (requires toggling crouch again to fix)
