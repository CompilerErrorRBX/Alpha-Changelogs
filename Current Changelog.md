# 📑 Changelog 07/17/2025 - 09/xx/2025

## 🟢 Status `Unreleased`

## 💬 Patch Notes

This update we are heavily focused on some changes to help aleviate the effects of cheaters in the game. While we do not normally get in to the technical details of this kind of development, know that we are working on it as much as we can!
We have also taken a lot of time this update to work on the performance of various systems in Aftermath. Our goal is to make this game mobile compatible in the future, and the first step is squeezing out as much performance as we can on the code side of things.
Gun fights should now be a lot less laggy for your fps and ping.
________

## 🗺️ Map Changes

### General Changes

________

## 📢 Features and Improvements

### 🔼 `Improvement` Voice chat indicator no longer displays above characters.

### 🔼 `Improvement` Various performance improvements
>- Improved performance of bullet related tasks by ~1000%
>- Improved performance of various camera related tasks by ~230%
>- Improved performance of sound related actions by roughly 35%
>- Improved performance of blood and other particles by > 400%
>- Improved performance of positioning FPV gun by 50%
>- Reduced network packet size by 90% in many cases.
>- Improved performance around generating weapon models. Roughly 85% faster on average.
>- Improved performance of positioning TPV gun models by ~400%

### 🔼 `Improvement` Improved foley sounds when stepping and landing.
>- All backpacks now make foley sounds
>- All vests now make foley sounds

### 🔼 `Improvement` Doubled the range of flashlights and headlights.

________

## ⚖️ Changes

### ❗ `Change` Removed `Medical Airdrop` from Radio Tower spawn pool

### ❗ `Change` Added `Weapon Airdrop` to Radio Tower spawn pool

### ❗ `Change` Changed how alt looking works. Better UX

### ❗ `Change` Reduced size of crosshair

### ❗ `Change` Increased max distance of Flashlight/Headlights to 120 studs from 60 studs

### ❗ `Change` Temporarily disabled guns on back

### ❗ `Change` Zombies are no-longer attracted to interaction noises (exluding doors)
________

## 🐛 Bugfixes
- Fixed a bug where zombies could sometimes kill players outside of the spawn box.
- Fixed a bug where audio would occasionally have a popping sound.
- Fixed a bug which caused bullet tracer images to flicker occasionally (Roblox unloading and reloading the texture)
- Fixed a bug which broke "foley" sounds when wearing armor/backpacks.
- Fixed a bug where looking in certain directions would break the fps gun view bobbing.
- Fixed a bug which prevented the `Blood` setting from being respected in general.
- Fixed a bug which prevented the `Bodies` setting from being respected on zombies.
- Fixed a bug which occasionally casued attachments to be at the wrong angle on third person weapon models.
- Fixed a bug which caused visual portions of world models to be shown while in first person.
- Fixed a bug which prevented molotovs from doing damage to players.
- Fixed a bug which prevented grenades from passing through open doors.
