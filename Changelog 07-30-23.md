# :bookmark_tabs:  Changelog 07/29/2023 - XX/XX/2023

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes
In this patch we focused on making players a bit less tanky. We found that healing items were a bit more effective than we were looking for with this game, so we slowed down healing across the board.

## :fire: New Items
- Added `Tourniquet`.
  > Alternative to bandages, stops 3 stages of bleeding, consumes in 3 seconds.
  > Bandage, by contrast, stops 1 stage of bleeding and consumes in 3 seconds (See medical item changes in the changes section).

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Concussion Status Effect
> Causes brief vision impact, ear ringing, and weapon flinch upon starting.
- Bullet Headshots result in a concussion 100% of the time, with a duration that is based on the damage dealt `(max 2s)`.
- Melee headshots have a percentage chance to cause concussion, with a duration that is based on damage dealt `(max 2s)`.

### :arrow_up_small: `Improvement`

________

## :balance_scale: Changes

### :exclamation: `Change` Medical Items
- Decreased `Healing Salve` healing from `7hp -> 5hp`.
- Increased `Healing Salve` healing duration from `2s -> 10s (0.5hp / second)`.
- Increased `Dressed Bandage` healing duration from `4s -> 10s (1hp / second)`.
- Increased `Small Medkit` healing duration from `5s -> 20s (2hp / second)`.
- Increased `Large Medkit` healing duration from `12.5s -> 20s (5hp / second)`.
- Increased `Bandage` use time from `1.5s -> 3s`.

________

## :bug: Bugfixes
- Fixed a bug which made healing items heal twice as much as intended.
- Fixed PVP melee.
