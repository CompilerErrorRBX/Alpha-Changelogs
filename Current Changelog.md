# 📑 Changelog 02/13/2026 - xx/xx/2026

## 🟢 Status `Unreleased`

## 💬 Patch Notes

________

## 🔫 New Items

________

## 📢 Features and Improvements

### 🔼 `Improvement` Improved performance of zombies outside of render distance.
- Should be lower impact on animation step
- Slightly increased CPU cost to toggle between rendering.

________

## ⚖️ Changes

### ❗ `Change` Vehicle Spawns
- Police cars now only spawn near police stations.
- Sedans are now separate from Police cars, move a bit slower, and have a few more colors

### ❗ `Change` Sheds
- Buffed `Industrial` ground item spawns.

### ❗ `Change` Tool Cabinets
- Previously all tall cabinets in the game spawned `Kitchen` items.
- Tool Cabinets now spawn `IndustrialCabinet` items instead of `KitchenCabinet` items.
- This is the same spawn pool as `Industrial` ground items.

### ❗ `Change` Office Desks
- Previously all desks in the game spawned `Desk` items.
- Office Desks now spawn `OfficeDesk` items instead of `Desk` items.

### ❗ `Change` Locked Military Locker
- Buffed spawns from 4-6 to 5-8.

### ❗ `Change` Locked Medical Cabinet
- Added scissors to spawn pool.

### ❗ `Change` Construction Zombie
- Now spawns at construction areas.
- Reduced spawn percentage in generic zombie spawns.
- Drops `Industrial` items, `LowTierWeapon` items, and `IndustrialMelee` items.

### ❗ `Change` Temporarily disabled interior rendering test
> Checking to see if this might be what causes console users to have extremely low render distances.
> It seems highly unlikely, but we feel that the complaints started at roughly the same time as when we implemented
> this feature. So we'll disable this for a week or so to see how things are looking.

________

## 🐛 Bugfixes
- (Hopefully) fixed a bug which caused gun shot sounds to be buggy.
- (Hopefully} fixed a bug which caused the gun hud to disappear.
- Fixed a (Roblox) bug which prevented location pings from being audible.
- Fixed a bug where weapon models didn't show up in the character viewport inventory screen.
- Fixed a bug where Fire Station was incorrectly spawning too much ground loot.
- Fixed a bug where you can cough while dead.
- Fixed a bug where cars can spawn inside of eachother.
- Fixed a bug which caused zombies to appear to slide across your screen in certain cases.
