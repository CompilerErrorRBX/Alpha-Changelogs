# :bookmark_tabs:  Changelog 04/15/2024 - 04/19/2024

## :green_circle: Status `Released`

## :speech_balloon: Patch Notes
This week we spent a bit of time on addressing some more frustrating bugs,
we also added a few items into the spawn pool and optimized a few processes.

We felt there were a few too many .50 BMG weapons in the loot pool, so we reduced their natural spawn rates.
Statistically speaking, the .50 BMGs are far more likely to be from natural spawn than they are to be from airdrops.

________

## :gun: New Items

### MK4 Pistol

### Welding Mask
- Face Mask, Aesthetic.

### Hunting Clothing
- Desert Camo
- Forest Camo
- Woodland Camo
- Snow
- Olive

________

## :loudspeaker: Features and Improvements

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

### :arrow_up_small: `Improvement` 10/22 Takedown gunshot far sound
> Previously 10/22 Takedown did not play a far gunshot sound. This has been changed.
> The sound travels less far than other guns sound, due to its low caliber.
> This applies to the new MK4 pistol as well.

________

## :balance_scale: Changes

### :exclamation: `Change` Removed view bobbing while moving (temporary).

### :exclamation: `Change` Reduced spawn rate of `MRAD` and `AWM` (from 0.5% each -> 0.125% each)

### :exclamation: `Change` Increased explosion radius of `Anti Personnel Landmines` (from 20 -> 30 studs)

________

## :bug: Bugfixes
- Fixed a bug which made grenades do no damage to players.
- Fixed a bug where zombie stimulus objects weren't properly cleaned up.
- Fixed a bug where weapons in the cabins would be placed on the floor when they shouldn't be.
- Fixed a bug where players would fall through a floor when going prone in some cases.
- Fixed a bug where some guns had an incorrect name on the death screen.
- Fixed a bug where players could respawn on their dead body by leaving and rejoining without respawning.
- Fixed a bug which could cause players to go invisble when joining near them.
- Believe we fixed a bug where players could kill eachother immediately after disbanding their squad in some cases.
- Believe we fixed a bug where sprinting would stop randomly (🤞)

## Known Issues
- Occasional desync in crouch-to-stand behavior (requires toggling crouch again to fix).
- Orientation of some ground items is incorrect (caused by the removal of the legacy workflow on ground items).
