# 1.0.0
This version is built for Stellaris Cetus 4.3.0 (BETA 48b3)

## Fixes
    - N/A

## Changes
    - N/A

## Features
    - Initial Release


# 1.0.1
This version is built for Stellaris Cetus 4.3.0 (BETA 48b3)

## Fixes
    - Fix Deposit decisions completely, turns out they needed some testing
    - Fix Tooltip for Planet Restoration

## Changes
    - N/A

## Features
    - N/A


# 1.0.2
This version is built for Stellaris Cetus 4.3.0 (BETA 48b3)

## Fixes
    - Fix Deposit decisions tooltips and icons


# 1.1.0
This version is built for Stellaris Cetus 4.3.0 (BETA 48b3)

## Fixes
    - Make sure World shaper tradition perk works correctly (allows you to see Toxic planets and terraform them)
    - Change deposit decisions to (on queue/unqueue) change the planet flag to remove other decisions of the same type (basic/strategic deposit)

## Changes
    - Overwrite Detox and Worldshaper to stop you being able to pick them if you have started the Terraform tradition, also removes said perks on starting Terraform tradition (If you already had them).
    - Update Localization for deposit decisions

## Features
    - Add a Cultivated Worldscaping decision that replaces Mastery of Nature on a planet. Basically same effects etc, should be a vanilla thing imo.


# 1.1.1
This version is built for Stellaris Cetus 4.3.1 (f646)

## Fixes
    - Add a small "glow" to Terraform tradition tile, similar to vanilla ones
    - Deposit decisions can only be done on habitable planets
    - Slight loc update to trigger to show failure (for APs World shaper and Detox if you have terraform tradition)

## Changes
    - Changes to techs granted via the tradition. (Each gives 25% in each tech, if you haven't already got it unlocked)
        - Adopt gives Terrestrial sculpting
        - World shaper gives ecological adaptation
        - Planet restoration gives Climate restortion

## Features
    - Terraform Tradition finish adds Gaia Master world pref
        - Doubles Gaia world bonuses for pops that have them
        - Also removed flat planet bonus from Terraform tradition finish


# 1.2.0
This version is built for Stellaris Cetus 4.3.3 (456f)

## Fixes
    - Fix Planet probing rare resource modifier
        - Should have had a 10% increase to Volatile Motes, Rare Crystals and Exotic Gas production, now does!

## Changes
    - Change allow triggers for strategic resource deposit decisions
        - Allow both the mining and creation techs for these decisions.
        - eg Exotic Gas Extraction or Exotic Gas Refining would let you create an Exotic gas deposit.

    - Add some basic AI weights for deicisons, AP perks and terraform tradition picks.

## Features
    - Add New Worlds Agenda
        - This agenda creates habitable planets in the largest sector (by system size), can be done once per sector.
            - Each sector is flagged once done, so will do next largest sector if done again
        - Creates a habitable planet per 5 systems of that sector, with a minimum of 1 planet created.
        - Uses existing planetary bodies, will find something between 12 -> 25 (inclusive) size. Some other checks as well

    - Add an Underground Complex deposit
        - Counts as a strategic deposit, simply adds +1 to max planet districts.


# 1.2.1
This version is built for Stellaris Cetus 4.3.3 (456f)

## Fixes
    - Gas giants are no longer transformed by New World's agenda
    - Fix scoping for monthly income check

## Changes
    - New Worlds agenda now gives a minimum of 3 planets when creating habitable worlds (If sector has less then 15 systems, you will get 3 habitable planets inside it)

## Features
    - Add Creator of Worlds Ascension Perk
        - Requires Climate Restoration tech, 3+ ascension perks, and finishing the Terraform tradition tree
        - Unlocks the "Mark Terraforming Candidate" decision on barren, frozen, toxic, and molten planets
        - Unlocks the "Repair Shattered World" decision on broken and shattered planets (requires Mega-Engineering tech)