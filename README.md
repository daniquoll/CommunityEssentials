# LacunaPluginTemplate

[🇷🇺 Русский](README_ru.md)

This is a template for creating [Lacuna](https://lacunabot.com) plugins.

## How to use this template

1. Close this repository
2. In the server settings on [lacunabot.com](https://lacunabot.com/@me/guilds), export the custom commands and automations you want to add to your plugin and upload the files to the `puzzles/` folder
3. Edit the `manifest.json` file by adding the plugin information to it
4. Edit the `README.md` file and add a detailed description of your plugin
5. Change your repository description

### How to localize a plugin

The `manifest.json` file may contain the `name_l10ns` and `summary_l10ns` properties, for example:

```json
{
    "name": "Plugin name",
    "name_l10ns": {
        "ru": "Название плагина"
    },
    "summary": "A short description for your plugin",
    "summary_l10ns": {
        "ru": "Короткое описание для вашего плагина"
    },
    "version": "1.0.0",
    "mv": 1
}
```

To localize the `README.md` file, create a copy of it and add the localization name to the file name: `README_[two_letters_code].md` (e.g., `README_ru.md`)

You can check the list of available localizations [here](https://github.com/LacunaHub/LacunaLocale/blob/master/index.js#L19).

## How to publish a plugin

1. Add the `lacuna-bot-plugin` topic for your repository in the information settings
2. Wait for your plugin to get verified

## Support

You can ask your questions on our [official server](https://discord.gg/n8ZkQMPb).