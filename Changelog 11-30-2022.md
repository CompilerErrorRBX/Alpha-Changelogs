# :bookmark_tabs:  Changelog 11/30/2022 - 12/XX/2022

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes
This update we focused heavily on preparing the game for future unofficial server ownership and managment by our players. We want to provide our community with the tools to make their unique survival experience possible.

Additionally a lot of time was put into making the map feel more interesting and new areas were added.

________

## :star2: New Items
- :new: Bomber Jacket
  > Available in Black, Green, Blue, and Red. Tier 2 Shirt.
- :new: Puffer Jacket
  > Available in Black, Green, Blue, and Red. Tier 2 Shirt.
- :new: Track Pants
  > Available in Black, Green, Blue, and Light Blue. Tier 1 Pants.

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Added Loading Screen
Players are now presented with a loading screen while they wait for the game to start.

### :white_check_mark: `Feature` Server Configuration
Server configuration has been added and allows server owners to configure their server the way they want it. There's more to come for this feature, but this is a great start.
  
### :white_check_mark: `Feature` Server Player Management
Player management dashboard is live! This dashboard allows server owners and their designated moderators to perform various actions on their players. The dashboard also displays prior moderation logs for the specified player.

- Data Recovery
- Mimicking
  > Allows the moderator to see and control all of the available items and stats for a given player.
- Spectate
- Mute
  > Allows a duration and reason to be specified.
- Data Wipe
- Server Ban
  > Similarly with the Mute action, a duration and reason can also be specified here.
- Game Ban
  > Available only to offical game staff.

### :arrow_up_small: `Improvement` Ground Item Scrapping
Items can now be scrapped from the ground.

### :arrow_up_small: `Improvement` NPC Improvements
- Improved NPC interpolation logic.
  > NPCs are now interpolated by priority by default. Can be turned off in Debug Settings.
- Improved NPC player tracking.
- Improced NPC chase logic.
- Zombies now have glowing eyes.

________

## :balance_scale: Changes

### :exclamation: `Change` Various Map Refactoring and Additions
- Added new small town around the Hospital.
- Flattened the mountain where the radio tower was and temporarily removed the radio tower.
- Added small neighborhoods throughout the map.
- Added a new neighborhood in middle of map.
- Moved Mansion to middle of map.

### :exclamation: `Change` Added Clothing Tiers
Added a three tiered system to clothing.
- Shirt Tiers:
  - Tier 1 have 4 slots and 2kg carry capacity.
  - Tier 2 have 6 slots and 3kg carry capacity.
  - Tier 3 have 8 slots and 4kg carry capacity.
- Pants Tiers
  - Tier 1 have 4 slots and 2.5kg carry capacity.
  - Tier 2 have 6 slots and 3.5kg carry capacity.
  - Tier 3 have 8 slots and 4.5kg carry capacity.

Additionally, all existing clothing have been updated to reflect one of these tiers.

### :exclamation: `Change` Removed Large Backpack spawns from zombies.
We originally had large backpacks spawning on zombies so that we had a place for them to spawn.
This was early on in the game's development. We've removed this spawn since there are far better places for them to spawn.

________

## :bug: Bugfixes
- Fixed a defect which made NPCs ignore the "Ragdolls" user setting.
- Fixed a defect which made inventories unusable when picked up in a certain way.
- Fixed a defect where looted corpse inventories weren't removed from the player's UI upon despawn.

