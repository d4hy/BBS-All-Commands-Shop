# BBS All Commands Shop

An OpenKH LuaBackend mod for the Steam release of **Kingdom Hearts Birth by Sleep Final Mix**. It makes legitimate commands available for purchase immediately while preserving the original character-specific shop lists.

## Features

- Unlocks 90 legitimate purchasable command IDs.
- Uses the game's original Terra, Ventus, and Aqua shop lists, so each character sees only commands from their own list.
- Keeps commands marked hidden or internal by the game out of the shop.
- Hides 18 movement, defense, and reprisal action IDs that display placeholder names, `XXX` descriptions, or invalid prices in the purchase interface.
- Does not edit the save file or game executable.
- Contains no extracted game assets.

Mega Flare is intentionally not added because the game marks it as unavailable for shop purchase.

## Requirements

- Kingdom Hearts Birth by Sleep Final Mix from the Steam release of Kingdom Hearts HD 1.5+2.5 ReMIX
- OpenKH Mod Manager
- LuaBackend configured for Birth by Sleep

## Installation

1. Download the release ZIP.
2. Install it through OpenKH Mod Manager for Birth by Sleep.
3. Enable **BBS All Commands Shop** and the BBS LuaBackend loader.
4. Select **Build and Run**.

Restart the game after replacing an older copy of the mod so LuaBackend unloads the previous script.

## How it works

The Lua script restores the game's original Command Shop filtering instructions, sets the shop requirement for valid command IDs to zero, and marks invalid action entries as hidden. Character filtering remains controlled by the game's original shop data.

## Compatibility

The memory addresses in this project target the current Steam GL executable. A future game update may require updated addresses.

## License

Released under the [MIT License](LICENSE).

## Disclaimer

This is an unofficial fan-made mod. Kingdom Hearts and related properties belong to their respective owners. This project is not affiliated with or endorsed by Square Enix or Disney.
