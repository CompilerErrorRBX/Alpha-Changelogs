# :bookmark_tabs:  Changelog 05/18/2024 - 05/24/2024

## :green_circle: Status `Released`

## :speech_balloon: Patch Notes
This week, we spent a lot of time on prepping for the new equipment attachment system.
This change involved a fairly significant rework to how item inventories are tracked but we believe it will be well worth it.

Some of the advantages to this change is a more trivial system for recording *which* slot an item was stored in during a save.
That means that once a user is migrated over to the new loading system (old data is not compatible, but should uplift without issue)
their items will load in the slot they had them in before leaving prior.
Another advantage to this system is that it also allows for much more flexibility in what types of items can have inventories, 
and how many inventories those items can have (used to only allow 1). This opens up a door for us to create pouch attachments for vests
which will allow them to carry items.

With the aforementioned system, we changed how NVGs are equipped. Instead of them going into your eyewear slot, they will (going forward) attach to a military helmet (or any helmet with the appropriate mount, current military helmets are the only ones).
This will require players to have a military helmet in order to use NVGs, so we've made it so that when a helmet runs out of durability, it no longer breaks. NVGs can be attached to a broken helmet.

________

## :gun: New Items

### Night Vision Tier 3
- Quad nog night vision goggles.
- Better FOV, and they're blue!

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Equipment Attachments.
> Certain equipment can now take attachment items.
- This change lacks visuals when the item is not equipped. This will be added later.

### :white_check_mark: `Feature` New NVG models and concept.
> NVGs are now an attachment for military helmets.

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

### :exclamation: `Change` Added Military Helmet to Equipment Airdrop and increased price (from 200 -> 249).
> Since we're now requiring a military helmet to use NVGs, we've added a military helmet.
> To reflect the increased value of the purchase, we've also increased its price.

### :exclamation: `Change` Added underbarrel attachment to `MK-47`

### :exclamation: `Change` Military Helmets no longer break on 0 durability
- This is to facilitate the change to NVGs where they are now an attachment for military helemts.

________

## :bug: Bugfixes
- Fixed a bug that could allow for nearly unlimited ammo by unequipping ammo from a gun in a certain case.
- Fixed a bug where .44 Magnum Revolver was not spawning in some police spawns.
- Fixed a bug which caused your weapons to disable upon cancelling the consumption of an item (eat, drink, heal, etc).
- Fixed a bug which prevented cancelling an action on an item by clicking it again.
- Fixed a bug where server region was not being properly displayed.
- Fixed a bug where number of players in the server was incorrect at times.
- Hopefully fixed a bug which caused players to have issues walking up stairs (this is a patch, we'll continue to improve on this later).
