Adding a plugin to the server
=============================

Want to add a cool plugin to the server? Whether it's one you found online or made yourself, anyone is welcome to submit a plugin via a **pull request** to the server. Before you submit your plugin, there's a few things you need to know first.

## What you need

You will need the following things in order to add a plugin to the server.

* Minecraft account
* GitHub account (Don't have one? Register for one [here](https://github.com/join)!)
* [SpigotMC.org](https://www.spigotmc.org) account (optional)
* Good searching skills


## Adding a plugin

This Minecraft server is all open source, just like the software and plugins that make it what it is. As a result, you are able to file "issues" for problems on the server and submit "pull requests" to add things to the server. If you know of a plugin or want to find one to do a specific thing, you can open a pull request to add in the plugin.


### Finding a plugin

When looking for a plugin, it's important to know the difference between a **mod** and a **plugin**. A Minecraft modification, or "mod", changes the actual Minecraft game client you use. When using a modded game, you can only connect to special servers that support the mod for them to work. Usually this does not include the "regular" multiplayer servers. Spigot is a server software that "replaces" the vanilla Minecraft server software by Mojang. With Spigot, it has an API, or Application Programming Interface, that developers can use to write their own plugins. These plugins work inside of Spigot, so you can use them on the "regular" Minecraft game client.

Bukkit/Spigot has been around since 2011. Since it's been around so long and is very popular, there's many plugins scattered across the Internet. The two most common places to look for plugins are [BukkitDev](http://dev.bukkit.org/) and [SpigotMC Resources](https://www.spigotmc.org/resources/). These two sites have directories and listings of plugins published by their authors. SpigotMC Resources is actively maintained while BukkitDev isn't as actively used anymore. You should search both for plugins that might be interesting or useful.

#### Plugin requirements

If you find a plugin on BukkitDev or SpigotMC Resources you want to add to the server, you need to make sure it meets a few basic requirements.

1. The plugin must be open source in a publicly viewable place, like GitHub.
2. The plugin must use an [approved license](https://opensource.org/licenses) from the [Open Source Initiative](https://opensource.org/).

If the plugin does not meet these requirements, it cannot be added to the repository for the Minecraft server.


## Submitting a pull request

Once you have a plugin that meets the requirements, it's time to submit a pull request. When adding the plugin to this repo, you will need to add its JAR file to `server/plugins/` to make sure that Spigot is able to load it into the server. Additionally, you will need to edit the README file in the `server/plugins/` folder and add the information in for your plugin. This list has plugin names, where to find their source code, and what license they use. Also note, the list is sorted alphabetically.

If you are submitting a plugin with documentation, it is appreciated if you also submit the configuration file in your pull request. This saves time from having to learn the plugin and have an administrator configure it themselves.

If you are able, please make sure you test your changes as well before submitting anything to the server.