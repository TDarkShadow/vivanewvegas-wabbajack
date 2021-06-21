# Viva New Vegas - Wabbajack port <!-- omit in toc -->

## MODLIST SUMMARY <!-- omit in toc -->



 Viva New Vegas is a comprehensive modding guide for Fallout New Vegas that will carefully walk you through how to install all the mods you will need for a perfectly stable, smooth, and most importantly, enjoyable experience. The guide is highly accessible for everyone, no matter your modding experience. You can find the (manual) guide at <https://vivanewvegas.github.io>. This modlist functions as a one-click install to have the guide installed and improves Fallout New Vegas with increased performance, many bugfixes, some gameplay improvements, and quality of life extras.

## TABLE OF CONTENTS <!-- omit in toc -->
- [REQUIREMENTS](#requirements)
- [PREPARATION](#preparation)
  - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
  - [Uninstalling the game](#uninstalling-the-game)
    - [Steam](#steam)
    - [GOG](#gog)
  - [Making a new Steam Library](#making-a-new-steam-library)
  - [Set the Game language to English](#set-the-game-language-to-english)
    - [Steam](#steam-1)
    - [GOG](#gog-1)
  - [Pre Modlist Installation Instructions](#pre-modlist-installation-instructions)
- [MODLIST INSTALLATION](#modlist-installation)
  - [Modlist Installation Instructions](#modlist-installation-instructions)
  - [Post Installation Instructions](#post-installation-instructions)
- [UPDATING](#updating)
- [BEFORE YOU BEGIN PLAYING](#before-you-begin-playing)
- [KNOWN ISSUES](#known-issues)
- [FREQUENTLY ASKED QUESTIONS](#frequently-asked-questions)
  - [The list is down / in maintenance!](#the-list-is-down--in-maintenance)
  - [Why do I get a `Application Load Error 5:0000065434` error message when I try to launch the game?](#why-do-i-get-a-application-load-error-50000065434-error-message-when-i-try-to-launch-the-game)
  - [How do I fix NPCs "bouncing" when playing above 60 FPS?](#how-do-i-fix-npcs-bouncing-when-playing-above-60-fps)
  - [What steps do I have to take to run the game in an ultrawide resolution?](#what-steps-do-i-have-to-take-to-run-the-game-in-an-ultrawide-resolution)
  - [Why didn't I get any DLC pop-ups / items after starting a new game?](#why-didnt-i-get-any-dlc-pop-ups--items-after-starting-a-new-game)
  - [I can't find any Gun Runners Arsenal uniques at vendors?](#i-cant-find-any-gun-runners-arsenal-uniques-at-vendors)
  - [Why isn't XYZ mod in the list?](#why-isnt-xyz-mod-in-the-list)
  - [I have a bug / question!](#i-have-a-bug--question)
  - [I want to support your work!](#i-want-to-support-your-work)
- [CREDITS AND THANKS](#credits-and-thanks)

## REQUIREMENTS

* Latest version of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest).
* A clean **English** installation of Fallout New Vegas, and all DLCs.
  * Also known as Fallout: New Vegas Ultimate Edition.
  * **Acquired through either [GOG](https://www.gog.com/game/fallout_new_vegas_ultimate_edition/) or [Steam](https://store.steampowered.com/sub/13435/).**
* Around 12 GB of free space.
  * 9,5 GB for Fallout New vegas itself.
  * 500 MB for the mod downloads.
  * 1,5 GB for the modlist installation.
* A [Nexusmods](https://www.nexusmods.com/) account.
  * Nexus Premium is not necessary, but will help to download the modlist faster.

## PREPARATION

These steps are only needed if you install this Modlist for the first time. If you are updating the Modlist, jump straight to [UPDATING](#updating).

### Installing Microsoft Visual C++ Redistributable Package

You likely already have this installed, but in case you haven't. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### Uninstalling the game

If you have the game installed under `C:\Program Files\`, `C:\Program Files (x86)\`, your Desktop, or your Documents folders, follow these steps to remove it.

#### Steam

1. Open **Steam** and go to your **Library**.
2. Find **Fallout: New Vegas** in the list.
3. Right-click on it and select **Manage** -> **Uninstall**.
4. Navigate to `Steam\steamapps\common\` and, if present, delete the **Fallout New Vegas** folder.

#### GOG

1. Open **GOG** and go to your **Library**.
2. Find **Fallout: New Vegas** in the list.
3. Right-click on it and select **Manage Installation** -> **Uninstall**.
4. Navigate to where the game was installed (`GOG Galaxy\Games` by default) and, if present, delete the **Fallout New Vegas** folder.

### Making a new Steam Library

If you already have a Steam library set up outside of any default Windows folder, or you have the game on GOG, skip this step.

A new Steam library needs to be set up to install the game on, as the default library is in a default Windows UAC-protected folder (`C:\Program Files (x86)\Steam`).

1. Open **Steam** and select **Steam** -> **Settings** in the top left.
2. In the **Downloads** tab, select **Steam Library Folders**.
3. Select **Add Library Folder** and select a location outside of any default Windows folders.
   * For example, `C:\Games\Steam`.
4. Exit out of the settings when you are finished.

By default, Steam only allows one library per drive, but there is a workaround. If for example you already have the default Steam library at `C:\Program Files (x86)\Steam`, but still want your game on your `C:\` drive, you will need to follow [these instructions](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to do so.

### Set the Game language to English

This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and support will not be given to people with a non-English game.

#### Steam

1. Open **GOG** and go to your **Library**.
2. Find **Fallout: New Vegas** in the list.
3. Right-click on it and select **Properties...**.
4. Click on the **Language** tab and select **English** from the dropdown menu.

#### GOG

1. Open **Steam** and go to your **Library**.
2. Find **Fallout: New Vegas** in the list.
3. Right-click on it and select **Manage Installation** -> **Configure...**.
4. Next to **Language**, select **English** from the dropdown menu.

### Pre Modlist Installation Instructions

1. Navigate to **Documents\My Games\\** and if present, delete the **FalloutNV** folder.
   * This will delete all saves you have, but the modlist requires you to start a new game anyway.
2. Navigate to your Fallout New Vegas installation folder.
3. Run **FalloutNVLauncher.exe**.
4. Click OK to both pop-ups that say **Detecting Video Hardware**.
5. Select **Options** then select the **Ultra** (or **High**, for better performance) preset option.
6. Set the **Resolution** option to your preference.
7. Click **OK** then **Exit**.
8. Go to the **Data** folder and if present, delete **FalloutNV_lang.esp**.

## MODLIST INSTALLATION

### Modlist Installation Instructions

1. Download the latest version of Wabbajack.
2. Create a new folder anywhere that is **NOT** under C:\Program Files, C:\Users or C:\Windows.
3. Place the downloaded Wabbajack.exe into this folder.
4. Run Wabbajack.exe.
5. Locate **Viva New Vegas** on the gallery and click the down arrow to download the modlist file.
6. In **Installation Location** select an empty folder that is **NOT** under C:\Program Files, C:\Users or C:\Windows.
   * **DO NOT INSTALL THIS LIST INTO YOUR STEAM GAME PATH OR THE FOLDER WITH THE WABBAJACK EXE.**
7. The downloads location will auto-populate. This can be changed if preferred.
8. Click the button with the Play Arrow to begin the process.
9. Accept the Nexusmods API request if asked.
10. When Wabbajack completes you will see either a green **Installation Complete** screen or a red **Installation Failed** screen. If successful, proceed.

### Post Installation Instructions

1. Navigate to the Viva New Vegas installation folder.
2. Open the folder named **Game Folder Files**.
3. Copy all files in this folder and paste it into your Fallout New Vegas installation folder.
   * **COPY _ONLY_ THE FILES IN THE "GAME FOLDER FILES" FOLDER.**
4. Right-click on **FalloutNVpatch.exe** and run as admin. Press Enter when finished.
5. Open the folder **NVHR**.
6. Start **cpu_info.exe**.
7. Open the folder that **cpu_info.exe** tells you.
8. Copy **d3dx9_38.dll** to your Fallout New Vegas folder.
9. Delete the folder **NVHR**.

## UPDATING

When this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves. Start a new game after updating, if noted in the Changelog.

**Wabbajack will delete all files that are not part of the Modlist when updating!** This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

You can circumvent this behavior by renaming the mod with the prefix **[NoDelete]**. For example, you've added a mod named **[SAMURAI Floating Damage](https://www.nexusmods.com/newvegas/mods/71618)**. In MO2, renamed the mod name to **[NoDelete] SAMURAI Floating Damage** so Wabbajack doesn't remove the mod when updating / reinstalling the modlist.

Updating is the same as installing. You only have to make sure that you select the same path and tick the **Overwrite Existing Modlist** checkbox in Wabbajack.

## BEFORE YOU BEGIN PLAYING

* This modlist comes with 3 profiles you can choose to play with.
  * **Viva New Vegas** which is the default profile and made for first time playing.
  * **Viva Wasted Vegas** for people who want a grittier apocalypse experience.
  * **Viva Basic Vegas** for who wants to use VNV as a modding or mod creation base.
    * It's recommended to download the [4GB patched GECK](https://www.nexusmods.com/newvegas/mods/64888?tab=files) but it gets marked as an false positive by Windows Defender.
* Once you have selected the profile you want to use, open the **INI Editor** ![INI Editor](mo2ini.png), go to tab **falloutcustom.ini** and change **iNumHWThreads=2** from **2** to the amount of your system logical processors.
  * If you do not know how many logical processors your CPU has, use [your Task Manager](https://support.microsoft.com/en-us/windows/find-out-how-many-cores-your-processor-has-3126ef99-0247-33b3-81fc-065e9fb0c35b) to find out.
* Launch the game using the **New Vegas** option in MO2.
* On the left panel is a mod entitled **lStewieAI's Tweaks** - this is a file loaded with options that change how the game plays and crucial engine level fixes. If you are happy with how the game plays you won't need to touch anything in this mod. Otherwise, you can look through the ini in this mod and enable or disable tweaks and quality of life changes as you see fit.
  * Axonis, the author of Vanilla UI Plus, has their own [lStewieAI's Tweaks Preset ini](https://www.nexusmods.com/newvegas/mods/67185).
  * If you create one yourself, make it an additional mod and prefix it with `[NoDelete]` so it doesn't get deleted with you update the modlist.

## KNOWN ISSUES

* Loot Menu doesn't work during the character generation quest while you're still in Doc Mitchell's house. This is intended.

## FREQUENTLY ASKED QUESTIONS

### The list is down / in maintenance!

Sorry, I'll get it back up asap. In the meantime, you can follow our manual guide at <https://vivanewvegas.github.io> which always get priority updates.

### Why do I get a `Application Load Error 5:0000065434` error message when I try to launch the game?

Run your game directly through Steam once. You may also need to restart Steam and/or your PC.

### How do I fix NPCs "bouncing" when playing above 60 FPS?

1. Click the ![INI Editor](mo2ini.png) button at the top of MO2 and select **INI Editor**.
2. Go to the tab **FalloutCustom.ini**.
   * Make sure you are in the FalloutCustom.ini tab and **NOT** the Custom.ini tab.
3. Paste in the following:
```ini
[FootIK]
fOnOffGain=0.01
bFootPlacementOn=0
fPelvisUpDownBias=0
fPelvisOffsetDamping=0
fOriginalGroundHeightMS=0
```
4. Save and exit

### What steps do I have to take to run the game in an ultrawide resolution?

1. Click the ![INI Editor](mo2ini.png) button at the top of MO2 and select **INI Editor**.
2. Go to the tab **FalloutCustom.ini**.
   * Make sure you are in the FalloutCustom.ini tab and **NOT** the Custom.ini tab.
3. Paste in the following:
```ini
[Display]
iSize W=3440
iSize H=1440
```
  * Change the values to whatever resolution you are going to play in.
4. Save and exit
5. Right-click on **lStewieAl's Tweaks - Custom INI** mod (from Bug Fixes/QOL) in the left pane of MO2 and select **Open in Explorer**.
6. Navigate to `nvse/plugins/` and open **nvse_stewie_tweaks.ini** in a text editor.
7. Set `bUltrawideSupport` to `1`.

### Why didn't I get any DLC pop-ups / items after starting a new game?

[Simple DLC Delay](https://www.nexusmods.com/newvegas/mods/62779) prevents the DLC pop-ups from showing until you reach a certain level or the starting location for the DLC.
<details>
  <summary>Dead Money</summary>

  Radio starts broadcasting at level 20, listen to start the quest.
  Or go to [Abandoned Brotherhood of Steel Bunker](https://fallout.fandom.com/wiki/Abandoned_Brotherhood_of_Steel_bunker).
</details>
<details>
  <summary>Honest Hearts</summary>

  Radio starts broadcasting at level 10, listen to start the quest.
  Or go to [Northern Passage](https://fallout.fandom.com/wiki/Northern_passage).
</details>
<details>
  <summary>Old World Blues</summary>

  Radio starts broadcasting at level 15, listen to start the quest.
  Or go to [Mojave Drive-in](https://fallout.fandom.com/wiki/Mojave_Drive-in).
</details>
<details>
  <summary>Lonesome Road</summary>

  Radio starts broadcasting at level 20, listen to start the quest.
  Or go to [Canyon Wreckage](https://fallout.fandom.com/wiki/Canyon_wreckage).
</details>

[JSawyer Ultimate Edition](https://www.nexusmods.com/newvegas/mods/61592) scatters the pre-order pack items (also known as Courier's Stash) to the following locations;
<details>
  <summary>Caravan Pack</summary>
  The items can be found inside [Hell's Motel](https://fallout.fandom.com/wiki/Hell's_Motel).
</details>
<details>
  <summary>Classic Pack</summary>
  The items can be found inside [Wrecked Highwayman](https://fallout.fandom.com/wiki/Wrecked_Highwayman).
</details>
<details>
  <summary> Mercenary Pack</summary>
  The items can be found inside [Bradley's shack](https://fallout.fandom.com/wiki/Bradley's_shack).
</details>
<details>
  <summary>Tribal Pack</summary>
  The items can be found in the house right next to [Lucky Jim Mine](https://fallout.fandom.com/wiki/Lucky_Jim_Mine).
</details>

### I can't find any Gun Runners Arsenal uniques at vendors?

[GRA Unique Weapons Relocated](https://www.nexusmods.com/newvegas/mods/68153) moves all unique weapons of Gun Runners' Arsenal to diverse locations throughout the game.

<details>
  <summary>Bozar</summary>

  Bozar is found on a dead Super Mutant Master surrounded by cazadores on the unmarked path between [Red Rock Canyon](https://fallout.fandom.com/wiki/Red_Rock_Canyon) and [Jacobstown](https://fallout.fandom.com/wiki/Jacobstown).
</details>
<details>
  <summary>Cleansing Flame</summary>

  Cleansing Flame is found in one of the storage rooms of the [Ultra-Luxe Kitchen](https://fallout.fandom.com/wiki/Ultra-Luxe#Kitchens).
</details>
<details>
  <summary>Embrace of the Mantis King</summary>

  Embrace of the Mantis King may be found any time before the conclusion of the story in Zion on a named White Legs enemy inside [Glass Chime cave](https://fallout.fandom.com/wiki/Glass_Chime_cave). **You need to find it before concluding the Honest Hearts story because the White Legs NPCs will disappear once you do.**
</details>
<details>
  <summary>Esther</summary>

  Esther can be found propped up in the corner inside the [Nellis Workshop](https://fallout.fandom.com/wiki/Nellis_workshop).
</details>
<details>
  <summary>Gehenna</summary>

  Gehenna is found on Jeremiah, a dead prospector at [Cottonwood Crater](https://fallout.fandom.com/wiki/Cottonwood_crater).
</details>
<details>
  <summary>Greased Lightning</summary>

  Greased Lightning is located inside the [Silver Peak Mine](https://fallout.fandom.com/wiki/Silver_Peak_Mine) next to a skeleton and the Enclave Remnants Power Helmet.
</details>
<details>
  <summary>Li'l Devil</summary>

  Li'l Devil is found inside a Hard locked briefcase in the [Lucky 38's Cocktail Lounge](https://fallout.fandom.com/wiki/Lucky_38_cocktail_lounge).
</details>
<details>
  <summary>Medicine Stick</summary>

  Medicine Stick is atop the fireplace inside the [Zion Ranger Station](https://fallout.fandom.com/wiki/Zion_Ranger_station).
</details>
<details>
  <summary>MF Hyperbreeder Alpha</summary>

  MF Hyperbreeder Alpha is found on [Test Subject 1](https://fallout.fandom.com/wiki/Test_Subject_1) in [The Cuckoo's Nest](https://fallout.fandom.com/wiki/The_Cuckoo's_Nest).
</details>
<details>
  <summary>Nuka-Breaker</summary>

  Nuka-Breaker can be found on [Duke](https://fallout.fandom.com/wiki/Duke_(Fallout:_New_Vegas)) at [Zapp's Neon Signs](https://fallout.fandom.com/wiki/Zapp's_Neon_Signs), a location within the Fiend ruins area directly around [Vault 3](https://fallout.fandom.com/wiki/Vault_3).
</details>
<details>
  <summary>Paciencia</summary>

  Paciencia is leaning against a tree near a skeleton at the [Vault 22 dwellers' guard camp](https://fallout.fandom.com/wiki/Vault_22_dwellers%27_guard_camp).
</details>
<details>
  <summary>Sleepytyme</summary>

  Sleepytyme is on [Big Sal's desk](https://fallout.fandom.com/wiki/Big_Sal's_office) inside [Gomorrah](https://fallout.fandom.com/wiki/Gomorrah).
</details>
<details>
  <summary>Sprtel-Wood 9700</summary>

  Sprtel-Wood 9700 may be found next to a dead Brotherhood Paladin at the crater near [Black Mountain](https://fallout.fandom.com/wiki/Black_Mountain).
</details>
<details>
  <summary>The Smitty Special</summary>

  The Smitty Special can be picked up from a table in the upstairs area of the [Silver Rush](https://fallout.fandom.com/wiki/Silver_Rush).
</details>
<details>
  <summary>Two-Step Goodbye</summary>

  Two-Step Goodbye is on a workbench inside the [Weather Monitoring Station](https://fallout.fandom.com/wiki/Weather_monitoring_station).
</details>

### Why isn't XYZ mod in the list?

This modlist tries to be as customizable as possible while also fixing as many bugs as possible. That being said, check [Mods to Avoid](https://vivanewvegas.github.io/avoid-mods.html) to find out what mods you should avoid and suggestions for potential replacements of same.

### I have a bug / question!

Ask it in the [Viva New Vegas Discord](https://discord.gg/DhX5S27). The support channel in the Wabbajack Discord is for installation questions, not support for in-game stuff, suggestions, or bug reports.

### I want to support your work!

I thank you for that thought but you should probably donate to Qolore first. You can find his Patreon [here](https://www.patreon.com/vivanewvegas) or his Paypal [here](https://www.patreon.com/vivanewvegas). If you want to support Wabbajack, go [here](https://www.patreon.com/user/overview?u=11907933).

## CREDITS AND THANKS

* _YOU_ for actually reading the readme!
* Qolore for creating such an amazing mod guide.
* ALL the mod authors that made the mods featured in this list.
* Halgari and everyone in the Wabbajack Team.
* Trawzified, Lively, and Kaethela for guiding me into this endavour.
* LadyZeefa for making the first steps to have Viva New Vegas available on Wabbajack.

##### This readme is based off of [Starstruck Courier's readme](https://github.com/Kaethela/Starstruck-Courier/blob/main/README.md) and [Qwest's readme](https://github.com/SovnSkyrim/QWEST/blob/main/README.md). <!-- omit in toc -->
