# Galactic Couriers  
**NOTE:** if updating from an older version, make sure that files "mission.txt" and "jobs.txt" are *not* present in the plugin's data folder.
___  
### Description  
Galactic Couriers is a plugin for the game [Endless Sky](https://github.com/endless-sky/endless-sky). It tells a story of a small breakaway community of humans, who (with the help of the player) manage to discover an uninhabited cluster of star systems, settle it, and become a fully-fledged faction.
___
### Installation  
The installation process is the same as all other ES plugins. Once you download the plugin, place the *galactic-couriers* folder into your game's *plugins* folder. This folder by default is in *C:\Users\YourUserName\AppData\Roaming\endless-sky* on Windows.  
This plugin *should* work just fine even when applied to an already well-progressed game, but it is still advised to backup your save game when installing *any* plugin.  
I am not responsible for your save breaking, but if it does I'll be happy to help you fix it, just open a new issue.  
___  
### How to start  
Once the plugin is installed, you will notice a single new star system appearing on your map. You won't be able to interact with it in any way until you finish the first mission, though.  
This mission becomes available once you finish the main story and make contact with all alien races. The mission starts randomly when entering a spaceport on any human planet. Here are the full conditions:  
<details>

	source
		government "Free Worlds" "Republic" "Syndicate"
	to offer
		has "First Contact: Hai: offered"
		has "First Contact: Remnant: offered"
		has "First Contact: Wanderer: offered"
		has "Coalition: First Contact: offered"
		has "main plot completed"
		random >= 75

</details>  

___  
### TO-DO List  
***Spoilers ahead***
- [ ] Add options to defer or skip all non-critical missions
- [ ] Create jobs unique to the Courier star cluster
- [ ] Conclude chapter 2
- [ ] Create custom outfits for the Ar'leng
- [ ] Add a side-story with levelled boss fights
- [ ] Add an option to adopt the Courier ship swizzle
- [ ] Create custom hails for Courier pilots
- [ ] Create custom news popups for Courier spaceports
