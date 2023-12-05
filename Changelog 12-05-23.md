# :bookmark_tabs:  Changelog 12/05/2023 - xx/xx/2023

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes
In this update we focused on adding more content to the game and tuning it more towards our vision for the final product we want this game to be.

________

## :gun: New Items

### Bolt Cutters
- Melee Weapon, also useful for dealing with barbed wire.

### Plastic Scrap
- Stack size 200, crafting component.

### Glass Scrap
- Stack size 200, crafting component.

________

## :thread: New Crafting Recipes

### Large Medkit Recipe
- Ingredients: 4x `Dressed Bandage`, 2x `Duct Tape`, 1x `Saline Solution`

### Small Medkit Recipe
- Ingredients: 8x `Healing Salve`, 1x `Duct Tape`, 1x `Saline Solution`

### Dressed Bandage Recipe
- Ingredients: 2x `Healing Salve`, 1x `Saline Solution`

### Duct Tape Recipe
- Ingredients: 5x `Scrap Cloth`, 1x `Sap`

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` NEW FEATURE
> Feature details

### :arrow_up_small: `Improvement` Interaction Improvements
> We found that interacting with certain objects was very difficult, as the system was unable to validate that you actually had line of sight to larger objects like cars and desks, so we've attempted to improve the logic around determining if you can truly see what you're interacting with. This is still imperfect, but it should make many previously impossible interactions possible.
> Additionally, we improved the responsiveness of how line of sight is determined, so the interactions you're trying to reach should be much easier to reach.

### :arrow_up_small: `Improvement` Scrap context menu action no longer closes context menu
> Trying to scrap many items was very burdensome since it required you to right click on the item
> and then click scrap over and over. Instead of that, we've made it so the context menu stays open and you can keep on clicking.

________

## :balance_scale: Changes

### :exclamation: `Change` Player Grave Despawn Timer Increase
- Increased grave despawn time from 10 -> 20 minutes

### :exclamation: `Change` Cloth Scrap
- Increased stack size from 10 -> 200
- Decreased weight from 0.1 -> 0.01kg

### :exclamation: `Change` Bandages
- Bandages heal for 2 HP now
- Crafting recipe requires 3 `Scrap Cloth` instead of 1
- Scraps into 3x `Scrap Cloth`

### :exclamation: `Change` Healing Salve
- Crafting recipe requires 6 `Scrap Cloth` instead of 3
- Scraps into 6x `Scrap Cloth`
- Reduces infection time by 30 seconds

### :exclamation: `Change` Leg Splint
- Crafting recipe requires 12 `Cloth` instead of 4
- Scraps into 6 `Cloth`
- Scraps into 2x `Stick` and 12x `Cloth`

### :exclamation: `Change` Various Item Changes
- `Salt Packet` Increased stack size from 64 -> 200
- `Empty Bottle` Scraps into 8x `Plastic Scrap`
- `Empty Glass Bottle` Scraps into 10x `Glass Scrap`
- `Empty Glass Jar` Scraps into 10x `Glass Scrap`
- `Duct Tape` Scraps into 5x `Cloth Scrap`
- `Dressed Bandage` Reduces infection time by 1 minute
- All ammo items can be scrapped into their basic components
- All clothing items give 12x `Cloth Scrap` instead of 2x
- Nearly all items can be scrapped into basic components

________

## :bug: Bugfixes
- Bug that was fixed
