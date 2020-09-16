# Reporting an incompatibility

We've all ben there. You download that modpack, 
or finish installing your handpicked mods, 
and you've loaded your client, and you're waiting for the server to start when you notice it.

The server crashed

The idea of this document is to allow you to help other users that might experience the same issues as you.
This is a comprehensive guide to reporting incompatibilities with Mods/Plugins on Magma.
Please note that this does not cover incompatibility with plugins that are not published for a game version
Magma supports. This means even if a 1.8 plugin works on a 1.12 spigot server, if it doesn't work on Magma, we
don't support that incompatibility. If, however, the plugin is a 1.12 plugin and it doesn't work on Magma 1.12,
this is the place to report it.

## Where to report incompatibilites

The first place to report an incompatibiliy is on the issue page of Magma's repos 
- [1.12.2](https://github.com/magmafoundation/Magma)
- [1.15.2](https://github.com/magmafoundation/Magma-1.15.X) - Alpha
- [1.16.3](https://github.com/magmafoundation/Magma-1.16.X) - Unreleased

Before opening a ticket, please check to see if someone else has already reported the
incompatbility you found either in the issues of the Magma repo, or on this repo.

Each game version folder holds a sub folder called incompatibilities.
Inside will be any incompatbily scenarios that have been found

## Submiting an incompatibility request

1) Fork this repo to your own user/org if you haven't already
2) Navigate to the incompatibilites folder for your game version
3) Check to see if your incompatibility has already been listed
4) If not listed make a new file called mod_name.mod.incompatible or plugin_name.plugin.incompatible (The other extentions apply too .library and .coremod)
  - If your incompatibility is because of a mixture of two or more mods/plugins please create a file named with the following convention:
    - If your incompatibility is between two mods, please use the following name 
        - `first_mod_name-second_mod_name.mod.incompatbile`
    - If your incompatibility is between more than two mods, please use the following name 
        - `first_mod_name-second_mod_name-number_of_incompatible_mods.modgroup.incompatbile`
    - If your incompatibility is between two plugins, please use the following name 
        - `first_plugin_name-second_plugin_name.mixed.plugin.incompatbile`
    - If your incompatibility is between more than two plugins, please use the following name 
        - `first_plugin_name-second_plugin_name-number_of_incompatbile_plugins.plugingroup.incompatbile`
    - If your incompatibility is between a plugin and a mod, please use the following name 
        - `mod_name-plugin_name.mixed.incompatbile`
    - If your incompatibility is between more than one or more plugins and one ore more mods, please use the following name 
        - `first_mod_name-first_plugin_name-number_of_incompatible_mods-number_of_incompatible_plugins.mixedgroup.incompatbile`
5) Then fill out the template for the incompatibility listing. If you don't know what to fill out, please refer to example_incompatibilities.md   

If you have any questions or struggles related to submitting an incompatibility rquest, please contact Kwright02 on [discord](https://discord.gg/jm8vNpX)

    
