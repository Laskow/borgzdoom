# borgzdoom
borgzdoom is a customized GZDoom engine based on GZDoom 4.8.2.

## Differences

- Physics
  - The flying player no longer bobs.

- Water physics
  - Projectiles are unaffected by water, moving consistently as they do on the surface.
  - Actors in water no longer bob violently.
  - The water friction is disabled.

- Automap
  - The Automap replaces the map arrow with the player sprite. If you prefer the map arrow, you can switch them through the options. 
  - The stats (items, secrets, and monsters) are displayed at the bottom of the screen.

- Sounds
  - The usefail sound is disabled.

- Options
  - Some multiplayer options have been removed from MENUDEF.
  - The player skin is no longer displayed in the Player Setup option.
