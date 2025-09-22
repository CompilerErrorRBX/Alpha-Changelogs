# 📑 Changelog 07/17/2025 - 08/xx/2025

## 🟢 Status `Unreleased`

## 💬 Patch Notes

This update we are heavily focused on some changes to help aleviate the effects of cheaters in the game. While we do not normally get in to the technical details of this kind of development, know that we are working on it as much as we can!
We are also looking in to our vehicle system, and building out features for that to better match the survival aspect of the game. Cars no longer instantly elevate you above other players upon finding them.
Players must now gather materials before cars can be driven. Cars now require a `Battery`, `Sparkplug`, `Fuel`, and `Car Keys` to be operational. They also now come with storage so you can carry more loot with you!

________

## 🗺️ Map Changes

### General Changes

________

## 📢 Features and Improvements

### ✅ `Feature` Vehicle Overhaul
>- Vehicles now have an interactable interface to add or remove items.
>- Vehicles now require a Battery, Sparkplug, Fuel, and Car Keys to be operational.
>- Vehicles now have a storage where in items can be placed to carry around with you.

### 🔼 `Improvement` Voice chat indicator no longer displays above characters.

### 🔼 `Improvement` Rewrote bot NPCs.
>- Previous implementation was a prototype from years ago, and constantly breaks when we do major upgrades to our systems.
>- New system builds from what we learned over the years with NPCs. It will be more stable, and the NPC players fit more seamlessly in to the world.

### 🔼 `Improvement` Various performance improvements
>- Improved speed of bullet related tasks by ~1000%
>- Improved performance of sound related actions by roughly 35%
>- Improved performance of blood and other particles by > 400%
>- Reduced network packet size by 90% in many cases.

________

## ⚖️ Changes

### ❗ `Change` Removed `Medical Airdrop` from Radio Tower spawn pool

### ❗ `Change` Added `Weapon Airdrop` to Radio Tower spawn pool

### ❗ `Change` Changed how alt looking works. Better UX.

________

## 🐛 Bugfixes
- Fixed a bug where zombies could sometimes kill players outside of the spawn box.
- Fixed an audio bug which occasionally caused popping sounds.
- Fixed a bug which caused bullet tracer images to flicker occasionally (Roblox unloading and reloading the texture)
- Fixed a bug which broke "foley" sounds when wearing armor/backpacks
- Fixed a buf where looking in certain directions would break the fps gun view bobbing.
