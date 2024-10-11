# :bookmark_tabs:  Changelog 10/07/2024 - 10/11/2024

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes

________

## :loudspeaker: Features and Improvements

### :arrow_up_small: `Improvement` Player footstep sound improvements
- Timing of footsteps is more properly timed with animations.
- Added support for multiple footstep types (barefoot, boots, etc).
- Optimized use of footstep sounds.

### :arrow_up_small: `Improvement` SKS now uses a clip instead of single reload.

### :arrow_up_small: `Improvement` Airdrops can no longer be purchased during scheduled restarts.
- Attempting to purchase an airdrop while the server is on a scheduled restart will stop the purchase.

### :arrow_up_small: `Improvement` Various improvements to rain.
- Improved interior sound from rain.
- Improved performance of rain. (further optimizations to be made in the future if Roblox fixes [this bug](https://devforum.roblox.com/t/moving-attachments-with-child-particleemitters-causes-long-updateinvalidparts-step/3189733))

### :arrow_up_small: `Improvement` Various network improvements
> Currently, the most process intensive part of the game lies in networking. There are a lot of things that need to be replicated in the game
> and we're working to improve the efficiency of those things.

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
- Fixed a bug which caused zombies to have the wrong equipment shown sometimes.
- Fixed a bug where car explosions caused welds to break on nearby objects.
- (Needs testing) Fixed a bug which caused vehicles to be silent sometimes.
