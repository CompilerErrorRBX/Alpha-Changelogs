# :bookmark_tabs:  Changelog 01/17/2023 - 01/XX/2023

## :red_circle: Status `Unreleased`
<!-- ## :green_circle: Status `Released` -->

## :speech_balloon: Patch Notes

________

## :star2: New Items
- :new: Press Vest, FBI Vest (Skin), and Police Vest
  > Reworked the police vest model and added a press vest and FBI vest.
- :new: Sap
  > Obtained by gathering conifer trees.
  > Used in crafting healing salve.
- :new: Healing Salve
  > Fast use healing item.
  > Heals for 7HP and stops one level of bleeding

________

## :loudspeaker: Features and Improvements

### :white_check_mark: `Feature` Zombie Vaulting
- Zombies can vault over short walls now.

### :white_check_mark: `Feature` Sprinting Zombies
- Some zombies are sprinters, these are faster than players and pose a larger threat than the regular zombies.

### :arrow_up_small: `Improvement` Day Time Length Increased
- We've added configuration around a bias toward day time on the day cycle. Day time is now significantly longer than night.

### :arrow_up_small: `Improvement` Zombie Horde Movement
- Less spinny
  > We felt that zombies were a bit too "spiny" when a horde surrounded a player while they were up on top of something. 
  > Now they will more likely face the player than spin.
  > As a result of this change, zombies are far more likely to get stuck on things.

### :arrow_up_small: `Improvement` Vehicle Collisions
- Players can be shot out of cars now.
  > Reworked vehicle collision meshes with simplified collision geometry which should result in far better bullet hit registration around vehicles.

### :arrow_up_small: `Improvement` Truck and Sedan Reworks
- Reworked the 

________

## :balance_scale: Changes

### :exclamation: `Change` Military Zombies
- Military zombies are now always sprinters.
- Police zombies no longer spawn in military zombie spawns.

### :exclamation: `Change` Honey Provides Antibiotics

### :exclamation: `Change` Camping Axe
- Added a slight move speed debuff of 5% while holding the camping axe.
- Increased swing stamina consumption 3 > 8

### :exclamation: `Change` Arrows now only require sticks to craft
- We felt that arrows were a bit too difficult to craft so we've made them much cheaper.

### :exclamation: `Change` Brightened moonlight slightly
- Shadows and distance are still dark, but the ground around the player in the grass is a bit brighter.

### :exclamation: `Change` Medical Items
- Bandages no longer heal.
- Dressed bandages healing reduced (20HP in 4s > 10HP in 4s)
- Small medkit healing reduced (50HP in 5s > 40HP in 5s)
- Large medkit healing change (100HP in 10s > 100HP in 12s) (10HP/s > 8HP/s)

### :exclamation: `Change` Reduced zombie vision range
- We felt zombies could see a bit too far when they weren't bugged so we reduced their vision distance on players by about 15%.
  > This was applied after fixing the bug where they couldn't see nearly as far as they were meant to.

### :exclamation: `Change` Arrow crafting recipe quantity reduction
- Getting 4 arrows per stick felt a bit excessive so we've reduced this to 1 per stick.

________

## :bug: Bugfixes
- Fixed a bug which made it impossible to interact with some containers (I believe this is fixed as of 2/4/2023)
- Fixed a bug which made zombie's max vision distance very short.
- Fixed a bug where purified water gave caffeine.
- Fixed a bug where the truck would spin after a player exited while turning.
- Fixed texturing on the bow.
- Fixed a bug where certain parts that were meant to be invisible weren't.
