<hr>

:warning: **The maintenance and support of this project has been moved to a [new repository](https://github.com/Spellhold-Studios/Red-Dragon-Summoning-Spell).**

<hr><br>

![Latest Release](https://img.shields.io/github/v/release/SpellholdStudios/Red_Dragon_Summoning_Spell?include_prereleases&color=darkred)<a name="top" id="top"> </a>
![Platform](https://img.shields.io/static/v1?label=platform&message=windows%20%7C%20macos%20%7C%20linux&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French%20%7C%20Italian%20%7C%20Russian%20%7C%20Spanish&color=limegreen)

<div align="center"><h1></a>Red Dragon Summoning Spell</h1>

<h3>A mod hosted by Spellhold Studios for Baldur's Gate II: Throne of Bhaal (classical and EE games),
Baldur's Gate Trilogy and EET<h3>

</div><br />


**Original Author:** Coco_Pliz  
**Mod Website:** <a href="http://www.shsforums.net/forum/127-mod-resurrections/">Spellhold Studios</a>  
**Mod Forum:** <a href="http://www.shsforums.net/topic/40883-red-dragon-summoning-spell-weidu-version/">Red Dragon Summoning Spell</a>  

## 

[Read the mod's readme](https://spellholdstudios.github.io/readmes/dragonsummon-readme-english.txt)

[Download the mod at Spellhold Studios](http://www.shsforums.net/files/file/799-dragon-summon-weidu/)<br>

## 

<div align="center">
<a href="#intro">Overview</a> &#x2B25; <a href="#compat">Compatibility</a> &#x2B25; <a href="#installation">Installation</a> &#x2B25; <a href="#components">Components</a> &#x2B25; <a href="#credits">Credits</a> &#x2B25; <a href="#versions">Versions History</a></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Overview

This mod adds a new 9th level spell scroll in Ribald's secret stock of items.

:warning: You must not use it everywhere because Red Dragon is a very big monster and can block your characters.

!!! And don't forget that using it too much will remove pleasure of the game !!!


<hr>


## <a name="compat" id="compat"></a>Compatibility

This mod is designed to work on the following Infinity Engine games: the original Baldur's Gate II (BG2 or just SoA) with the Throne of Bhaal (ToB) expansion, Baldur's Gate II: Enhanced Edition (BG2:EE), the conversion projects <a href="http://www.shsforums.net/forum/261-bgt-weidu/">Baldur's Gate Trilogy (BGT)</a> and <a href="https://github.com/K4thos/EET/releases">Enhanced Edition Trilogy (EET)</a>.

This is a WeiDU mod, and therefore should be compatible with all WeiDU mods. If you encounter any bugs, please <a href="http://www.shsforums.net/topic/40883-red-dragon-summoning-spell-weidu-version/">report them on the forum!</a><br>

>Although it is not required for the Red Dragon Summoning Spell mod to function properly, classical game players are strongly recommended to download and install the latest version of the <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a> before proceeding with the installation of this mod.<br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

*If you've previously installed the mod, remove it before extracting the new version. To do this, run **`setup-dragonsummon.exe`**, un-install all previously installed main component and delete the :file_folder: **dragonsummon** folder.*

*When installing or un-installing, **do not close the DOS window** by clicking on the **X** button! Instead, press the **Enter** key whenever instructed to do so.*

*__Disable any antivirus__ or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.*

## 

#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.

## 

#### Windows

The Red Dragon Summoning Spell mod for Windows is distributed as an extractable compressed archive and includes a WeiDU installer.

Extract the contents of the mod archive into the folder of the game you wish to modify (*the folder which contains the "CHITIN.KEY" file*), using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. On successful extraction, there should be a :file_folder: dragonsummon folder and a setup-dragonsummon.exe file in your game folder. To install, simply double-click **`setup-dragonsummon.exe`** and follow the instructions on screen.

Run **`setup-dragonsummon.exe`** in your game folder to reinstall, un-install or otherwise change the components settings.

## 

#### Mac OS X

The Red Dragon Summoning Spell mod for Mac OS X is distributed is distributed in the same compressed archive and includes a WeiDU installer.

First, extract the files from the archive into your game directory. On successful extraction, there should be a :file_folder: dragonsummon folder, setup-dragonsummon and setup-dragonsummon.command files in your game folder. To install, simply double-click **`setup-dragonsummon.command`** and follow the instructions on screen.

Run **`setup-dragonsummon.command`** in your game folder to reinstall, un-install or otherwise change the components settings.

## 

#### Linux

The Red Dragon Summoning Spell mod for Linux is distributed in the same compressed archive and does not include a WeiDU installer.

Extract the contents of the mod to the folder of the game you wish to modify.

Download the latest version of WeiDU for Linux from <a href="https://github.com/WeiDUorg/weidu/releases">WeiDU.org</a> and copy weidu and weinstall to /usr/bin. Following that, open a terminal, **`cd`** to your game installation directory, run tolower and answer 'Y' to both queries. You can avoid running the second option (linux.ini) if you've already ran it once in the same directory. To save time, the archive is already tolowered, so there's no need to run the first option (lowercasing file names) either if you've extracted only this mod since the last time you lowercased file names. If you're unsure, running tolower and choosing both options is the safe bet.

To install, run **`weinstall setup-dragonsummon`** in your game folder. Then run **`wine BGMain.exe`** (or **`wine baldur.exe`** for EE games) and start playing.

## 

#### Note for Complete Un-installation

In addition to the methods above for removing individual components, you can completely un-install the mod using **`setup-dragonsummon --uninstall`** at the command line to remove all components without wading through prompts.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

#### Author: Coco_Pliz

## 

#### Special Acknowledgements to:

- Extremist: Proofread the original mod.
- kevmus: First WeiDU conversion.
- ilot: Italian translation.
- Gwendolyne: French translation.
- Lisandro: Spanish translation.
- Fess, Austin and aerie.ru team: Russian translation.
- AL|EN: Wrote <a href="https://forums.beamdog.com/discussion/78364/infinity-auto-packager-automatically-generate-and-adds-mod-packages-to-release-when-you-publish-it">Infinity Auto Packager</a> tool which automatically provides Windows, Linux and Mac versions in the same archive file.

&#9755; If you wish to translate the mod, have a suggestion, or should encounter any bugs, please report them to the maintainers at the <a href="http://www.shsforums.net/topic/40883-red-dragon-summoning-spell-weidu-version/">mod forum</a>.</br>

## 

#### Copyrights Information

###### The Red Dragon Summoning Spell is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by Coco_Pliz, based on material from the game Baldur's Gate II and its expansion.
###### All mod content is &copy;Coco_Pliz.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.

###### This mod was created to be freely enjoyed by all Baldur's Gate II players, and its content is free of rights. However, it should not be sold, published, compiled or redistributed in any form without the consent of the author.

###### The modding community for the Infinity Engine has been going strong for more than 10 years now, and is the culmination of thousands of unpaid modding hours by fellow fans of the game. Modders produce their best work and players get the best, well-supported mods when we all work together.
###### There are two big ways to upset this harmony. One is to claim someone else's work as your own. The second is to host and redistribute a mod without permission from the author(s).
###### Be kind to your fellow players and modders. Don't do either.</br></br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Versions History

##### Version 2.1.0 (August 30, 2020)

- Added Italian translation (by ilot).

## 

##### Version 2.0.0 (June 12, 2020)

- Added *dragonsummon.ini* metadata file to support AL|EN's "Project Infinity".
- Renamed *Setup-DragonSummon.tp2* -> *dragonsummon.tp2* to support AL|EN's "Project Infinity".
- Replaced `AUTHOR` keyword with `SUPPORT`.
- Added missing `HANDLE_CHARSETS` function to convert string entries for EE games.
- Added `REQUIRE_PREDICATE` conditions to avoid installing the mod in inaccurate games.
- Added component `DESIGNATED` number and "*red_dragon_summoning_spell*" `LABEL`.
- Removed `READLN` action and included into main component the option adding the scroll in Ribald's secret stock of items, to support AL|EN's "Project Infinity".
- Added native BG2:EE and EET compatibility.
- Added new spell and scroll icon.
- Fixed wrong spell level (9 - was 7).
- Wrote an accurate spell description.
- Added French translation (thanks Gwendolyne).
- Added Russian translation (thanks Fess and Austin).
- Added Spanish translation (thanks Lisandro).
- Updated translations (Gwendolyne and Austin).
- Updated and renamed readme file to *dragonsummon-readme-english.txt*, then moved it into new "*readme*" folder.
- Removed useless "*backup*" folder.
- Reorganized mod architecture tree: created or renamed folders to sort files according to their types.
- Lower cased files.
- Included Linux and Mac Os X versions in the same package (thanks AL|EN's Infinity Auto Packager tool!).
- Added archive libiconv-1.9.2-1-src.7z with iconv licence info.
- Updated WeiDU installer to v246.
- Uploaded mod to official Spellhold Studios GitHub mirror account.

## 

##### Version 1 (May 25, 2009)

- Added an option that places the spell scroll in Ribald's store.
- WeiDU conversion by kevmus.

## 

##### Original Version

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>
