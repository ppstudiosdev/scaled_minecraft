# Scaled Minecraft

Scaled Minecraft is a Minecraft plugin designed to manage and load/unload specific areas of the world dynamically based on instance configurations. This plugin is particularly useful for large-scale servers where different instances or zones need to be managed separately to optimize performance.

## Features

- Dynamically load and unload chunks in a specified area of the world.
- Manage multiple instances with configurable area sizes.
- Efficiently handle large world areas (e.g., 10,000 x 10,000 blocks per instance).
- Automatically determine chunk coordinates and load/unload them during the plugin's lifecycle.

## Installation

1. Download the latest release of the plugin from the [Releases](https://github.com/ppstudiosdev/scaled_minecraft/releases) page.
2. Place the downloaded `.jar` file into the `plugins` folder of your Minecraft server.
3. Start the server to generate the default configuration file.
4. Configure the `instance_id` in the `config.yml` file located in the `plugins/scaled_minecraft` directory.
5. Restart the server to apply the changes.

## Configuration

The plugin uses a simple configuration file (`config.yml`) to manage the instance ID. This ID is crucial as it defines the specific area of the world that this plugin instance will manage.

```yaml
# config.yml
# This file was created with IntelliJ from PixelPlayer Studios (RxbbitIT) Discord: rxbbit.it

# The unique ID for this instance. This ID determines the start and end coordinates for the area managed by this instance.
instance_id: 1
