<div align="center">

# 💎 Gen-Splitter

**Share generator drops between teammates in [MBedwars](https://www.spigotmc.org/resources/mbedwars.13940/).**

![Java 8+](https://img.shields.io/badge/Java-8%2B-orange?logo=openjdk&logoColor=white)
![MBedwars](https://img.shields.io/badge/requires-MBedwars%205-dc2626)
![License](https://img.shields.io/badge/license-GPL--3.0-blue)

> BlockStorm's fork of [MetallicGoat/Gen-Splitting](https://github.com/MetallicGoat/Gen-Splitting).

</div>

---

## ✨ Features

| | Feature | |
|---|---|---|
| ✂️ | **Gen splitting** | When a player picks up items from a generator, teammates standing nearby get the same items |
| 🧲 | **Auto collect** | When a player is killed, the killer receives their resources directly instead of them dropping on the ground |
| 🕳️ | **Anti void drops** | Stops players from dropping items while they are above the void |
| 🆙 | **LevelShop support** | Also splits experience levels when the MBedwars LevelShop addon is installed |

## ⚙️ Configuration

The add-on's `config.yml` is in its folder inside MBedwars' add-ons directory:

| Option | Default | |
|---|---|---|
| `Gen-Splitter` | `true` | Turn splitting on or off |
| `Split-Spawners` | iron, gold | Which spawner materials are split |
| `Split-Radius` | `2.5` | How close teammates must be, in blocks |
| `Split-LevelShop-Addon` | `true` | Split experience levels from the LevelShop addon |
| `Anti-Void-Drops` | `false` | Block dropping items into the void |
| `Auto-Collect.Enabled` | `true` | Turn auto collect on or off |
| `Auto-Collect.Percentage-Kept` | `100` | Percentage of the victim's resources the killer receives |
| `Auto-Collect.Message` | `{item} &f+{amount}` | Message shown to the killer for each resource |

## 📦 Requirements

| Plugin | |
|---|---|
| MBedwars 5 | **Required** |
| MBedwars LevelShop | Optional |

## 🛠️ Building

```bash
mvn clean package
```

## 📄 License

Gen-Splitter is licensed under the [GNU GPL v3](LICENCE.md), inherited from the original project by MetallicGoat.
Changes in this fork are released under the same license.
