# Magma Compatibility Repository
This repo contains an effective list of mods/plugins that have a verified working version on Magma. 
This list coveres al released (and future) Magma versions.


IMPORTANT NOTICE: This is not an official product endorsed by Magmafoundation LLC and is a community
project aimed at providing a place where users of Magma can share what works with the platform. That said,
this repo is not managed by Magmafoundation LLC and has a right to it's own discretion to user submitted content.


Something that is hard to account for is mods and plugins that aren't compatible with eachother. If you find that
and two or more mods or plugins are not compatible with eachother, please read reporting_incompatibilities.md


# Submitting a compatibility verficiation request

Please follow all requirements for submiting a compatibility verification.
If you do not follow all requirements, then your reuqest may be ignored or deleted

1) To submit any request type, first fork this repo to your own user/org

## Submitting a mod compatibility verification request

2) First select the corrosponding game version folder for the mod, then enter the compatible_mods directory

3) Then see if there's already a file for your mod (Should be mod_name.mod Example: extra_utilities.mod)

  - If the mod you are requesting verification for has dependencies that aren't already listed, 
    please also make a file for those mods (Just follow the same convention as shown above 
    unless it is strictly a library mod. then use the .library extention)
    
  - If the mod you are requesting verification for has a core mod dependency that isn't inside 
    the core_mods folder for your game version please add a file for it using the .coremod extention
    
4) For an example of how to format the contents of your file, please see example_mod.mod, example_library.library, and example_core_mod.coremod. Once you have filled out the format for your mod, please make sure it is in the correct game version folder and correctely titled. All names should be lowercased, with underscores `_` instead of spaces ` `
  
## Submitting a plugin compatibility verification request

2) First select the corrosponding game version folder for the plugin, then the compatible_plugins folder

3) Then see if there's already a file for your plugin (Should be plugin_name.plugin Example: essentials.plugin)

  - If the plugin you are requesting verification for has dependencies that aren't already listed, 
    please also make a file for those plugins (Just follow the same convention as shown above 
    unless it is strictly a library plugin. then use the .libary extention)
    
4) For an example of how to format the contents of your file, please see example_plugin.plugin and example_library_plugin.library. Once you have filled out the format for your mod, please make sure it is in the correct game version folder and correctely titled. All names should be lowercased, with underscores `_` instead of spaces ` `


  ## Finishing your request


5) Once you have input all the plugins/mods you wish to submit with your request, please open a pull request on this repo.

  - First, select compare across forks at the top of the pull request page
  - Then select your fork of the repo from the list
  - Comment a summary of your request
  - Create request and wait for it's aprooval
  
  Depending on the size of your request, and the volume of requests, it could take up to 7 days to process your request.
 
