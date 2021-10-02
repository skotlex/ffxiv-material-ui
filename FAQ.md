![logo](ModPacks/Resources/Preview/github_faq_logo.png)

## Icons are missing or displaying incorrectly after patches
There are two main reasons, one being invisible due to newly added textures and the other being broken existing textures. In the first case, I have to additional work to the new textures that are not visible. It has no choice but to wait until I finish my work. 

However, if the existing texture is broken, the index file may be corrupted with high probability. In this case, you may need to restore the index from the [link](https://github.com/skotlex/ffxiv-material-ui/tree/master/Index_Backups) and try again, or in the worst case, reinstall the game. To prevent this, it is recommended that mods be disabled using the `help` → `start over` function in TexTools just before patching.

## What should I do when a new patch comes out?
1. Make a backup of your current mods! (Click `Mods` → `Create Modpack` → `Basic ModPack`)
    - In the Name text field give it a fitting name, for example 'Backup', and click `SELECT ACTIVE`
    - Finally click `CREATE MODPACK` in the bottom right to create your backup modpack.
2. Prior to patching your game perform a 'Start Over'. (Click `Help` → `Start Over`, then click Yes.)
3. Close TexTools and patch your game.
4. Relaunch TexTools.
5. Reinstall your backup modpack! (Click `Mods` → `Import Modpack`)
    - Navigate to the modpack created during `Step 1` (documents/textools folder by default) and import your modpack.

## How can I apply the option?
1. Apply `Material 4K-UI BLACK (version).ttmp2`
2. Download `OPTIONS.zip` and move to the wanted folder.
3. Apply ttmp2 in the folder.
#### Please refer to [INSTALL GUIDE](README.md/#install-guide) of [README.md](README.md) for how to use textool.

## How do I use Simple job hud?
It is only possible in simple job hud. Please refer to the following site: [SQEX simple hud guide](https://na.finalfantasyxiv.com/blog/002175.html)

## I Applied mods, but the in-game doesn't change.
If mods is not applied when you start the game, you have to change the in-game setting.
#### Set 4K UI resolution
<details>
<summary>Click for visual reference</summary>

![guide1](ModPacks/Resources/Preview/guide1.png)

</details>

1. Click `ESC key on keyboard` → `System Configuration` → `Graphic Settings` tab → `UI Resolution Settings`
2. Choose the option: `High (4k)`
    - This is an in-game setting that does NOT require a 4k monitor.
    - It should makes the UI assets render at a higher resolution if you do have a 4k monitor.
3. Reset the game.
#### Set color scheme
<details>
<summary>Click for visual reference</summary>

![guide2](ModPacks/Resources/Preview/guide2.png)

</details>

1. Click `ESC key on keyboard` → `System Configuration` → `Theme Settings`
2. Choose the option: `Dark`
3. Reset the game.

## Can I change the color of the HP/MP/Gauge bars?
No. It's not that it is impossible, just not very intuitive. More than anything else, you can't get the color you want perfectly.\
Please refer to the following link to explain the principle of gauge bar color. [Issues#61 color cast bar](https://github.com/skotlex/ffxiv-material-ui/issues/61#issuecomment-524636275)
