# Stat definition table

## Entities
### Generic entity info
- Audio
- Actions
- Decorator
- Hit zones
- Materials
- Faction
- Visuals

### Projectile
- Collision type: raycast, rigidbody
- Damage falloff
- Detonate action
- Detonate on: collision, death, lifetime over
- Gravity factor
- Lifetime: full, on ground, post detonate
- Homing info
- Bounce: max bounce count, stop at max bounce
- Min distance
- On instigator death: do nothing, ?
- Raycast shape (if raycast collision)
- Rigidbody info (if rigidbody collision)
- Is simultaed locally
- Speed
- Sticky

### Character
- AI info
- Animation
- Locomotion: acceleration, movement speed, mass
- Health:
  - Max HP
  - Regen delay
  - Regen rate
  - Stun HP
  - Stun decay rate
  - Stun decay delay
  - Stun length
  - Stunned action
  - Take melee damage action
  - Take ranged damage action
- Armorshield:
  - Max armorshield
  - Regen delay
  - Regen rate
  - Material: override, material type
  - Active action
  - Broken action
  - Hit action
  - Inactive action
  - Inactive hit action
  - Regen action
  - Restored action
- Wargear list

### AI info
...

## Wargears
### Wargear
- Wargear type: melee, pistol, ranged, heavy, equipment, class perk, weapon perk, ability
- Abilities
- Actions
- Camera info: cameras, zoom levels
- Common info:
  - Sound bank
  - Animation set
- Ammunition info
- Heat info

### Ammunition info
- Autorecharge: recharge per sec, delay
- Clip
- Reserve
- Low ammo amount

### Heat info
- High heat amount
- Overheat amount
- Overheat delay
- Passive cooldown: delay after heat gain, delay after overheat, cooldown rate
- Cooldown action
- State actions: high heat, overheat, overheat completed, overheat delay

### Abilities
- Generic settings:
  - Trigger: ammo requirement, heat requirement, auto/semi
  - AI settings: hold/click, min/max recovery time, min/max hold time, min/max ideal range, min/max range, probability, must be stationary
- Attacks:
  - Melee:
  - Normal ranged:
    - Aim actions
    - Fire actions
    - Stop fire actions
    - Hit actions
    - Max range
    - Collision filter
    - Delivery type: raycast, shapecast, projectile
    - Ammo used per shot
    - RoF, burst length
    - Damage falloff
    - Coverage falloff (shapecast only)
    - Climb, sway, scatter
    - Penetration: points, material costs, maximum thickness
  - Charged ranged:
  - Pump ranged:

### Climb, sway, scatter

## Actions
- Action type: lifetime, on deploy, on pickup, on stow, on tracked projectile destroyed, while deployed, triggered
- Triggered action name
- Commands

## Commands
- Trigger sound event
- 