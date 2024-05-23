# :bookmark_tabs:  Changelog 05/18/2024 - xx/xx/xxxx

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes

________

## :gun: New Items

### ITEM
- DETAILS

________

## :thread: New Crafting Recipes

### RECIPE
- DETAILS

________

## :loudspeaker: Features and Improvements


### :white_check_mark: `Feature` FEATURE

### :arrow_up_small: `Improvement` Added unbind and reset to default for all keybindings.
> Previously, the only way to unbind a keybind was to set it to a dead control (Esc, or Select on controller).
> Now those controls can be completely unbound.
>
> Additionally, we added a way to reset all keybinds to the defaults that we have set.

### :arrow_up_small: `Improvement` Added the necessary logic to allow binding inventory toggle to `E`.
> Previously, when binding your inventory keybind to `E` it would create a broken state for the inventory toggle button.
> This is because the inventory would close and reopen immediately (or open and close immediately).

### :arrow_up_small: `Improvement` Inventory item layout is now persisted.
> Previously, upon rejoining, items were sorted semi-randomly from first to last slot.
> Going forward, the items will be loaded where you left them.

________

## :balance_scale: Changes

### :exclamation: `Change` Added underbarrel attachment to `MK-47`

________

## :bug: Bugfixes
- Fixed a bug that could allow for nearly unlimited ammo by unequipping ammo from a gun in a certain case.
- Fixed a bug where .44 Magnum Revolver was not spawning in some police spawns.
- Fixed a bug which caused your weapons to disable upon cancelling the consumption of an item (eat, drink, heal, etc).
