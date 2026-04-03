# 📑 Changelog 02/28/2026 - 03/XX/2026

## 🟢 Status `Unreleased`

________

## 🔫 New Items

### Makeshift Shotgun
- New crafting recipe like all other makeshift weapons
  
________

## 🗺️ Map Changes

### Nuclear
- Moved a bit west of its current location.
- Remade to be a lot larger.
- Contains many lootable areas not in the gas zone.
- Increased military loot.

### Nuclear Apartments
- Small apartment/residential area added west of Nuclear.
- Good area for newly spawned players.

________

## 📢 Features and Improvements

### ✅ `Feature` Armor Penetration
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
- Medical Items now reduce bleeding by more to compensate.

### ❗ `Change` Weapon Damage
- Rebalanced guns headshot multipliers to account for increased damage from armor penetration.
- Reduced torso damage multiplier from 1.2x -> 1.1x
- Reduced arm damage multiplier from 1.1x -> 1.05x
- Buffed `Barret 50` base damage from 78 -> 84.
- Buffed `AWM` base damage from 78 -> 83.
- Buffed `MRAD` base damage from 78 -> 86.
- Changed `Makeshift Sniper` to have better base stats than `R700`, but less armor penetration.
- Changed `Makeshift SMG` to have better base stats than `UMP45`, buit less armor penetration.
- Configured `ASVAL` to have significantly better armor penetration compared to other Assault Rifles.

### ❗ `Change` Makeshift Weapons
- `Makeshift Sniper` base damage increased from 45 -> 55
- `Makeshift Sniper` durability increased from 50 -> 200
- `Makeshift SMG` base damage increased from 20 -> 25
- `Makeshift SMG` durability increased from 100 -> 500

### ❗ `Change` Spring
- Removed crafting recipe.
- Added to `Industrial` spawn pool.

### ❗ `Change` Bear Trap
- Increased crafting `Spring` requirement from 4 to 7.
- Added to `Hunting Cabin` spawn pool

### ❗ `Change` Makeshift SMG recipe
- Replaced requirement for chopped logs with sticks

### ❗ `Change` Makeshift Sniper recipe
- Replaced requirement for chopped logs with sticks

### ❗ `Change` Swinging with melee weapons no longer cancels your run state

### ❗ `Change` Buffed explosion damage to vehicles by 33%

________

## 🐛 Bugfixes
- Fixed a bug where zombies did not attack doors.
- Fixed a bug where zombies did not sprint in some cases.
- Fixed a bug which prevented users on a controller for placing or cancelling item placement.
- Fixed a bug where changing between third and first person while shooting would cause your bullets to become innaccurate.
- Fixed a bug with shotguns where you could reload them while shooting.
- Fixed some bugs with missing gun handling sounds.
- Fixed a bug where shooting while reloading causes your gun to shoot once the reload completes.
