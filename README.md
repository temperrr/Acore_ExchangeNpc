## lua-exchange-npc
Lua script for Azerothcore with ElunaLua to spawn an NPC and have it exchange mats as configured.

#### Find me on patreon: https://www.patreon.com/Honeys

## Requirements:
Compile your [Azerothcore](https://github.com/azerothcore/azerothcore-wotlk) with [Eluna Lua](https://www.azerothcore.org/catalogue-details.html?id=131435473).
The ElunaLua module itself doesn't require much setup/config. Just specify the subfolder where to put your lua_scripts in its .conf file.

If the directory was not changed, add the .lua script to your `../lua_scripts/` directory.
Adjust the top part of the .lua file with the config flags.

## Admin usage:
Adjust the top part of the .lua file with the config flags. 
- if the entry wasn't changed, do `.npc add (temp) 1116001`

## GM usage:
Nothing to do.

## Player Usage:
Talk to the NPC, exchange items.
