![logo](ModPacks/Resources/Preview/github_faq_logo.png)

## CONTENTS
1. [TEXTOOLS](#textools)
2. [PENUMBRA](#penumbra)
3. [IN-GAME SETTINGS](#in-game-settings)

## TEXTOOLS
### 🔖 Icons are missing or displaying incorrectly after patches
There are two main reasons, one being invisible due to newly added textures and the other being broken existing textures. In the first case, I have to do additional work to the new textures that are not yet visible. There is no choice but to wait until I finish my work.

If the existing texture is broken however, the index file is probably broken. This usually occurs after updating or re-installing FFXIV with mods enabled. In this case, you may need to restore the index via textools via `help` → `download index backups`. If this does not work, you can try to manually download them from the repo [here](Index_Backups) or in the worst case, reinstall the game. To prevent this, it is recommended that mods be disabled using the `help` → `start over` function in TexTools just before patching.

- Sample case
  - [Issues#237 Realm icon/package icon being weird](https://github.com/skotlex/ffxiv-material-ui/issues/237)
  - [Issues#213 Wrong/Missing Icons](https://github.com/skotlex/ffxiv-material-ui/issues/213)
  - [Issues#181 Broken Lakeland map](https://github.com/skotlex/ffxiv-material-ui/issues/181)

### 🔖 What should I do when a new patch comes out?
1. Make a backup of your current mods (Click `Mods` → `Create Modpack` → `Backup ModPack`)
    - In the Name text field give it a fitting name, for example 'Backup', and click `SELECT ALL` or you wants item
    - Finally click `CREATE MODPACK` in the bottom right to create your backup modpack.
2. Prior to patching your game perform a 'Start Over'. (Click `Help` → `Start Over`, then click Yes.)
3. Close TexTools and patch your game.
4. Relaunch TexTools.
5. Reinstall your backup modpack (Click `Mods` → `Import Modpack`)
    - Navigate to the modpack created during `Step 1` (documents/textools folder by default) and import your modpack.

### 🔖 How can I apply the option?
1. Apply `Material 4K-UI BLACK (version).ttmp2`
2. Download `OPTIONS.zip` and move to the wanted folder.
3. Apply ttmp2 in the folder.
#### Please refer to [INSTALL GUIDE](README.md/#install-guide) of [README.md](README.md) for how to use textools.

### 🔖 How do I use Simple job hud?
It is only possible in simple job hud. Please refer to the following site: [SQEX simple hud guide](https://na.finalfantasyxiv.com/blog/002175.html)

### 🔖 I Applied mods, but the in-game doesn't change.
Please refer [IN-GAME SETTINGS](#in-game-settings)

### 🔖 Can I change the color of the HP/MP/Gauge bars?
No. It's not that it is impossible, just not very intuitive. More than anything else, you can't get the color you want perfectly.\
Please refer to the following link to explain the principle of gauge bar color. [Issues#61 color cast bar](https://github.com/skotlex/ffxiv-material-ui/issues/61#issuecomment-524636275)

## PENUMBRA
### 🔖 Can I use user creation or custom mods in penumbra?
1. Input command /penumbra in chatlog
2. Move to 'Import Mods' tab
3. Click 'Import TexTools Modpacks' button
4. Select you want .ttmp2

### 🔖 An error appears that the folder does not have access or write rights.
When you specify a path in the Penumbra `settings` tab, not make the Penumbra `Root Folder` in the ffxiv game's folder, but instead somewhere close to a drive, like `C:\XIVMods`

### 🔖 I Applied mods, but the in-game doesn't change.
Please refer [IN-GAME SETTINGS](#in-game-settings)

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
