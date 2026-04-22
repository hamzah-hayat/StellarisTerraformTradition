# Stellaris Terraform Tradition
![Stellaris Terraform Tradition Image](https://github.com/hamzah-hayat/StellarisTerraformTradition/raw/master/thumbnail.png "Stellaris Terraform Tradition Image")

## Overview
Stellaris Terraform Tradition is a mod for Stellaris that introduces a new tradition tree focused on terraforming. This mod adds  decisions and unique tradition effects to enhance your empire's terraforming capabilities and planetary management. It is designed to reward an empire willing to invest into terraforming technologies and who plans on creating a series of Gaia worlds for their pops to live on.

## Terraform Tradition Tree Effects

### Adopt Effects
- Terraforming Speed: Increases the speed at which you can terraform planets, allowing you to transform barren worlds into habitable ones more quickly.
- Clearing Blockers: Reduces the time and cost required to clear planetary blockers.
- Grants Terrestrial Sculpting as a tech option (if not already researched)
- New Worlds Agenda: New Worlds Agenda creates habitable planets in your largest sector (by system size), one planet is made habitable for each five systems in that sector.
    Each Sector can only be effected once.

### Finish Effects
- Planetary Benefits: Provides empire-wide bonuses to planet jobs, population happiness, and logistic growth, similar to Gaia worlds but at a reduced rate.
- Ascension Perk: Grants an additional ascension perk point.
- Unlocks the Creator of Worlds ascension perk
    - Allows marking barren, frozen, toxic, and molten planets as terraforming candidates
    - Allows repairing shattered worlds (requires Mega-Engineering tech)

### Frontier Exploitation
- Basic Resource Efficiency: Increases Job Efficiency for Technicians, Miners and Farmers by a flat 15%.

### Planet Probing
- Gives a flat increase to Crystal, Volatile Moles and Exotic gas production by 25%
- Planetary Deposits: Allows you to create planetary deposits on your worlds, allowing you to further specialise their role.
    - You may create one "Basic" deposit per planet. For Generator, Mining or Agricultural deposits.
    - You may create one "Advanced" deposit per planet. For Rare Crystal, Exotic Gas ,Volatile Mote or Betharian Field deposits. These decisions require the appropriate resource technology first. Also there is a simple +1 planet size deposit decision.

### World Shaper
- Gaia Worlds: Lets you terraform worlds into Gaia worlds
- Reduces terraform cost by 25%
- Grants Ecological Adaptation as a tech option (if not already researched)

### Climate Engineering
- Speeds up terraforming speed by 25% and reduces cost of terraforming by 25%.

### Planet Restoration
- Allows you to terraform Toxic and Frozen planets, if you have the climate restoration technology.
- Grants Climate Restoration as a tech option (if not already researched)

## Installation - Manual
1. Download or clone this repository into your Stellaris mods folder.
2. Ensure the folder structure is preserved (the `descriptor.mod` file should be in the root of the mod folder).
3. Enable "Stellaris Terraform Tradition" in your Stellaris launcher.

Or install via the Steam workshop.

## Compatibility
- Designed for Stellaris version 4.3.0 and above.
- Compatible with most mods that do not alter the same tradition trees or terraforming mechanics.
- Vanilla file overwrites:
    - Overwrites the "Conquer Nature" agenda to unlock it via the Terraform tradition as well.
    - Overwrites the system tooltips for frozen_terraforming_tooltip and toxic_terraforming_tooltip, plus the rule has_ascension_for_terraforming_candidate to allow frozen/toxic worlds showing up in GUI
    - Overrides the World Shaper and Detox perks, to add a condition that does not let you pick them if you already have the Terraform tradition

## Credits
- Mod Author: Hamzah Hayat
- Special thanks to the Stellaris modding community for resources and inspiration.
- Thanks to the (Megastructures Tradition mod)[https://steamcommunity.com/sharedfiles/filedetails/?id=2962431363] by Lezzistrata and A-Sartek for being the main inspiration for this mod.

## Changelog
See `CHANGELOG.md` for a list of recent changes.