# 📑 Changelog 05/29/2025 - 06/xx/2025

## 🟢 Status `Unreleased`

## 💬 Patch Notes

________
## 🔫 Weapon Changes

### Recoil Changes (20% increase)
- AKM
- AWM
- M82
- Double Barrel Shotgun
- FAL
- Famas
- G36k
- R700
- M110k
- M4A1
- MK14
- MK18
- MK47
- MRAD
- PKM
- SCAR

### M249 / PKM
- Reduced speed nerf from 0.85x to 0.95x

## 🔫 New Items

### Makeshift Helmet
- A craftable helmet.
- Has a face shield slot and NVG slot.

### Makeshift Face Mask
- A craftable face mask.
- Fits only the Makeshift Helmet.
- Provides extra protection.

________

## 📢 Features and Improvements

### ✅ `Feature` Feature

### 🔼 `Improvement` [Server] Improved performance of determining simulated zombies.
- Roughly 830% faster algorithm to find simulated zombies.
- 99.9999997% smaller memory footprint (should also reduce memory garbage collection).

### 🔼 `Improvement` Vehicle speed calculation now matches with other in-game distance units.
- Previously, MPH in cars was based on a 1-stud-per-foot calculation, now it's closer to `0.784` studs per foot.

________

## 🗺️ Map Changes

### Redfield South M.B
- Redid existing military base layout.
- Moved to be on road south of Redfield.
- More military loot.

### Redfield West Neighborhood
- Redid terrain.
- Updated treelines.

### New Haven East Neighborhood
- Added new neighborhood.
- Fresh-Spawn neighborhood.

### Prison
- Increased military loot in the campsite at the front.
- Spread zombie spawns out a little bit more

### Chestnut Oaks
- Significantly reduced the amount of zombie spawns

## ⚖️ Changes

### ❗ `Change` Torso Armor now also protects the shoulders.
> Shotguns like the Mossberg used to one shot a full tier 2 armored player
> when all pellets hit the shoulder with about `118.8` damage point-blank.
> This is now closer to `60` damage point blank

### ❗ `Change` Updated ACOG/Reflex/RedDot attachments rendering.

### ❗ `Change` You can now hear other players reload their gun.

### ❗ `Change` POI music is now quieter.

### ❗ `Change` Updated gunshot sounds to match when the distant sound plays, so it no longer sounds like two shots.

### ❗ `Change` Reduced weight of lower tier medical items.
>- Bandage weight reduced from 0.15kg to 0.05kg.
>- Healing Salve weight reduced from 0.15kg to 0.1kg.
>- Dressed Bandage weight reduced from 0.25kg to 0.2kg.
>- Antibiotics weight reduced from 0.1kg to 0.05kg.

________

## 🐛 Bugfixes
- Fixed a bug which caused weapons to always spawn with attachments.
- Fixed a bug where the bomb shelter hatch could not be opened from the inside using the crank.
- Fixed a bug where weapon view models and usable item view models blocked and cancelled interactions.
- Fixed a bug which caused exploiter airdrops to all land really close to eachother.
- Fixed a bug where helicopter crash equipment crates did not get cleaned up.
- Fixed a bug which caused some invisible collision blocks to be visible in game.
- Fixed a bug causing sight attachments to be misaligned when ADSing.
- Fixed a bug causing gunshot sounds to not play correctly.
- Fixed a bug causing breathing sounds to never go away.
- Fixed a bug where desert eagle run animation had the left arm bent backwards.
- Fixed a bug where NPC players would always be in a jumping animation.
- Fixed a bug where zombie footstep sounds played at the wrong location sometimes.
- Fixed a bug where zombies would make noises from beyond audible distance (wasting performance).
- Fixed a bug where bird sounds were occasionally inside of the camera.
- Fixed a bug where the `Makeshift Vest` didn't actually have 1.5x armor (instead only had 1x).
- Fixed a bug which caused players to go up into the ceiling of the laundry building in the `Prison` POI.
- Fixed a bug which allowed bear traps to be placed against walls.
- Fixed a bug causing zombies to not make footstep sounds.
