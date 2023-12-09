# :bookmark_tabs:  Changelog 12/05/2023 - xx/xx/2023

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes
In this update we focused on adding more content to the game and tuning it more towards our vision for the final product we want this game to be.

________

## :gun: New Items

### Beartrap
- Can be placed anywhere that it fits, deploys when any player steps on it. Once deployed can be picked up again.

### Anti-Personnel Landmine
- Buried landmine designed for use against players. Can only be placed on natural ground. Deploys when any player steps on it.

### Composite Fiber
- Crafting Component

### Advanced Composite Fiber
- Crafting Component

### Spring
- Crafting Component

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

### Spring Recipe
- Ingredients: 5x `Scrap Metal`

### Composite Fiber Recipe
- Ingredients: 1x `Duct Tape`, 10x `Scrap Metal`, 2x `Scrap Glass`

### Advanced Composite Fiber Recipe
- Ingredients: 5x `Composite Fiber`, 10x `Scrap Glass`, 2x `Scrap Metal`, 10x `Scrap Plastic`

### Beartrap Recipe
- Ingredients: 50x `Scrap Metal`, 4x `Spring`

### Anti-Personnel Landmine Recipe
- Ingredients: 1x `Duct Tape`, 1x `Frag Grenade`, 25x `Scrap Metal`, 4x `Spring`

### Backpack Recipes
- All three tiers can be crafted.

### Vest Recipes
- Both tiers of vests can be crafted.

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Equipment Airdrops
- Can be purchased in the shop under the boosts tab.
- Alternatively, can be called in from the map.
- Spawn rates:
![image](https://github.com/CompilerErrorRBX/Alpha-Changelogs/assets/10750096/510f5df8-8b26-4788-9973-86a1920ff2da)


### :white_check_mark: `Feature` Shop
- Used for purchasing an equipment airdrop, and more later.

### :arrow_up_small: `Improvement` Interaction Improvements
> We found that interacting with certain objects was very difficult, as the system was unable to validate that you actually had line of sight to larger objects like cars and desks, so we've attempted to improve the logic around determining if you can truly see what you're interacting with. This is still imperfect, but it should make many previously impossible interactions possible.
> Additionally, we improved the responsiveness of how line of sight is determined, so the interactions you're trying to reach should be much easier to reach.

### :arrow_up_small: `Improvement` Scrap context menu action no longer closes context menu
> Trying to scrap many items was very burdensome since it required you to right click on the item
> and then click scrap over and over. Instead of that, we've made it so the context menu stays open and you can keep on clicking.

### :arrow_up_small: `Improvement` Player graves remove when emptied.

### :arrow_up_small: `Improvement` Nearby explosions cause concussions.

### :arrow_up_small: `Improvement` New ACOG reticle.

________

## :balance_scale: Changes

### :exclamation: `Change` Player Grave Despawn Timer Increase
- Increased grave despawn time from 10 -> 20 minutes

### :exclamation: `Change` Cloth Scrap
- Increased stack size from 10 -> 200
- Decreased weight from 0.1 -> 0.01kg

### :exclamation: `Change` Bandages
- Bandages heal for 2 HP now
- Crafting recipe requires 3 `Cloth Scrap` instead of 1
- Scraps into 3x `Cloth Scrap`

### :exclamation: `Change` Healing Salve
- Crafting recipe requires 6 `Cloth Scrap` instead of 3
- Scraps into 6x `Cloth Scrap`
- Reduces infection time by 30 seconds

### :exclamation: `Change` Leg Splint
- Crafting recipe requires 12 `Cloth Scrap` instead of 4
- Scraps into 6 `Cloth Scrap`
- Scraps into 2x `Stick` and 12x `Cloth Scrap`

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

### :exclamation: `Change` Various Zombie Changes
- Basic zombies no long run, only sprinters zombies run now.

### :exclamation: `Change` Various Zombie Item Changes
- `Military Vest` no longer spawns on zombies
- `Military Helmet` no longer spawns on zombies
- `Police Vest` no longer spawns on zombies

________

## :bug: Bugfixes
- Fixed a bug where some blood effects were shown with blood disabled.
- Fixed a bug where after scrapping an equipped inventory item, the inventory UI for that item was never cleaned up.
- Fixed a bug where zombies would go invisible sometimes. (🤞 I hope 🤞)
- Fixed a bug where sometimes when a player joined their camera would not attach to their character.
- Fixed a bug where the MRAD would never spawn.
