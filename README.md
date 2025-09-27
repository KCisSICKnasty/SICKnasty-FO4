# The SICKnasty Suite

**CURRENT VERSION: 1.1.0**

Fallout 4 is a very special game to me. It came out while I was in community college. At the time, I only had Xbox 360 which I used to play Fallout 3 and Fallout New Vegas. FO4 actually inspired me to build a PC. I even told the guy that helped me get parts, "This PC will be so I can play Fallout 4." I've put hundreds upon hundreds of hours into the vanilla game. When the show came out, it got me wanting to play again, but the next gen content was such a tease (I finished it all in less than a few hours). Then I remembered...I got a PC for a reason. Many wild failures as I learned first hand how modding worked later, we've landed here. Welcome to the sickest and nastiest Fallout 4 experience you've ever seen.


**Load Order Library: https://loadorderlibrary.com/lists/sicknasty-fo4**

*For sanity's sake, I'm not doing a "deep dive" on the contents of the list. There are too many mods and trying to explain them all in depth is far too exhausting for both me to maintain and you to read. If you want to know what's in the list, click the above link and have a look at what's under the hood.*


**REQUIREMENTS:**

- Freshly installed Steam copy of Fallout 4 ver.1.10.984.0 (NG update)*
- Visual C++ 2015, 2017, 2019, 2022 Redistributable Package: https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist (Install both x86 and x64 (skip ARM64). It's already installed if it says "repair" or "uninstall". In this case you can skip this step.)
- Windows 10 x64 or Windows 11: https://www.microsoft.com/en-us/software-download/windows11
- Roughly 460 GB of space
- SERVERisSICKnasty (support server): https://discord.gg/pca64xM2Cz
- Patience

***NOTE: The method SICKnasty - FO4 uses for root files is called the "Stock Game" method. What this means is that a version of Fallout 4 and Creation Kit are already included for you in a folder fittingly called "Stock Game" within your installation location. Doing things this way mean that your Steam installation is never touched and uninstalling the list is as simple as deleting your install location.***

**Exclusions:**

*NOTE: This operation is required because Windows can block MO2 and mod files from loading due to how MO2's virtualized filesystem works.*

- Open Windows Security.
- Open Virus & threat protection.
- Click Manage settings under Virus & threat protection settings.
- Scroll down and click Add or remove exclusions under Exclusions.
- Add a Folder exclusion and point it to the Installation Location folder.


**Uninstalling/Reinstalling the Game:**

- Open Steam and go to your Library.
- Find Fallout 4 in the list.
- Right-click on it and select Manage -> Uninstall.
- Navigate to Steam\steamapps\common and, if present, delete the Fallout 4 folder.
- Navigate to Documents\My Games\Fallout 4 and delete all INI files inside it.
- Open Steam and go to your Library.
- Find Fallout 4 in the list and select Install. (Wherever you had it already is fine.)
- Select Next then wait for the install to finish.
- In your Steam Library, right-click on Fallout 4, and click on Properties in the resulting context menu.
- In the resulting new window, click on the drop-down at the top of the right pane underneath Automatic Updates.
- Set it to "Only update this game when I launch it".
- Run the game from Steam, or through Fallout4Launcher.exe in the game files if you are using an offline copy.
- Click OK to both pop-ups that say Detecting Video Hardware.
- If there aren't any pop-ups, navigate to Documents\My Games\Fallout 4 and delete all INI files, then retry.
- Click OK then Exit.


**Wabbajack installation:**

- Download the latest Wabbajack: https://www.nexusmods.com/site/mods/403
- Create a new folder anywhere outside of any default Windows folders, and the game folder itself. (Example: C:\Modding\Wabbajack)
- Place the downloaded Wabbajack.exe in this folder, then run it.
- Click Browse Modlists, then tick the Show Unofficial Lists box in the corner.
- Locate "The SICKnasty Suite" in the gallery and click the download button in the corner.
- In Installation Location select an empty folder that is NOT the following: the Steam folder, any default Windows folders, the game folder, the folder where you put Wabbajack.exe. (Example: C:\Modding\The SICKnasty Suite)
- Begin the installation.
- Accept the Nexus Mods API request. (If you are not a Premium user you will need to manually click download for each mod.)
- Once complete, the installation will show a green Installation Complete screen.
- If you see a red Installation Failed screen, try log-in again through the Wabbajack settings, then reinstall the list to the same folder.
	

**Setting up Mod Organizer 2:**

- Launch ModOrganizer.exe from your Installation Location.
- If you see a pop-up called "Register?", select Yes.
	
	
**Additional Downloads:** *(Discord requires an account in order to join servers. If you don't have a Discord, you should make one. Especially if you want support from me for this list. ;D)*

- Download M8r98a4f2's Complex Item Sorter version: 1.13 beta 2 from the Collective Modding Discord here: https://discord.gg/pF9U5FmD6w (file pinned in "complex-sorter-support" channel)
- Drag the zip file into MO2 under "Interface" separator. Enable the mod.

**NOTE: If Discord is not allowing you to access this file for whatever reason, I'm told by users that the Nexus version works fine. I cannot verify this, however.**

**NOTE: Rename any additional download folder to include "[No Delete]" in front of their names. This will prevent Wabbajack from deleting them when you update the list. This applies to any mod you've added to the list as well.**


**Post Installation Steps:**
	
**First and foremost, make sure that the version of Fallout 4 MO2 is pathed to is the version I include for you in the "game" folder.**

- In MO2, open "Settings"
- Navigate to the "Paths" tab
- Change the bottom path to "(whatever you named your install location)/game/Fallout4.exe"

*Auto Clean All Fallout 4 DLC and CC Next Gen Edition*

***Feature:*** Semi-automated batch plugin cleaner for all base game, DLC, and CC plugins.

- In MO2, click on the drop-down in the right pane next to the Run button
- Click <Edit...>, then click the + symbol in the top left and Add from file
- In the resulting explorer window, navigate to the "FO4Edit 4.1.5f" folder in your install location
- Highlight "batch_clean_plugins.bat" and then confirm
- Press Apply in the lower right, then OK
- Select "BatchCleanPlugins" from the drop-down and run it
- When xEdit shows on screen, hit the "Enter" key
- When it finishes, close xEdit
- Repeat until all base game and CC content plugins have been cleaned

*Simple Fallout 4 Downgrader*

***Feature:*** One button press downgrader for your game.

The version of FO4 that I've included for you is already downgraded! Check to be sure, however. If it's not, follow the 2 steps below.

- Under executables, choose "Simple Fallout 4 Downgrader"
- Click "Run" and wait for it to finish, then close the window

*Bethini Pie*

***Feature:*** Optimal ini tweaks at the push of a button.

- In MO2, click on the drop-down in the right pane next to the Run button
- Click <Edit...>, then click the + symbol in the top left and Add from file
- In the resulting explorer window, navigate to the "Bethini Pie" folder in your install location
- Highlight "Bethini.exe" and then confirm
- Press Apply in the lower right, then OK
- Select BethINI from the drop-down and run it
- Click Fallout 4 then press Select Game.
- Choose a preset you prefer (I choose Ultra)
- Apply Recommended Tweaks
- Set Display Mode to Borderless Windowed
- Select the resolution you want to display the game in
- Make sure Text Language is set to English both in BethINI Pie and on Steam (other languages are not supported by the guide)
- Edit the other settings to your liking
- Click File then Save in the top left, then confirm the prompts and close BethINI


*Fallout4Prefs.ini*

***"These are my recommended Fallout4Prefs.ini TerrainManager settings. This will increases performance, and eliminates other LOD issues."*** - **DoubleYou** *(Far Object LOD Improvement Project mod description)*

*TLDR:* I had to do this to generate LOD. DoubleYou is the almighty master of LOD. If they say to do something and it will increase performance, just ***do it!!!***

- In the top right corner of the left panel in MO2, click the folder icon
- In the resulting drop down, click "Open MyGames Folder"
- Open the file called "Fallout4Prefs.ini"
- Under the section titled [TerrainManager], input these corresponding values:
	- fBlockMaximumDistance=262144
	- fBlockLevel2Distance=131072
	- fBlockLevel1Distance=65536
	- fBlockLevel0Distance=32768
	- fSplitDistanceMult=1.000
- File > Save > Close the window


*High FPS Physics Fix*

***Feature:*** Anything FPS related to your game, configurable via ini.

- Double click "High FPS Physics Fix" in MO2 under the "F4SE Plugins" separator
- Navigate to the "INI Files" tab
- Click on "F4SE\plugins\HighFPSPhysicsFix.ini"
- Change the following:
	- Set DisableBlackLoadingScreens to true (line 37)
	- Set PostloadingMenuSpeed to 3.0 (line 51)
	- Set OneThreadWhileLoading to false (line 84)
	- Set FixOCBPSpeed to false (line 221)
- If you use VRR, set InGameFPS (line 58) to a number you can reach across the majority of the game[3], it has to be between 48[4] and refresh rate - (refresh rate x 6.8%)
- If you use fixed refresh rate (meaning no VRR), set InGameFPS (line 59) to your refresh rate - 0.005 or fractions of your refresh rate. For example on 60hz you can lock to 59.995 or 30. Just like on VRR, choose whether to lock to a fraction or RR-0.005 based on which is closest to your lowest FPS
- If you set InGameFPS to a value higher than 60, do the following as well:
	- Set DynamicUpdateBudget to true (line 291)
	- Set BudgetMaxFPS to the same value as InGameFPS (line 310)

- Do not touch other settings unless you know what you are doing! For example you should know that:
	- AllowTearing needs to stay enabled, it's a requirement for VRR and won't lead to tearing during gameplay - the mod turns off V-Sync only during loading (making it faster)
	- Enabling DisableAnimationOnLoadingScreens will freeze loading screens and any overlay you use, this is intended and will speed up loading by about 40%. You can enable it if you don't mind frozen loading screens

NOTE: You can check if you are using VRR by going to the Nvidia Control Panel if you're on Nvidia or Adrenalin's Display Settings if you're on AMD. If the G-Sync tab is missing from NVCP, your display doesn't support it or doesn't have the feature enabled in the OSD.

NOTE: Nvidia users need to make sure that G-Sync is set to Fullscreen and that Display Specific settings are enabled, the Windowed option is problematic due to it being a hacky method. Both of the settings are wrongly named so they do not actually directly refer to the display method.

You always want your FPS capped by a limiter instead of being hardware bound, this will reduce lag and increase power efficiency. It is also less jarring for the player when visual smoothness is the same across all scenes.

The VRR range on most monitors starts at 48, but it might also start at 30 or 1. You can check this on Nvidia's page or from your monitor's specifications.


*Buffout 4 NG with PDB support*

***Feature:*** It's Buffout...but for the engine. I really don't know what else to say.

- Double click "Buffout 4 NG with PDB support" in MO2 under the "F4SE" seperator
- Navigate to the "Text Files" tab
- Change the following:
	- Set BSTextureStreamerLocalHeap to false (line 29)
	- Set HavokMemorySystem to false (line 30)
	- Set Input Switch to true (line 32) **Optional** *Only relevant if using a controller*
	- Set MemoryManager to false (line 34)
	- Set ScaleformAllocator to false (line 36)
	- Set SmallBlockAllocator to false (line 37)
	- Set F4EE to true (line 50)


*Assorted Modular Tweaks - ESPless* **Optional-ish**

***Feature:*** A bunch of QOL tweaks all handled via ini. Feel free to set these to your liking and ignore the steps below. The following are just my personal preferences.

- Double click "Assorted Modular Tweaks - ESPless - Config" in MO2 under the "Tweaks" seperator
- Navigate to the "INI Files" tab
- Click on the first option labeled "Config"
- Change the following:
	- Set bHighlightConsoleReference to 1 (line 26)
	- Set iImprovedRagdolls to 1 (line 33)
	- Set iLessIntrusiveTutorial to 1 (line 37)
	- Set iLongerPowerLines to 1 (line 45)
	- Set iRemoveIronSightsBlur to 1 (line 61)
	- Set iUncapPickPocketChance to 1 (line 84)


*Terminals Lock Up - ESPless* **Optional-ish**

***Feature:*** Exactly what the name of the mod says.

- Double click "Terminals Lock Up - ESPless" in MO2 under the "Tweaks" seperator
- Navigate to the "INI Files" tab
- Change the following:
	- Set iEnableMessages to 1 (line 8)


**Launching Fallout 4:**
	
Make sure that the version of Fallout 4 MO2 is pointing to is the version in your installation location (a folder named "game"). You can check this in MO2 by clicking the gear icon > Settings > Paths.

- In MO2, you will see a dropdown menu on the right side, to the left of the "Run" button
- Select F4SE
- Click "Run" (this is how you should run the game each time)


**DISCLAIMER!!!**

*This mod list is ***VERY*** big. The BA2 limit was hit a ***long*** time ago & you'll probably be confused if you try to open it without reading this. Like, "Why didn't I wait forever for the menu to load? Why is the game not letting me start?" We sacrifice the infinite darkness of waiting for the game to start & show the Bethesda logo in exchange for what I'd like to call, "watching the Audio load". Once the main menu opens, and you can navigate to settings, do so and you'll notice that you can alter any of them except for "Audio", which has a loading wheel next to it. When that finishes, only then may you start. It is going to take a long time to load. It is a large list with many large mods in Loose Files format. The only downside to this is you gotta "watch the Audio load". But it's cool, right?*


**MCM:**

After leaving the vault, you'll want to actually open up MCM for the first time:

- In your start menu, choose "MCM". *Note: It will take a very, very long time to load. Even with MCM Booster. It will only be this long the first time you open it on a new save file as it builds the cache.*
- Set VAFS hotkey.
- Set True Storms to on.

**Other:**

- Power Armor Handling Improvements - Retain Armor Buffs: Craft (at chem bench) & set holotape "Remove Armor on PA Entry: Always but keep buffs" (or Auto if Survival) or Carryweight is doubled.
- See Through Scopes -  Toggle Tactical Reload on.

**Optional Mods:**

- Mutant Menagerie - Life Finds A Way - No Spider Patch *(if you're arachnophobic)*: https://www.nexusmods.com/fallout4/mods/85873?tab=description
- Gamepad - Input *(for better controller support)*: https://www.nexusmods.com/fallout4/mods/76116
- Ultra Wide Interface (21x9) *(for wide screen compatibility)*: https://www.nexusmods.com/fallout4/mods/65677

*STEAM - Boost Lite-* **Optional**

Feature: Reduces the amount of GPU, CPU, & RAM usage from Steam so Fallout 4 can use it.

Instructions:

- In your Steam app, click on "Steam" in the top left corner.
- In the dropdown menu, click on "Settings".
- In the left menu, click on "Friends & Chat".
- Deactivate "Sign in to friends when Steam starts".
- In the left menu again, click on "Interface".
- Change "Start Up Location" to Library.
- Deactivate the following:
	- Run Steam when my computer starts
	- Ask which account to use each time Steam starts
	- Start Steam in Big Picture Mode.
	- Enable smooth scrolling in web views
	- Enable GPU accelerated rendering in web views
	- Enable hardware video decoding, if supported
- In MO2, right-click on "STEAM - Boost Lite" on the left side under the "Tools" seperator.
- Select "Open in Explorer".
- Rename the file extension from ".txt" to ".bat".
- Make a copy of your new .bat and place it in your Steam root folder.
- Make another copy and place it somewhere you can regularly access it.
- Start Steam from this .bat and enjoy!


**VRAMr:** *Optional*
	
Feature: Small performance boost.

This step is ***insanely*** optional, and being entirely honest, the performance gain you'll see is small. However, if you have a good bit of space on your hard drive to spare (and a hefty bit of time to spare), it's still honest performance.

The video tutorial in the mod description (https://www.nexusmods.com/fallout4/mods/80305) does a better job of explaining how to do it than I ever could, but I've also included the pdf guide in your "Tools > Guides" folder and the VRAMr location you'll want to point the executable to is under the "-Tools-" separator. If you're going to do this step, this is the time to do it.


**Personal Radio:** *Optional*

Feature: Add up to 200 music tracks to the game!

Instructions:

- Add "MultiXwm" as an executable in MO2 (found in your install location in its own dedicated fodler) and Run it.

- Drag your chosen tracks into the to resulting window.

- Convert all to XWM format (recommended to use the default program bitrate) and export it wherever. NOTE: You must keep the old file name like 1.xwm, so rename them before exporting!!!

- In MO2, navigate to Personal Radio (and/or Personal Radio 2) under "Audio" separator, right click the mod, and choose "open in explorer".

- Drag all the tracks from where you exported them into the folder "sound\fx\mus\radio\PersonalRadio", replacing the files with yours when asked.

- In game, tune into your MyRadio station, and enjoy!


**Plugins disabled FOR A REASON:**

- SKKScriptLatencyTest.esp: Only enable if you're having significant lag. When enabled, you will automatically have a ring equipped that will show you location information. For details, check the mod's description (https://www.nexusmods.com/fallout4/mods/35853).
- FCOM Custom Faction.esp: Only enable if you're prepared to use it. For details, check the mod's description (https://www.nexusmods.com/fallout4/mods/42402).
- Face Ripper Presets.esp: Only enable if you're prepared to use it. For details, check the mod's description (https://www.nexusmods.com/fallout4/mods/3878).


**Tools:**

- **Creation Kit**
- **Creation Kit Platform Extended for Fallout 4:** https://www.nexusmods.com/fallout4/mods/51165
- **FO4Edit:** https://www.nexusmods.com/fallout4/mods/2737
- **Vault-Tec Enhanced FaceGen System - VEFS:** https://www.nexusmods.com/fallout4/mods/86374
- **DynDOLOD 3 Alpha:** https://www.nexusmods.com/skyrimspecialedition/mods/DynDOLOD-3/68518
- **Wrye Flash:** https://www.nexusmods.com/site/mods/591
- **Cathedral Assets Optimizer:** https://www.nexusmods.com/skyrimspecialedition/mods/23316
- **Collective Modding Toolkit:** https://www.nexusmods.com/fallout4/mods/87907
- **Merge Plugins:** https://www.nexusmods.com/skyrim/mods/69905
- **Synthesis:** https://github.com/Mutagen-Modding/Synthesis/
- **M8r98a4f2's Complex Item Sorter:** https://www.nexusmods.com/fallout4/mods/48826
- **4estGimp - M8r98a4f2's Complex Item Sorter Enhancements:** https://www.nexusmods.com/fallout4/mods/51307
- **MultiXwm:** https://www.nexusmods.com/fallout4/mods/3663


**Scripts:**

- *PJM's Precombine - Previs Patching Scripts:* https://www.nexusmods.com/fallout4/mods/69978
- *Far Object LOD Improvement Project:* https://www.nexusmods.com/fallout4/mods/61884
- *Seasons Change - A Merry Modding Days Mod:* https://www.nexusmods.com/fallout4/mods/76710
- *Power Armor Repair Takes Skill (PARTS):* https://www.nexusmods.com/fallout4/mods/58409
- *Pra's Fo4Edit Scripts - Automatic Patch Generation:* https://www.nexusmods.com/fallout4/mods/28898
- *Fix Cubemaps:* https://www.nexusmods.com/fallout4/mods/95531
- *Power Armor Repair Takes Skill (PARTS):* https://www.nexusmods.com/fallout4/mods/58409


**Ways you can make my day:**

- Patreon: https://www.patreon.com/kcissicknasty
- Buy-Me-a-Coffee: https://buymeacoffee.com/kcissicknasty
- **Check out my band, ADA:** https://open.spotify.com/artist/7D5hStnbyJ8lcvg1Fgc4jR