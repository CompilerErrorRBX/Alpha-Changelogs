# 📑 Changelog 04/06/2026 - xx/xx/2026

## 🟢 Status `Unreleased`
________

## 🔫 New Items

### 300 Blackout
- New ammo type for guns chambered in .300 BLK
- Generally harder hitting than SMGs, but weaker base damage than .223
- More armor penetration than .223

### Honey Badger
- New weapon that shoots .300 Blackout
- Built in suppressor
- Similar to AS-VAL. Short range, lower damage, higher armor penetration.
- Located where you find most military loot.
  
________

## 📢 Features and Improvements

### ✅ `Feature` [QOL] Added default skin setting
> Items can be configured with a default skin from the item skinnning interface.
> This will cause an item's skin to be set to your preferred default if the item was not skinned by another player.
> One caveat to this is that this change required additional data to be recorded for the items, which means that existing skin settings
> will not be recognized as "player set", so upon picking them up for the first time, their skin will be overridden to your preferred default (if set).

### 🔼 `Improvement` Improvements to Skin UI
- Highlights added for currently equipped skin and currently viewed skin.

### 🔼 `Improvement` Zombies can visibly miss attacks now.
- Previously zombies would not play an attack animation if they failed an attack.
- Now you will always see them attack regardless if they hit you or not.

________

## ⚖️ Changes

### ❗ `Change` ASVAL
- Increased bullet speed by 30%.
- Increased base damage from 22 -> 24.

### ❗ `Change` Pistol Ammo
- Reduced weight of 45 ACP from 1.6u to 1.2u
- Reduced weight of 9mm from 1.6u to 1.0u
- Reduced weight of 22lr from 1.0u to 0.8u
- Reduced weight of 44 magnum from 1.6u to 1.4u

### ❗ `Change` Military Zombies
- Reduced health from 100 -> 90

________

## 🐛 Bugfixes
- Fixed a bug which caused zombies to never return to their spawn. (this was especially disruptive during large combat scenarios, where zombies would arrive from much further away than intended)
- Fixed a bug which prevented zombies from matching target speed upon reaching attack range (this made them very difficult to hit up close
- Fixed a bug which caused a new sound to be generated every time a player entered or exitted a vehicle, never being cleaned up.
- Potentitally fixed a bug which caused vehicles to fling upon entering (some kind of Roblox physics change seems to be the culprit here)
