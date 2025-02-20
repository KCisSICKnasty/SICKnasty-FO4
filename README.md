# SICKnasty - FO4

__CURRENT VERSION: 2.5.0__

Fallout 4 is a very special game to me. It came out while I was in community college. At the time, I only had Xbox 360 which I used to play Fallout 3 and Fallout New Vegas. FO4 actually inspired me to build a PC. I even told the guy that helped me get parts, "This PC will be so I can play Fallout 4." I've put hundreds upon hundreds of hours into the vanilla game. When the show came out, it got me wanting to play again, but the next gen content was such a tease (I finished it all in less than a few hours). Then I remembered...I got a PC for a reason.

Many wild failures as I learned first hand how modding worked later, we've landed here. Welcome to the sickest and nastiest Fallout 4 experience you've ever seen.

__REQUIREMENTS:__

- Fallout 4 ver.1.10.984.0 (NG update)*
- Visual C++ 2015, 2017, 2019, 2022 Redistributable Package: https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist (Install both x86 and x64 (skip ARM64). It's already installed if it says "repair" or "uninstall". In this case you can skip this step.)
- Roughly 405 GB of space
- Patience**

*SICKNASTY - FO4 WILL ONLY WORK FOR STEAM INSTALLATIONS OF THE GAME!!! It requires the NextGen content, but then uses Simple Fallout 4 Downgrader to roll back the update and keep the content. GOG is not supported, sorry! :(

*You will need a fresh install of Fallout 4. For some reason after installation, despite having the correct version of Address Library, F4SE plugins will not work. I've reached out to WJ support on the issue, but to no avail.

**This mod list is VERY big. The BA2 limit was hit a long time ago & you'll probably be confused if you try to open it without reading this. Like, "Why didn't I wait forever for the menu to load? Why is the game not letting me start?" We sacrifice the infinite darkness of waiting for the game to start & show the Bethesda logo in exchange for what I'd like to call, "watching the Audio load". Once the main menu opens, and you can navigate to settings, do so and you'll notice that you can alter any of them except for "Audio", which has a loading wheel next to it. When that finishes, only then may you start. It is going to take a long time to load. It is a large list with many large mods in Loose Files format. The only downside to this is you gotta "watch the Audio load". But it's cool, right?

__Uninstalling/Reinstalling the Game: (copy & pasted from The Midnight Ride website)__

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

__Wabbajack installation: (copy & pasted from The Midnight Ride website)__

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

__Post Installation Steps:__

_Exclusions: (copy & pasted from The Midnight Ride website)_ *NOTE: This operation is required because Windows can block MO2 and mod files from loading due to how MO2's virtualized filesystem works.*

- Open Windows Security.
- Open Virus & threat protection.
- Click Manage settings under Virus & threat protection settings.
- Scroll down and click Add or remove exclusions under Exclusions.
- Add a Folder exclusion and point it to the Installation Location folder.

_Setting up MO2: (copy & pasted from The Midnight Ride website)_

- Launch ModOrganizer.exe from your Installation Location.
- If you see a pop-up called Register?, select Yes.

__DISABLE CHALLENGES (FNV) before launching the game! There is an incompatibility currently with MAIM 3 since the update. If you cripple a limb, you will trigger Tough Guy infinitely and shoot up a lot of levels before leaving Vault 111. bp42s said they will release a modified version, so when that comes out, simply update and reactivate the mod.__

_INI settings:_

*Fallout Launcher:*

- In MO2, click on the drop-down in the right pane next to the Run button.
- Select "Fallout Launcher" and click Run.
- Within the launcher, select Options and then the Ultra Preset option.
- Close the launcher. (Do not click start or you will have to repeat everything!)
	
*Bethini Pie:*

- In MO2, click on the drop-down in the right pane next to the Run button.
- Click <Edit...>, then click the + symbol in the top left and Add from file.
- In the resulting explorer window, navigate to the Bethini Pie folder in your install location.
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

*Fallout4Custom.ini:* (Recommended for Game Configuration Menu)

- Navigate to your Fallout 4 Folder at the following location "Documents\My Games\Fallout4"
- Open (or create, if missing) Fallout4Custom.ini
- Add the following lines under the [Archive] section of your Fallout4Custom.ini and Fallout4.ini
	[Archive]
	bInvalidateOlderFiles=1
	sResourceDataDirsFinal=
- Also, in the [Launcher] section of the Fallout4Prefs.ini file, add the following line:
	[Launcher]:
	bEnableFileSelection=1

*High FPS Physics Fix* __NOTE: FOLLOWING STEPS FOR NVIDIA USERS ONLY!! THE BASE SETTINGS NEEDED ARE ALREADY DONE FOR YOU!!! If you are not a Nvidia user, you will need to disable the Nvidia Reflex Support mod in the left side under "Utilities". You will also need to download the "(No Multithreading)" version of Interior NavCut Fix here: https://www.nexusmods.com/fallout4/mods/72904?tab=files&file_id=292234&nmm=1 (replace or remove the version included)__

- Double click "SICKnasty INI Config" under the "SICKnasty Resources" seperator.
- Navigate to the "INI" tab.
- Click on "F4SE\plugins\HighFPSPhysicsFix.ini".
- Make sure that G-Sync is set to Fullscreen and that Display Specific settings are enabled in the Control Panel, the Windowed option is problematic due to it being a hacky method. Both of the settings are wrongly named so they do not actually directly refer to the display method.
- If you use fixed refresh rate (meaning no VRR), set InGameFPS (line 59) to your refresh rate - 0.005 or fractions of your refresh rate. For example on 60hz you can lock to 59.995 or 30. Just like on VRR, choose whether to lock to a fraction or RR-0.005 based on which is closest to your lowest FPS.
- If you set InGameFPS to a value higher than 60, do the following as well:
- Set DynamicUpdateBudget to true (line 291).
- Set BudgetMaxFPS to the same value as InGameFPS (line 310).

*Custom Companion Names: (optional)*

- Set any NPCs names to whatever you'd like. Instructions are in the ini file itself.

__Discord Downloads:__ *(Discord requires an account in order to join servers. If you don't have a Discord, you should make one. Especially if you want support from me for this list. ;D)*

- Download M8r98a4f2's Complex Item Sorter version: 1.13 beta 2 from the Collective Modding Discord here: https://discord.gg/pF9U5FmD6w (file found in "complex-sorter-support" channel)
- Drag the zip file into MO2 under "HUD & Sorting" separator. Enable the mod.
- Download MAIM version: 3.02 from the MAIM Hub Discord here: https://discord.gg/uqZZpqT9Ze (link found in "official-releases" channel)
- Drag the zip file into MO2 under "HUD & Sorting" separator. Enable the mod & plugins.

**NOTE: I've had MAIM 3 added to the whitelist for Wabbajack to recognize it, but have received no support on why the meta file is not working properly, despite being correct. One day, someone will respond and at least one of these 2 downloads wont be required anymore.**

_Other Off-Site Downloads:_

- Download Combat Drones here: https://storage.icestormng-mods.de/s/EGmEbj6mZ2EK3tY?path=%2F1.1%2FRelease
- Drag the zip file into MO2 under "Factions" separator. Enable the mod & plugin.

__NOTE: For each off-site download, rename their files to include "[No Delete]" in front of their names. This will prevent Wabbajack from deleting them when you update the list. This applies to any mod you've added to the list as well.__

_LOD Output, Complex Sorter Hotfix, and Load Order:_

- Download all 3 of the Update files here (following the instructions in the desciptions): https://www.nexusmods.com/fallout4/mods/88357

__Tools:__

_Collective Modding Toolkit-_

Features: (copy & pasted from Collective Modding Toolkit's mod description)

- Downgrades and upgrades Fallout 4 and Creation kit between Old-Gen and Next-Gen with delta patches. (Requires F4SE﻿ 0.6.23, Address Library﻿ AIO/1.10.163, and BASS﻿)
- Provides counts of data files by type; plugins (Full/Light) and BA2 (General and Textures)
- Patches BA2 files to either v1 (OG) or v8 (NG)
- Scans F4SE DLLs for game version support
- Scans your mod setup for potential issues.
- Automatically update Complex Sorter INIs for the latest xEdit. (**NOTE!!! DO NOT USE THIS FEATURE CURRENTLY AS IT CAN BREAK YOUR ENTIRE INSTALL OF XEDIT!!!)

_STEAM - Boost Lite-_

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

_Unpackrr_

Feature: User friendly program that lets you unpack BA2 with a button press if you decide to make additions and hit your archive limit.

Instructions:

- In your installation folder, navigate to Tools > Unpackrr
- Run the .exe file.
- Click the folder icon to the right of the open text field. ("Fallout 4 mod folder")
- Choose the folder titled "Mods" in your installation folder.
- Set the Extraction size threshold to "<1", and unpack the smallest BA2.
- If still experiencing CTD, repeat and increase threshold to "<2", "<3", etc. until you stop CTD.

__Optional Mods:__

- Mutant Menagerie - Life Finds A Way - No Spider Patch (if you're arachnophobic): https://www.nexusmods.com/fallout4/mods/85873?tab=description
- PRIME Plus -Hydraulica- (optional 75% lower volume option if it's still too loud for your liking): https://www.nexusmods.com/fallout4/mods/52749
- Ultra Wide Interface (21x9) (for wide screen compatibility): https://www.nexusmods.com/fallout4/mods/65677
	In the FOMOD, select (in order):
	- Vanilla
	- Vanilla
	- LooksMenu
	- Vanilla
	- Another Mod
	- FallUI - Inventory
	- FallUI - Workbench
	- FallUI - Confirm Boxes
	- FallUI - Sleep and Wait Menu
	- Vanilla
	- Visible (Default)
	- FallUI - HUD
	- Another INI settings
	- MCM Booster
	- Visible (Default)
	- Black borders (Default)
	- Vanilla (Default)

__Launching Fallout 4:__

Make sure that the version of Fallout 4 MO2 is pointing to is the version in your installation location (a folder named "Stock Game"). You can check this in MO2 by clicking the gear icon > Settings > Paths.

- In MO2, you will see a dropdown menu on the right side, to the left of the "Run" button.
- F4SE should be an executable in this menu. Click it.
- Once selected, click "Run". This is how you should run the game each time. (Alternatively, you could make a F4SE shortcut so you don't have to open MO2 to launch the game)

_Note on PIP-Pad:_

- Installing before exiting vault 111 causes pipboy open lag. Fixed by open and closing pipboy when leaving vault 111.
- Using the flashlight before leaving vault 111 will break it. Fixed by open and closing pipboy when leaving vault 111.

In other words, don't try to open your pipboy before you leave Vault 111. (Not that you should anyway because you don't have one until you leave.)

__MCM:__

- Click on "MCM Settings Manager"
- Load the Preset "SICKnastyMCMsettings"
- From here, set any hotkeys you would like (i.e. VAFS, Gasmasks Hotkeys, Dynamic Hotkeys, etc.) and set up your HUD, but I'd advise against adjusting any settings outside from that unless you know what you're doing.

__THE DEEP DIVE:__

This list was made with survival mode in mind. It wont hit as hard on any other difficulty. It's okay though, because you can tweak survival mode however you want thanks to Unlimited Survival Mode - F4SE! So, don't be a scaredy cat! It's really difficult to try and explain what every single mod does, but I'll point out some of the meat and potatoes that make it special. The SICKnasty core, if you will.

**Utilities**

- X-Cell
- RobCo Patcher
- Baka Framework
- Mod Configuration Menu
- MCM Booster
- Settlement Menu Manager
- Perchik71 - In Game MOD Explorer (MCM)
- Game Configuration Menu
- Game Visuals Configuration Menu - GVCM
- PipboyTabs
- Workshop Framework
- HUDFramework
- Extended Dialogue Interface
- Random Encounter Framework
- Unlimited Survival Mode (F4SE)
- Vanilla Uniques Framework
- Burst-Fire Framework (BFF)
- Real Time Cover Penetration Framework
- Mag Poop - Visual Reload Framework

**Fixes**

- Buffout 4 NG with PDB support
- Unofficial Fallout 4 Patch - UFO4P
- Community Fixes Merged
- The Midnight Ride - Glitchfinder All-In-One
- Previsibines Repair Pack Stable Branch - PRP
- Leveled Item Fixes (LIF)

**Quests**

- The Tunnels - For Cave People and Molerats
- The Sewers
- Fourville
- Attack of the Lobotomites
- Caves Of The Commonwealth
- Subversion - The Institute-Railroad Alliance Alternate Ending
- Children of Ug-Qualtoth
- The Secret of Huntress Manor - A Far Harbor Story
- Atomic Radio and Tales from the Commonwealth
- The Wild Key Chase - Quest and Location mod
- Ashland Station - Quest-Dungeon-Settlement
- Nordic Europa Research Facility (Dungeon)
- Polaria Systems (Dungeon)
- In The Flesh - A Horror Quest Mod
- Mechanist Omega - An Antagonist Quest Mod
- 20 Leagues Under the Sea - Vault 120

**New Lands**

- America Rising 2 - Legacy of the Enclave
- Boon Island - Isles Of New England
- Fallout Vermont
- Fallout 4 Northern Springs DLC
- The Wilderness - Now with four anomalies and a map
- The Marshland DLC - For Swampmonsters and Toxic People
- Xander's Aid - DLC
- Hunter's Abyss
- Maxwell's World

**Gameplay**

- True Perks
- Loaded Out - An Encumbrance and Carry Weight Overhaul Mod
- Ultimate Hacking
- MUTATION
- SCOURGE
- Flyable Personal Vertibird
- Campsite - Simple Wasteland Camping (and HD Sleeping Bags)
- Better Companions - All In One
- Amazing FollowerTweaks Plus (AFT Plus)
- PIP-Pad
- Garmin Foretrex 901
- Looted World
- Classic Holstered Weapons System (CHW)
- Fallout 2287 - Gas Masks of the Wasteland
- Fallout 2287 - Nuclear Winter

**Combat**

- Tactical Reload
- Enhanced Movement
- Bullet Counted Reload System (BCR)
- Bullet in the Chamber - Expanded Weapon Mechanics
- Bullet Penetration and Ricochet (BPR)
- VAFS Redux - Bullet Time and Manual Critical
- TRUE DAMAGE - Weapon Damage Normalized By Ammo Caliber
- MAIM 3
- Combat AI Empowered
- Energy Weapons Fixed - Continuous Beams Burst Fire Tri-beam Lasers
- Weapons of Fate (Ballistics Overhaul)
- Munitions - Ammo Expansion Project
- Munitions - Additional Ammo
- Munitions - Advanced Calibers (MAC)
- CALIBER - COMPLEX
- The Attachment Pack- Grenade Retrieval System
- Bastion - A Power Armor Overhaul
- Power Armor Handling Improvements - Retain Armor Buffs
- Perennial Power Armor - Lightweight Power Armor Rebalance
- ITO institute Technology Overhaul Full - Version 2

**Weather & Ambience**

- True Storms - Wasteland Edition (Thunder-Rain-Weather Redone)
- Seasons Change - A Merry Modding Days Mod
- Icicles - A 2024 Merry Modding Days Mod
- Lightweight Lighting - Gloom Edition
- Reverb and Ambiance Overhaul
- LOST Audio Tweaks
- Fallout 4 Resound Project - Guns
- OLD WORLD RADIO - BOSTON

**Companions**

- Automatron Expanded Weapons System
- I'm Darlene
- Heather Casdin - A Unique Companion Experience by llamaRCA
- Father Companion - Alternate Ending Option for Fallout 4
- Capital Wasteland Dogmeat
- FALLOUT Brotherhood - A Storyteller Quest Mod
- Ellen - the cartographer
- The Machine And Her
- Old Time Religion
- ARMSTRONG AND DUKE
- David Hunter - A Brotherhood Story

**Faction Overhauls**

- We Are the Minutemen
- You and What Army 2
- Church of Atom Overhaul
- Radical
- 4estGimp - Super Mutant Redux-No AWKCR
- Forced Evolution - Super Mutant Addons
- 4estGimp - Raider Overhaul ONE
- Raider Gangs Extended
- Courser Crusher
- PROJECT JAVELIN - Courser Replacer
- More Feral Ghouls. A Zombie Mod
- FGEP - Feral Ghouls Expansion Pack - The Definitive Edition
- Plutonium Creatures
- Improved America Rising 2
- Improved Brotherhood of Steel
- Improved Guards
- Improved Hostile Factions
- Improved Institute
- Improved Minutemen
- Improved Nuka Raiders
- Improved Railroad

**New Factions**

- NPCs Travel
- Mutant Menagerie - Life Finds A Way
- Zetans - Alien invaders in the Commonwealth
- Dreadsharks Of The Commonwealth
- Nightstrikers
- Institute Centaurs
- Lamprey Floaters
- Defective Synths
- Combat Drones
- Techno Mutants
- Faction Reinforcements

**Settlements**

- Sim Settlements 2
- Settlement Menu Manager
- OCDecorator
- The Master Plan
- Vault-Tec Workshop Overhaul Redux
- RL_Recruit_Framework
- Better Settlers
- Recruitable Settlers

**Weapons**

- Weapon Overhaul Project (WOP) - Combined Arms - Service Rifle - M1 Garand - Wattz Laser - Point Lookout - 22LR Pistol
- The Widow Shotgun
- Remote Explosives - C4 with Detonators and More
- Unique Replacers Project - Vendor Legendary Weapons
- Unique Replacers Project - Unique Legendary Weapons
- Unique Replacers Project - Mod Added Legendaries

**Armor & Clothing**

- Backpacks of the Commonwealth
- Gunner Outfit Pack (STANDALONE)
- Synth Overhaul - C.A.S.T
- NanoSuit
- Jetpacks FAO v5 - Installer
- The Pip-Boy Glove
- West Tek Tactical Gloves
- K-9 Harness -- Tactical Body Armor and Backpack for Dogmeat
- Dogmeat's Backpack
- Black Widow Armor and Pipboy (Pip-boy)
- Unique Replacers Project - Legendary Unique Armor And Power Armor

**Power Armor**

- MidWest Power Armor Revolution
- Ultracite Power Armor
- Institute Power Armor Redux...Redux
- Submersible Power Armor Redux

**Player Homes**

- Airship - Player Home and Settlement
- Survivalist's Bus
- Sailboat Abode (A Fast Travel Ship)
- Basement Living - Bunker and Basement Player Homes (with standalone Workshops)

**Crafting**

- Standalone Workbenches
- Equipment and Crafting Overhaul (ECO) - Redux
- Legendary Effect Overhaul (LEO) - Crafting - Drops - Modifications - And More
- Legendary AutoBot (LAB) - Craftable legendary effects for Automatron robots

**Visuals**

- Far Object LOD Improvement Project
- Caliente's Beautiful Bodies Enhancer
- OCBP
- 3BBB Physics (CBBE - TWB)
- HiPoly Faces REDUX (Seamless Kit - CBBE - TWB - FG - AB)
- High Resolution Texture Pack 2K and 4K - Valius
- FlaconOil's Complete Retexture Project -in progress-
- Targeted Textures Extended
- FO4FI HD Project - Architecture
- Lucid's Texture Upgrades
- NMC's Texture Bundle
- The Natural Bundle - Assorted Textures (2K - 4K)
- Grime Ash Moss Enhanced (GAME)
- Rusty Subway Textures
- Holotape Visual Improvement
- SuperAlloys - Enhanced Power Armor Paints and 4k Textures
- Fallout 4 Particle Patch - No More Glowing Objects
- Ultimate Window Overhaul Redone

**Patch Repositories**

- 1st Person Power Armor Footsteps Fix
- Bullet Counted Reload - Patches
- Mag Defecate Patches
- Vish's Patch Hub (UFO4P)
- sattyre's Patches for various Mods
- Random Encounter Framework Patch Hub
- Patches for Lively's Keywords Resource and Whisper's Standalone Workbenches
- SCOURGE - Patch Repository
- Less Loot - Assorted Locations and Quest Mod Patches for Survival
- Better Notes - Patches - Quests
- Better Notes - Patches - Locations and New Lands
- CaptainLaserbeam's Assorted SS2 Patches - DLC Munitions RO SMR WI and more
- Settlement Menu Manager Patches (SMM)
- Various Clothes Patches for ECO and NEO
- 4estGimp - Minor Equipment and Crafting Overhaul Patches
- Unofficial NEO Patches
- Tactical Reload Patch Repository (DEPRECATED)
- Tactical Reload Repository - Diacute'd
- Fawkes' Tactical Reload Patches
- TRUE DAMAGE - Patch Repository
- Reaper's Munitions Patches
- Zodicab's Munitions and MAA Patches
- Brian's Munitions Patches
- Munitions - Ammo Conversions
- DegenerateDak ESLified Patch Hub
- Miscellanous Performance Optimization - PRP
- Emirals Previs Patches for PRP .74
- Camora's Branch 74 PRP Patch Hub

I'll continue updating this README as I get things in order, but this is the culmination of months spent in front of xEdit, Nexus, Discord, and MO2. If there's a bug, please let me know and I'll fix it in an update! In a way, you're helping me run this like a beta. I was nervous as all heck to upload this list, but I got the courage to finally do it! I'm a stay at home dad, so I've got nothing but time to answer questions and resolve issues! (:

**Tools used:**

- Creation Kit Platform Extended for Fallout 4: https://www.nexusmods.com/fallout4/mods/51165
- FO4Edit: https://www.nexusmods.com/fallout4/mods/2737
- Vault-Tec Enhanced FaceGen System - VEFS: https://www.nexusmods.com/fallout4/mods/86374
- DynDOLOD 3 Alpha: https://www.nexusmods.com/skyrimspecialedition/mods/DynDOLOD-3/68518
- PJM's Precombine - Previs Patching Scripts: https://www.nexusmods.com/fallout4/mods/69978
- Wrye Bash: https://www.nexusmods.com/site/mods/591
- Cathedral Assets Optimizer: https://www.nexusmods.com/skyrimspecialedition/mods/23316

__Need help?__

_SERVERisSICKnasty (support server): https://discord.gg/W9HRjDFVzX_

Start in the #sicknasty-fo4-support channel, and I'll get to you as soon as I can! Make sure to give me as many details as you can on the issue so I can pinpoint the cause!

If your issue involves CTD, that makes things even easier! You can just give me your CLASSIC fed crash log and I can tell you what it means!

- Download FO4 Crash Log Auto Scanner And Setup Integrity Checker (CLASSIC) here: https://www.nexusmods.com/fallout4/mods/56255
- Follow the instructions in the mod description.
- Post your most recent crash log AUTOSCAN in the #sicknasty-fo4-crashlogs channel.

_Note: CLASSIC is the only thing I'll disagree with The Midnight Ride on, as it is fully supported by The Collective Modding Discord. The only reason the modlist has ever CTD has been because of BA2 limit, which CLASSIC has correctly diagnosed everytime._

__Load Order Library: https://loadorderlibrary.com/lists/sicknasty-fo4__

__Ways you can make my day:__

- Patreon: https://www.patreon.com/kcissicknasty
- Buy-Me-a-Coffee: https://buymeacoffee.com/kcissicknasty
- My band, ADA: https://open.spotify.com/artist/7D5hStnbyJ8lcvg1Fgc4jR