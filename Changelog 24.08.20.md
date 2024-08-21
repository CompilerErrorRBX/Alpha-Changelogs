# :bookmark_tabs:  Changelog 08/20/2024 - xx/xx/xxxx

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

### :arrow_up_small: `Improvement` Network improvements
- Zombie initialization network packet now scales on `O(log(m)*n)` from `O(m*n)` (about 85% smaller packet size in the current case. From `~133KB` -> `20KB`)
- Zombie update network packet size reduced by ~15%. (Worst case, from `6.14MB/s` -> `5.25MB/s`)
- Reduced character network packet size by 90%

________

## :balance_scale: Changes

### :exclamation: `Change` CHANGE

________

## :bug: Bugfixes
- Fixed a bug which caused a hangup on the server which broke server/client initialization in rare cases.
- Fixed a bug where zombie update data was sent over the network unnecessarily. Likely a small boost to server performance here.
