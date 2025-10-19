# The SICKnasty Suite

**CURRENT VERSION: 1.1.3**

**Load Order Library: https://loadorderlibrary.com/lists/the-sicknasty-suite**


**PREAMBLE:**

Fallout 4 is a very special game to me. It came out while I was in community college. At the time, I only had Xbox 360 which I used to play Fallout 3 and Fallout New Vegas. FO4 actually inspired me to build a PC. I even told the guy that helped me get parts, "This PC will be so I can play Fallout 4." I've put hundreds upon hundreds of hours into the vanilla game. When the show came out, it got me wanting to play again, but the next gen content was such a tease (I finished it all in less than a few hours). Then I remembered...I got a PC for a reason. Many wild failures as I learned first hand how modding worked later, we've landed here. Welcome to the sickest and nastiest Fallout 4 experience you've ever seen.


**REQUIREMENTS:**

- **Freshly installed** Steam copy of Fallout 4 ver.1.10.984.0 (NG update)*
- Visual C++ 2015, 2017, 2019, 2022 Redistributable Package: https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist (Install both x86 and x64 (skip ARM64). It's already installed if it says "repair" or "uninstall". In this case you can skip this step.)
- Windows 10 x64 or Windows 11: https://www.microsoft.com/en-us/software-download/windows11
- *Roughly* 460 GB of space
- SERVERisSICKnasty (support server): https://discord.gg/pca64xM2Cz
- ***Patience***


**EXCLUSIONS:**

*NOTE: This operation is required because Windows can block MO2 and mod files from loading due to how MO2's virtualized filesystem works.*

- Open Windows Security.
- Open Virus & threat protection.
- Click Manage settings under Virus & threat protection settings.
- Scroll down and click Add or remove exclusions under Exclusions.
- Add a Folder exclusion and point it to the Installation Location folder.


**UNINSTALLING/REINSTALLING:**

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


**WABBAJACK:**

- Download the latest Wabbajack: https://www.nexusmods.com/site/mods/403
- Create a new folder anywhere except default Windows folders or the game folder itself (Example: C:\Modding\Wabbajack)
- Place Wabbajack.exe in this folder, then run it
- Click Browse Modlists, then tick the "Show Unofficial Lists" box in the corner
- Locate "The SICKnasty Suite" in the gallery and click the download button in the corner
- In Installation Location select a folder that's NOT the following: Steam folder, default Windows folder, game folder, folder you just put Wabbajack.exe (Example: C:\Modding\The SICKnasty Suite)
- Begin installing
- Accept the Nexus Mods API request (If you are not a Premium user you will need to manually click download for each mod)
- Once complete, the installation will show a green Installation Complete screen
- If you see a red Installation Failed screen, try to log-in again through the Wabbajack settings, then reinstall the list to the same folder
	

**MOD ORGANIZER 2:**

- Launch ModOrganizer.exe from your Installation Location
- If you see a pop-up called "Register?", select "Yes"
	
	
**DISCORD DOWNLOADS:** *(Discord requires an account in order to join servers. If you don't have a Discord, you should make one. Especially if you want support from me for this list. ;D)*

- Join the **Collective Modding Discord**: https://discord.gg/pF9U5FmD6w
- Download **M8r98a4f2's Complex Sorter 1.13-beta2** (file pinned in "complex-sorter-support" channel)
- Drag the zip file into MO2 above "4estGimp - M8r98a4f2's Complex Item Sorter Enhancements" under "Interface" separator. Enable the mod.
- Download **MCM Settings Manager - v1.3-beta2** (file pinned in "m8r-development" channel under "MCM Settings Manager")
- Drag the zip file into MO2 below "MCM Settings Manager" under "Interface" separator. Enable the mod.
- Download **MCM_Booster_v1.1-beta2** (file pinned in "m8r-docs-downloads" channel under "Downloads")
- Drag the zip file into MO2 below "MCM Booster" under "Interface" separator. Enable the mod.

**NOTE: Rename any additional download folder to include "[No Delete]" in front of their names. This will prevent Wabbajack from deleting them when you update the list. This applies to any mod you've added to the list as well.**


**POST INSTALLATION:**
	
**First and foremost, make sure that the version of Fallout 4 MO2 is pathed to is the version I include for you in the "game" folder.**

- In MO2, open "Settings"
- Navigate to the "Paths" tab
- Change the bottom path to "(whatever you named your install location)/game/Fallout4.exe"


*Auto Clean All Fallout 4 DLC and CC Next Gen Edition*

***Feature:*** Batch base, DLC, and NGCCC plugin cleaner.

- In MO2, click on the drop-down in the right pane next to the Run button
- Select BatchCleanPlugins and run it
- When the xEdit screen appears, click "Ok"
- When you see the message "Background Loader: finished", close xEdit
- Repeat until it says complete


*Bethini Pie*

***Feature:*** Optimal ini tweaks at the push of a button.

- In MO2, click on the drop-down in the right pane next to the Run button
- Click <Edit...>, then the "+" symbol in the top left, and "Add from file"
- In the resulting explorer window, navigate to the "Bethini Pie" folder in your install location
- Highlight "Bethini.exe" and then confirm
- Apply > OK
- Select BethINI from the drop-down and run it
- Click "Fallout 4" then press "Select Game"
- Choose a preset you prefer (I choose Ultra)
- Click "Apply Recommended Tweaks"
- Set "Display Mode" to "Borderless Windowed"
- Select the resolution you want to display the game in
- Make sure Text Language is set to English both in BethINI Pie and on Steam (other languages are not supported by the guide)
- Edit the other settings to your liking
- File > Save > File > Exit


*High FPS Physics Fix*

***Feature:*** Anything FPS related to your game, configurable via ini.

***Bonus:*** I no longer back The Midnight Ride since it's switched to the NG executable, but it has a calculator specifically for HFPSPF: https://themidnightride.moddinglinked.com/utilities.html (scroll down halfway)

**NOTE:** I provide a pre-configured version of HFPSPF's ini, though the InGameFPS is set for a Fixed Refresh rate of 60. If that setup doesn't fit yours, you'll have to follow the steps below to tailor it to your rig. Otherwise, you can skip this step.

- Double click "The SICKnasty Suite - Resources - SICKnastySETTINGSconfig" in MO2 under the "The SICKnasty Suite - Resources" separator
- Navigate to the "INI Files" tab
- Click on "F4SE\plugins\HighFPSPhysicsFix.ini"
- If you use VRR, set InGameFPS (line 59) to a number you can reach across the majority of the game[3], it has to be between 48[4] and refresh rate - (refresh rate x 6.8%)
- If you use fixed refresh rate (meaning no VRR), set InGameFPS (line 59) to your refresh rate - 0.005 or fractions of your refresh rate. For example on 60hz you can lock to 59.995 or 30. Just like on VRR, choose whether to lock to a fraction or RR-0.005 based on which is closest to your lowest FPS
- If you've set a value that's higher than 60, do the following as well:
	- Set DynamicUpdateBudget to true (line 291)
	- Set BudgetMaxFPS to the same value as InGameFPS (line 310)


*Place Everywhere*

***Feature:*** 

- Double click "Place Everywhere - Place.ini - togglable" in MO2 under the "Utilities" seperator
- Set hotkeys to your liking (or don't if you choose not to use the mod)
- In game, press F8 to activate "place-everywhere" mode (off by default)


**LAUNCHING THE GAME:**

***NOTE: The method SICKnasty - FO4 uses for root files is called the "Stock Game" method. What this means is that a version of Fallout 4 is already included for you in a folder called "game" within your installation location. This method keeps your Steam installation untouched and uninstalling the list is as simple as deleting your install location.***

- Make sure that the version of Fallout 4 MO2 is pointing to is the version in "game" (You can check this in MO2 by clicking the gear icon > Settings > Paths)
- In MO2, you will see a dropdown menu on the right side, to the left of the "Run" button
- Select F4SE
- Click "Run" (this is how you should run the game each time)


**DISCLAIMER!!!**

*This mod list is ***VERY*** big. You'll probably be confused if you try to open it without reading this. Like, "Why didn't I wait forever for the menu to load? Why is the game not letting me start?" We sacrifice the infinite darkness of waiting for the game to start & show the Bethesda logo in exchange for what I'd like to call, "watching the Audio load". Once the main menu opens, and you can navigate to settings, do so and you'll notice that you can alter any of them except for "Audio", which has a loading wheel next to it. When that finishes, only then may you start. It is going to take a long time to load. It is a large list with many large mods in Loose Files format. The only downside to this is you gotta "watch the Audio load". But it's cool, right?*


*Character Creation*

Amazing FollowerTweaks Plus (AFT Plus) allows you to also edit your spouse's appearance. So, if you would like to utilize this feature, this is when!


*MCM*

After leaving the vault, you'll want to actually open up MCM for the first time:

- In your start menu, choose "MCM" (first time will load for a long time while it builds cache)
- Set VAFS hotkey
- Turn True Storms on
- Turn Bullet Counted Reload on
- In Workshop Plus, set "Fly in Workshop Mode" to "OFF" and set hotkeys
- In Power Armor Handling Improvements - Retain Armor Buffs, set "Remove Armor on PA Entry:" to "Auto"
- Configure Condition Boy to your liking

*Holotape*

You also have your Pipboy now! Time to put a holotape in it:

-See Through Scopes: Turn on Tactical Reload


**OPTIONAL:**

I ship the list with a lot of tools that I used to curate the list. Since they're completely optional, it's up to you to explore their use. (Or you can just ping me in my Discord! I love to help! :D) You'll find them in the "tools" folder in your install location. I will, however, go into the following 2:


*FO4Edit*

***Feature:*** The magnum opus of modding tools, used alongside Creation Kit.

Instructions:

- In your install location, move the folder "FO4Edit 4.1.5f" so that it's in it's on dedicated folder on your drive
- Add "FO4Edit" as an executable in MO2 (FO4Edit 4.1.5f>Optional>FO4Edit64.exe)

**NOTE:** Use the 64 version of FO4Edit for everything involving it. Using the normal version will result in xEdit crashing due to too many mods.


*Personal Radio*

***Feature:*** Add up to 200 music tracks to the game!

Instructions:

- Add "MultiXwm" as an executable in MO2 (install location > tools > MultiXwm.exe) and Run it
- Drag your chosen tracks into the to resulting window
- Convert all to XWM format (recommended to use the default program bitrate) and export it wherever (NOTE: You must keep the old file name like 1.xwm, so rename them before exporting!!!)
- In MO2, navigate to Personal Radio (and/or Personal Radio 2) under "Audio" separator, right click the mod, and choose "open in explorer"
- Drag all the tracks from where you exported them into the folder "sound\fx\mus\radio\PersonalRadio", replacing the files with yours when asked
- In game, tune into your MyRadio station, and enjoy!


*Optional mods*

- **flipped condition boy** *(if you move your HUD around)*: https://www.nexusmods.com/fallout4/mods/74464
- **Equalizer PA - Next Gen - Old Gen - Version** *(if you don't like the Maryland flag retexture and want to change it)*: https://www.nexusmods.com/fallout4/mods/90881
- **Mutant Menagerie - Life Finds A Way - No Spider Patch** *(if you're arachnophobic)*: https://www.nexusmods.com/fallout4/mods/85873?tab=description
- **Gamepad - Input** *(better controller support)*: https://www.nexusmods.com/fallout4/mods/76116
- **Ultra Wide Interface (21x9)** *(wide screen compatibility)*: https://www.nexusmods.com/fallout4/mods/65677
- **Gumroad CROSS Enhanced Textures** *(use discount code "cross99off" to get them for free)*: https://niero.gumroad.com/
- **CROSS_Chosen_Of_Atom Enhanced Textures** *(Niero's public Patreon post)*: https://www.patreon.com/posts/cross-chosen-of-25213700
- **Perchik71 - In Game MOD Explorer (MCM)** *(good tool, hard to understand)*: https://www.nexusmods.com/fallout4/mods/56922

**NOTE: If you download the Gumroad CROSS textures, you'll have to install them as a mod in MO2 and unpack any of them that are in BA2. I include Unpackrr and Cathedral Assets Optimizer. Unpackrr has a mod page on Nexus with instructions.**
**NOTE: If you change the Maryland flag texture on the Equalizer PA, I will cry.**


**Plugins disabled FOR A REASON:**

Only enable the following utility plugins if you're prepared to use them (details on usage can be found on each mod's respective page):

- **SKKScriptLatencyTest.esp:** https://www.nexusmods.com/fallout4/mods/35853
- **SKKObjectCounter.esp:** https://www.nexusmods.com/fallout4/mods/70733
- **FCOM Custom Faction.esp:** https://www.nexusmods.com/fallout4/mods/42402
- **Face Ripper Presets.esp:** https://www.nexusmods.com/fallout4/mods/3878
- **AutoCellDisplay.esp:** https://www.nexusmods.com/fallout4/mods/69978


The following plugins are disabled after patch generation:

- **FO4LODGen.esp**
- **Optimized Vanilla Tree LODs.esp**


If you see a mod has hidden or missing files, **THIS IS INTENDED!!!** This means that its files have been packed into one of the mods under "Workfiles" separator or hidden because one of my outputs overwrites it. This is done so I can repack all of my outputs without any loose files overriding them. **DO NOT REINSTALL THESE MODS!!!**


**OUTRO:**

This mod list was made by me and only me. That's not by choice, it's just how it's been. That's also not me saying to go easy on me. I can take it. I continue to learn new things and implement them in updates. Not just the products, but the tools. I wanted my suite to be one that you could pick apart and tweak to your liking. That said, by all means, feel free to upload patches for my list! As long as your patch falls within the permissions from the mod author of whatever mod(s) you're patching!


**SUGGESTIONS:**

Always welcome if their through the correct channel in my Discord server. However, there are guidelines on what not to suggest:

- Anything lore breaking (there are exceptions and they are already included)
- Texture overhauls (use GVCM if you don't like the colors, but I wont budge on what I've concocted)
- Anything by Thuggysmurf
- Anything by QRSR
- Anything by Halffaces
- Anything by MunkySpunk

**Ways you can make my day:**

- **Patreon:** https://www.patreon.com/kcissicknasty
- **Buy-Me-a-Coffee:** https://buymeacoffee.com/kcissicknasty