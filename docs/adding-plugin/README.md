Adding a plugin to the server
=============================

Want to add a cool plugin to the server? Whether it's one you found online or made yourself, anyone is welcome to submit a plugin via a **pull request** to the server. Before you submit your plugin, there's a few things you need to know first.


## Finding a plugin

Bukkit/Spigot has been around since 2011. Since it's been around so long and is very popular, there's many plugins scattered across the Internet. The two most common places to look for plugins are [BukkitDev]() and [SpigotMC Resources](). These two sites have directories and listings of plugins published by their authors. SpigotMC Resources is actively maintained while BukkitDev isn't as actively used anymore. You should search both for plugins that might be interesting or useful.

### Requirements

If you find a plugin you want to add to the server, you need to make sure it meets a few basic requirements.

1. The plugin must be open source in a publicly viewable place, like GitHub.
2. The plugin must use an [approved license](https://opensource.org/licenses) from the [Open Source Initiative](https://opensource.org/).

If the plugin does not meet these requirements, it cannot be added to the repository for the Minecraft server.


## Submitting a pull request

Once you have a plugin that meets the requirements, it's time to submit a pull request. When adding the plugin to this repo, you will need to add its JAR file to `server/plugins/` to make sure that Spigot is able to load it into the server. Additionally, you will need to edit the README file in the `server/plugins/` folder and add the information in for your plugin. This list has plugin names, where to find their source code, and what license they use. Also note, the list is sorted alphabetically.

If you are submitting a plugin with documentation, it is appreciated if you also submit the configuration file in your pull request. This saves time from having to learn the plugin and have an administrator configure it themselves.

If you are able, please make sure you test your changes as well before submitting anything to the server.