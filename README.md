# SICKnasty - FO4

	**CURRENT VERSION: 3.0.0**

Fallout 4 is a very special game to me. It came out while I was in community college. At the time, I only had Xbox 360 which I used to play Fallout 3 and Fallout New Vegas. FO4 actually inspired me to build a PC. I even told the guy that helped me get parts, "This PC will be so I can play Fallout 4." I've put hundreds upon hundreds of hours into the vanilla game. When the show came out, it got me wanting to play again, but the next gen content was such a tease (I finished it all in less than a few hours). Then I remembered...I got a PC for a reason. Many wild failures as I learned first hand how modding worked later, we've landed here. Welcome to the sickest and nastiest Fallout 4 experience you've ever seen.


**Load Order Library: https://loadorderlibrary.com/lists/sicknasty-fo4**

*For sanity's sake, I'm not doing a "deep dive" on the contents of the list. There are too many mods and trying to explain them all in depth is far too exhausting for both me to maintain and you to read. If you want to know what's in the list, click the above link and have a look at what's under the hood.*


	**REQUIREMENTS:**

- Freshly installed Steam copy of Fallout 4 ver.1.10.984.0 (NG update)*
- Steam copy of Creation Kit
- Visual C++ 2015, 2017, 2019, 2022 Redistributable Package: https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist (Install both x86 and x64 (skip ARM64). It's already installed if it says "repair" or "uninstall". In this case you can skip this step.)
- Roughly 405 GB of space
- SERVERisSICKnasty (support server): https://discord.gg/W9HRjDFVzX
- Patience


	**Exclusions:** *(copy & pasted from The Midnight Ride website) NOTE: This operation is required because Windows can block MO2 and mod files from loading due to how MO2's virtualized filesystem works.*

- Open Windows Security.
- Open Virus & threat protection.
- Click Manage settings under Virus & threat protection settings.
- Scroll down and click Add or remove exclusions under Exclusions.
- Add a Folder exclusion and point it to the Installation Location folder.


	**Uninstalling/Reinstalling the Game:** *(copy & pasted from The Midnight Ride website)*

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
- Run the game from Steam, or through Fallout 4Launcher.exe in the game files if you are using an offline copy.
- Click OK to both pop-ups that say Detecting Video Hardware.
- If there aren't any pop-ups, navigate to Documents\My Games\Fallout 4 and delete all INI files, then retry.
- Click OK then Exit.


	**Wabbajack installation:** *(copy & pasted from The Midnight Ride website)*

- Download the latest Wabbajack: https://www.nexusmods.com/site/mods/403
- Create a new folder anywhere outside of any default Windows folders, and the game folder itself. (Example: C:\Modding\Wabbajack)
- Place the downloaded Wabbajack.exe in this folder, then run it.
- Click Browse Modlists, then tick the Show Unofficial Lists box in the corner.
- Locate "SICKnasty - FO4" in the gallery and click the download button in the corner.
- In Installation Location select an empty folder that is NOT the following: the Steam folder, any default Windows folders, the game folder, the folder where you put Wabbajack.exe. (Example: C:\Modding\SICKnasty - FO4)
- Begin the installation.
- Accept the Nexus Mods API request. (If you are not a Premium user you will need to manually click download for each mod.)
- Once complete, the installation will show a green Installation Complete screen.
- If you see a red Installation Failed screen, try log-in again through the Wabbajack settings, then reinstall the list to the same folder.
	
	
	**"EMPTY ME INTO STOCK GAME":**
	
- Navigate to your install location for the list.
- Right click the folder titled **"EMPTY ME INTO STOCK GAME"** and in the drop down menu, click **"Open in new window"**.
- In the new window, highlight all of the folder's contents *(CTRL+A)*.
- Right click one of the highlighted files and in the drop down menu, click **"Cut"**.
- Go back to the original window with your install location and open the folder titled **"Stock Game"**.
- Right click anywhere in the window *(without highlighting a file)* and in the drop down menu, click **"Paste"**.

*This is to hopefully mitigate the "dreaded error" as we've come to call it in Discord. Sometimes, after installing, users have reported an error where upon trying to launch the game through MO2, it will say F4SE is not present. I'm hoping that by manually placing F4SE & Co. into "Stock Game", it will trick MO2 into realizing it is, in fact, present. If you want to see my struggles with Wabbajack support trying to pinpoint this error, I have the screenshots pinned in my Discord along with a fix for this issue. I apologize in advance if this happens to you, because the fix is a doozy. (A full reinstall, essentially...)*


	**Setting up Mod Organizer 2:** *(copy & pasted from The Midnight Ride website)*

- Launch ModOrganizer.exe from your Installation Location.
- If you see a pop-up called "Register?", select Yes.


	**Setting up xEdit:**
	
*Note: I've included xEdit in case you decide to make your own patches for the list to upload to Nexus. There are plenty of great xEdit tutorials, such as on The Midnight Ride's website, so I wont go through the basics, but feel free to reach out to me in Discord if you have questions about making patches.*

- Navigate to your installation folder.
- Drag the folder titled "FO4Edit 4.1.5f" from your installation folder into the root of whatever drive you installed the list to. (For example: *C:\SICKnasty - FO4\FO4Edit 4.1.5f* ---> **C:\FO4Edit 4.1.5f**)
- In MO2, click on the drop-down in the right pane next to the Run button.
- Click <Edit...>, then click the + symbol in the top left and Add from file.
- In the resulting explorer window, navigate to the "FO4Edit 4.1.5f" folder.
- Open the "Optional" folder, highlight "FO4Edit64.exe", and then confirm.
- Press Apply in the lower right, then OK.


	**Setting up VEFS:** ***Optional***
	
- Navigate to your installation folder.
- Drag the folder titled "Vault-Tec Enhanced FaceGen System - VEFS" from your installation folder into the root of whatever drive you installed the list to. (For example: *C:\SICKnasty - FO4\Vault-Tec Enhanced FaceGen System - VEFS* ---> **C:\Vault-Tec Enhanced FaceGen System - VEFS**)
- In MO2, click on the drop-down in the right pane next to the Run button.
- Click <Edit...>, then click the + symbol in the top left and Add from file.
- In the resulting explorer window, navigate to the "Vault-Tec Enhanced FaceGen System - VEFS" folder.
- Highlight "FaceGen Generator.bat" and then confirm.
- Press Apply in the lower right, then OK.
	

	**Additional Downloads:** *(Discord requires an account in order to join servers. If you don't have a Discord, you should make one. Especially if you want support from me for this list. ;D)*

- Download M8r98a4f2's Complex Item Sorter version: 1.13 beta 2 from the Collective Modding Discord here: https://discord.gg/pF9U5FmD6w (file found in "complex-sorter-support" channel)
- Drag the zip file into MO2 under "HUD & Sorting" separator. Enable the mod.
- Download Combat Drones here: https://storage.icestormng-mods.de/s/EGmEbj6mZ2EK3tY?path=%2F1.1%2FRelease
- Drag the zip file into MO2 under "Factions" separator. Enable the mod & plugin.
- Download all 3 of the Update files here (following the instructions in each file desciption): https://www.nexusmods.com/fallout4/mods/88357

**NOTE: If Discord is not allowing you to access this file for whatever reason, I'm told by users that the Nexus version works fine. I cannot verify this, however.**

**NOTE: Rename any additional download folder to include "[No Delete]" in front of their names. This will prevent Wabbajack from deleting them when you update the list. This applies to any mod you've added to the list as well.**


	**Optional Mods:**

Included under the "-Optional Mods-" seperator are 3 mods explained below with links that further explain them.

- Mutant Menagerie - Life Finds A Way - No Spider Patch *(if you're arachnophobic)*: https://www.nexusmods.com/fallout4/mods/85873?tab=description
- Gamepad - Input *(for better controller support)*: https://www.nexusmods.com/fallout4/mods/76116
- Ultra Wide Interface (21x9) *(for wide screen compatibility)*: https://www.nexusmods.com/fallout4/mods/65677

All you have to do is double click the mod in MO2, navigate to the "Filetree" tab, hold the control key down while clicking each file that's hidden, and then select "Unhide".


	**Post Installation Steps:**

*Bethini Pie*

***Feature:*** Optimal ini tweaks at the push of a button.

- In MO2, click on the drop-down in the right pane next to the Run button.
- Click <Edit...>, then click the + symbol in the top left and Add from file.
- In the resulting explorer window, navigate to the "Bethini Pie" folder in your install location.
- Highlight "Bethini.exe" and then confirm.
- Press Apply in the lower right, then OK.
- Select BethINI from the drop-down and run it.
- Click Fallout 4 then press Select Game.
- Choose a preset you prefer (I choose Ultra)
- Apply Recommended Tweaks.
- Set Display Mode to Borderless Windowed.
- Select the resolution you want to display the game in.
- Make sure Text Language is set to English both in BethINI Pie and on Steam (other languages are not supported by the guide).
- Edit the other settings to your liking.
- Click File then Save in the top left, then confirm the prompts and close BethINI.


*Auto Clean All Fallout 4 DLC and CC Next Gen Edition*

***Feature:*** Exactly what the name of the mod says, except you can add mods to the txt file it includes (which I have).

- In MO2, click on the drop-down in the right pane next to the Run button.
- Click <Edit...>, then click the + symbol in the top left and Add from file.
- In the resulting explorer window, navigate to your "FO4Edit 4.1.5f" folder.
- Highlight "batch_clean_plugins.bat" and then confirm.
- Press Apply in the lower right, then OK.
- Select "batch_clean_plugins.bat" from the drop-down and run it.
- Follow the prompts until all plugins have been cleaned.


*Fallout4Prefs.ini*

***"These are my recommended Fallout4Prefs.ini TerrainManager settings. This will increases performance, and eliminates other LOD issues."*** - **DoubleYou** *(Far Object LOD Improvement Project mod description)*

*TLDR:* I had to do this to generate LOD. DoubleYou is the almighty master of LOD. If they say to do something and it will increase performance, just ***do it!!!***

- In the top right corner of the left panel in MO2, click the folder icon.
- In the resulting drop down, click "Open MyGames Folder".
- Open the file called "Fallout4Prefs.ini".
- Under the section titled [TerrainManager], input these corresponding values:
	- fBlockMaximumDistance=262144
	- fBlockLevel2Distance=131072
	- fBlockLevel1Distance=65536
	- fBlockLevel0Distance=32768
	- fSplitDistanceMult=1.000
- File > Save > Close the window.


*High FPS Physics Fix*

***Feature:*** Anything FPS related to your game, configurable via ini.

- Double click "High FPS Physics Fix" in MO2 under the "-Bug Fixes-" separator.
- Navigate to the "INI Files" tab.
- Click on "F4SE\plugins\HighFPSPhysicsFix.ini".
- Change the following:
	- Set DisableBlackLoadingScreens to true (line 37).
	- Set PostloadingMenuSpeed to 3.0 (line 51).
	- Set OneThreadWhileLoading to false (line 84).
	- Set FixOCBPSpeed to false (line 221).
- If you use VRR, set InGameFPS (line 58) to a number you can reach across the majority of the game[3], it has to be between 48[4] and refresh rate - (refresh rate x 6.8%)
- If you use fixed refresh rate (meaning no VRR), set InGameFPS (line 59) to your refresh rate - 0.005 or fractions of your refresh rate. For example on 60hz you can lock to 59.995 or 30. Just like on VRR, choose whether to lock to a fraction or RR-0.005 based on which is closest to your lowest FPS.
- If you set InGameFPS to a value higher than 60, do the following as well:
	- Set DynamicUpdateBudget to true (line 291).
	- Set BudgetMaxFPS to the same value as InGameFPS (line 310).

	**The following has been copy/pasted from The Midnight Ride website, under the "High FPS Physics Fix" section: https://themidnightride.moddinglinked.com/utilities.html **

	1. Do not touch other settings unless you know what you are doing! For example you should know that:
		- AllowTearing needs to stay enabled, it's a requirement for VRR and won't lead to tearing during gameplay - the mod turns off V-Sync only during loading (making it faster).
		- Enabling DisableAnimationOnLoadingScreens will freeze loading screens and any overlay you use, this is intended and will speed up loading by about 40%. You can enable it if you don't mind frozen loading screens.

	2. You can check if you are using VRR by going to the Nvidia Control Panel if you're on Nvidia or Adrenalin's Display Settings if you're on AMD. If the G-Sync tab is missing from NVCP, your display doesn't support it or doesn't have the feature enabled in the OSD.

	3. Nvidia users need to make sure that G-Sync is set to Fullscreen and that Display Specific settings are enabled, the Windowed option is problematic due to it being a hacky method. Both of the settings are wrongly named so they do not actually directly refer to the display method.

	4. You always want your FPS capped by a limiter instead of being hardware bound, this will reduce lag and increase power efficiency. It is also less jarring for the player when visual smoothness is the same across all scenes.

	The VRR range on most monitors starts at 48, but it might also start at 30 or 1. You can check this on Nvidia's page or from your monitor's specifications.


*Buffout 4 NG with PDB support*

***Feature:*** It's Buffout...but for the engine. I really don't know what else to say.

- Double click "Buffout 4 NG with PDB support" in MO2 under the "-Bug Fixes-" seperator.
- Navigate to the "Text Files" tab.
- Change the following:
	- Set BSTextureStreamerLocalHeap to false (line 29).
	- Set HavokMemorySystem to false (line 30).
	- Set Input Switch to true (line 32). **Optional** *Only relevant if using a controller*
	- Set MemoryManager to false (line 34).
	- Set ScaleformAllocator to false (line 36)
	- Set SmallBlockAllocator to false (line 37).
	- Set F4EE to true (line 50).


*Assorted Modular Tweaks - ESPless* **Optional-ish**

***Feature:*** A bunch of QOL tweaks all handled via ini. Feel free to set these to your liking and ignore the steps below. The following are just my personal preferences.

- Double click "Assorted Modular Tweaks - ESPless - Config" in MO2 under the "-Tweaks-" seperator.
- Navigate to the "INI Files" tab.
- Change the following:
	- Set iRemoveIronSightsBlur to 1 (line 36).
	- Set iUncapPickPocketChance to 1 (line 40).
	- Set iLongerPowerLines to 1 (line 67).
	- Set iImprovedRagdolls to 1 (line 74).
	- Set iLessIntrusiveTutorial to 1 (line 86).
	- Set iBetterVertibirdMinigun to 1 (line 90).
	- Set iQuestItemsAreNotJunk to 1 (line 95).
	- Set iHighlightConsoleReference to 1 (line 99).
	- Set iClearConsoleOnLoad to 1 (line 115).


*Terminals Lock Up - ESPless* **Optional-ish**

***Feature:*** Exactly what the name of the mod says.

- Double click "Terminals Lock Up - ESPless" in MO2 under the "-Tweaks-" seperator.
- Navigate to the "INI Files" tab.
- Change the following:
	- Set iEnableMessages to 1 (line 8).


*Custom Companion Names* **Optional**

***Feature:*** Exactly what the name of the mod says.

- Double click "SICKnasty INI Config" in MO2 under the "-Companions-" seperator.
- Navigate to the "INI Files" tab.
- Set any NPCs names to whatever you'd like. Instructions are in the ini file itself.


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
	
This step is ***insanely*** optional, and being entirely honest, the performance gain you'll see is small. However, if you have a good bit of space on your hard drive to spare (and a hefty bit of time to spare), it's still honest performance.

The video tutorial in the mod description (https://www.nexusmods.com/fallout4/mods/80305) does a better job of explaining how to do it than I ever could, but I've also included the pdf guide in your "Tools > Guides" folder and the VRAMr location you'll want to point the executable to is under the "-Tools-" separator. If you're going to do this step, this is the time to do it.


	**Launching Fallout 4:**
	
Make sure that the version of Fallout 4 MO2 is pointing to is the version in your installation location (a folder named "Stock Game"). You can check this in MO2 by clicking the gear icon > Settings > Paths.

- In MO2, you will see a dropdown menu on the right side, to the left of the "Run" button.
- F4SE should be an executable in this menu. Click it.
- Once selected, click "Run". This is how you should run the game each time.
	
		**DISCLAIMER!!!**

*This mod list is ***VERY*** big. The BA2 limit was hit a ***long*** time ago & you'll probably be confused if you try to open it without reading this. Like, "Why didn't I wait forever for the menu to load? Why is the game not letting me start?" We sacrifice the infinite darkness of waiting for the game to start & show the Bethesda logo in exchange for what I'd like to call, "watching the Audio load". Once the main menu opens, and you can navigate to settings, do so and you'll notice that you can alter any of them except for "Audio", which has a loading wheel next to it. When that finishes, only then may you start. It is going to take a long time to load. It is a large list with many large mods in Loose Files format. The only downside to this is you gotta "watch the Audio load". But it's cool, right?*


	**MCM:**

Once you leave Vault 111, some options will flash on screen that you'll have to deal with. The main one you'll want to make sure you choose correctly is **Nuclear Winter**. When given the option, choose "Realism". Choosing the "Nuclear Winter" option will make only winter weathers happen, which will make your experience much more difficult and less interesting.

After making your choices, you'll want to actually open up MCM:

- In your start menu, choose "MCM". *Note: It will take a very, very long time to load. Even with MCM Booster. It will only be this long the first time you open it on a new save file as it builds the cache.*


*Note on PIP-Pad:*

- Installing before exiting vault 111 causes pipboy open lag. Fixed by open and closing pipboy when leaving vault 111.
- Using the flashlight before leaving vault 111 will break it. Fixed by open and closing pipboy when leaving vault 111.

In other words, **don't try to open your pipboy before you leave Vault 111**. I've disabled the pipboy light for this list, so you shouldn't have to worry about the first one. Should probably not try to, just to be safe.


	**FAQ:**

***Q:***

	*Why did I CTD immediately in the main menu?*

***A***

	**9/10 times, it is because you didn't do one of the most crucial steps: watching the audio load.

***Q:***

	*Why didn't my game save on exiting?*

***A***

	**Because I've disabled it. You can turn it back on by disabling the mod "Disable Exit Save" under the separator "-F4SE Plugins-". Though, you wouldn't be playing a true survival mode playthrough, in my opinion.**

***Q:***

	*Why are there so many mods that say they are empty or have their contents hidden in MO2?*
	
***A:***

	**Because the contents of the mod have been unpacked and/or repacked into BA2. This cuts down on the number of BA2 since a lot of mods will only have a few files whereas my repacks have a size limit of 20 GB. Packing loose files also cuts down on load times (less audio to watch load) and the less number of BA2 the game has to load will increase your performance! I leave the empty mods there so you can see what is repacked and in what order they've won/lost conflicts. DO NOT REINSTALL OR UNHIDE ANYTHING!!!**

***Q:***

	*"Why cant I use my pipboy light?"*

***A:***

	**Because I've disabled it. In my opinion, the pipboy light is immersion breaking and there's little reason to ever turn it off. The list has plenty of alternatives.**

***Q:***

	*"Why cant I VATS?"*

***A:***

	**You can** ***VAFS~*** **In short, VATS is OP and honestly makes combat boring in my opinion since most problems can be solved with a little Luck and VATS. VAFS makes VATS a bullet time mechanic based on Perception rather than a time stop mechanic based on Agility. This makes VATS during combat feel more like an actual combat mechanic rather than a pause button with optional 'press button to insta-kill' mechanic.**

***Q:***

	*"Why does it say I'm cold and what are these HUD elements about 'CBT' and such?"
	
***A:***

	**That would be Nuclear Winter. You'll have to start dressing accordingly when traversing the wasteland. Find spots of warmth and always wear fresh Hand Warmers (found as loot). You can adjust the HUD element and severity in MCM if you find the extra resource management to be a bit much.**

***Q:***

	*"I broke a limb and died. How?"*

***A:***

	**Welcome to the wonderful world of MAIM. Introducing new injury mechanics with deathly consequences. No more walking around on a broken leg like it's nothing. Stimpaks are no longer a fix-all for your limbs. You'll need to bandage those cuts and bullet wounds.**

***Q:***

	*"Why are enemies in power armor not taking damage?*

***A:***

	**For all the hardcore difficulty the list presents you with, you have 1 mod in your corner: Bastion. Those enemies wont hurt you either if you're wearing it. Bastion makes power armor an actual layer of armor, so only the pieces will take damage until they break. Then, you will only take damage in the area that is exposed. If things are getting tough, armor up wastelander!** ***(Just make sure you bring plenty of fusion cores with you!!!)***

***Q:***
	
	*"Can I add/remove 'insert mod'?"*

***A:***

	**(Mostly) everything I've used for the list is included in a folder called "Tools" within your installation location. Adding/removing something will likely require you to rebuild one of the outputs. If you're prepared to do a little learning of your own, then the answer is yes.**

***Q:***
	
	*"I've had a CTD!"* ***or*** *"I found a visual bug!"*  ***or*** *This weapon is doing no damage/will not reload! What do I do?!*

***A:***

	
	**Firstly, join the support Discord server so I can actually talk to you! Secondly, I've included CLASSIC in your "Tools" folder. The Midnight Ride has CLASSIC on the "Tools to Avoid" page, though the reasoning (in my opinion) is very weak. Essentially, it's advised against because you shouldn't rely on automated crash log scans. Which is true, but as someone who admittedly cannot read a crash log, CLASSIC has helped me pinpoint issues in the list without fail. The only CTD I've ever experienced while making the list was hitting the BA2 limit, which it correctly diagnosed everytime. If you don't want to use it, you can use the crash log section of the Collective Modding Discord as a "lite" version of CLASSIC. I have a section for crash logs in my Discord server. Additionally, if you find a visual error, a mod called Auto Cell Display allows you to craft a ring in the ECO Utility Workbench which, when worn, displays exact cell coordinates and other helpful information. If you want to really help me find your issue, screenshot the bug with this ring's information on screen! As for weapons, obviously, I'll need to know the weapon name that's bugged when you make your report.**

***Q:***

	*What is SICKnasty - FO4?*

***A***

	**In short, SICKnasty - FO4 is FO4.5. My modlist makes you ask yourself:** *"Am I dead yet?"* ***If*** the answer to that is **no**, then ***don't giveup!!!*** **The difficulty is meant to make you think outside of the box, taking into account what you need to bring with you for each trek you make to the next post. For all your contusions and broken limbs, you'll find real rewards and a character progression you can actually feel.**


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


**Ways you can make my day:**

- Patreon: https://www.patreon.com/kcissicknasty
- Buy-Me-a-Coffee: https://buymeacoffee.com/kcissicknasty
- **Check out my band, ADA:** https://open.spotify.com/artist/7D5hStnbyJ8lcvg1Fgc4jR