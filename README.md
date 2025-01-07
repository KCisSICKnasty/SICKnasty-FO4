# SICKnasty - FO4

__CURRENT VERSION: 2.4.7__

__Some users are not receiving the correct version of Fallout4.exe in their Stock Game folder. If you get an error about F4SE not working or anything related to a F4SE error, just use Simple Fallout 4 Downgrader after you're done: https://www.nexusmods.com/fallout4/mods/81933__

__I don't know why it's happening again. Wabbajack Support Discord says it's a user problem, but the executable isn't correct on your end and it is on mine so somehow you changed the executable before even opening the list. I have no answers and I'm sorry. :(__

Fallout 4 is a very special game to me. It came out while I was in community college. At the time, I only had Xbox 360 which I used to play Fallout 3 and Fallout New Vegas. FO4 actually inspired me to build a PC. I even told the guy that helped me get parts, "This PC will be so I can play Fallout 4." I've put hundreds upon hundreds of hours into the vanilla game. When the show came out, it got me wanting to play again, but the next gen content was such a tease (I finished it all in less than a few hours). Then I remembered...I got a PC for a reason.

Many wild failures as I learned first hand how modding worked later, we've landed here. Welcome to the sickest and nastiest Fallout 4 experience you've ever seen.

__SERVERisSICKnasty (support server): https://discord.gg/W9HRjDFVzX__

__REQUIREMENTS:__

- Fallout 4 ver.1.10.984.0 (NG update)*
- Wabbajack
- Roughly 306 GB of space
- Patience**

