# Description
This Addon adds Landmines to [Hideous Destructor](https://codeberg.org/mc776/HideousDestructor). 

They DO NOT SPAWN NATURALLY and are mainly intended for mappers!


# Credits
Matt for [Hideous Destructor](https://codeberg.org/mc776/HideousDestructor) and the code for the Barrels and IEDs that i borrowed used for this.


# Contents
## Neutral Landmine:
    * Scans for both enemies and players
    * Once triggered, explodes after 15 tics
    * Can be shot to trigger early
    * Cannot be picked up by the player
    * Does not see players with NoTarget enabled
    * ID number: 24000
    * Class: HDNeutralLandmine

## Hostile Landmine:
    * Scans for ONLY players, not enemies
    * Otherwise mechanically the same as the Neutral mine
    * ID number: 24001
    * Class: HDHostileLandmine
