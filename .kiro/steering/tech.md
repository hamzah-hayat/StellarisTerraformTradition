# Tech Stack & Build

## Technology
- **Engine:** Stellaris Clausewitz Engine modding framework
- **Language:** Paradox scripting language (`.txt` files with custom syntax)
- **Localisation:** YAML-like `.yml` files with BOM encoding
- **Graphics:** DDS image format for icons and sprites, `.gfx` files for sprite definitions

## No Build System
This is a Stellaris mod — there is no compilation, build step, or package manager. Files are loaded directly by the game engine at runtime.

## Testing
- Manual testing in-game via the Stellaris console
- Check the game's error log at `Documents/Paradox Interactive/Stellaris/logs/error.log` after loading
- Script documentation reference files are available in the `script_documentation/` workspace folder (effects.log, triggers.log, modifiers.log, scopes.log)

## Versioning
- Mod version tracked in `descriptor.mod` (`version="X.Y.Z"`)
- Changelog maintained in `CHANGELOG.md` (detailed) and `CHANGELOG_STEAM.md` (Steam-formatted)
- `supported_version` in descriptor.mod tracks compatible Stellaris version

## Reference Documentation
The `script_documentation/` folder contains Stellaris engine documentation:
- `effects.log` — Available effects/commands
- `triggers.log` — Available condition triggers
- `modifiers.log` — Available modifiers
- `scopes.log` — Scope types and transitions
- `localizations.log` — Localization commands

The `Stellaris/common/` folder contains vanilla game files for reference when overriding or extending behavior.
