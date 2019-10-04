# Novucs' FactionsTop
An efficient and comprehensive factions ranking system.

# THIS IS NOT THE OFFICIAL PAGE

## This is a temporary measure to support the plugin until novucs can update it

This Bukkit plugin adds a command to the well known factions plugin to display
all factions on the server, ordered by wealth. The wealth of a faction is
determined by calculating the value of all blocks and chest contents stored in
the faction claims. This specific implementation aims to provide real-time
results while still maintaining a good performance.

## Supports
* FactionsUUID by drtshock
* H2 and MySQL

## Usage
### Commands
| **Command**      | **Description**                 |
| -----------------| --------------------------------|
| /ftop <page>     | List all top factions in chat   |
| /ftopgui <page>  | List all top factions with GUI  |
| /ftoprecalculate | Recalculates all faction values |
| /ftopreload      | Reload the plugin settings      |
| /ftopversion     | View the plugin version         |

### Permissions
| **Permission**          | **Description**                 | **Default** |
| ------------------------| ------------------------------- | ----------- |
| factionstop.use         | List all top factions           | everyone    |
| factionstop.recalculate | Recalculate all faction values  | operator    |
| factionstop.reload      | Reload the plugin settings      | operator    |
| factionstop.sign.break  | Break FactionsTop ranking signs | operator    |
| factionstop.sign.place  | Place FactionsTop ranking signs | operator    |

## Development
### Prerequisites
* [Maven](https://maven.apache.org/)
* [OpenJDK 8](https://openjdk.java.net/install/)

### Project Setup (For UNIX)
```sh
# Clone the factions-top repository.
git clone git@github.com:novucs/factions-top.git

# Install factions-top.
mvn clean install
```
