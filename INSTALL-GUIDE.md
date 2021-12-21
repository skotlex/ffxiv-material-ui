## INSTALL-GUIDE CONTENTS
1. [TEXTOOLS](#textools)
2. [PENUMBRA](#penumbra)
3. [IN-GAME SETTINGS](#in-game-settings)

## TEXTOOLS
#### If the game is running before following the guide, close it.
1. Download the latest version of the Material UI and OPTIONS from the [Releases page](https://github.com/skotlex/ffxiv-material-ui/releases/latest).
![down_cnts](ModPacks/Resources/Preview/down_cnts.png)
2. Unzip the downloaded compressed files to somewhere you can find them.  
    - If you already have TexTools installed skip to `step 5`
3. Download the latest version of the `Install_TexTools.exe` file from [here](https://github.com/TexTools/FFXIV_TexTools_UI/releases/latest).
4. Install and run the program.
    - If you do not have the latest version of .NET you will not be able to open the program and will get an error. If this happens download the latest version of .NET here  [.NET downloads](https://dotnet.microsoft.com/download/dotnet/5.0/runtime)

    - Try opening the program again.
    - For additional troubleshooting, join their discord [here](https://discord.gg/ffxivtextools).
5. Click `Help` → `Backup Index Files` menu.
    - This will create a backup, so that if you want to revert the changes you can clear all of them by clicking `Help` → `Start Over`.
6. Click `Mods` → `Import Mod Packs`
7. Select `Material 4K-UI BLACK (version).ttmp2` and hit open button.
    - If you want to apply additional OPTIONS, select the OPTIONS ttmp2 in the same way as `step 6 to 7`
    - Any mods containing conflicting textures will be loaded in the order that they were installed meaning installing an option __before__ the main file will not work as expected. It is generally best to install mods one by one instead of all at once
8. All of the textures will now be loaded next time you launch FFXIV.

#### YouTube guide
- Thank you `Whiskeyz` for providing this video
  - 📹 https://www.youtube.com/watch?v=zbLWV4Y9HQI

## PENUMBRA
>**If you are a person who uses the material UI for mods, I recommend using Penumbra rather than TexTool. This is updated automatically without having to worry about the index file breaking down every time a patch occurs. You can also easily apply various options.**

I would like to express my great gratitude to __@Sevii__ for making and managing this.\
\
📌🔗 **[Material UI Accent Plugin by Sevii](https://github.com/Sevii77/ffxiv_materialui_accent)**
![sevii_mui_preview](https://user-images.githubusercontent.com/31692408/146949022-9e13d6b8-b4f6-44aa-bebb-365db16e7d25.png)

⚠️ **WARNING!!!** ⚠️
>**If you were previously using Material UI mods using the TexTool, you should click the 'Help → Start Over' menus and turn the index back to its original state. If TexTool and Penumbra are used at the same time, conflicts may occur.**

- For more information on `XIVLauncher`, please refer to this 🔗 [github page](https://goatcorp.github.io/faq/)

1. Refer to the github page to install XIVLauncher.\
🔗 https://github.com/goatcorp/FFXIVQuickLauncher/releases/latest

2. Run FF14 using XIVLauncher.

3. Please refer to the video below and install and apply the plugins.
```
https://raw.githubusercontent.com/xivdev/Penumbra/master/repo.json
https://raw.githubusercontent.com/Sevii77/ffxiv_materialui_accent/master/repo.json
```

4. Re-login or visit the Aesthetician and quit.

<details><summary>Click for video guide (Thanks to @Sevii and @Meconate)</summary>

https://user-images.githubusercontent.com/31692408/146950911-2d721e43-42a0-4466-b556-8796a61c4c93.mp4

</details>

## IN-GAME SETTINGS
If mods is not applied when you start the game, you have to change the in-game setting.
#### Set 4K UI resolution
1. Click `ESC key on keyboard` → `System Configuration` → `Graphic Settings` tab → `UI Resolution Settings`
2. Choose the option: `High (4k)`
    - This is an in-game setting that does NOT require a 4k monitor.
    - It should makes the UI assets render at a higher resolution if you do have a 4k monitor.
3. Reset the game.

<details><summary>Click for visual reference</summary>

![guide1](ModPacks/Resources/Preview/guide1.png)

</details>

#### Set color scheme
1. Click `ESC key on keyboard` → `System Configuration` → `Theme Settings`
2. Choose the option: `Dark`
3. Reset the game.

<details>
<summary>Click for visual reference</summary>

![guide2](ModPacks/Resources/Preview/guide2.png)

</details>
