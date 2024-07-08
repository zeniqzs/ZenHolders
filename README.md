# ZenHolders Plugin 🎮

The ZenHolders Plugin provides comprehensive placeholder functionality for various player statistics and data in Minecraft. With this plugin, you can easily access important game information and use it in your server or plugins.

## Functionalities 📊

### Deaths Placeholder 💀

The Deaths Placeholder allows displaying a player's death count or accessing their rank based on deaths.

#### Usage

- `%player_deaths%`: Displays the player's death count.
- `%player_deaths_place_[number]%`: Displays the death count of the player at the specified rank. (Numbers: 1 - 99 )
  - Example: `%player_deaths_place_1%` shows the deaths of the player with the most deaths.
  - `%player_deaths_place_1_name%`: Displays the name and death count of the player with the most deaths.

#### Configuration

The configuration file (`config.yml`) allows customization of placeholder formatting:

```yaml
configuration:
  formating:
    billions: "B"
    millions: "M"
    thousands: "k"
```

Other Placeholders 📈
In addition to Deaths, the ZenHolders Plugin provides placeholders for various other statistics:

Money (Vault) 💰
Jumps 🏃‍♂️
PlacedBlocks 🧱
BrokenBlocks 🔨
Kills ⚔️
Playtime ⏰
These placeholders can be used similarly to the Deaths Placeholder, allowing detailed customization and analysis of player statistics.

Integration and Customization 🛠️
The plugin can be easily integrated into existing Bukkit/Spigot servers. Ensure you customize the configuration file according to requirements and properly attribute the plugin developer.

Customization
To adapt the plugin to specific needs, you can extend or modify its functionalities. Ensure thorough testing of all changes to maintain server stability.

Developer Notes
The developer Zeniqzs offers this plugin for free. Please ensure that the developer's name or website link is mentioned in the configuration file or other publicly visible files (such as plugin.yml, leaderboards.yml, or config.yml) for proper recognition.#

# Example configuration in plugin.yml
```yaml
author: Zeniqzs
website: https://zeniqzs.eu
```

Support and Contact 📧
For questions, suggestions, or bug reports, you can contact the developer through the website or create an issue on GitHub.

- Website: https://zeniqzs.eu
- GitHub Repository: https://github.com/zeniqzs/zenholders
