---
date: 2019-05-06
title: FiveM Introduction
categories:
  - Rust
description: Getting started with Rust
type: Document
---

# Rust Introduction
First time hosting a Rust server? Don’t worry, we’re here to help.

## First Steps:
The Rust game server will work out of the box, with no pre-configuration needed.
You can do some simple steps to adjust the server appearance to your liking.
Once the server has been installed and you have logged into the gamepanel head over to  `Configuration` -> `Startup Parameters`

* Server Name
This is the name the server will have on the Rust server browser.
* OxideMod
`1` to enable, `2` to disable.
Oxidemod is a plugin loader for rust, and plugins will not work if it's disabled.
You can find a lot of plugins [here](https://umod.org/plugins). Plugins are very easy to install, 
Simply download the `.cs` file from that page, and upload it to `/oxide/plugins` on you File Manager. 
All plugins in this folder will be loaded automatically by the server, and a config file is usually created at `/oxide/config`. 
The file manager on our gamepanel has a built in text editor thats great for small edits, like configs.
* Level
This is the map name used. If you're unsure how this works, leave it at `Procedural Map`. 
Procedural map is very configurable and you can preview maps [here](http://playrust.io/). 
* World Size; This will be the map size, start out at 3500, and adjust as you see fit.
* World Seed: This is how the map will look, head over to [http://playrust.io/](http://playrust.io/). to make a preview before deciding on a number.
* Description
This is the description that appears under Server Name. supports multiple lines, type `\n` to start a new one.
Example: `This will be the first line \n And this will be the second line.`
* URL
The URL for your server. This is what comes up when clicking the "Visit Website" button on the server browser.

If you have more questions, don't hesitate to contact us trough a ticket or on Discord!