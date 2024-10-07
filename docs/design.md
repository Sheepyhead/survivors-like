# Survivors-like design doc
## Minimum viable product
### Main menu
- Buttons
  - Start game
  - Upgrades
  - Options
  - Quit
- Music
### Upgrades
- One upgrade
  - Boost everything
  - Indicate what level the upgrade is
- Respec upgrades button
- Show gold amount
- Return button
### Options
- Window mode setting
- Resolution setting
- Volume slider
### Game
- Background
  - Scrolls practically infinitely
  - Detailing that shows that it scrolls
  - Breakable crates
- Enemies
  - One type of enemy that gets stronger, faster and more numerous over time
  - Spawn outside of the viewport
  - Beeline it toward player
  - Deal damage with a cooldown when touching player hitbox
  - Sound when die
- GUI
  - Timer that counts up
  - XP bar
  - Gold count
  - Weapon display
  - Health bar
  - Damage numbers on hit
- Pause menu
  - Transparent menu that pops up on escape
  - Pauses the game
  - Buttons
    - Continue
    - Options (see Options menu)
    - Exit to main menu
    - Exit to desktop
- Pickups
  - XP orbs
    - Spawn from killed monsters
  - Gold
    - Spawn from breaking stuff in the environment like crates
- Player
  - Always in the center of the screen
  - Basic animation when moving
  - Stats
    - HP
    - Move speed (m/s)
    - Attack speed (Cooldown in seconds between attacks)
    - Damage modifier (%)
    - XP
      - Level up improves all stats and heals your hp
      - Next level up goal is higher than the last (quadratic? Exponential? Maybe implement a couple different ones to switch between)
  - Weapons
    - Starts with basic projectile weapon, launches toward the nearest enemy
    - At level 2 get a damage aura
    - At level 3 get a minion (seeking missile that doesn't run out and follows the character targeting enemies within a certain radius, dealing damage on contact)
    - Each weapon makes a unique sound on hit
    - Each weapon is affected by player stats where relevant
### Game Over
- Screen fades
- Become unable to move
- Summary of level, gold gained, enemies killed, time survived etc

## Plot outline
In the nine layers of hell devils war eternally against demons. You, however, are a devil in love with your hot demon wife. Unfortunately Asmodeus, lord of hell has whisked her away for his own nefarious purposes. Use your infernal magics to mow your way through all nine hells and save your hot demon wife. When a devil dies in the hells, they are reborn on the first layer, stripped of their equipment and magics, keeping only what lessons have been scorched into their infernal soul.