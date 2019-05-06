---
date: 2019-05-06
title: FiveM Introduction
categories:
  - FiveM
description: Getting started with FiveM
type: Document
---

### First time hosting a FiveM server? Don’t worry, we’re here to help.

## Required step:
Once it’s ordered and set up, you’re going to need a license key from FiveM.
You can get it for free at their site [here](https://keymaster.fivem.net/)

Once you have a key ready open up the gamepanel and navigate to `Configuration` then `Startup Parameter`.
Paste the key in the box there and click save.
You can now start up the server and it should run without any issues.

## Other useful info:
Inside Startup parameter where you set up your key, there’s a couple other boxes.


* Server Hostname:
Here you can input what the server will be named on the FiveM Server browser.

* OneSync:
A FiveM early access perk, currently a FiveM Patreon feature.
To use this you will need a whitelisted key.
This can only be acquired by joining FiveM’s patreon signup, read more here: https://www.patreon.com/fivem
OneSync will allow you to have slots up to 64. With OneSync disabled max slots is 32.

 

## Addons/Plugins/Resources
FiveM addon/plugin is called a resource. It’s fairly easy to set up once you understand the basics of it.
You can find a lot of good resources [here](https://forum.fivem.net/c/development/releases) or on GitHub.

### Here’s how to install a resource:
Once you have picked out and downloaded a resource you want to add, you will need to upload the folder to your FiveM resource folder. I would recommend using a FTP client to do so.
You can find the SFTP info under `Configuration` then `SFTP Settings`.

Once the folder is uploaded, you have to copy the folders name, avoid having spaces in it.
Then open up your server.cfg located in the root folder.

In there you will see a couple lines saying start `some name`, this is how resources are started.
Below those you need to add a new line, type start resoucefoldername

Save the file, and restart the server.

The resource should now be loaded and started.

 

If you have more questions, feel free to contact us trough a ticket or on Discord.