# :bookmark_tabs:  Changelog 02/08/2023 - 02/XX/2023

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes
This update we wanted to put a lot of focus into the zombies. We've noticed some scalability issues during testing sessions and those need to be addressed before we begin open weekend testing. This is not the only requirement to get us to open weekend testing but it is a very good step forward.
________

## :star2: New Items
- :new: 
________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Added bleeding effect
- Blood droplets roll down your screen (off to the sides) with a red border.

### :white_check_mark: `Feature` Added sound effect for critically low health.

### :arrow_up_small: `Improvement` Zombie Performance
- Improved zombie stimulus lookup time by 98% on average.
- Improved zombie movement and flocking logic performance by 80%.
- Reduced zombie network usage by 75%.
- Added over 100 new sounds to zombies.
- Overall zombie performance improved by ~10x.

### :arrow_up_small: `Improvement` Zombie Behavior
- Reduced the amount of spinning that zombies do.

### :arrow_up_small: `Improvement` Car Improvements
- Added Horn (H by default)
- Added Headlights (L by default)

________

## :balance_scale: Changes

### :exclamation: `Change` Camping Axe Weight
- Increased camping axe weight from 0.7kg -> 2.5kg.

### :exclamation: `Change` Map Changes
- Added food canning POI.
- Added various neighborhoods.
- Started on lobby area.
- Added Radio Tower.

### :exclamation: `Change` Gas Mask Effects
- Added breathing sound.
- Added slight sound muffling.

________

## :bug: Bugfixes
- Fixed a bug which caused inventories to bug out and disappear when a player tried to pick up an inventory item while their inventory was full. 
- Fixed a bug which made cars behave weirdly when a passenger entered for the first time.
- Fixed a bug which prevented slider based settings from loading properly.
- Fixed a bug which made some zombies go invisible for players who joined the game after the server started.
