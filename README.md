<<<<<<< Updated upstream
MemeNames by Zelix-Eldre'Thalas.
=======
<<<<<<< HEAD
#MemeNames 
Written by Zelix-Eldre'Thalas.
=======
MemeNames by Zelix-Eldre'Thalas.
>>>>>>> 0d315cdd886006b7858ce652bb43ff5815626b25
>>>>>>> Stashed changes

Renames Items in-game through Addon Functionality to allow Meme-y Names to be displayed instead of regular items names.
Inspired by nicknaming the Hymnal of the Path to Book of Blasting, Phial to Granny Plague's Bathwater.

Features:
* Renames Items.
* Ability to add Random Name to Items that Changes Each Session.
* Chat Commands to Rename, Add, Reset, Clear, and Re-Randomize names.
<<<<<<< Updated upstream
=======
<<<<<<< HEAD
* Holding Alt will display the Item's Real Name as well.
=======
>>>>>>> 0d315cdd886006b7858ce652bb43ff5815626b25
>>>>>>> Stashed changes
	
Where to find new Names:
* Item Tooltips
* Chat Messages
* Dungeon/Loot Journal
	
Planned Features (Maybe, and if I have time.):
* Add Options UI
* Effect More Frames
* Allow Randomized Items to Reroll Periodically
* In-Game Sharing and Syncing
* Chaos Mode (Allow Random Names to not be session locked. Read FAQ for Details)
* Spells
	
Commands | Effect
---------|---------
/mn -help | Display's Commands.
/mn -random | Rerolls Random Names.
/mn Link Name | Sets and Items, or if an name is already set, add a random name.
/mn Link -clear | Removes all names for the item.
/mn Link -reset | Resets the Item back to the Default Name already programmed in the addon.
		
FAQ:
* Does this break TOS?
  * No. This does not modify any files, and it strictly limited to Clients who have this AddOn installed and Enabled. Item Links do not change for other players without this addon. If Blizzard does not like the functionality they're free to break the methods used like previous brokenn addons.
	
* Random isn't so Random?
<<<<<<< Updated upstream
  * While programming this addon I found that when mousing over items in your inventory, character sheet, or inspection, the server seems to continously query the item, firing off multiple events every few seconds causing the Tooltip to jitter with random names. To Prevent this each Random Item is set to one of the Random Names upon seeing the item for the first time. Either Relog, ReloadUI, or type /mn -random, to reroll item names.
  * If I have time, I may add a "chaos" mode that will continously cycle through the names, or eventually I'll make it re-randomize every so often.
=======
<<<<<<< HEAD
  * Mousing Over Tooltips are constantly firing events to pick up if any Modifier Keys are Held Down. This will cause the Tooltip to jitter with random names. To Prevent this each Random Item is set to one of the Random Names upon seeing the item for the first time. Either Relog, ReloadUI, or type /mn -random, to reroll item names.
  * If I have time, I may add a "chaos" mode that will continously cycle through the names, or eventually I'll make it re-randomize every so often.
=======
  * While programming this addon I found that when mousing over items in your inventory, character sheet, or inspection, the server seems to continously query the item, firing off multiple events every few seconds causing the Tooltip to jitter with random names. To Prevent this each Random Item is set to one of the Random Names upon seeing the item for the first time. Either Relog, ReloadUI, or type /mn -random, to reroll item names.
  * If I have time, I may add a "chaos" mode that will continously cycle through the names, or eventually I'll make it re-randomize every so often.
>>>>>>> 0d315cdd886006b7858ce652bb43ff5815626b25
>>>>>>> Stashed changes
