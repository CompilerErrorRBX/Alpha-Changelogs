# :bookmark_tabs:  Changelog 03/18/2024 - 03/22/2024

## :green_circle: Status `Released`

## :speech_balloon: Patch Notes
This week, we focused primary on some performance issues and frustrating bugs players have been experiencing.

One big change in this patch was that we no longer persist logout position between servers, so to spawn in the same spot you were in last time you'll need to log into the same server.
We know this is a confusing change, and it will make much more sense once we implement the future server-list and lobby place.

We also introduced the newest gun and ammo type, `.22 LR`.
________

## :gun: New Items

### 10/22 Takedown
- .22 LR Rifle

### Uzi Rework
- Changed from 9MM Parabellum to .22 LR.
- Damage reduction (from 18 to 17).

________

## :thread: New Crafting Recipes

### .22 LR Bullet Recipe
- Recipe 3x `Gun Powder` and 1x `Scrap Metal`

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` FEATURE

### :arrow_up_small: `Improvement` Interaction accuracy
> Previously, it was difficult to interact with doors for a few reasons. This should feel a lot easier now after this change.
> It will also impact other interactions, although less noticable most likely.

### :arrow_up_small: `Improvement` Arms are now flat while prone
> Previously, in 3rd person, when looking forward your arms would be facing straight down. This caused guns and weapons to point through the floor.

### :arrow_up_small: `Improvement` Arm look animations are disabled on ladders

### :arrow_up_small: `Improvement` Death Screen now shows who killed you
- At the moment, a bleedout will not show who killed you on the death screen.

### :arrow_up_small: `Improvement` Client Performance Improvements
- Reworked how several things were loading in, should result in much smoother framerates overall.
- Cleaned up some memory usage. Reduced overall client memory usage by > 1 GB by addressing a memory leak 👀
- Deferred loading on ground items, containers, doors, etc.

________

## :balance_scale: Changes

### :exclamation: `Change` Increased SMG bullet velocity (from 1400 -> 1700)

### :exclamation: `Change` Last location is now only saved to the specific server instance the player played on.
> This change should prevent players from leaving the server, joining another and moving, then rejoining the server to be in a different location.
> The future state of this system will be almost everything being saved to the specific server (persisted on the server list). In the meantime we felt this was a good way to prevent the "move location on an empty server" strat.

________

## :bug: Bugfixes
- Fixed a bug which made it so all of a player's outfit was removed upon death.
- Fixed a bug where players had an invisible infection in a certain case.
