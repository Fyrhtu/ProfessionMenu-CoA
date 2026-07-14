# ProfessionMenu — Woodworking

Based on **[Ascension-Addons/ProfessionMenu](https://github.com/Ascension-Addons/ProfessionMenu)** (launcher package, flat layout).

## Change (only)

In `ProfessionMenu/ProfessionMenu.lua`, after Woodcutting:

```lua
{
    1005011, -- Artisan
    1005010, -- Expert
    1005009, -- Journeyman
    1005008, -- Apprentice
}, --WOODWORKING
```

Plus `CA_IsSpellKnown` fallback when checking known professions (Ascension custom IDs).

## PR target

https://github.com/Ascension-Addons/ProfessionMenu
