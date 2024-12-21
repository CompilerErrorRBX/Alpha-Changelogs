# :bookmark_tabs:  Changelog 12/08/2023 - 12/15/2023

<!-- ## :red_circle: Status `Unreleased` -->
## :green_circle: Status `Released`

## :speech_balloon: Patch Notes
> We spent most of this patch working on our upcoming vehicle update, while that was not ready for release we did also fix several bugs and made a few other improvements.
________

## :loudspeaker: Features and Improvements

### :arrow_up_small: `Improvement` Fixed some potential client-side memory leaks.
> We've noticed many clients crashing over the past few weeks, and we're seeing high memory usage. We'll continue to track down other potential leaks, but this should help the game to run a bit better.

### :arrow_up_small: `Improvement` Bicycle type vehicles should be less wobbly.

### :arrow_up_small: `Improvement` Added Scrap Hotkey.
> Right clicking and clicking on scrapping was a bit clunky for how often it needed to be done, so we added a hotkey for it. Default F on keyboards and X on controller.

________

## :balance_scale: Changes

### :exclamation: `Change` Equipment Airdrop item changes
- Added (1 - 2x) `Tactical Bacon`
- Added (1 - 2x) `Energy Drinks`
- Added 1x random `Medium Backpack`

### :exclamation: `Change` Changed default Hotkey to open map with a Controller from Select to DPad Left.

________

## :bug: Bugfixes
- Fixed a bug which made the distance check on foraging invalidate the gather action.
- Fixed a bug where when searching a container it could sometimes enter an unsearchable state.
- Fixed an issue where several sounds weren't playing.
- Fixed a bug which prevented players from sprinting sometimes.
- Fixed a bug which caused vehicle seat interactions to get reversed in certain cases.
- Fixed a bug where players would fall and die upon joining the game.
- Fixed a bug where players who rejoined while in a squad did not have a squad member tag for the other members of their squad.
- Fixed a bug where a label was never created for a new member joins a squad.
- Fixed a bug where items could be "duplicated" during crafting certain recipes.
- Reverted an accidental change to how weapons are switched on controllers, it was meant to be LB/RB to toggle, but was set to Y.
- Fixed a bug where spark effects from bullet impacts were colliding with players.
