# :bookmark_tabs:  Changelog 10/07/2024 - 10/23/2024

## :green_circle: Status `Released`

## :speech_balloon: Patch Notes
While working on the survival update, we've noticed some rather impactful bugs and lacking features.
We took some time to address some of these issues in this update. Some of these fixes are with respect to
areas where performance was lacking (rain, footsteps, etc). Our footsteps changes have opened up a lot of
new and interesting functionality. Like different footstep profiles (barefoot, shoes, backpack).

________

## :loudspeaker: Features and Improvements

### :arrow_up_small: `Improvement` Player footstep sound improvements.
- Timing of footsteps is more properly timed with animations.
- Added support for multiple footstep types (barefoot, boots, etc).
- Optimized use of footstep sounds.

### :arrow_up_small: `Improvement` SKS now uses a clip instead of single reload.

### :arrow_up_small: `Improvement` Airdrops can no longer be purchased during scheduled restarts.
- Attempting to purchase an airdrop while the server is on a scheduled restart will stop the purchase.

### :arrow_up_small: `Improvement` Various improvements to rain.
- Improved interior sound from rain.
- Improved performance of rain. (further optimizations to be made in the future if Roblox fixes [this bug](https://devforum.roblox.com/t/moving-attachments-with-child-particleemitters-causes-long-updateinvalidparts-step/3189733))

________

## :balance_scale: Changes

### :exclamation: `Change` Removed shoes as a starter item.

### :exclamation: `Change` Buffed basic shoes. (non `Sneakers` and `Boots`)
- Increases move speed by 2.5%
________

## :bug: Bugfixes
- Fixed a major bug which prevented players from damaging other players and zombies.
- Fixed a bug which prevented players from shutting off the gas sequence in the `Chinese Bunker`.
- Fixed a bug which prevented the rain sound from stopping after a storm ended.
- Fixed a bug which prevented quick use slots from being cleared after death.
- Fixed a bug which prevented players from shooting immediately after firing a rechambering weapon.
- Fixed a bug which caused zombies to have the wrong equipment shown sometimes.
- Fixed a bug which caused zombies to become simulated far later than they're meant to be.
- Fixed a bug which caused vehicles to be silent sometimes.
- Fixed a bug which caused car explosions to break welds on nearby objects.
- Fixed a bug which caused weird behaviors with cars upon entering and exiting.
- Fixed a bug which caused players to appear to rotate when they were using alt-look.
- Fixed a bug which allowed players to jump out of passsenger seats in cars.
