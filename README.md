# SICKnasty - FO4

__CURRENT VERSION: 2.4.7__

__We're back to Wabbajack not giving you the correct version. Just use Simple Fallout 4 Downgrader after you're done: https://www.nexusmods.com/fallout4/mods/81933__

__I don't know why it's happening again. Wabbajack Support Discord says it's a user problem, but the executable isn't correct on your end and it is on mine so somehow you changed the executable before even opening the list. I have no answers and I'm sorry. :(__

Fallout 4 is a very special game to me. It came out while I was in community college. At the time, I only had Xbox 360 which I used to play Fallout 3 and Fallout New Vegas. FO4 actually inspired me to build a PC. I even told the guy that helped me get parts, "This PC will be so I can play Fallout 4." I've put hundreds upon hundreds of hours into the vanilla game. When the show came out, it got me wanting to play again, but the next gen content was such a tease (I finished it all in less than a few hours). Then I remembered...I got a PC for a reason.

Many wild failures as I learned first hand how modding worked later, we've landed here. Welcome to the sickest and nastiest Fallout 4 experience you've ever seen.

__Load Order Library: https://loadorderlibrary.com/lists/sicknasty-fo4__

__SERVERisSICKnasty (support server): https://discord.gg/W9HRjDFVzX__

__REQUIREMENTS:__

- Fallout 4 ver.1.10.984.0 (NG update)*
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

