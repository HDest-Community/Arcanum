# Arcanum
_Originally made by Accensus, now maintained by the community.  Requires [AceCoreLib](https://github.com/HDest-Community/AceCoreLib)_

A magic addon for the Classic Doom gameplay mod: Hideous Destructor.


## Important
- To cast self/mass spells, look at your feet and summon a rune. When casting such spells, you must be within the sigil to be able to activate the runes.
- When casting targeted spells, you can only activate the runes from behind. There is an angle limit so you cannot cheese runes from behind a corner.
- Touch spells require the sigil to be within 2m of the target.
- Gold numbers denote values that change with spell level.
- When updating the mod mid-playthrough after new spells have been added, use `ARC_ReInitSpells` to refresh the list. Existing spells will not be reset.

## Notes
- Loadout code is `arc`.
- Configuration codes are:
	- `blues`: Starting blues. Up to 4 digits.
- Blue barrels may spawn in place of regular explosive barrels. If you use them while you have a single partial potion sitting in your inventory, it will fill it up. If the barrel is above 80% (90% if incapped) and you are not holding a potion, you can take a sip directly.
- One barrel is the equivalent of 5 potions, or 2 soulspheres.
- Barrels can be shot they will leak! They can also break if they take too much damage.

### How it works
- Blues are absorbed passively into the tome at a standard rate of one bluesphere per 20 minutes. That rate grows or shrinks depending on the current amount of blues you have in you. More spheres means faster absorption and vice versa. You can't eat a single bluesphere and become a god of death.

## Known issues
- Sometimes some runes can spawn above the sigil when floors are involved. This is unfixable due to the engine not allowing anything below the floor or above the ceiling unless it has +NOINTERACTION, but at that point you would be completely unable to trigger the runes.

## Incompatibilities
- Josh's Action Bubbles seems to make the rune activation not work unless you are crouching. This is an issue with the Player Heading feature. Turn it off and Arcanum will work.

## Credits

Code:
- Accensus

Sprites:
- Runes are the Strogg alphabet from Quake (id Software)
- Sigils by Accensus
- Leaky barrel by Mor'ladim

Sounds:
- Diablo II (Blizzard Entertainment)

Fonts:
- Gargoyle Wing (Jimmy; https://forum.zdoom.org/viewtopic.php?t=33409)

Extensive Testing & Feedback:
- squiggle
- Archer
- Sledge