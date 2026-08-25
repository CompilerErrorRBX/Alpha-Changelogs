# 📑 Changelog 04/06/2026 - xx/xx/2026

## 🟢 Status `Unreleased`
________

## 🔫 New Items

________

## 🗺️ Map Changes

________

## 📢 Features and Improvements

### ✅ `Feature` Reworked the Combat Log system
- Removed combat 2x in favor of a single stage system.
- Upon leaving in combat, your character stays behind in game for the duration of the timer
- If your character is killed, you lose your stuff, otherwise items are kept.

### ✅ `Feature` Vehicle System Rework
- Improved client-side performance for vehicle simulations.
- Condensed all vehicle interactions into a single interaction with multiple options (hold interaction key)
- Added ability to switch seats while inside of a car (hold interaction key)
- Added storage slots to vehicles (hold interaction key to access storage)
- Fixed a bug with cars which could improperly kill zombies, leading to a client/server desync and the infamous "invisible zombie" bug (not positive this is the *only* case)

### ✅ `Feature` Grave Equipment Slot
- Choose your grave from a new slot in the equipment menu click it to browse and preview every grave you own in 3D.

### ✅ `Feature` Search Nearby Containers
- Unsearched containers now show up around you ready to be searched, instead of staying hidden until opened.

### ✅ `Feature` Quick Use Menu
- Opening the quick use menu now cancels any item action in progress (like bandaging), so you can react instantly.
- Item counts now show as a badge on each option and update live while the menu is open.
- Items without a flat icon (grenades, weapons) now show their 3D model in the center of the menu.

### ✅ `Feature` Inventory & Nearby Items
- Storage panels and loose items near you now lay out neatly no more overlapping windows, items off the edge of the screen, or wasted empty space.
- Storage slots now fill their panels evenly.

### ✅ `Feature` Support for multiple recipes to craft an item
> This has greater future value than today. Eventually this will have greater use in crafting benches and other crafters.

### ✅ `Feature` Add search to several UIs
- Settings is now fully searchable.
- Shop is searchable.
- Shop inventory is searchable.
- Improved search in crafting UI.

### 🔼 `Improvement` Status Effect Redesign
- Status effects now stack and queue properly overlapping heals combine into one stronger effect instead of waiting in line.

### 🔼 `Improvement` Console QOL Update
- Better controller support across the board, including selecting weapons and quick use items from a radial menu.

### 🔼 `Improvement` Quick Item Move
- Items now move into a container from your inventory when you click them with a container open.
- Holding Shift + click will move a specified amount.

### 🔼 `Improvement` Purchase buttons take you to the product
- Instead of just dropping you in the store, these buttons now accurately find the associated products that the item belongs to.

### 🔼 `Improvement` Use With QOL Update
- Clicking a use with item (water purification tablets) will now show a list of items it can be used with next to it.

### 🔼 `Improvement` Airdrop plane is now visible on the map

### 🔼 `Improvement` Various Shop Improvements

### 🔼 `Improvement` Brought back guns on back

### 🔼 `Improvement` Performance
- Item models are now cached and reused everywhere they're shown, reducing stutter when browsing inventories and loot.
- Item icons are almost all images instead of viewport frame renders now (some noticeable changes in item icons, but all representative still).
- Reduced the resolution of several unnecessarily high resolution images.
- The crafting menu no longer does hidden work while closed.
- Reduced amount of work performed on weapon slots.

________

## ⚖️ Changes

### ❗ `Change` CHANGE

________

## 🐛 Bugfixes
- Fixed a major bug where doors could desync and become misaligned visually.
- Fixed a very long standing bug where being invited to a squad would occasionally allow you to see where the members of that squad were.
- Fixed another very long standing bug where weapons linked to the quick use bar never being cleared on death.
- Fixed a bug where quick craft items didn't show as greyed out when not craftable.
- Fixed a bug where PS5 users would experience most items moving around in their inventory (Viewport frame bug in Roblox, now using images).
- Fixed a bug where whistling and glass bottles breaking didn't attract zombies.
- Fixed inventories being able to hold one more item than their limit allowed in a specific case.
- Fixed weapons on the ground showing the wrong attachments.
- Fixed over-sized ground piles behaving incorrectly when picked up.
- Fixed a minor bug where a loot grave could collide with a player that the dead player was standing on.
- Fixed a bug where you couldn't hear the burning effect from being on fire while in first person.
- Fixed a bug which prevented zombies from attacking a player in various stances and in various cases.
- Fixed a bug which allowed zombies to hit the player from further away than intended in certain cases.
- Fixed a bug which caused gun attachments in the selected gun HUD UI to be scattered in some cases.
- Fixed a bug which allowed melee spamming by rapidly switching between melees in the quick use bar.
- Fixed a niche bug where snowballs would contain unlimited quantities.
- Fixed a bug where some percentages showed a super long value (i.e. 32.000000000000002%)
- Fixed a bug where the Gingerbread Helmet was missing the NVG attachment reference, so it wouldn't show NVGs.
- Fixed a bug which allowed bear traps to be placed at odd angles on top of items.
