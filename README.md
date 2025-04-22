# ElementalAbilityStar Plugin

## Overview
ElementalAbilityStar is a custom Minecraft plugin designed for Spigot or Paper servers. This plugin allows players to obtain random elemental abilities by using a special item called the "Ability Gambler." Admins can preview and test these abilities through a user-friendly GUI.

## Features
- **Random Elemental Abilities:** Players can right-click the "Ability Gambler" item to receive a random elemental ability.
- **Admin GUI:** Admins can access a GUI to preview and assign abilities using the `/aristagiveadminitem` command.
- **Ability Management:** Players can only have one active ability at a time, which is lost upon death or logout.
- **Configurable Options:** Customize the name and lore of the Ability Gambler, toggle abilities on/off, and set persistence options.

## Installation
1. Download the latest version of the ElementalAbilityStar plugin.
2. Place the plugin JAR file into the `plugins` folder of your Spigot or Paper server.
3. Restart the server to generate the configuration files.
4. Configure the `config.yml` file as needed.
5. Use the Shopkeepers plugin to sell the "Ability Gambler" item to players.

## Commands
- `/aristagiveadminitem`: Opens a GUI for admins to select and assign elemental abilities. Requires the `elementalabilities.admin` permission.

## Elemental Abilities
- 🔥 **Pyro:** Immune to fire/lava; attackers are set on fire.
- 🌊 **Aqua:** Water Breathing + Dolphin’s Grace.
- 🌪️ **Windwalker:** Speed II + Slow Falling.
- 🌍 **Geo:** Resistance I + Knockback immunity.
- ⚡ **Storm:** Strength I + chance to strike lightning on hit.
- 🌑 **Shadow:** Night Vision + Invisibility (cancels on damage).
- ☠️ **Venom:** Poison mobs on hit.
- 🧛 **Bloodthirst:** Heal 1 heart on mob kill.

## Configuration
The plugin's configuration options can be found in the `config.yml` file. You can customize the following:
- Toggle abilities on/off.
- Change the name and lore of the Ability Gambler item.
- Set whether abilities persist after death or logout.

## Compatibility
ElementalAbilityStar is fully compatible with the Shopkeepers plugin, allowing players to purchase the "Ability Gambler" item easily.

## Support
For any issues or feature requests, please open an issue on the GitHub repository. Contributions are welcome!
