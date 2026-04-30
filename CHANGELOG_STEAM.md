[h1]1.2.2[/h1]
This version is built for Stellaris Cetus v4.3.5 (df6e)

[h2]Fixes[/h2]
[list]
[*] New Worlds agenda now correctly checks that at least one sector has not already been used, preventing re-selection of already-processed sectors
[*] Mark Terraforming Candidate and Repair Shattered World decisions are now instant (removed enactment time)
[/list]

[h2]Changes[/h2]
[list]
[*] Creator of Worlds ascension perk now grants +0.1 influence per colonized Gaia planet (recalculated monthly via on_action event)
[/list]

[h2]Features[/h2]
[list]
[*] Added Gaia terraform links for Volcanic, Hive, Machine, Nanotech, and Nanite worlds (requires World Shaper tradition and Climate Restoration tech where appropriate)
[*] Added direct Toxic → Gaia terraform link (requires Planet Restoration, World Shaper, and Climate Restoration)
[/list]


[h1]1.2.1[/h1]
This version is built for Stellaris Cetus 4.3.3 (456f)

[h2]Fixes[/h2]
[list]
[*] Gas giants are no longer transformed by New World's agenda
[*] Fix scoping for monthly income check
[/list]

[h2]Changes[/h2]
[list]
[*] New Worlds agenda now gives a minimum of 3 planets when creating habitable worlds (If sector has less then 15 systems, you will get 3 habitable planets inside it)
[/list]

[h2]Features[/h2]
[list]
[*] Add Creator of Worlds Ascension Perk
[list]
[*] Requires Climate Restoration tech, 3+ ascension perks, and finishing the Terraform tradition tree
[*] Unlocks the "Mark Terraforming Candidate" decision on barren, frozen, toxic, and molten planets
[*] Unlocks the "Repair Shattered World" decision on broken and shattered planets (requires Mega-Engineering tech)
[/list]
[/list]


[h1]1.2.0[/h1]
This version is built for Stellaris Cetus 4.3.3 (456f)

[h2]Fixes[/h2]
[list]
[*] Fix Planet probing rare resource modifier
[list]
[*] Should have had a 10% increase to Volatile Motes, Rare Crystals and Exotic Gas production, now does!
[/list]
[/list]

[h2]Changes[/h2]
[list]
[*] Change allow triggers for strategic resource deposit decisions
[list]
[*] Allow both the mining and creation techs for these decisions.
[*] eg Exotic Gas Extraction or Exotic Gas Refining would let you create an Exotic gas deposit.
[/list]
[*] Add some basic AI weights for deicisons, AP perks and terraform tradition picks.
[/list]

[h2]Features[/h2]
[list]
[*] Add New Worlds Agenda
[list]
[*] This agenda creates habitable planets in the largest sector (by system size), can be done once per sector.
[*] Each sector is flagged once done, so will do next largest sector if done again
[*] Creates a habitable planet per 5 systems of that sector, with a minimum of 1 planet created.
[*] Uses existing planetary bodies, will find something between 12 -> 25 (inclusive) size. Some other checks as well
[/list]
[*] Add an Underground Complex deposit
[list]
[*] Counts as a strategic deposit, simply adds +1 to max planet districts.
[/list]
[/list]


[h1]1.1.1[/h1]
This version is built for Stellaris Cetus 4.3.1 (f646)

[h2]Fixes[/h2]
[list]
[*] Add a small "glow" to Terraform tradition tile, similar to vanilla ones
[*] Deposit decisions can only be done on habitable planets
[*] Slight loc update to trigger to show failure (for APs World shaper and Detox if you have terraform tradition)
[/list]

[h2]Changes[/h2]
[list]
[*] Changes to techs granted via the tradition. (Each gives 25% in each tech, if you haven't already got it unlocked)
[list]
[*] Adopt gives Terrestrial sculpting
[*] World shaper gives ecological adaptation
[*] Planet restoration gives Climate restortion
[/list]
[/list]

[h2]Features[/h2]
[list]
[*] Terraform Tradition finish adds Gaia Master world pref
[list]
[*] Doubles Gaia world bonuses for pops that have them
[*] Also removed flat planet bonus from Terraform tradition finish
[/list]
[/list]


[h1]1.1.0[/h1]
This version is built for Stellaris Cetus 4.3.0 (BETA 48b3)

[h2]Fixes[/h2]
[list]
[*] Make sure World shaper tradition perk works correctly (allows you to see Toxic planets and terraform them)
[*] Change deposit decisions to (on queue/unqueue) change the planet flag to remove other decisions of the same type (basic/strategic deposit)
[/list]

[h2]Changes[/h2]
[list]
[*] Overwrite Detox and Worldshaper to stop you being able to pick them if you have started the Terraform tradition, also removes said perks on starting Terraform tradition (If you already had them).
[*] Update Localization for deposit decisions
[/list]

[h2]Features[/h2]
[list]
[*] Add a Cultivated Worldscaping decision that replaces Mastery of Nature on a planet. Basically same effects etc, should be a vanilla thing imo.
[/list]


[h1]1.0.2[/h1]
This version is built for Stellaris Cetus 4.3.0 (BETA 48b3)

[h2]Fixes[/h2]
[list]
[*] Fix Deposit decisions tooltips and icons
[/list]


[h1]1.0.1[/h1]
This version is built for Stellaris Cetus 4.3.0 (BETA 48b3)

[h2]Fixes[/h2]
[list]
[*] Fix Deposit decisions completely, turns out they needed some testing
[*] Fix Tooltip for Planet Restoration
[/list]

[h2]Changes[/h2]
[list]
[*] N/A
[/list]

[h2]Features[/h2]
[list]
[*] N/A
[/list]


[h1]1.0.0[/h1]
This version is built for Stellaris Cetus 4.3.0 (BETA 48b3)

[h2]Fixes[/h2]
[list]
[*] N/A
[/list]

[h2]Changes[/h2]
[list]
[*] N/A
[/list]

[h2]Features[/h2]
[list]
[*] Initial Release
[/list]
