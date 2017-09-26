# Priest

## Cantrips

### Nursing Shadow

_From the shadows, you call a nurse from the Dark World to tend on the wounds of an ally._

Select **ally** target.  The Nursing Shadow will heals a single target ally for (1d4)+3.

### Weakening Shade

_You cast a dark ominous shade engulfing an enemy._

Select **enemy** target.  The Weakening Shade will deal damage to a single target for (1d4)+3.

## Abilities

### Reanimate

_You whisper scattered words under your breath as your eyes turn black and you sacrifice part of soul to another ally._

Select **ally** target.  
```
if (target hit points equal 0)
  {
    You bring the target back up to life with half of their total hit points.
    Sacrificing (1d4)-1 damage to yourself
  }
else
  {
    You heal the target for (3d12)+6.
    Sacrificing (1d4)-1 damage to yourself.
  }
```


### Underworld

_You bite your finger drawing blood.  Using the blood you illustrate symbols on the floor around you causing the space in another area to turn black and misty._


Up to 30ft away, you project and channel a 15x15ft square.

If a target in the square is an enemy, you deal (1d10)+4 damage.

If a target in the square is an ally, you heal for (1d10)+4.

During the channel you have a 0 movement speed.
