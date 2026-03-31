# The SICKnasty Suite

**CURRENT VERSION: 1.2.2**

**Load Order Library: https://loadorderlibrary.com/lists/the-sicknasty-suite **


**PREAMBLE:**

Fallout 4 is a very special game to me. It came out while I was in community college. At the time, I only had Xbox 360 which I used to play Fallout 3 and Fallout New Vegas. FO4 actually inspired me to build a PC. I even told the guy that helped me get parts, "This PC will be so I can play Fallout 4." I've put hundreds upon hundreds of hours into the vanilla game. When the show came out, it got me wanting to play again, but the next gen content was such a tease (I finished it all in less than a few hours). Then I remembered...I got a PC for a reason. Many wild failures as I learned first hand how modding worked later, we've landed here. Welcome to the sickest and nastiest Fallout 4 experience you've ever seen.


**REQUIREMENTS:**

- **Freshly installed** Steam copy of Fallout 4 ver.1.11.191 (AE update)
- Visual C++ 2015, 2017, 2019, 2022 Redistributable Package: https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist (Install both x86 and x64 (skip ARM64). It's already installed if it says "repair" or "uninstall". In this case you can skip this step.)
- Windows 10 x64 or Windows 11: https://www.microsoft.com/en-us/software-download/windows11
- *Roughly* 485 GB of space
- SERVERisSICKnasty (support server): https://discord.gg/pca64xM2Cz
- **FREE** Bethesda.NET Creation Club Content: (use the links below to bookmark the mods, and then, from the Creations tab in the Main Menu, install each)
	- Brotherhood of Steel T60 Pistol (https://creations.bethesda.net/en/fallout4/details/dd740e06-f7e4-421e-b1b1-3d5f94c62f5e/Brotherhood_of_Steel_T60_Pistol)
	- Doom BFG (https://creations.bethesda.net/en/fallout4/details/ec0d66e6-13e1-4f04-acc7-00a13c204c77/Doom_BFG)
	- Doom Classic Marine Armor (https://creations.bethesda.net/en/fallout4/details/d5a106e2-28f2-4d38-bfb3-e057894fb51e/Doom_Classic_Marine_Armor)
	- Fantasy Hero Set (https://creations.bethesda.net/en/fallout4/details/2d677856-b3bd-435f-918f-19e2ea5f0a2d/Fantasy_Hero_Set)
	- Morgan's Space Suit (https://creations.bethesda.net/en/fallout4/details/2615a680-883c-4420-9a48-a2a0f455c993/Morgan_s_Space_Suit)
	- Quake Thunderbolt (https://creations.bethesda.net/en/fallout4/details/3c0aa0b2-81d3-4d55-b591-fe7905c9816e/Quake_Thunderbolt)
	- Revenge of the Van Graffs (https://creations.bethesda.net/en/fallout4/details/4be8d5f2-e153-407f-9a19-935c74f012d5/Revenge_of_the_Van_Graffs)
	- Tale of the Beast Hunter (https://creations.bethesda.net/en/fallout4/details/7fc565f2-eaf5-458b-9ec6-55490432970d/Tale_of_the_Beast_Hunter)
	- The Varmint Rifle (https://creations.bethesda.net/en/fallout4/details/59409bbe-2b5e-4191-817a-5bd4692ad21a/The_Varmint_Rifle)
- ***Patience***


**UNINSTALLING/REINSTALLING:**

- Open Steam and go to your Library
- Find Fallout 4 in the list
- Right-click on it and select Manage -> Uninstall
- Navigate to Steam\steamapps\common and, if present, delete the Fallout 4 folder
- Navigate to Documents\My Games\Fallout 4 and delete all INI files inside it
- Open Steam and go to your Library
- Find Fallout 4 in the list and select Install (Wherever you had it already is fine)
- Select Next then wait for the install to finish
- In your Steam Library, right-click on Fallout 4, and click on Properties in the resulting context menu
- In the resulting new window, click on the drop-down at the top of the right pane underneath Automatic Updates
- Set it to "Only update this game when I launch it"
- Run the game from Steam, or through Fallout4Launcher.exe in the game files if you are using an offline copy
- Click OK to both pop-ups that say Detecting Video Hardware
- If there aren't any pop-ups, navigate to Documents\My Games\Fallout 4 and delete all INI files, then retry
- Launch the game once through Steam, and navigate to the Creations tab in the Main Menu
- Locate the Creation Club mods listed in the requirements above (if you have them bookmarked, you will find them in your Bookmarks) and install them
- Leave the Creations menu, and press OK to the pop-up
- Exit the game


**WABBAJACK:**

- Download the latest **Wabbajack**: https://www.nexusmods.com/site/mods/403
- Create a new folder anywhere ***except*** default Windows folders or the game folder itself (Example: C:\Modding\Wabbajack)
- Place **Wabbajack.exe** in this folder, then run it
- Click **Browse Modlists**, then tick the **Show Unofficial Lists** box in the corner
- Locate **The SICKnasty Suite** in the gallery and click the download button in the corner
- In your **Installation Location** select a folder that's ***NOT*** the following: Steam folder, default Windows folder, game folder, folder you just put Wabbajack.exe (Example: C:\Modding\The SICKnasty Suite)
- Begin installing
- Accept the Nexus Mods API request (If you are not a Premium user you will need to manually click download for each mod)
- Once complete, the installation will show a green Installation Complete screen
- If you see a red Installation Failed screen, try to log-in again through the Wabbajack settings, then reinstall the list to the same folder


**EXCLUSIONS:**

*NOTE: This operation is required because Windows can block MO2 and mod files from loading due to how MO2's virtualized filesystem works.*

- Open **Windows Security**
- Open **Virus & threat protection**
- Click **Manage settings** under **Virus & threat protection settings**
- Scroll down and click **Add or remove exclusions** under **Exclusions**
- Add a **Folder** exclusion and point it to your **Installation Location** folder


**MOD ORGANIZER 2:**

- Launch **ModOrganizer.exe** from your **Installation Location**
- If you see a pop-up that asks **Register?**, select **Yes**


**HIGH DPI SCALING FIX:**

- Right-click on **Fallout4.exe** in the **Stock Game"** folder
- Open **Properties** and navigate to the **Compatibility** tab
- Click on **Change high DPI settings**
- Set **High DPI scaling override** to **Application**
	

**POST INSTALLATION:**
	
***NOTE: The method used for root files is called the "Stock Game" method. What this means is that a version of Fallout 4 is already included for you in a folder called "Stock Game" within your installation location. This method keeps your Steam installation untouched and uninstalling the list is as simple as deleting your install location. Just to be sure, check that MO2 didn't change the path.***

- In MO2, open **Settings**
- Navigate to the **Paths** tab
- Change the bottom path to **InstallLocation/Stock Game/Fallout4.exe** (unless it is already set correctly, in which case, proceed)


**FREE CC CONTENT:**

Wabbajack wont include these, so you'll have to manually add them.

- Open **Windows Explorer** to your **InstallLocation/Stock Game/data** folder
- Open a **2nd Windows Explorer** to your **SteamLibrary/steamapps/common/Fallout 4/Data** folder
- From the 2nd window, locate and highlight (CTRL+Right Click) the **plugin**, **Textures.ba2**, & **Main.ba2** for the following:
	- bgs_varmintrifle
	- ptrfo4001_t60pistol
	- ptrfo4002_vangraff
	- vchgs001fo4_ncrbeasthunter
- Click & drag (or copy/paste) all 12 files into your **InstallLocation/Stock Game/data** folder
- If MO2 is open, press F5


*High FPS Physics Fix*

***Bonus:*** The Midnight Ride has a calculator specifically for HFPSPF: https://themidnightride.moddinglinked.com/utilities.html (scroll down halfway)

**NOTE:** I provide a pre-configured version of HFPSPF's ini, though the InGameFPS is set for a Fixed Refresh rate of 60. If that setup doesn't fit yours, you'll have to follow the steps below to tailor it to your rig. Otherwise, you can skip this step.

Instructions:

- Double click "The SICKnasty Suite - A Wabbajack Experience - Config" in MO2 under the "Workfiles" separator
- Navigate to the "INI Files" tab
- Click on "F4SE\plugins\HighFPSPhysicsFix.ini"
- If you use VRR, set InGameFPS (line 59) to a number you can reach across the majority of the game[3], it has to be between 48[4] and refresh rate - (refresh rate x 6.8%)
- If you use fixed refresh rate (meaning no VRR), set InGameFPS (line 59) to your refresh rate - 0.005 or fractions of your refresh rate. For example on 60hz you can lock to 59.995 or 30. Just like on VRR, choose whether to lock to a fraction or RR-0.005 based on which is closest to your lowest FPS
- If you've set a value that's higher than 60, do the following as well:
	- Set DynamicUpdateBudget to true (line 291)
	- Set BudgetMaxFPS to the same value as InGameFPS (line 310)


*Place Everywhere*

Instructions:

- Double click "Place Everywhere - Place.ini - togglable" in MO2 under the "Utilities" seperator
- Set hotkeys to your liking (or don't if you choose not to use the mod)
- In game, press F8 to activate "place-everywhere" mode (off by default)


***NOTE: If using a controller, go in the addictol.toml and change "bInputSwitch=false", if not you will be switching to the mouse when in dialog and you will get some twitching and drift.***


**LAUNCHING THE GAME:**

- In MO2, you will see a dropdown menu on the right side, to the left of the "Run" button
- Select F4SE
- Click "Run" (this is how you should run the game each time)


**DISCLAIMER!!!**

*This mod list is ***VERY*** big. You'll probably be confused if you try to launch the game without reading this. Like, "Why didn't I wait forever for the menu to load? Why is the game not letting me start?" We sacrifice the infinite darkness of waiting for the game to start & show the Bethesda logo in exchange for what I'd like to call, "watching the Audio load". Once the main menu opens, and you can navigate to settings, do so and you'll notice that you can alter any of them except for "Audio", which has a loading wheel next to it. When that finishes, only then may you start. It is going to take a long time to load. It is a large list with many large mods in Loose Files format. The only downside to this is you gotta "watch the Audio load". But it's cool, right?*


*Mod Configuration Menu*

After leaving the vault, you'll want to actually open up MCM for the first time:

- In your pause menu, choose "MCM" (first time will load for a long time while it builds cache)
- Set VAFS hotkey (I recommend replacing the pipboy light key, since I've disabled its function)
- Set Configurable Hotkeys
- Turn True Storms on
- Turn Bullet Counted Reload on
- In Workshop Plus:
	- set "Fly in Workshop Mode" to "OFF" and set hotkeys (or remember to NEVER use a jetpack in Workshop Mode, *or else*)
- In Power Armor Handling Improvements - Retain Armor Buffs:
	- Set "Remove Armor on PA Entry but keep buffs" (or Auto if Survival) or Carryweight is doubled

**NOTE:** I am currently unable to create an MCM Preset, but if you are willing to share yours with me, I will ship it with the list! (:


**Plugins disabled FOR A REASON:**

Only enable the following utility plugins if you're prepared to use them (details on usage can be found on each mod's respective page):

- **Face Ripper Presets.esp:** https://www.nexusmods.com/fallout4/mods/3878
- **AutoCellDisplay.esp:** https://www.nexusmods.com/fallout4/mods/69978


**A note on lore:**

The SICKnasty Suite is a **LORE-FRIENDLY** modlist...depending on your definition. I personally do not find assets used in other games to be breaking the lore, IF implemented in a lore-friendly way. I also tolerate a small amount of Wild Wasteland-esque 4th wall breaking. *That being said, however.* There are exactly 2 mods in the list that have non-lore friendly content that I excuse as Wild Wasteland encounters:

- **Submersible Power Armor Redux - BioShock Inspired -** *The mod Vanillified - Submersible Power Armor Redux removes everything except for the power armor which is distributed through Improved Hostile Factions & Power Armor to the People.*
- **Faction Reinforcements -** *Introduces a companion called Mechachu, a robotic Pikachu. Just don't use him if he's that bothersome.*


**OPTIONAL:**

I ship the list with the tools and guides that I used to curate the list (and some that I plan to use). You'll find them in the "Modding Tools" folder. Since they're completely optional, it's up to you to explore their use (or you can just ping me in my Discord! I love to help! :D).


*Optional mods*

- **Personal Radio (ESL version with randomizer)** *(if you want to add your own music to the game)*: https://www.nexusmods.com/fallout4/mods/89156
- **flipped condition boy** *(if you move your HUD around)*: https://www.nexusmods.com/fallout4/mods/74464
- **Equalizer PA - Next Gen - Old Gen - Version** *(if you don't like the Maryland flag retexture and want to change it)*: https://www.nexusmods.com/fallout4/mods/90881
- **Mutant Menagerie - Life Finds A Way - No Spider Patch** *(if you're arachnophobic)*: https://www.nexusmods.com/fallout4/mods/85873?tab=description
- **Gamepad - Input** *(better controller support)*: https://www.nexusmods.com/fallout4/mods/76116
- **Ultra Wide Interface (21x9)** *(wide screen compatibility)*: https://www.nexusmods.com/fallout4/mods/65677
- **CROSS_Chosen_Of_Atom Enhanced Textures** *(Niero's public Patreon post)*: https://www.patreon.com/posts/cross-chosen-of-25213700
- **FCOM 3.0 Custom Faction Template** *(make your own FCOM crew)*: https://www.nexusmods.com/fallout4/mods/42402
- **M8r98a4f2's Complex Sorter 1.13-beta2** *(file pinned in "complex-sorter-support" channel of the Collective Modding Discord)*: https://discord.gg/pF9U5FmD6w
- **MCM Settings Manager - v1.3-beta2** *(file pinned in "m8r-development" channel under "MCM Settings Manager")*
- **MCM_Booster_v1.1-beta2** *(file pinned in "m8r-docs-downloads" channel under "Downloads")* 

**NOTE: If you download the Gumroad CROSS textures, you'll have to install them as a mod in MO2 and unpack any of them that are in BA2. I include Unpackrr and Cathedral Assets Optimizer. Unpackrr has a mod page on Nexus with instructions.**
**NOTE: If you change the Maryland flag texture on the Equalizer PA, I will cry.**


**MAKING SUGGESTIONS:**

*Always* welcome if their through the ***correct channel*** in my Discord server.

**However, there are exceptions:**

- Anything by QRSR
- Anything by Ketaroz
- Anything by Thuggysmurf
- Anything by MunkySpunk
- Anything by Halffaces
- Anything by Oppressor08


**DEVIATION:**

If you choose to add or remove anything from the list, this is all possible with the tools I provide.
***However...***
It goes without saying that support from me will be sparse.
For instance, a common question is, "Can I use ENB?" In short, yes. You can. I've never touched ENB before in my life though, so it's on you to explore that option and maintain it with each update.
This goes with removals as well. If it breaks an output, the burden of recreating and maintaining that output will rest on your shoulders.


**OUTRO:**

This mod list was made by **me and only me**. That's not by choice, it's just how it's been. That's also not me saying to go easy on me. I can take it. I continue to learn new things and implement them in updates. Not just the products, but the tools. I wanted my suite to be one that you could pick apart and tweak to your liking. That said, by all means, feel free to upload patches for my list! As long as your patch falls within the permissions from the mod author of whatever mod(s) you're patching!


**Ways you can make my day:**

- **Patreon:** https://www.patreon.com/kcissicknasty
- **Buy-Me-a-Coffee:** https://buymeacoffee.com/kcissicknasty