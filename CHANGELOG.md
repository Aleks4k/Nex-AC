v1.9.54

Changes:
* Improved anti-speedhack in vehicle
* Improved validation of unoccupied sync parameters (using Pawn.RakNet)
* Added protection against invisibility sending invalid camera mode with a detonator in hand (powered by Pawn.RakNet)
* Improved behavior of OnCheatDetected triggering for onfoot/in vehicle teleport, if the punishment isn't set to kick
* Added "#define AC_MAX_SKINS" (312 by default)
* Minor improvements

Fixes:
* Fixed a bug in protection against fake NPCs when YSF plugin is used
* Fixed a bug in NOPs protection with a kick for giving ammo for a non-existent weapon if a player had another weapon in this slot
* Fixed behavior of some algorithms when OnTrailerUpdate is being desynced by the server
