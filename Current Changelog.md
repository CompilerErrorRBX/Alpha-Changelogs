# 📑 Changelog 12/26/2025 - --/--/2025

## 🟢 Status `Unreleased`

## 💬 Patch Notes
________

________

## 📢 Features and Improvements

### ✅ `Feature` Added feature to perform product data recoveries.
- Hopefully we never need to use this again, but it makes doing more complex data recoveries trivial in the future.

### 🔼 `Improvement` Disabled chat for users who are not age verified.

### 🔼 `Improvement` Significant fixes to server performance.
- Santa Event contained CPU leaks which, over time, caused significant performance slowdowns on servers.
- Found some old code which should not have been running which was consuming about 10% of available frame time to maintain 60 FPS on servers.

### 🔼 `Improvement` Improvements to various moderation tools.
________

## ⚖️ Changes

### ❗ `Change` Ended the Santa Christmas event.
- Santa Bundle is no longer for sale.
- Christmas crates are not longer for sale.
- Snow Ghillie no longer obtainable.
- Map returned to greener pastures.

________

## 🐛 Bugfixes
- [Major] Fixed a bug which prevented the game from initializing in some cases, leading to an infinite loading screen.
- Fixed a bug which made the `Fallen Soldier` and `Bag 'O Tricks` graves skins inaccessible.
- Fixed a bug which allowed airdrop products to be shown in the lobby shop.
- Fixed a bug which prevented bleed outs from being registered as kills.
- Fixed a bug which caused zombies to never load in certain conditions.
- Fixed a bug which caused the camera to be messed up after dying in first person.
- Fixed a bug which allowed cheaters to fly if they never touched the ground from spawn.
- (Hopefully) fixed a bug which caused players to fall through the ground when their ping was really high.
- Readded missing `Medical Airdrop` product to the shop.
- Readded missing `Halloween Crate` product to the shop.
