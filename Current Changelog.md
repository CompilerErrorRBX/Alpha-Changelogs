# 📑 Changelog 01/19/2026 - 02/06/2026

## 🟢 Status `Unreleased`

## 💬 Patch Notes
________

## 🔫 New Items

### Assault Vest
- Tier 3 Body Armor.
- Found in Humvee and bunk chests.

### Firefighter Helmet
- Tier1 Helmet.
- Found near `Fire Department` and on `Firefighter zombies`.

### Ballistic Helmet
- Tier1 Helmet.
- Replaces Tier2 `Military Helmet` in `Police Stations`.
- Much more common than previous helmet.

### Scissors
- Used to craft medkits.
- Spawns in `Bathroom Vanity`, `Kitchen Cabinet`, and `Filing Cabinet`.

### Reflex Gloves (tier 1 - 3)
- Dexterity glove class (other classes coming soon).
- 10-30% aim speed buff
- 10-30% climb speed buff
- 10-30% reload speed buff

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
- Changed texture on ghillie suit to appear more grassy, and added a hood.
________

## ⚖️ Changes

### ❗ `Change` AS-VAL changes (buff)
> Future state of this weapon will be again buffed with changes to the armor system. This weapon will have a higher armor penetration value than things like .223 or 7.62 soviet.
> This weapon belongs to a class of short-ranged, high damage, high armor penetration, high fire rate weapons. Think tier 3 SMGs.
- Increased base damage (from 18 -> 22)
- Increased headshot multiplier (from 2 -> 2.2)

### ❗ `Change` Makeshift Sniper changes
- Increased damage from 40 -> 50
- Decreased max distance from 1361m -> 972m

### ❗ `Change` Weapon Aim Speeds
- Pistols had aim speeds buffed from 1x -> 1.15x
- SMGs had aim speeds buffed from 1x -> 1.05x
- Rifles had aim speeds nerfed from 1x -> 0.9x
- Snipers had aim speeds nerfed from 1x -> 0.8x
- Shotguns had aim speeds nerfed from 1x -> 0.9x

### ❗ `Change` Weapon Lockers
- Separated `Military Weapon Lockers`, `Fire Station Lockers`, and `Police Weapon Lockers`.
- Military Weapon Lockers now spawn exclusively military loot.
- Police Weapon Lockers now spawn exclusively police loot.
- Fire Station Lockers now spawn firefighter loot and weapons.

### ❗ `Change` Buffed Medical loot in apartments
- Many apartment bathrooms have a closets which spawn `Industrial` items. Now they spawn `Bathroom Vanity` items.
- Added `Bathroom Vanity` ground items to bathroom shelves.

### ❗ `Change` Medkits now require scissors to craft

### ❗ `Change` M249 is now more rare

### ❗ `Change` Added `Under Barrel` attachment for `FN-FAL`

### ❗ `Change` Industrial areas now spawn construction helmets (Tier1)

### ❗ `Change` Residential garages now spawn more motorcycle helmets (Tier1)

### ❗ `Change` Minor Changes
- Reduced spawn rate of construction helmets on construction zombies (from 100% -> 30%).
- Reduced the spawn rate of `Duffle Bag` items in military gear spawns. This was unintentionally set to about 40% (when a backpack spawns) when it should have been about 6%.
- Firefighters zombies have a 6% gas mask drop rate (previously this never dropped).
- Added tier 2 pants spawns where tier 2 shirts spawn (this was an oversight)
- Buffed `Helmet` and `Vest` spawn rates in police stations.
- Retextured police vest.

________

## 🐛 Bugfixes
- Fixed a bug where players third person weapon models would get desynced.
- Fixed a bug where removing an optic from your weapon didn't unhide the ironsights.
- Fixed a bug which caused Russian FSB balaclava to be reskinned as a black mask.
