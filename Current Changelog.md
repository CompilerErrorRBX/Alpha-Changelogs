# 📑 Changelog 01/19/2026 - 01/xx/2026

## 🟢 Status `Unreleased`

## 💬 Patch Notes
________

## 🔫 New Items

### Assault Vest
- Tier 3 Body Armor.
- Found in Humvee and bunk chests.

### Firefighter Helmet
- Tier1 Helmet skin.
- Found near Fire Department and on Firefighter zombies

### Scissors
- Used to craft medkits.
- Spawns in `Bathroom Vanity`.
________

## 🗺️ Map Changes

### North Paradise
- More apartments.
- Removed farmland.
- Added neighborhood.
- Connected it with existing neighborhood.
- Added military checkpoint.
- Added small survivor camp.

________

## 📢 Features and Improvements

### ✅ `Feature` 

### 🔼 `Improvement` Improved the look of the first person view arms
> Previously, they had a long stretched out texture at the end. Now we pull detail from elsewhere in the texture for clothing.
- Added support for gloves and other things attached to the arms.
- Ghillie suits are now visible on the first person arms model.

### 🔼 `Improvement` Minor Improvements
- Improved UV texture mapping of the ground pants model.
- Improved UV texture mapping of the ground shirts model.
________

## ⚖️ Changes

### ❗ `Change` AS-VAL changes (buff)
> Future state of this weapon will be again buffed with changes to the armor system. This weapon will have a higher armor penetration value than things like .223 or 7.62 soviet.
> This weapon belongs to a class of short-ranged, high damage, high armor penetration, high fire rate weapons. Think tier 3 SMGs.
- Increased base damage (from 18 -> 22)
- Increased headshot multiplier (from 2 -> 2.2)

### ❗ `Change` Buffed Medical loot in apartments
- Many apartment bathrooms have a closets which spawn `Industrial` items. Now they spawn `Bathroom Vanity` items.
- Added `Bathroom Vanity` ground items to bathroom shelves.

### ❗ `Change` Medkits now require scissors to craft

### ❗ `Change` M249 is now more rare

### ❗ `Change` Industrial areas now spawn construction helmets (Tier1)

### ❗ `Change` Residential garages now spawn more motorcycle helmets (Tier1)

### ❗ `Change` Minor Changes
- Reduced spawn rate of construction helmets on construction zombies (from 100% -> 30%).
- Reduced the spawn rate of `Duffle Bag` items in military gear spawns. This was unintentionally set to about 40% (when a backpack spawns) when it should have been about 4%.
- Firefighters zombies have a 6% gas mask drop rate (previously this never dropped).
- Added tier 2 pants spawns where tier 2 shirts spawn (this was an oversight)
- Added `Underbarrel` attachment point for the `FN-FAL`

________

## 🐛 Bugfixes
- Fixed a bug where players third person weapon models would get desynced.
- Fixed a bug where removing an optic from your weapon didn't unhide the ironsights.
- Fixed a bug which caused Russian FSB balaclava to be reskinned as a black mask.
