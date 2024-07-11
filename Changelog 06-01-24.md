# :bookmark_tabs:  Changelog 06/01/2024 - xx/xx/xxxx

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes
With the game being in a rather buggy state, we set out this time to improve some of the longer standing issues.

Vehicles were a big rework this time, we wanted them to feel more fluid, but also be more stable and interesting.
So we redid out vehicle system, added health which allows us to add another dimension to PVP and PVE with vehicles.
We're still working to get these more stable and fix some of the new and existing bugs.

We also wanted to take this time to refactor the item spawning system. Originally, it was only designed to spawn items
within a container, which was causing us to have multiple spawn systems that were each effectively trying to do the same
thing. Now we have a centralized system that is flexible and maintains consistency across all of the different spawn systems.

The reworked spawn system also fixes several bugs with backpacks and clothing inventories being wiped. It also addresses
some item initialization issues which caused problems like one of the attachment slots missing on some guns, which caused
issues like a gun that didn't actually consume ammo.

________

## :gun: New Items

### Wrench
- Melee
- Repairs vehicles

________

## :thread: New Crafting Recipes

### Frag Grenade Recipe
- Requires `Scrap Metal` (x25)
- Requires `Gun Powder` (x75)

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Combat Log Penalties
- Added a really basic combat log penalty until the more ideal system is ready.

### :white_check_mark: `Feature` Added Bullet Collaterals to Zombies
- Bullets can pen zombies and hit zombies behind them now.

### :white_check_mark: `Feature` Vehicle Overhaul
> Not our final vision for cars by any means, but we felt cars were really lacking. So we spent some time improving their physics.
- Cars take damage now.
- Zombies no longer walk through cars (excluding when a player drives through them).
- Zombies attack cars.
- Cars should no longer freeze momentarily when shot.

### :arrow_up_small: `Improvement` Item Spawn System Rework
- Refactored spawn logic to be identical between containers and ground items.
- Improved flexibility of complex spawn logic.
- Improved performance of item respawning.
- Ground items can now spawn in groups (i.e. a gun with boxes of ammo that belong to it next to eachother)

### :arrow_up_small: `Improvement` Context action keybinds now work on ground items
- Previously, trying to scrap an item on the ground with the scrap keybind did nothing.

________

## :balance_scale: Changes

### :exclamation: `Change` Uzi is now a sidearm.

### :exclamation: `Change` Increased spawn rate of Chinese Soldier Zombie by 1000%.

### :exclamation: `Change` Temporarily disabled last location saving in servers.
> Players were abusing the fact that while loading in, the buildings around them weren't fully visible yet and being able to see players through walls.
> So we've disabled location saving to prevent relogging in the same spot to abuse this from occurring.

________

## :arrows_clockwise: Minor Changes
- Removed Russian weapon spawns from outside of Chinese bunker.

________

## :bug: Bugfixes
- Fixed a bug which caused vehicles to be launched into space when two players entered them sometimes.
- Fixed a bug which caused invisible drivers in vehicles sometimes (we hope 🤞)
- Fixed a bug where Chinese Soldier Zombies would spawn inside of the floor in the reactor room sometimes.
- Fixed a bug which caused rain to never happen.
- Fixed a bug which allowed shotguns to wallbang in certain cases.
- Fixed a bug which caused zombie corpses to fall through the ground.
- Fixed a bug which caused melee to do no damage to players.
- Fixed a bug which prevented ground items and container items from being removed when the Chinese bunker POI doors closed.
- Fixed a bug which caused one of the attachment slots to be missing for a weapon, also allowing it to fire without consuming ammo.
- Fixed a bug which caused some containers to show the wrong items. Occasionally, some players might see an empty container while it has items for others.
- Fixed a bug which prevented players from actually cancelling context actions (like scrapping, healing, eating, etc) when clicking on the item again.
- Fixed a bug which caused guns to be misaligned occasionally when a player loads into the game.
