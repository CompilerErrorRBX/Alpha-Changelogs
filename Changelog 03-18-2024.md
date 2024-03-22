# :bookmark_tabs:  Changelog 03/18/2024 - xx/xx/xxxx

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

### :arrow_up_small: `Improvement` Death Screen now shows who killed you.
- At the moment, a bleedout will not show who killed you on the death screen.

### :arrow_up_small: `Improvement` Client Performance Improvements
- Reworked how several things were loading in, should result in fewer FPS drop spikes.
- Cleaned up some memory usage. Reduced overall client memory usage by > 1 GB by addressing a memory leak 👀
- Deferred loading on ground items, containers, doors, etc.

________

## :balance_scale: Changes

### :exclamation: `Change` Last location is now only saved to the specific server instance the player played on.
> This change should prevent players from leaving the server, joining another and moving, then rejoining the server to be in a different location.
> The future state of this system will be almost everything being saved to the specific server (persisted on the server list). In the meantime we felt this was a good way to prevent the "move location on an empty server" strat.

________

## :bug: Bugfixes
- Fixed a bug which made it so all of a player's outfit was removed upon death.
- Fixed a bug where players had an invisible infection in a certain case.
