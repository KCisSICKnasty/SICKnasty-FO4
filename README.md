# SICKnasty - FO4

Fallout 4 is a very special game to me. It came out while I was in community college. At the time, I only had Xbox 360 which I used to play Fallout 3 and Fallout New Vegas.
FO4 actually inspired me to build a PC. I even told the guy that helped me get parts, "This PC will be so I can play Fallout 4." I've put hundreds upon hundreds of hours into
the vanilla game. When the show came out, it got me wanting to play again, but the next gen content was such a tease (I finished it all in less than a few hours). Then I
remembered...I got a PC for a reason.

Many wild failures as I learned first hand how modding worked later, we've landed here. Welcome to the sickest and nastiest Fallout 4 experience you've ever seen.

REQUIREMENTS:

- Fallout 4 (Steam copy)*
- Mod Organizer 2
- Wabbajack
- The Midnight Ride**
- Patience***

*SICKNASTY - FO4 WILL ONLY WORK FOR STEAM INSTALLATIONS OF THE GAME!!! It requires the NextGen content, but then uses Simple Fallout 4 Downgrader to roll back the update
and keep the content. GOG is not supported, sorry! :(

***This mod list is VERY big. The BA2 limit was hit a long time ago & you'll probably be confused if you try to open it without reading this. Like, "Why didn't I wait forever
for the menu to load? Why is the game not letting me start?" We sacrifice the infinite darkness of waiting for the game to start & show the Bethesda logo in exchange for what
I'd like to call, "watching the Audio load". Once the main menu opens, and you can navigate to settings, do so and you'll notice that you can alter any of them except for
"Audio", which has a loading wheel next to it. When that finishes, only then may you start. It is going to take a long time to load. It is a large list with many large mods in
Loose Files format. The only downside to this is you gotta "watch the Audio load". But it's cool, right?

Setting up MO2, BethiniPie, etc.:

Just use The Midnight Ride: https://themidnightride.moddinglinked.com/utilities.html

I can't put it any better. Follow it for the initial installs, but ignore everything after "Mod Organizer Downloads" (you're here because you're downloading a list, right?).
The Midnight Ride is the golden standard, in my opinion, for setting up your game to be modded. I'd recommend giving it a look over so you can at least be familiar with how
to do things in MO2. I won't explain those things here because it would just be me repeating what's said there. TMR website is where I learned and it should be where you learn
too! (:

MOST IMPORTANTLY, NAVIGATE TO STOCK GAME FOLDER AND LAUNCH: fo4downgrader.exe

It will say "Patch successful!" and then you may continue!

Off-Site Downloads:

Download Combat Drones here: https://storage.icestormng-mods.de/s/EGmEbj6mZ2EK3tY?path=%2F1.1%2FRelease

	Drag the zip file into MO2. Enable the mod and plugin.

Download OCBP for Fallout 4 here: https://www.loverslab.com/files/file/18604-ocbp-for-fallout-4/

	*Note: You'll have to make an account. OCBP is required for 3BBB.
	
	Drag the zip file into MO2, directly above 3BBB Physics (CBBE - TWB) and enable it.

Download M8r98a4f2's Complex Item Sorter version: 1.13 beta 2 from the Collective Modding Discord here: https://discord.com/channels/830436661736243230/915413649638707251/1147636681860714546

Download MCM Booster version: 1.1 beta 2 from the Collective Modding Discord here: https://discord.com/channels/830436661736243230/1031848835993047050/1031849157394169888
	
	*Before you get huffy over having to join a Discord, it's a very useful hub where you can get direct help from your favorite mod's authors. You can also leave after.

Settings you must check in Mod Organizer 2 (double click and navigate to txt file):

High FPS Physics Fix:
- set line 26 to true
- set line 37 to true
- set line 51 to 3.0

Buffout 4 NG with PDB support:
- set line 26 to false
- set line 27 to false
- set line 31 to false
- set line 33 to false
- set line 34 to false

All Weapons HD (A.W.H.D.): (this requires going into your game folder, which you can do through the folder icon at the top of your modlist in MO2)

- Fallout4Prefs.ini - Navigate to the very bottom and you will see the line [Launcher]. Directly underneath this, add the following line: bEnableFileSelection=1

- Fallout4Custom.ini - [Archive]

		      bInvalidateOlderFiles=1s

		      ResourceDataDirsFinal=

Make F4SE an executable in MO2. Details on that found in The Midnight Ride. Make the executable of fallout4.exe the one in the Stock Game folder.

Settings you must change manually in game:

Power Armor Handling Improvements - Retain Armor Buffs:

- Backpacks of the Commonwealth - Set holotape "Remove Armor on PA Entry: Always but keep buffs" (or Auto if Survival) or Carryweight is doubled.

MAIM Speed:

- Set Hotkeys to your preference
- Turn on scroll wheel and configure if you would like

VAFS Redux:

- Set activation hotkey
- Set criticals hotkey

Configure anything else to your desire. HUD should be good to go as is, but if there are inconsistencies, do let me know!

The cherry on top:

Download my resource files from here: https://www.nexusmods.com/fallout4/mods/88357

Download VRAMr here- https://www.nexusmods.com/fallout4/mods/80305

Follow the video on the mod description page and enjoy better performance.

Plugins that are disabled FOR A REASON!!!

- UniqueReplacer - WastelandK9Armor.esp
- UniqueReplacer - LunarSSRecon.esp
- UniqueReplacer - JustSweeper.esp
- Dogmeat's Backpack.esp
- 0_Vault120_NordhagenHaven_PRP.esp
- Forever Radiation Lite.esp
- FR L XXXLNukes Patch.esp
- Tumba_Gunner_Collection_Smuggler.esp
- 3dscopes-replacer-bullpupbozar.esp
- 3dscopes-replacer-classicsniper.esp
- LOD Fixes and Additons.esp
- AnubisPlayer.esp
- AnubisPlayerVoice.esp
- Horrorghouls2.2.esl

DO NOT RE-ENABLE OR YOU WILL EXPERIENCE MOODINESS!!!

Reading material:

If any mod includes a PDF or a txt file, you can find that neatly tucked into a folder called "reading material". I encourage taking a look at those whenever you have some
free time!

THE DEEP DIVE:

This list was made fully with survival mode in mind. It wont hit as hard in normal game. It's okay though, because you can tweak survival mode however you want thanks to
Unlimited Survival Mode - F4SE! So, don't be a scaredy cat!

It's really difficult to try and explain what every single mod does, but I'll point out some of the meat and potatoes that make it special.

For perks, a full overall that stitches together True Perks, VAFS, MAIM, and True Damage. I carry over almost everything from VAFS so the mechanic wins, but keep the
requirements that True Perks puts in place so there's no mixup. Anything that touches damage is nerfed with changes carried over from True Damage. Any MAIM conflicts are
taken care of. All of this is done with the SICKnastyPERKmodule.

Since True Damage makes bullets hurt a lot more, why not more bullets? Munitions & Co. give us tons of new ammunition. Thanks to DJINDO, the new ammo types will play well with
TD also! I'd use Reaper's RobCo mod, but I prefer seeing everything worked out in xEdit for this one specifically. Same reason we're not using the True Damage Easy Load Order
mod.

"But True Damage & MAIM make the game so hard..." Get Power Armor. Thanks to Bastion, you're now literally covered. Damage wont go through until the piece is broken, and then you'll
only take damage in the specific spot. We've got some nifty mods to make Bastion smart, so Power Armor is more of a necessity.

Warsaw's Improved factions series serves as a base for a ton of the weapon and armor mods on this list. I've more or less included everything that they can interact with that
doesn't conflict. Raider Overhaul & Raider Gangs Extended, Super Mutant Redux & Forced Evolution, More Feral Ghouls & Feral Ghoul Expansion Pack, We Are the Minutemen & You
and What Army 2...You name it, bud. If the faction exists, it's been overhauled.

Weapon and Armor mods are plentiful, but I cannot stand chem bench clutter & am not interested in 500 ARs from the real world or CoD. Therefore, any mod that adds a new weapon
or piece of armor/clothing is ran through URP (Unique Replacers Project). This series of mods replaces FO4's vanilla uniques with mods. The mods it uses are stripped of any
crafting capabilities or LL injections, making finding the unique it has replaced the only way to obtain it. This gives a lot of variety to the unique weapons & makes it more
exciting when you find them.

The only weapons in the list not touched by URP are those included in the WOP (Weapon Overhaul Project). This includes Combined Arms & the Expansion pack, the Service Rifle,
the Wattz Laser Gun, the M1 Garand, the weapons added by Point Lookout, & the 22LR Pistol. The only armor/clothing in the list not touched by URP are included because they
probably interact well with Gasmasks of the Wasteland.

Speaking of which, there's 2 new resources you need to manage & conditions you need to keep track of. Gasmasks of the Wasteland makes wearing a gas mask a necessity when
traversing the Commonwealth with replacable filters you'll need to keep on hand. Nuclear Winter (WHICH DOES NOT ADD WEATHER TO THE GAME!!!) makes your body temperature
something you'll actually need to keep track of (with realism, so if it's December, well...Boston sucks in the winter...). Keep your character properly dressed and make sure
you keep those hands warm!

My patches are all esp flagged esl plugins made in xEdit. Most of them are self explanatory (SICKnastyPERKmodule contains all perk related patches, SICKnastyGASMASKmodule
forwards the gasmasks from Gasmasks of the Wasteland into inventories and carries over any NPC changes, etc.).

I'll continue updating this README as I get things in order, but this is the culmination of months spent in front of xEdit, Nexus, Discord, and MO2. If there's a bug, please let me
know and I'll fix it in an update! In a way, you're helping me run this like a beta. I was nervous as all heck to upload this list, but I got the courage to finally do it! I'm a stay
at home dad, so I've got nothing but time to answer questions and resolve issues! (:

Once you've installed the modlist, head here for the Complex Sorter files and the LODGen Output: https://www.nexusmods.com/fallout4/mods/88357

Load Order Library: https://loadorderlibrary.com/lists/sicknasty-fo4

Discord: https://discord.gg/W9HRjDFVzX

Patreon: https://www.patreon.com/kcissicknasty

Buy-Me-a-Coffee: https://buymeacoffee.com/kcissicknasty

My band, ADA: https://open.spotify.com/artist/7D5hStnbyJ8lcvg1Fgc4jR
