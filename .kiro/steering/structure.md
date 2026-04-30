# Project Structure

## Root Layout
```
StellarisTerraformTradition/
├── descriptor.mod              # Mod metadata (name, version, tags, workshop ID)
├── thumbnail.png               # Steam Workshop thumbnail
├── README.md                   # GitHub readme
├── README_STEAM.md             # Steam Workshop description
├── CHANGELOG.md                # Detailed changelog
├── CHANGELOG_STEAM.md          # Steam-formatted changelog
├── common/                     # Game data definitions
├── events/                     # Event scripts
├── gfx/                        # Graphics assets
├── interface/                  # UI sprite definitions
└── localisation/               # Text strings
```

## common/ Subfolders
Each subfolder mirrors Stellaris's `common/` structure:
- `ascension_perks/` — Custom and overridden ascension perks
- `council_agendas/` — Council agenda definitions
- `decisions/` — Planet decisions (deposit creation, terraforming candidates)
- `deposits/` — Custom deposit definitions
- `game_rules/` — Overridden game rules
- `on_actions/` — Event triggers (monthly pulse, etc.)
- `script_values/` — Reusable calculated values
- `static_modifiers/` — Empire/planet modifiers
- `system_tooltips/` — Overridden tooltip text
- `terraform/` — Terraform link definitions
- `tradition_categories/` — Tradition tree category definition
- `traditions/` — Individual tradition perk effects
- `traits/` — Species trait definitions

## Naming Conventions
- All mod files use `tt_` prefix (e.g., `tt_terraform_decisions.txt`, `tt_events.txt`)
- Tradition keys use `tr_terraform_` prefix (e.g., `tr_terraform_adopt`, `tr_terraform_world_shaper`)
- Decision keys use `tt_decision_` prefix
- Event namespace: `tt_events`
- Planet flags use `tt_` prefix (e.g., `tt_established_basic_deposit`)
- Ascension perk for this mod: `ap_tt_creator_of_worlds`
- Localisation file: `TerraformTradition_l_english.yml`

## File Conventions
- One file per subfolder (keeps the mod compact and easy to maintain)
- Comments use `#` with section headers for organization
- `##` for major sections, `###` for individual item descriptions
- Indentation: tabs (matching Paradox convention)
- Localisation keys use `:0` suffix for base priority

## Vanilla Overrides
Files that intentionally override vanilla behavior (no `tt_` prefix):
- `common/ascension_perks/tt_ascension_perks.txt` — Overrides `ap_world_shaper` and `ap_detox`
- `common/game_rules/tt_rules.txt` — Overrides `has_ascension_for_terraforming_candidate`
- `common/system_tooltips/tt_system_tooltips.txt` — Overrides frozen/toxic terraforming tooltips
