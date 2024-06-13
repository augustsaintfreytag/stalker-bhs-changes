![Artwork BHSRO Overhaul 04](https://github.com/augustsaintfreytag/stalker-bhs-changes/assets/7656669/b7c084f4-1184-4ef8-a522-896a37c01a99)

# STALKER Body Health System Changes

A mod implementing custom changes to the Body Health System mod and its add-on Body Health System Realistic Overhaul (BHSRO) for the GAMMA mod pack available for STALKER Anomaly (Open X-Ray/Monolith engine).

> [!WARNING]
> This mod is in active development and not yet functional.
> Do not install this mod in your game in its current version.
> This warning will be removed once the mod is considered playable.

## Features

This mod provides the following technical features:

- Introduce the ability to display pre-formatted text in item stats (via `utils_ui`)
- Introduce new stats icons for medical effects (pain, nerves, limbs, splint)
- Move texture reference identifiers to use `ui_actor_sleep_screen` (from `ui_ingame2_common`)
- Introduce script-based way to display consumable properties as proper stats (including an icon, formatting, and unit)
  - Update stats item for health restoration (`boost_health_restore`) with a new medically inspired unit (PAR/h)
  - Update stats item for damage resistance (`boost_damage_immunity`), rebrand as analgesic (painkilling) effect with new "levels" unit
  - Add stats item for limb splinting (`boost_limb_splint`), part of BHS functionality
  - Add stats item for limb restoration (`boost_limb_restore`), part of BHS functionality
  - Add stats item for limb surgery (`boost_limb_surgery`), part of BHS functionality

It also provides the following content-related changes:

- Add new human-written descriptions to all medical items
- List consistent tags in item descriptions (medical item, imported item, core effects)
- Update descriptions and tags to use appropriate and lore-fitting medical terms
- Rebrand some medical items to realistic analogues, reduce yoinkage from other games (e.g. Tarkov)
- Change effects and durations of some medical items for balance, enjoyment, and description consistency

## License

This mod was created by Saint for free use by the STALKER modding community with basic attribution under the MIT license. This mod may be distributed with mod packs. Parts of this mod use DLTX created by Demonized (https://github.com/themrdemonized). Body Health System created by Grokitach (https://www.moddb.com/mods/stalker-anomaly/addons/100-groks-body-health-system-redux-for-151), and the Realistic Overhaul by Mirrowel (https://www.moddb.com/mods/stalker-anomaly/addons/bhs-realistic-overhaul).
