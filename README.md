# Scaled Minecraft based on Minestom (1.21.1)

Scaled Minecraft is a Minecraft Server designed for Minestom to manage and load/unload specific areas of the world dynamically based on instance configurations. This Server is particularly useful for large-scale servers where different instances or zones need to be managed separately to optimize performance.

## Features

- Dynamically load and unload chunks in a specified area of the world.
- Manage multiple instances with configurable area sizes.
- Efficiently handle large world areas (e.g., 10,000 x 10,000 blocks per instance).
- Automatically determine chunk coordinates and load/unload them during the Server's lifecycle.

## Installation

1. Download the latest release of the plugin from the [Releases](https://github.com/ppstudiosdev/scaled_minecraft/releases) page.
2. Unzip the ZIP File.
3. Start the Server with the `s.sh` or the `s.bat` alternativ use the `s.cs` for more performance file.

## Configuration

The plugin uses a simple configuration file (`config.yml`) to manage the instance ID. This ID is crucial as it defines the specific area of the world that this plugin instance will manage.

```yaml

NEW FEATURES - COMING SOON

# config.yml
# This file was created with IntelliJ from PixelPlayer Studios (RxbbitIT) Discord: rxbbit.it

# The unique ID for this instance. This ID determines the start and end coordinates for the area managed by this instance.
instance_id: 1

# Database Connection Settings
#
# ------------------------------------------------------------
#            Scaled Minecraft - Database Types 
#          Example Database-Types are Supported
#  POSTGRESQL, SQLLITE, MONGODB, MARIADB, MYSQL, POSTSQL usw.
# ------------------------------------------------------------
type: SQLLITE

ip: 123.456.789.10
port: 1234
user: scaled_minecraft
database: scaled_minecraft
