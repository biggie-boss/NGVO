# NGVO - A Visual Baseline Modlist

![banner image](https://staticdelivery.nexusmods.com/mods/1704/images/119972/119972-1724967916-1263394473.png)

Wabbajack Modlist Installer by biggie_boss.

<table stlyle="border: none;">
<tr>
<td><a href="https://www.nexusmods.com/skyrimspecialedition/mods/119972">Nexus Page</a></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><a href="https://loadorderlibrary.com/lists/next-generation-visual-overhaul-NGVO">Load Order Library</a></td>
<td><a href="https://discord.gg/Tb5ETzBYjd"><img alt="Discord" src="https://cdn.logojoy.com/wp-content/uploads/20210422095037/discord-mascot.png" width="64px" ></a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Preamble

**NGVO** NGVO (Next Generation Visual Overhaul) is a comprehensive visual baseline list designed around the philosophy as making it as moddable as possible while offering the absolute best visuals you can find. As such, the plugin count is under 300 with less than 40 ESP/ESM's, giving you over 210 ESP/ESM slots to work with.

## System Requirements

### Disclaimer

Owing to the need to clean master files and certain errors with Wabbajack, NGVO only supports **English Steam** versions of Skyrim Special Edition. **GOG and other Languages are not supported**.

:warning: :exclamation: **NGVO REQUIRES YOUR SKYRIM VERSION TO BE UPDATED TO 1.6.1170 AND THIS IS THE GAME VERSION THAT THE MODLIST RUNS ON** :exclamation: :warning:

***

Only, Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**. Your windows version **must be 21H2 or newer** to run both Wabbajack and NGVO.

Running the list from Hard Disk Drives or external drives is **STRONGLY ADVISED AGAINST**. A lot of content is swapped at game run time and, as a result, fast storage and RAM are needed.

### Recommended System Requirements

NGVO requires a mid-tier modern system to run to its fullest potential. The recommended specs given below are based on utilizing the ENB in the list. For community shaders, you can subtract a little bit from them. Users have reported being able to run on hardware slightly lower than this, however your mileage may vary.

| Component    | Recommended for 1080p | 
|:--------------:|:-------------:|
| CPU | 10th Generation i5 or better/equivalent
| Ram | 16GB DDR4 Ram  + 40GB Pagefile 
| Storage | SATA SSD or higher
| GPU | RTX 3060 or better/equivalent

| Component    | Recommended for 1440p | 
|:--------------:|:-------------:|
| CPU | 12th Generation i7 or better/equivalent
| Ram | 32GB DDR4 Ram  + 40GB Pagefile 
| Storage | M.2 SSD
| GPU | RTX 4070 or better/equivalent

Space required: ~150GB Download Size ~100GB install Size ~250GB Total

See how to setup a page file here: https://www.tomshardware.com/news/how-to-manage-virtual-memory-pagefile-windows-10,36929.html

:warning: **NOTE**: AMD RX 580 and older cards are **not supported**. :warning:

## Installation

Installing NGVO is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing NGVO, please complete the following steps.


1. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-8.0.5-windows-x64-installer)
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Make sure your Skyrim Steam installation is updated to the latest version (1.6.1170) and set to the English language. I HIGHLY recommend not installing Steam, Skyrim nor any modlist into yur Program Files. 
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Launch the game to the main menu and allow it to download the free creation club addon files. **DO NOT VERIFY YOUR GAME FILES, DO NOT ALT TAB** If you already verified, go to step 6. 
6. If you get a curios or other cc error, go into your Skyrim Steam installation "Data" folder and delete ALL files beginning with "cc". Then relaunch the game and re-download the 4 free creation club content. **DO NOT ALT TAB**
7. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, causes more problems than it solves.
8. **Install the Skyrim Special Edition: Creation Kit on Steam and run it at least once.** https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/

***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

:warning: **NOTE**: NGVO will **always** require the latest version of Wabbajack **UNLESS IT IS SPECIFICALLY STATED HERE**. :warning:

#### Downloading and Installing NGVO

Downloading and installing NGVO can take a while depending on your internet connection and computer. To install NGVO, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on NGVO and wait for it to download.
3. Set the installation folder to be somewhere like C:\NGVO. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

***

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run Wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
    - **Make sure you have downloaded all the FREE AE update content!**
	- Make sure you have the Creation Kit installed. Go back to [Pre-Installation](#pre-installation) and read it properly this time.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- You did not follow the steps in [Pre-Installation](#pre-installation). Go back and follow it.
	- If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in Windows Defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Stock Game & Root Builder

NGVO utilizes a Wabbajack technology called Stock Game. What this essentially does is create a copy of your Skyrim installation within the installation location of the list. This enables greater compatibility with other mod-lists.

NGVO also utilizes Root Builder alongside Stock Game to enable easier management of hooks such as ENB, Reshade and Engine Fixes. Please see our guide to [Root Builder](https://github.com/The-Animonculory/Modding-Resources/blob/main/Root%20Builder%20for%20Skyrim%20AE.md) for more details.
***

**NOTE**: Screenshots save to `Overwrite\Stock Game`.

### Starting up the list
Open the installation folder and double-click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `NGVO` and press the `Run` button.

### In-game MCM options

NGVO has no required MCM options to be selected; however, you can load the smoothcam preset if you wish to do so.

You are welcome to change any others to achieve your desired setup.
 
## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- Althro & Ylikollikas for answering all my questions.
- ShadowSorcery for creating NGVO's awesome logo.
- Halgari and everyone on the WJ Team - Wabbajack is awesome and so are you.
- All of the amazing mod authors whose work made this modlist possible.
