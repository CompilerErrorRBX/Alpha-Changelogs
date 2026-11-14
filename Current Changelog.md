# 📑 Changelog 11/07/2026 - 11/xx/2026

## 🟢 Status `Unreleased`
________

## 📢 Features and Improvements

### ✅ `Feature` Feature

### 🔼 `Improvement` Leaning now cancels sprint instead of being blocked
- Previously, leaning was blocked while sprinting.

### 🔼 `Improvement` Rewrote the anti-fly system
- Hopefully should have far less false positives and deal with cheating faster.
- Fixes a major bug with the previous version which caused major rubberbanding issues.

### 🔼 `Improvement` Car engine interaction is now active while in the car, so batteries and sparkplugs can be managed while in the car.

### 🔼 `Improvement` Improved server performance
- Still more improvements to be made, we're having to deal with these issues incrementally. With all of the new systems there's a lot of nuance to this issue.

### 🔼 `Improvement` Added gas filters as spawns on gas masks.
- Also increased spawn rates.

________

## ⚖️ Changes

### ❗ `Change` [Potentially annoying] Changed interaction key from `E` to `F` on Keyboard
- This frees up Q/E for leaning

### ❗ `Change` Made lean use `Q`/`E` and are `Hold` by default

### ❗ `Change` Removed `Q` as default keybind for toggle aim (now unbound)

### ❗ `Change` Made night a bit brighter.

### 🔫 Crafting Recipe Changes

### Makeshift Vest
- Reduced `Scrap Metal` requirement (from 50 -> 12)
- Reduced `Scrap Cloth` requirement (from 50 -> 12)
- Reduced `Stick` requirement (from 4 -> 2)

### Makeshift Armor Plate
- Removed `Composite Fiber` requirement
- Reduced `Scrap Metal` requirement (from 50 -> 40)
- Added `Scrap Cloth` requirement (20x)
- Added `Duct Tape` requirement (1x)

### 🔫 Item Changes
- Reduced `Car Battery` weight by 25% (from 8kg to 6kg)

________

## 🐛 Bugfixes
- [MAJOR] Fixed a bug where players would be rubberbanded super far back in certain cases.
- Fixed a bug where player's mouse was getting stuck in some cases.
- Fixed a bug where `Weapon Repair Kit` could add battery to NVGs.
- Fixed a bug where the quick craft slots couldn't be clicked to be used.
- Fixed a bug where suppressors didn't actually get used up when they ran out of durability.
- Fixed a bug preventing many of the vehicle spawns, and all police car spawns.
- (Hopefully) fixed a bug which allowed players to take fall damage upon spawning.
- Fixed a bug which caused players to spawn without clicking anything in the spawn menu.

