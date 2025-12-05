# 📑 Changelog 10/26/2025 - 11/???/2025

## 🟢 Status `Unreleased`

## 💬 Patch Notes
________

## 🗺️ Map Changes

### North East of Airfield POI
- Redesigned small neighborhood to the north east of airfield.
- Now has spawn locations for players.
- Added some farm buildings near overpass south east of airfield

### Airfield
- Larger POI than before.
- More loot than before.
- More spread out looting.
- Added more hazmat zombies/medical spawns.

### Neighborhood
- New fresh-spawn neighborhood West of Almosta Town.

### Radio Tower
- Reduced mountain steepness.
  
________

## ✨ New Event

### Russian Airfield Raid

________

## 🔫 New Items

### Assault Pack
- Tier 4 Backpack
- 32 slot capacity
- 4500μ weight capacity

### M79 Grenade Launcher
- 40MM Grenade Launcher.
- Found in heli crash event.

### Makeshift Helmet
- Crafted Tier 1-2 helmet (tier 2 with additional face shield attachment)
- Has attachment slot for night vision, and makeshift face shield.
- Recipe: 1x Duct Tape, 30x Scrap Cloth, 25x Scrap Metal, 1x Tier 1 Helmet (any)

### Makeshift Face Shield
- Crafted face shield attachment for `Makeshift Helmet`. Increases head protection by 1 tier.
- Recipe: 30x Scrap Cloth, 25x Scrap Metal

### AS-VAL
- Internally supressed assault rifle.
- Takes 9x39MM ammunition.

### 9x39MM Ammunition
- Subsonic round.

### Holo Sight
- Similar to Red Dot Sight

________

## 📢 Features and Improvements

### 🔼 `Improvement` Improved weather system
- Clouds were almost always being mixed in too heavily to sunny days.
- Fixed there never being rain. Still uncommon, but more than before.

### 🔼 `Improvement` Improved UI/UX of compass.

### 🔼 `Improvement` Added screen shake effect when explosions explode nearby.

### 🔼 `Improvement` [MINOR] Skinned items can have proper ground, character, and view models now.
- Previously, only one model was allowed per skin.
- A consequence of doing this is that *nearly* every non-weapon equippable item in the game with durability will be repaired.

### 🔼 `Improvement` [MINOR] Upon loading, if an item cannot be equipped it will attempt to put the item into your inventory.
- Previously, the item would just be deleted.
________

## ⚖️ Changes

### ❗ `Change` Made interaction selection more focused
- Previously, interactions could be picked all the way out to the edge of the screen. Now, only interactions near the center of your screen will be selected.

### ❗ `Change` Increased spawn rate of NVG Tier 3 significantly in high tier spawns.

### ❗ `Change` Humvees are now lootable. They contain military gear/weapons/ammo

### ❗ `Change` Buffed Ghillie from T1 to T3 clothing

### ❗ `Change` Hunting clothing converted into tier 2 skin
- Existing hunting shirts will be converted into a `Tier 3 Shirt` with the `Black Tactical` skin applied.
- Existing hunting pants will be converted into `Tier 3 Pants` with the `Black Tactical` skin applied.

### ❗ `Change` Welding Mask is now eyewear item instead of a facemask.

### ❗ `Change` Old NVG is removed from the game.
- Existing NVG will be replaced with the equivalent new NVG items (provided there is space in your inventory).

### ❗ `Change` Run animations on rifles and pistols are now standardized.

### ❗ `Change` Updated Fists animation set.

### ❗ `Change` Updated Medkit animation set.

### ❗ `Change` Updated Bandage animation set.

### ❗ `Change` Updated Axe/Fire Axe animation set.

### ❗ `Change` SCAR-L animation set.

### ❗ `Change` Makeshift Hatchet animation set.

### ❗ `Change` Explosions now do 6x more damage to vehicles.
- They also now shake your screen.

### ❗ `Change` The delay when releasing a grenade from your hand is lessoned.

### ❗ `Change` Updated item models
- Shoes, Sneakers, and Boots all got new models
- Large medkit got a new model

### ❗ `Change` Phasing out Operator helmets
> These are replaced with their respective basic military helmet. This is to facilitate the future hearing protection changes.

### ❗ `Change` Buffed rare zombie drops
- Firefighter zombies now drop related items.
- Police zombies drop weapons and ammo more often.
- Sheriff zombies drop weapons and ammo more often.
- Military zombies drop items more often.

________

## 🐛 Bugfixes
- Fixed a bug which prevented interiors from modifying sounds profiles.
- Fixed a bug which prevented rain from occurring.
- Fixed a bug with several sounds not playing in the correct sound group.
- Fixed a bug which caused gun ammo to become desynced from the server. Potentially preventing you from reloading or shooting.
- Fixed a bug which occasionally prevented blood droplets from displaying on screen.