*SICKNASTY - FO4 WILL ONLY WORK FOR STEAM INSTALLATIONS OF THE GAME!!! It requires the NextGen content, but then uses Simple Fallout 4 Downgrader to roll back the update and keep the content. GOG is not supported, sorry! :(

**This mod list is VERY big. The BA2 limit was hit a long time ago & you'll probably be confused if you try to open it without reading this. Like, "Why didn't I wait forever for the menu to load? Why is the game not letting me start?" We sacrifice the infinite darkness of waiting for the game to start & show the Bethesda logo in exchange for what I'd like to call, "watching the Audio load". Once the main menu opens, and you can navigate to settings, do so and you'll notice that you can alter any of them except for "Audio", which has a loading wheel next to it. When that finishes, only then may you start. It is going to take a long time to load. It is a large list with many large mods in Loose Files format. The only downside to this is you gotta "watch the Audio load". But it's cool, right?

__Wabbajack installation: (copy & pasted from The Midnight Ride website)__

- Download the latest Wabbajack.
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

_Exclusions: (copy & pasted from The Midnight Ride website)_

- Open Windows Security.
- Open Virus & threat protection.
- Click Manage settings under Virus & threat protection settings.
- Scroll down and click Add or remove exclusions under Exclusions.
- Add a Folder exclusion and point it to the Installation Location folder.

_Setting up MO2: (copy & pasted from The Midnight Ride website)_

- Launch ModOrganizer.exe from your Installation Location.
- If you see a pop-up called Register?, select Yes.

_INI settings:_

Bethini Pie: (copy & pasted from The Midnight Ride website)

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

High FPS Physics Fix: (copy & pasted from The Midnight Ride website)

- Locate High FPS Physics Fix in the Utilities separator, then double-click it.
- In the INI-Files tab, open F4SE/Plugins/HighFPSPhysicsFix.ini
- Set AllowTearing to true (line 26) (Enabling AllowTearing allows the mod to disable VSync during loading in order to make it faster, since the game loading time is largely limited by current framerate (up to a certain point). Enabling it will NOT lead to any tearing during gameplay. This setting is also a requirement for VRR.)
- Set DisableBlackLoadingScreens to true (line 37).
- Set DisableAnimationOnLoadingScreens to true (line 44). (Enabling DisableAnimationOnLoadingScreens will freeze loading screens and any overlay you use, this is intended and will lead to way faster loading times. You can omit it if you prefer looking at animated loading screens.)
- Set PostloadingMenuSpeed to 3.0 (line 51).
- If you use VRR (G-Sync/FreeSync), set InGameFPS (line 58) to any value close to your lowest FPS and not exceeding your refresh rate - (refresh rate x 6.8%) (You can check if you are using VRR by going to the Nvidia Control Panel if you're on Nvidia or Adrenalin's Display Settings if you're on AMD. If the G-Sync tab is missing from NVCP, your display doesn't support it or doesn't have the feature enabled in OSD.)

__NVIDIA USERS ONLY:__

- Make sure that G-Sync is set to Fullscreen and that Display Specific settings are enabled in the Control Panel, the Windowed option is problematic due to it being a hacky method. Both of the settings are wrongly named so they do not actually directly refer to the display method.
- If you use fixed refresh rate (meaning no VRR), set InGameFPS (line 58) to your refresh rate - 0.005 or fractions of your refresh rate. For example on 60hz you can lock to 59.995 or 30. Just like on VRR, choose whether to lock to a fraction or RR-0.005 based on which is closest to your lowest FPS.
- If you set InGameFPS to a value higher than 60, do the following as well:
- Set DynamicUpdateBudget to true (line 264).
- Set BudgetMaxFPS to the same value as InGameFPS (line 283).
- (If you are not a Nvidia user, you will need to disable the Nvidia Reflex Support mod in the left side under "Utilities". You will also need to download the "(No Multithreading)" version of Interior NavCut Fix here: https://www.nexusmods.com/fallout4/mods/72904?tab=files&file_id=292234&nmm=1 (replace or remove the version included))

X-Cell: (copy & pasted from The Midnight Ride website)

- Double-click X-Cell in the left pane of MO2.
- In the INI-Files tab, open F4SE/Plugins/x-cell.ini
- Set threads to false (line 8).

Buffout 4 NG with PDB support: (copy & pasted from The Midnight Ride website)

- Double-click Buffout 4 NG with PDB support in the left pane of MO2
- In the Text Files tab, select F4SE/Plugins/Buffout4.toml
- Change BSTextureStreamerLocalHeap to false (line 27)
- Change HavokMemorySystem to false (line 28)
- Change MemoryManager to false (line 32)
- Change ScaleformAllocator to false (line 34)
- Change SmallBlockAllocator to false (line 35)

Facial Expression and Eyetracking Engine Fixes - F4SE: (copy & pasted from The Midnight Ride website)

- Double-click Facial Expression and Eyetracking Engine Fixes - F4SE in the left pane of MO2.
- In the INI-Files tab, open F4SE/Plugins/FacialExpressionAndEyeTrackingEngineFixes.ini
- Set bBrownFace to 1 (line 5).

Unlimited Survival Mode (F4SE):

- Tweak settings to your liking. (Keep in mind though, many mods I include give you alternative ways to save. There will be redundancy if you re-enable quick save.)

Terminals Lock Up - ESPless:

- Set iEnableNoviceLockUps to 1 (line 13). Ultimate Hacking is in the list.

Assorted Modular Tweaks - ESPless - Config:

- Set iFasterTerminalsMultiplier to 5 (line 32).
- Set iRemoveIronSightsBlur to 1 (line 36).
- Set iUncapPickPocketChance to 1 (line 40).
- Set iLongerPowerLines to 1 (line 67).
- Set iImprovedRagdolls to 1 (line 74).
- Set iLessIntrusiveTutorial to 1 (line 86).
- Set iQuestItemsAreNotJunk to 1 (line 95).
- Set iHighlightConsoleReference to 1 (line 99).
- Set iClearConsoleOnLoad to 1 (line 115).

Custom Companion Names: (optional)

- Set any NPCs names to whatever you'd like. Instructions are in the ini file itself.

_LoversLab Downloads: (LoversLab requires an account in order to download. Don't worry, it's safe. (:_

- Download Companion Ivy ver.6.1 (& CompaionIvy_Nuka) here: https://www.loverslab.com/files/file/11260-meet-companion-ivy/
- Drag the zip file into MO2 under "Companions" separator. Enable the mod & plugins. (I am not using the mags because 1) I would like people to be able to stream/make content with my list and 2) I did not like what I saw in xEdit...)

_Discord Downloads: (Discord requires an account in order to join servers. If you don't have a Discord, you should make one. Especially if you want support from me for this list. ;D)_

- Download M8r98a4f2's Complex Item Sorter version: 1.13 beta 2 from the Collective Modding Discord here: https://discord.gg/pF9U5FmD6w (file found in "complex-sorter-support" channel)
- Drag the zip file into MO2 under "Sorting" separator. Enable the mod.
- Download MCM Booster version: 1.1 beta 2 from the Collective Modding Discord here: https://discord.gg/pF9U5FmD6w (file found in "m8r-docs-downloads" channel)
- Drag the zip file into MO2 under "User Interface" separator. Enable the mod.
- Download MAIM version: 3.02 from the MAIM Hub Discord here: https://discord.gg/uqZZpqT9Ze (link found in "official-releases" channel)
- Drag the zip file into MO2 under "Sorting" separator. Enable the mod & plugins.

_Other Off-Site Downloads:_

- Download Combat Drones here: https://storage.icestormng-mods.de/s/EGmEbj6mZ2EK3tY?path=%2F1.1%2FRelease
- Drag the zip file into MO2 under "Companions" separator. Enable the mod & plugin.

__NOTE: For each off-site download, rename their files to include "[No Delete]" in front of their names. This will prevent Wabbajack from deleting them when you update the list. This applies to any mod you've added to the list as well.__

_LOD Output and Load Order:_

- Download both of the Update files here (following the instructions in the desciptions): https://www.nexusmods.com/fallout4/mods/88357

__NOTE: All hidden ESPs or BA2s are HIDDEN FOR A REASON!!! Please don't unhide or enable anything hidden or you will experience moodiness.__

__Tools:__

In your installation location is a folder called "tools". Inside are a few easy to use utilities you can use that are optional as well as some documentation on how to do VRAMr, run Complex Sorter, etc..

_Collective Modding Toolkit-_

Features: (copy & pasted from the Collective Modding Toolkit's mod description)

- Downgrades and upgrades Fallout 4 and Creation kit between Old-Gen and Next-Gen with delta patches. (Requires F4SE﻿ 0.6.23, Address Library﻿ AIO/1.10.163, and BASS﻿)
- Provides counts of data files by type; plugins (Full/Light) and BA2 (General and Textures)
- Patches BA2 files to either v1 (OG) or v8 (NG)
- Scans F4SE DLLs for game version support
- Scans your mod setup for potential issues.
- Automatically update Complex Sorter INIs for the latest xEdit.

_MultiXwm-_

Instructions: (copy & pasted from Personal radio (version with randomizer)'s mod description)

- Use the program to convert your chosen tracks to XWM format. Recommended to use the default program bitrate, or if you want to use wav then use a converter like AIMP and convert XWM to wav 16 bit stereo and 44100 bitrate.  (wav files cause game crashes, this is not the recommended method!!!)
- The custom music must be added in Data\sound\fx\mus\radio\PersonalRadio where the original blank sound files with TTS voice calling track numbers are. Replace them with own music. You must keep the old file name like 1.xwm or 100 xwm, or they wont play, you can add at least 100 tracks.  or If you hear the automated voice calling numbers instead of your tracks - you have incorrectly replaced the tracks.
- It is recommended to first store your converted XWM files you want to use for mod in the temporary output file and rename them there and then replace all 100 empty tracks at once.

_Smooth Sun Shadows-_

Instructions: (Copy and pasted from Smooth Sun Shadows mod description)

- Double click the install .bat file and that's it. It's installed.

_Controller Controls Codes-_

Features: (copy & pasted from Controller Controls with Mod Support in the file's description)

- You want to change something yourself?
- You need those Codes for mods or other things?
- Dont want to google them erverytime?
- Here is a .txt file for those codes controller only atm.
- it provides
	xInput/Controlmap Hex codes
	DXscanCodes Hex and Dec (Decimal)

_Controller Controls MCM First Aid Kit-_

Features: (copy & pasted from Controller Controls with Mod Support's mod description)

For those who messed up their Keybinds.json while changing something theirselves
Mo2 Users have to copy MCM folder from this file to their overwrite, everyone else just set it to highest priority and overwrite anything that conflicts
All mods i covered here (and some more) are there, everything is unassigned
Slide function from TAEP is still set to B (277)
No more need to to set a random keyboard key to configurate something i covered in one of my versions
it also doesnt matter if you dont have the mods covered there (it will make no difference)
so dont worry and use this lifesaver

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

__Settings you must change manually in game via MCM:__

_MAIM Speed:_

- Set Hotkeys to your preference
- Turn on scroll wheel and configure if you would like

_VAFS Redux:_

- Set activation hotkey
- Set criticals hotkey

_Backpacks of the Commonwealth: (Note: This is only required if you're not playing on survival difficulty. Which you SHOULD be...)_

- Set holotape "Remove Armor on PA Entry: Always but keep buffs" (or Auto if Survival) or Carryweight is doubled. (Required for Power Armor Handling Improvements - Retain Armor Buffs to work.)

_Power Armor Handling Improvements:_

- Turn off the "Helmet off when in dialogue" option as it is buggy.

_See Through Scopes:_

- Switch Tactical Reload on.

Configure anything else to your desire. HUD should be good to go as is, but if there are inconsistencies, do let me know!

__THE DEEP DIVE:__

This list was made with survival mode in mind. It wont hit as hard on any other difficulty. It's okay though, because you can tweak survival mode however you want thanks to Unlimited Survival Mode - F4SE! So, don't be a scaredy cat! It's really difficult to try and explain what every single mod does, but I'll point out some of the meat and potatoes that make it special. The SICKnasty core, if you will.

_Perks-_

- True Perks
- Loaded Out - An Encumbrance and Carry Weight Overhaul Mod
- VAFS Redux - Bullet Time and Manual Critical
- TRUE DAMAGE - Weapon Damage Normalized By Ammo Caliber
- MAIM 3
- Ultimate Hacking
- MUTATION
- Magazine Perks Tab
- Pain Train & Impact Landing - Buffed And Reworked

_Quests & Worldspaces-_

- America Rising 2
- Remnants - Secrets of the Enclave
- Xander's Aid
- Fallout Vermont
- The Wilderness - Now with four anomalies and a map
- The Tunnels - For Cave People and Molerats
- Fallout 4 Northern Springs DLC
- Fourville
- Attack of the Lobotomites
- Caves Of The Commonwealth
- Subversion - The Institute-Railroad Alliance Alternate Ending
- Children of Ug-Qualtoth
- The Secret of Huntress Manor - A Far Harbor Story
- Atomic Radio and Tales from the Commonwealth
- The Wild Key Chase - Quest and Location mod
- Boon Island - Isles Of New England
- Ashland Station - Quest-Dungeon-Settlement
- Nordic Europa Research Facility (Dungeon)
- Polaria Systems (Dungeon)
- In The Flesh - A Horror Quest Mod
- Mechanist Omega - An Antagonist Quest Mod
- 20 Leagues Under the Sea - Vault 120
- Flashy(JoeR) - Crime And Punishment
- CHALLENGES - F4NV
- REPUTATION

_World Edits-_

- RADS
- Accessible Bridges - ESL
- Lootable Crates
- Atomic World
- Subway Runner - Revival
- Abandoned Hub (Underground Railroad ReRedux)
- Far Better Far Harbor - Exploration Expanded
- Rsiyo's Location Pack
- Bradberton Interiors
- Minuteman Watchtowers
- "People Live In" suite
- "We Can Live In" suite

_Ambience-_

- True Storms - Wasteland Edition (Thunder-Rain-Weather Redone)
- Seasons Change - A Merry Modding Days Mod
- Icicles - A 2024 Merry Modding Days Mod
- Lightweight Lighting - Gloom Edition
- Fallout 4 Enhanced Color Correction
- Reverb and Ambiance Overhaul
- LOST Audio Tweaks

_Companions-_

- Better Companions - All In One
- Amazing FollowerTweaks Plus (AFT Plus)
- Automatron Expanded Weapons System
- Combat AI Empowered
- I'm Darlene
- Heather Casdin - A Unique Companion Experience by llamaRCA
- Father Companion - Alternate Ending Option for Fallout 4
- Capital Wasteland Dogmeat
- FALLOUT Brotherhood - A Storyteller Quest Mod
- Ellen - the cartographer
- The Machine And Her
- Old Time Religion

_Factions-_

- SCOURGE
- The Alias Project - All In One
- We Are the Minutemen
- You and What Army 2
- Minutemen Takeover - Nuka World
- Church of Atom Overhaul
- Radical
- 4estGimp - Super Mutant Redux-No AWKCR
- Forced Evolution - Super Mutant Addons
- Techno Mutants
- Super Mutant Equality a Super Mutant Weapon Expansion
- 4estGimp - Raider Overhaul ONE
- Raider Gangs Extended
- Raider Gang Factions - A Raider Gangs Extended Add-On and Expansion
- ITO institute Technology Overhaul Full - Version 2
- Courser Crusher
- PROJECT JAVELIN - Courser Replacer
- Synth Overhaul - C.A.S.T
- More Feral Ghouls. A Zombie Mod
- FGEP - Feral Ghouls Expansion Pack - The Definitive Edition
- Mutant Menagerie - Life Finds A Way
- Zetans - Alien invaders in the Commonwealth
- Dreadsharks Of The Commonwealth
- Nightstrikers
- Institute Centaurs
- Lamprey Floaters
- Defective Synths
- Combat Drones
- Plutonium Creatures
- Faction Reinforcements
- NPCs Travel

_Settlements-_

- Workshop Framework
- Standalone Workbenches
- Sim Settlements 2
- Settlement Menu Manager
- OCDecorator
- The Master Plan
- Vault-Tec Workshop Overhaul Redux
- VertiCall 4 Settlements - Buildable Working Tacticool Vertibird Landing Pads
- RL_Recruit_Framework
- Better Settlers
- Recruitable Settlers

_Warsaw's Improved Series-_

- Improved America Rising 2
- Improved Brotherhood of Steel
- Improved Guards
- Improved Hostile Factions
- Improved Institute
- Improved Minutemen
- Improved Nuka Raiders
- Improved Railroad

_Weapons-_

- See Through Scopes
- Vanilla Uniques Framework
- Tactical Reload
- Bullet Counted Reload System (BCR)
- Bullet in the Chamber - Expanded Weapon Mechanics
- Real Time Cover Penetration Framework
- Bullet Penetration and Ricochet (BPR)
- Burst-Fire Framework (BFF)
- Munitions - Ammo Expansion Project
- Munitions - Additional Ammo
- Munitions - Advanced Calibers (MAC)
- Conversions - Munitions for All Vanilla Weapons
- CALIBER - COMPLEX
- Weapons of Fate (Ballistics Overhaul)
- Easy Ammo Vending Machine
- The Attachment Pack
- Pick up Ammo SFX
- Remote Explosives - C4 with Detonators and More
- Full Artillery System Overhaul
- PreWar Binoculars
- Grenade Retrieval System
- CMO - Complete Molotov Overhaul - A Logical Approach
- XXL Nukes (Nuclear Explosions Overhaul)
- Forever Radiation
- Mag Poop - Visual Reload Framework
- Energy Weapons Fixed - Continuous Beams Burst Fire Tri-beam Lasers
- Unique Replacers Project - Vendor Legendary Weapons
- Unique Replacers Project - Unique Legendary Weapons
- Unique Replacers Project - Mod Added Legendaries

_Armor & Clothing-_

- PIP-Pad
- Garmin Foretrex 901
- Gunner Outfit Pack (STANDALONE)
- NanoSuit
- Jetpacks FAO v5 - Installer
- The Pip-Boy Glove
- West Tek Tactical Gloves
- Institute Power Armor Redux...Redux
- Submersible Power Armor Redux
- K-9 Harness -- Tactical Body Armor and Backpack for Dogmeat
- Fallout 2287 - Gas Masks of the Wasteland
- Fallout 2287 - Nuclear Winter
- Black Widow Armor and Pipboy (Pip-boy)
- Bastion - A Power Armor Overhaul
- Enemies Fear Power Armor
- More Durable Power Armor Pieces (RobCo Patcher)
- Power Armor Handling Improvements - Retain Armor Buffs
- Run and Breathe Underwater with Power Armor
- Perennial Power Armor - Lightweight Power Armor Rebalance
- Unique Replacers Project - Legendary Unique Armor And Power Armor

_Survival Tweaks-_

- Unlimited Survival Mode (F4SE)
- Sip Or Save
- Sit Or Save (Only Sofas)
- Shelter Or Save
- Working Pulowski Shelters
- Smokeable Cigars - Cigarettes - Joints - With HardCore Auto Save
- Fill Multiple Bottles
- Flyable Personal Vertibird
- Campsite
- Flyable Personal Vertibird
- Salvage Beacons

_Player Homes-_

- Airship - Player Home and Settlement
- Survivalist's Bus
- Sailboat Abode (A Fast Travel Ship)
- Basement Living - Bunker and Basement Player Homes (with standalone Workshops)

_DankRafft Suite-_

- Leveled Item Fixes (LIF)
- Equipment and Crafting Overhaul (ECO) - Redux
- Legendary Effect Overhaul (LEO) - Crafting - Drops - Modifications - And More
- Legendary AutoBot (LAB) - Craftable legendary effects for Automatron robots
- Weapon Overhaul Project (WOP) - Combined Arms - Service Rifle - M1 Garand - Wattz Laser - Point Lookout - 22LR Pistol
- Looted World

_Textures-_

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
- All Weapons HD (A.W.H.D.)
- Holotape Visual Improvement
- SuperAlloys - Enhanced Power Armor Paints and 4k Textures
- Gloomy Glass - All transparent materials revised
- Fallout 4 Particle Patch - No More Glowing Objects
- Ultimate Window Overhaul Redone

_Mod Author Suites- (nearly every mod by these authors is in the list)_

- DoubleYouC: https://next.nexusmods.com/profile/DoubleYouC
- HappoMatka: https://next.nexusmods.com/profile/HappoMatka
- Halffaces: https://next.nexusmods.com/profile/Halffaces
- dpillari: https://next.nexusmods.com/profile/dpillari
- Omega4D2: https://next.nexusmods.com/profile/Omega4D2
- Oppressor08: https://next.nexusmods.com/profile/Oppressor08
- SavrenX: https://next.nexusmods.com/profile/SavrenX
- mm137: https://next.nexusmods.com/profile/mm137
- DeviousMeth0ds: https://next.nexusmods.com/profile/DeviousMeth0ds
- rsm000rsm: https://next.nexusmods.com/profile/rsm000rsm
- tumbajamba: https://next.nexusmods.com/profile/tumbajamba

I'll continue updating this README as I get things in order, but this is the culmination of months spent in front of xEdit, Nexus, Discord, and MO2. If there's a bug, please let me know and I'll fix it in an update! In a way, you're helping me run this like a beta. I was nervous as all heck to upload this list, but I got the courage to finally do it! I'm a stay at home dad, so I've got nothing but time to answer questions and resolve issues! (:

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
