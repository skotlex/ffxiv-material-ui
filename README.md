![logo](ModPacks/Resources/Preview/github_logo_w902.png)

## FFXIV Material UI (Discord/Black)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/skotlex/ffxiv-material-ui) ![GitHub all releases](https://img.shields.io/github/downloads/skotlex/ffxiv-material-ui/total) ![GitHub release (latest by SemVer including pre-releases)](https://img.shields.io/github/downloads-pre/skotlex/ffxiv-material-ui/latest/total) [![GitHub license](https://img.shields.io/github/license/skotlex/ffxiv-material-ui)](https://github.com/skotlex/ffxiv-material-ui/blob/master/LICENSE) [![Support Server](https://img.shields.io/discord/591914197219016707.svg?color=7289da&label=FFXIV/Material%20UI&logo=discord&style=flat-square)](https://discord.gg/T5sWUpgNPD)

*※ The document was written using a translator. Please excuse me even if the context is a little strange.*

## Contents
1. [Intro](#intro)  
2. [Mod downloads](#mod-downloads)  
3. [Preview mods](#preview-mods)  
4. [Preview options](#preview-options)
5. [Installing the mod](#installing-the-mod)  
6. [What to do for new FFXIV patches](#what-to-do-for-new-ffxiv-patches)  
7. [Disclaimers](#disclaimers)  
8. [FAQ](#faq)  
9. [Special thanks](#special-thanks)  
10. [Credit and support](#credit-and-support)  
11. [Contacts](#contacts)


---
# **Attention!**
#### At the time of writing, this mod only supports the Standard (HD/full HD) icons.
* 4K support is being worked on and is aiming to be implemented before 6.0, please see [here](https://github.com/skotlex/ffxiv-material-ui/issues/214) for more information.

#### At the time of writing, this mod only supports the Dark system color scheme.
* At this time, no other themes are supported nor are there any plans to do so.  

The System theme is changed by selecting the System Configuration menu, then Theme settings, then selecting Dark in the dropdown menu. <br> <details>
<summary>Click for visual reference</summary>

![screenshot](ModPacks/Resources/Theme.png)

</details>

#### Icons are missing or displaying incorrectly after the 5.5x patches
* In the past updating the game client without disabling mods usually worked fine, however, it was not in best practice to do so. Updating to 5.5 with mods enabled broke most installs as SquareEnix implemented a few major changes in how data was stored, which resulted in TexTools injecting mods into the wrong location.

You can try to resolve this by ensuring you have all the .ttmp2 files saved from any mods you wish to keep (or the download location to reobtain the information), then open textools, download the index backups, and then select "start over". The index backups can also be downloaded from [here](https://github.com/skotlex/ffxiv-material-ui/tree/master/Index_Backups). If none of those work, you will need to completely reinstall the game.

---
## Intro
Material UI replaces FFXIV's built-in theme (dark-theme)

There are two kinds, the concepts for each theme are as follows:

1. **Discord**: Discord color with default UI concept
2. **Black**: Targeting modern dark color, Edged UI

## Mod downloads
Download Link: [Click me](https://github.com/skotlex/ffxiv-material-ui/releases)

## Preview mods
There are also a lot of other things that have been changed. Check out the in-game screenshots!  
<b><i>※ All images can be viewed as original when clicked</i></b>

<details>
<summary>Click to expand</summary>

### ◇ Discord
![preview discord](ModPacks/Resources/Preview/preview(discord).png)

### ◇ Black
![preview black](ModPacks/Resources/Preview/preview(black).png)

### ◇ Simple JobHud bar
![preview jobhud bar](ModPacks/Resources/Preview/jobhud.png)

### ◇ Treasure Map Coordinate
![preview treasure map](ModPacks/Resources/Preview/mappack.png)

</details>

## Preview options
Document Link: [Click me](https://github.com/skotlex/ffxiv-material-ui/blob/master/preview_options.md)

## Installing the mod

1. Download and install FFXIV TexTools

***FOR TEXTOOLS, RECOMMEND TO USE THE LATEST VERSION.***

| Program name  | Download page |
|---|---|
| TexTools | [https://textools.dualwield.net](https://textools.dualwield.net) |

2. Back up the following files in advance before you work *(This is a preparation for mode failure)*

Hit [Help → Backup Index Files] menu.

**Source index-path**: `{Folder with ff14 installed}\game\sqpack\ffxiv`

| File list |   |
|---|---|
| 010000.win32.index | 010000.win32.index2 |
| 040000.win32.index | 040000.win32.index2 |
| 060000.win32.index | 060000.win32.index2 |

3. Apply Material-UI mod

Select and apply(import modpack) the *Material UI.ttmp2* file from the *[Mods → Import ModPacks]* menu

4. Enjoy!

## What to do for new FFXIV patches

I recommend making a mod backup, you can do this by selecting `Make Modpack` in the mods menu, selecting every active mod, and hitting create. Before downloading a new FFXIV patch it is safest to hit the `Start Over` option in the TexTools help menu, installing the FFXIV patch, then importing the mod backup you created previously. While these precautions don't always turn out to be necessary, you risk damaging your install if you don't take them.

If you difficult to understand what's written above, follow the steps below.
1. Hit `[Help → Start Over]`
2. Download new FFXIV patch
3. Hit `[Help → Backup Index Files]`
4. Import Material-UI mod

If you fail to back up the index files for any reason, you can download them from my github. [download link](https://github.com/skotlex/ffxiv-material-ui/tree/master/Index_Backups)

## Disclaimers

Use of this program is at your own risk. Square Enix does not permit the use of any third party tools, even those which do not modify the game. They have stated in interviews that they did not view parsers as a significant problem unless players use them to harass other players

## FAQ

**Can you change the color of the HP/MP/Gauge bars?**

Not currently. It's not that it is impossible, just not very intuitive. More than anything else, you can't get the color you want perfectly.

**How can I apply the option?**

1. Apply Material-UI(discord or black).ttmp2
2. Download OPTIONS.zip and move to the wanted folder. (ex. ~\OPTIONS\01_Minimap\03_discord-square-minimap)
3. Apply ttmp2 in the folder.

**How do I use Simple job hud?**

It is only possible in simple job hud. Please refer to the following site:
[SQEX simple hud guide](https://na.finalfantasyxiv.com/blog/002175.html)

## Special thanks

I always thank [*rien-doll*](https://github.com/rien-doll/minimal-ui) for inspiring me and for giving me knowledge. Her creativity always stimulates me. Most of all, I would like to thank everyone who uses this UI.

## Credit and support

This mod was created by *skotlex* and help of all testers.

If you like my work and want to support it, you can do it [here](https://ko-fi.com/skotlex). Of course, there is no coercion in this sponsorship, and it's just your choice.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/O4O8YTN7)

## Contacts

If you want to ask me something, I am willing to talk.

However, if possible, please use [my github issue page](https://github.com/skotlex/ffxiv-material-ui/issues) for various suggestions, questions, and requests for material-UI. It's gonna be easy to keep records, and it's gonna be easy to manage.

And please understand the awkwardness of the sentence because I am not an English user.

* Discord: SKOTLEX#3060
* Twitter: @skotlex
