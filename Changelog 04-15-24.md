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

### :arrow_up_small: `Improvement` Cleaned up some squad notification logic
- Removed the redundant "Invite Closed" message when a player joins a squad.

### :arrow_up_small: `Improvement` Minor server performance improvements
- Cleaned up some looping code to make it run more efficiently, should provide some smoother frames on the server.

### :arrow_up_small: `Improvement` Ground item optimizations
- Cleaned up some legacy workflows with ground items which reduces their overall part count.

### :arrow_up_small: `Improvement` Accuracy of most relevant interactables
> Previously, it could be difficult to interact with an item ontop of a cabinet for example.
> This improvement helps to, once again, prioritize the interactable that's under your mouse cursor.

________

## :balance_scale: Changes

### :exclamation: `Change` Removed view bobbing while moving (temporary).

### :exclamation: `Change` Reduced spawn rate of `MRAD` and `AWM` (from 0.5% each -> 0.125% each)

### :exclamation: `Change` Increased explosion radius of `Anti Personnel Landmines` (from 20 -> 30 studs)

________

## :bug: Bugfixes
- Fixed a bug which made grenades do no damage to players.
- Fixed a bug where stimulus objects weren't properly cleaned up.
- Fixed a bug where weapons in the cabins would be placed on the floor when they shouldn't be.
- Fixed a bug where players would fall through a floor when going prone in some cases.
- Fixed a bug where some guns had an incorrect name on the death screen.
- Fixed a bug where players could respawn on their dead body by leaving and rejoining without respawning.

- Believe we fixed a bug where players could kill eachother immediately after disbanding their squad in some cases.
- Believe we fixed a bug where sprinting would stop randomly (🤞)

## Known Issues
- Occasional desync in crouch-to-stand behavior (requires toggling crouch again to fix).
- Jumping while crouched causes a higher jump than intended.
