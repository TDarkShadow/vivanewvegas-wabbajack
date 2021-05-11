# Viva New Vegas - Wabbajack port

## MODLIST SUMMARY

 Viva New Vegas is originally a comprehensive modding guide for Fallout New Vegas that will carefully walk you through how to install all the mods you will need for a perfectly stable, smooth, and most importantly, enjoyable experience. The guide is highly accessible for everyone, no matter your modding experience. This modlist functions as a one-click install to have the guide installed and improves Fallout New Vegas with increased performance, many bugfixes, some gameplay improvements, and quality of life extras.

## REQUIREMENTS

* Latest version of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest).
* A clean **English** installation of Fallout New Vegas, and all DLCs.
  * Also known as Fallout: New Vegas Ultimate Edition.
  * **Acquired through either [GOG](https://www.gog.com/game/fallout_new_vegas_ultimate_edition/) or [Steam](https://store.steampowered.com/sub/13435/).**
* Around 12 GB of free space.
  * 9,5 GB for the game, and 2,5 GB for the modlist.
* A [Nexusmods](https://www.nexusmods.com/) account.

## PRE INSTALLATION INSTRUCTIONS

1. Navigate to **Documents\My Games\FalloutNV** and delete all the files ending in **.ini**.
2. Navigate to your Fallout New Vegas installation folder.
3. Run **FalloutNVLauncher.exe**.
4. Click OK to both pop-ups that say **Detecting Video Hardware**.
5. Select **Options** then select the **Ultra** (or **High**, for better performance) preset option.
6. Set the **Resolution** option to your preference.
7. Click **OK** then **Exit**.
8. If you have FNV from **GOG**, go to the **Data** folder and delete **FalloutNV_lang.esp**.

## MODLIST INSTALLATION INSTRUCTIONS

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

## POST INSTALLATION INSTRUCTIONS

1. Navigate to the Viva New Vegas installation folder.
2. Open the folder named **Game Folder Files**.
3. Copy all files in this folder and paste it into your Fallout New Vegas folder ("GOG/Games/Fallout New Vegas" or "steam/steamapps/common/Fallout New Vegas").
   * **COPY _ONLY_ THE FILES IN THE "GAME FOLDER FILES" FOLDER.**
4. Right-click on **FalloutNVpatch.exe** and run as admin. Press Enter when finished.
5. Open the folder **NVHR**.
6. Start **cpu_info.exe**.
7. Open the folder that **cpu_info.exe** tells you.
8. Copy **d3dx9_38.dll** to your Fallout New Vegas folder.
9. Delete the folder **NVHR**.

## BEFORE YOU BEGIN PLAYING

* This modlist comes with 3 profiles you can choose to play with.
  * **Viva New Vegas - Full** which is the default profile and made for first time playing.
  * **Viva New Vegas - Hardcore** for people who want the gritty apocalypse experience.
  * **Viva New Vegas - Base** for who wants to use VNV as a modding or mod creation base.
    * It's recommended to download the [4GB patched GECK](https://www.nexusmods.com/newvegas/mods/64888?tab=files) but it gets marked as an false positive by Windows Defender.
* Launch the game using the **New Vegas** option in MO2.
* On the left panel is a mod entitled **lStewieAI's Tweaks** - this is a file loaded with options that change how the game plays and crucial engine level fixes. If you are happy with how the game plays you won't need to touch anything in this mod. Otherwise, you can look through the ini in this mod and enable or disable tweaks and quality of life changes as you see fit.

## KNOWN ISSUES

* Loot Menu doesn't work during the character generation quest while you're still in Doc Mitchell's house. This is intended.

## [FREQUENTLY ASKED QUESTIONS](https://vivanewvegas.github.io/faq.html)

**Why isn't (insert any mod here) in the list?**

This modlist tries to be as customizable as possible, while fixing as many bugs as possible. Check [Mods to Avoid](https://vivanewvegas.github.io/avoid-mods.html).

##### This readme is based off of [Starstruck Courier's readme](https://github.com/Kaethela/Starstruck-Courier/blob/main/README.md).