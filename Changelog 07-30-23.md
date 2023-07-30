# :bookmark_tabs:  Changelog 07/29/2023 - XX/XX/2023

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes
In this patch we focused on making players a bit less tanky. We found that healing items were a bit more effective than we were looking for with this game, so we slowed down healing across the board.

## :fire: New Items
- Added `Tourniquet`.
  > Alternative to bandages, stops 3 stages of bleeding, consumes in 3 seconds.
  > Bandage, by contrast, stops 1 stage of bleeding and consumes in 3 seconds (See medical item changes in the changes section).

- Added `Shovel`, `BaseballBat`, `Machete`, `Cleaver`.
  > We want to continue to add more melee weapons, we started with a few low-hanging options.

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

> We felt that overall, players should need to disengage from combat before healing so when a player is damaged while healing, the healing will cease.
- Healing is stopped when a player takes damage from an attack.

### :exclamation: `Change` Molotov
- Decreased damage while standing in fire from `24hp/s -> 10hp/s`.
- Decreased burn damage from `35hp -> 20hp` over 20 seconds.

### :exclamation: `Change` More ways to "Break a leg!"
> We wanted to add a bit more utility to going for the legs, and expand on the usefulness and the vital importance of carrying a splint.
- Melee and bullets impacts on legs have a chance to apply the `Broken Leg` status effect.
- Slashing melee weapons do not break legs.

### :exclamation: `Change` `Broken Leg` status effect
> In addition to having more ways to break your leg, we drastically decreased the height you can fall from with a broken leg without taking damage, jumping will now, in most cases, cause some damage.
- Jump height extremely reduced with broken leg.

________

## :bug: Bugfixes
- Fixed a bug which made healing items heal twice as much as intended.
- Fixed PVP melee.
