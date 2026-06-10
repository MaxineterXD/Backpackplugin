# Backpack Plugin for Minecraft

A feature-rich backpack plugin for Minecraft servers running Bukkit/Spigot.

## 📖 Quick Start

New to the plugin? Check out the [QUICK_START.md](QUICK_START.md) guide for fast setup!

## Features

- **Personal Backpacks**: Each player gets their own backpack inventory
- **Tiered Permissions**: Three backpack sizes based on permissions
  - Small: 9 slots (default)
  - Medium: 27 slots (op)
  - Large: 54 slots (op)
- **Easy Access**: Simple commands to manage backpacks
- **Item Management**: Track items and backpack contents
- **Player Integration**: Backpacks are created on join, cleaned up on leave

## Texture Pack Installation

See [TEXTURE_PACK_SETUP.md](TEXTURE_PACK_SETUP.md) for detailed instructions on installing the custom texture pack.

**Recommended**: Use the "Backpack Bundles! 1.21.2+ Soundless.zip" texture pack for enhanced visuals!

## Commands

| Command | Description | Permission |
|---------|-------------|-----------|
| `/backpack` | Open your backpack | backpack.open |
| `/backpack open` | Open your backpack | backpack.open |
| `/backpack close` | Close your backpack | backpack.open |
| `/backpack size` | Check your backpack size | backpack.open |
| `/backpack count` | Check item count in backpack | backpack.open |
| `/backpack info` | View backpack information | backpack.open |
| `/backpack clear` | Clear your backpack | backpack.admin |
| `/backpack help` | Show help menu | backpack.open |

**Aliases**: `/bp` can be used instead of `/backpack`

## Permissions

| Permission | Description | Default |
|-----------|-------------|---------|
| `backpack.open` | Use backpack commands | true |
| `backpack.size.small` | Access small backpack (9 slots) | true |
| `backpack.size.medium` | Access medium backpack (27 slots) | op |
| `backpack.size.large` | Access large backpack (54 slots) | op |
| `backpack.admin` | Use admin commands | op |

## Configuration

The plugin currently stores backpacks in memory. Future versions will include:
- YAML/JSON persistence
- Database support
- Custom backpack sizes
- Visual customization

## Building

Requirements:
- Java 11 or higher
- Maven 3.6 or higher
- Spigot/Bukkit API 1.20


The compiled JAR will be in the `target/` folder.

## Compatibility

- **Minecraft Version**: 1.20 (configurable in pom.xml)
- **Server Software**: Bukkit, Spigot, Paper
- **Java Version**: 11+

## Features in Development

- [ ] Backpack persistence (save/load)
- [ ] Database support (MySQL/SQLite)
- [ ] Custom backpack skins/colors
- [ ] Backpack hotbar shortcut
- [ ] Shared backpacks
- [ ] Backpack upgrading system
- [ ] Configuration file support


## Support

For issues or feature requests, feel free to contact the development team.
