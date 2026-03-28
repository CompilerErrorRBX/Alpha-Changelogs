# 📑 Changelog 02/28/2026 - 03/XX/2026

## 🟢 Status `Unreleased`
________

## 📢 Features and Improvements

### 🔼 `Feature` Armor Penetration
- Different guns now cause different amounts of armor penetration.
- Guns with higher armor penetration now ignore more of the armors protection in that area.
- Guns with lower armor penetration more closely resemble how damage previously felt with armor.
- Snipers have on average 0.5 armor penetration.
- Rifles have on average 0.25 armor penetration.
- SMGs have on average 0.1 armor penetration.
- Melee has on average 0.1 armor penetration.
- Shotguns have 0 armor penetration.
- New damage multiplier calculation: `lerp(1 - (armor_modifier * armor_level), 0.9, armor_pen)`
- Old damage multiplier calculation: `1 - (armor_modifier * armor_level)`

### 🔼 `Improvement` Improved zombie collision handling
- Should be less likely to pass through objects now, although probably not perfect.
________

## ⚖️ Changes

### ❗ `Change` Bleeding System
- Max bleeds increased from 4 to 10.
- Bleed damage reduced from 0.5 hp/s/tier to 0.25 hp/s/tier
- Different guns cause different amounts of bleeding per shot. Snipers and Rifles deal more bleed damage than pistols and shotguns.

### ❗ `Change` Increased makeshift weapon durability
- `Makeshift SMG` increased from 100 -> 500
- `Makeshift Sniper` increased from 50 -> 200

### ❗ `Change` Makeshift SMG recipe
- Replaced requirement for chopped logs with sticks

### ❗ `Change` Makeshift Sniper recipe
- Replaced requirement for chopped logs with sticks

### ❗ `Change` Swinging with melee weapons no longer cancels your run state

### ❗ `Change` Temporarily removed `Spring` crafting recipe

### ❗ `Change` Increased `Bear Trap` `Spring` requirement from 4 to 7

________

## 🐛 Bugfixes
- Fixed a bug where zombies did not attack doors.
- Fixed a bug where zombies did not sprint in some cases.
- Fixed a bug which prevented users on a controller for placing or cancelling item placement.
- Fixed a bug where changing between third and first person while shooting would cause your bullets to become innaccurate.
- Fixed a bug with shotguns where you could reload them while shooting.
- Fixed some bugs with missing gun handling sounds.