- Download Wolfmark's XDI Fix here: https://drive.google.com/file/d/1NHGQkp27EFkPjQdQRwtXCTuCRRXecF0h/view
- In MO2, right click "Extended Dialogue Interface" and then click "Open in Explorer". Drag the XDI.dll file from the download into the Extended Dialogue Interface folder and let it replace it. (This fix in combination with DankRafft's mod allows us to use Extended Dialogue Interface without the need for individual patches.)

- Download Combat Drones here: https://storage.icestormng-mods.de/s/EGmEbj6mZ2EK3tY?path=%2F1.1%2FRelease
- Drag the zip file into MO2 under "Companions" separator. Enable the mod & plugin.

__NOTE: For each off-site download, rename their files to include "[No Delete]" in front of their names. This will prevent Wabbajack from deleting them when you update the list. This applies to any mod you've added to the list as well.__

_LOD Output and Load Order:_

- Download both of the Update files here (following the instructions in the desciptions): https://www.nexusmods.com/fallout4/mods/88357

__NOTE: All hidden ESPs or BA2s are HIDDEN FOR A REASON!!! Please don't unhide or enable anything hidden or you will experience moodiness.__

_Optional Mods:_

- Mutant Menagerie - Life Finds A Way - No Spider Patch (for those who are arachnophobic): https://www.nexusmods.com/fallout4/mods/85873?tab=description
- Controller Controls with Mod Support (for those that prefer to use a controller): https://www.nexusmods.com/fallout4/mods/61159
- VRAMr (highly recommed following the video guide in this mod's description for better performance tailored to the modlist): https://www.nexusmods.com/fallout4/mods/80305

__Launching Fallout 4:__

Make sure that the version of Fallout 4 MO2 is pointing to is the version in your installation location (a folder named "Stock Game"). You can check this in MO2 by clicking the gear icon > Settings > Paths.

- In MO2, you will see a dropdown menu on the right side, to the left of the "Run" button.
- F4SE should be an executable in this menu. Click it.
- Once selected, click "Run". This is how you should run the game each time. (Alternatively, you could make a F4SE shortcut so you don't have to open MO2 to launch the game)

__Settings you must change manually in game:__

_MAIM Speed:_

- Set Hotkeys to your preference
- Turn on scroll wheel and configure if you would like

_VAFS Redux:_

- Set activation hotkey
- Set criticals hotkey

_Backpacks of the Commonwealth: (Note: This is only required if you're not playing on survival difficulty. Which you SHOULD be...)_

- Set holotape "Remove Armor on PA Entry: Always but keep buffs" (or Auto if Survival) or Carryweight is doubled. (Required for Power Armor Handling Improvements - Retain Armor Buffs to work.)

_See Through Scopes:_

- Switch Tactical Reload on.

Configure anything else to your desire. HUD should be good to go as is, but if there are inconsistencies, do let me know!

__THE DEEP DIVE:__

This list was made fully with survival mode in mind. It wont hit as hard in normal game. It's okay though, because you can tweak survival mode however you want thanks to Unlimited Survival Mode - F4SE! So, don't be a scaredy cat! It's really difficult to try and explain what every single mod does, but I'll point out some of the meat and potatoes that make it special. The SICKnasty core, if you will.

- For perks, a full overall that stitches together True Perks, VAFS, MAIM, and True Damage. I carry over almost everything from VAFS so the mechanic wins, but keep the requirements that True Perks puts in place so there's no mixup. Anything that touches damage is nerfed with changes carried over from True Damage. Any MAIM conflicts are taken care of. All of this is done with the SICKnastyPERKmodule.
- Since True Damage makes bullets hurt a lot more, why not more bullets? Munitions & Co. give us tons of new ammunition. I'd use Reaper's RobCo mod, but I prefer seeing everything worked out in xEdit for this one specifically. Same reason we're not using the True Damage Easy Load Order mod.
- "But True Damage & MAIM make the game so hard..." Get Power Armor. Thanks to Bastion, you're now literally covered. Damage wont go through until the piece is broken, and then you'll only take damage in the specific spot. We've got some nifty mods to make Bastion smart, so Power Armor is more of a necessity.
- Warsaw's Improved factions series serves as a base for a ton of the weapon and armor mods on this list. I've more or less included everything that they can interact with that doesn't conflict. Raider Overhaul & Raider Gangs Extended, Super Mutant Redux & Forced Evolution, More Feral Ghouls & Feral Ghoul Expansion Pack, We Are the Minutemen & You and What Army 2...You name it, bud. If the faction exists, it's been overhauled.
- Weapon and Armor mods are plentiful, but I cannot stand chem bench clutter & am not interested in 500 ARs from the real world or CoD. Therefore, most mods that add new weapons or pieces of armor/clothing are ran through URP (Unique Replacers Project). This series of mods replaces FO4's vanilla uniques with mods. The mods it uses are stripped of any crafting capabilities or LL injections, making finding the unique it has replaced the only way to obtain it. This gives a lot of variety to the unique weapons & makes it more exciting when you find them.
- 2 new very lore friendly resources for you to manage: air quality and body temperature. Gasmasks of the Wasteland makes wearing a gas mask a necessity when traversing the Commonwealth with replacable filters you'll need to keep on hand. Nuclear Winter (WHICH DOES NOT ADD WEATHER TO THE GAME!!!) makes your body temperature something you'll actually need to keep track of (with realism, so if it's December, well...Boston sucks in the winter...). Keep your character properly dressed and make sure you keep those hands warm!
- For visual overhauls, we use HappoMatka's "Seen Some Shit" series, nearly all of Halfface's texture replacers, dpillari's HD suite of mods, Omega4D2's Modern Replacer series (but none of the immersion breaking ones), and DoubleYouC's landscape retextures to name a few. All wrapped up in the warm embrace of Lightweight Lighting - Gloomy Edition.
- Weather? You bet. True Storms combined with Seasons Change tag team all of the atmoshpere. I've used the script included with Seasons Change on the entire load order so you'll see snow on all of our stuff. You'll hear all kinds of new audio too thanks to the Lost Audio Tweaks suite of mods.
- My patches are all esp flagged esl plugins made in xEdit. Most of them are self explanatory (SICKnastyPERKmodule contains all perk related patches, SICKnastyGASMASKmodule forwards the gasmasks from Gasmasks of the Wasteland into inventories and carries over any NPC changes, etc.).

I'll continue updating this README as I get things in order, but this is the culmination of months spent in front of xEdit, Nexus, Discord, and MO2. If there's a bug, please let me know and I'll fix it in an update! In a way, you're helping me run this like a beta. I was nervous as all heck to upload this list, but I got the courage to finally do it! I'm a stay at home dad, so I've got nothing but time to answer questions and resolve issues! (:

__Ways you can make my day:__

- Patreon: https://www.patreon.com/kcissicknasty
- Buy-Me-a-Coffee: https://buymeacoffee.com/kcissicknasty
- My band, ADA: https://open.spotify.com/artist/7D5hStnbyJ8lcvg1Fgc4jR
