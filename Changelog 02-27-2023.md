# :bookmark_tabs:  Changelog 02/27/2023 - 03/01/2024

<!-- ## :red_circle: Status `Unreleased` -->
## :green_circle: Status `Released`

## :speech_balloon: Patch Notes
This week we focused on 
________

## :gun: New Items

### Makeshift Rifle
- A crafted sniper rifle.

### Makeshift SMG
- A crafted sub machine gun.

________

## :thread: Crafting Recipes

### Makeshift Rifle
- Requirements: `10x Chopped Logs`, `5x Composite Fiber`, `4x Duct Tape`, `200x Scrap Metal`, `5x Spring`

### Makeshift SMG
- Requirements: `6x Chopped Logs`, `4x Composite Fiber`, `4x Duct Tape`, `150x Scrap Metal`, `10x Spring`

### Removed Duffle Bag Recipe

### Removed Military Vest Recipe

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Added new death screen.

### :arrow_up_small: `Improvement` Improved melee hitreg. Should be more consistent now.

### :arrow_up_small: `Improvement` Minor optimizations to the gun system.

### :arrow_up_small: `Improvement` Improved how ground models were being rendered.
> Should yield a slight improvement for client FPS.

________

## :balance_scale: Changes

### :exclamation: `Change` Added bleeding stage 4
- Drains `2.0 HP/s`

### :exclamation: `Change` Buffed `Tourniquet` and `Large Medkit`
- Stops bleeding x4.

### :exclamation: `Change` Increased `Tourniquet` spawn rate

### :exclamation: `Change` Airdrop Purchase
> Made a small change here so that an airdrop purchase is only considered complete the moment the package lands on the ground.
> This should help reduce the number of scenarios where a player loses their airdrop because a server shut down.

### :exclamation: `Change` Reduced spawn rate for the `.44 Magnum Revolver`

### :exclamation: `Change` `M1911` can no longer accept an optic

### :exclamation: `Change` Reduced Ammo Scrap Yields
- `12 Gauge`: `Scrap Metal` - 2 -> 1, `Gun Powder` - 4 -> 2, `Scrap Plastic` - 4 -> 2
- `.223 Remington`: `Scrap Metal` - 4 -> 2, `Gun Powder` - 6 -> 3
- `.308 Winchester`: `Scrap Metal` - 5 -> 3, `Gun Powder` - 8 -> 4
- `.44 Magnum`: `Scrap Metal` - 3 -> 2, `Gun Powder` - 5 -> 2
- `.45 ACP`: `Scrap Metal` - 2 -> 1, `Gun Powder` - 4 -> 2
- `.50 BMG`: `Scrap Metal` - 6 -> 3, `Gun Powder` - 10 -> 5
- `9MM Parabellum`: `Scrap Metal` - 2 -> 1, `Gun Powder` - 4 -> 2

________

## :bug: Bugfixes
- Fixed a bug which completely broke crafting.
- Fixed a bug which caused any weapon item to be deleted when dropped (assuming it had no attachments).
- Fixed various zombie bugs.
