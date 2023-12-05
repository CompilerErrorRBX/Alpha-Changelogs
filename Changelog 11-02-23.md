# :bookmark_tabs:  Changelog 11/02/2023 - 12/05/2023

<!-- ## :red_circle: Status `Unreleased` -->
## :green_circle: Status `Released`

## :speech_balloon: Patch Notes
Mostly fixes and attempts to improve the zombie logic in this update. A big change for this update was making ladders interactable.
________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Server Player Counter
> Added a label to the top left of the screen which shows how many players are in the game.

### :white_check_mark: `Feature` Ladder Interactions
> We've felt for quite a while now that the "touch ladder to climb" system was very difficult to use.
> So we've changed the system to be interaction based which should give players much more control.

### :arrow_up_small: `Improvement` Partial Zombie Rewrite
> We felt that the zombies had gotten into a bad spot over the past several months of development.
> This patch we took some time to improve their movement logic and prevent some weird behaviors they had.
- Zombies now have thickness so they can't pass through windows and small holes like they used to.
- Zombies move in groups a bit more fluidly and bounce around less.
- Zombies should path around obstacles a bit better (not pathfinding)
- Temporarily removed zombie vaulting during this stage of the rewrite.
- Zombies will now break down doors when they run into them while chasing.
- Zombies track players after losing line of sight for a short period of time.

### :arrow_up_small: `Improvement` Minor Performance Improvements
> Did some work to clean up some old logic that wasn't performing quite as well as we'd like it to be.
- Yields a performance improvement of roughly 18% from quick benchmarking
________

## :bug: Bugfixes
- Fixed a bug which broke player respawning.
- Fixed a bug which sometimes caused an interaction to fail an interal distance check when it shouldn't.
- Fixed a memory leak caused by duplicate sound generation.
