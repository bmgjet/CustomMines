Custom Mines

Custom Mines allows players to change the damage and upgrade the land mine to 3 different modes using the chat command /mine.upgrade followed by the type to upgrade to.
Example
/mine.upgrade flame
/mine.upgrade smoke
/mine.upgrade flash

It will check a player is at a workbench of the level set in the config file as well as checking the player has the required parts to upgrade it which is set in the config file.

Admin commands for the plugin are as follows.
/mine.reload
This will reload the config file so you don’t need to restart the server to reload the settings.

/mine.upload arg
Convert your config file to base64 and you can provide the full base64 string as arg and it will upload it to your server.

/mine.version
Prints out what version is running.

The price to upgrade mines and their workbench requirement is set within the config file.

Note:
This will auto-toggle the modded tag on your server since it changes base gameplay.
Give Notices are disabled for admin and users to stop the massive chat spam that would happen.
Install:

Copy this dll to your HarmonyMods folder.
A default config file has been provided otherwise the mod will create a new config on its own with default settings.
