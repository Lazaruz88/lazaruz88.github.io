---
date: 2019-05-06
title: DarkRP installation
categories:
  - Garry's Mod
description: Getting started with DarkRP
type: Document
---

## Start off by navigating to [DarkRP's github](https://github.com/FPtje/DarkRP)

1. Click `Download as ZIP`
2. Open up the gamepanel and navigate to File Management
3. Head over to the folder `/garrysmod/gamemodes` and click the blue button top right corner Upload
4. Select the `DarkRP-master.zip` you downloaded from github, and let it finish.
5. Click the three dots to the right of the zip and select `decompress`. If it's missing, hit F5 or click the refresh button on the panel
6. Now you will have a new folder named DarkRP-master. This has to be renamed to `darkrp` _lowercase_.
7. Next, head over to `Configuration`, then select `Startup Parameters`.
8. Edit the Gamemode box from `sandbox` to `darkrp`. This has to be _lowercase_ as well
9. Restart the server and you're done. Pay attention to the console to ensure nothing went wrong.


### Now that you have checked that the server starts up correctly in DarkRP gamemode,
### you can move over to installing DarkRP Modification.

1. Open up the gamepanel and navigate to `Mod Manager`.
2. On both `css_content.zip` and `darkrpmodification.zip` click Add. 
3. This will automatically add two new folders to `/garrysmod/addons`. So open up File manager and head over to `/garrysmod/addons`.
4. Now DarkRP with DarkRP Modification is fully installed, and you can start configuring as you see fit.
5. Please note that you shouldn't edit any DarkRP files inside `/garrysmod/gamemodes`. This is why we installed `/garrysmod/addon/darkrpmodification`.

A good place to start will be to read trough it's config files to get a understanding on how it works.
You can find the main config at garrysmod/addons/darkrpmodification/lua/darkrp_config


If you have any questions don't hesitate to contact us through a ticket or at discord!