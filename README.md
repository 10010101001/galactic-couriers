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
- [ ] **Conclude chapter 2** *(after all the other things are done)*
- [ ] Create custom outfits for the Ar'leng
- [ ] Add a side-story with levelled boss fights
- [ ] Add an option to adopt the Courier ship swizzle
- [ ] Create custom hails for Courier pilots
- [ ] Create custom news popups for Courier spaceports
- [ ] Add reminders for easy to miss "meet me ..." mission triggers

___
### Story overview  
***Even more spoilers ahead! Do not read this if you're actually interested in downloading the plugin and playing through the story. The only reason I'm writing this is so that if you have a suggestion for the story you have a place to read up on the full context of the plugin's lore.***  

I want the story of this plugin to be divided into separate "chapters", with each chapter having an interesting introduction and conclusion.  

The Couriers intitially started as a company under the Republic called the Galactic Couriers *(hence the weird name of the plugin)*, but as they became more and more successful their leaders and even employees started to receive threats from anonymous sources *(I wanted to imply that it was the Syndicate and the Parliament because the Couriers began to have too much power for their liking, but given that the storylines for the Republic and the Syndicate don't exist yet I just kept it anonymous)*.  
The Couriers pretended to disband their company, but instead they secretely moved their operations into a lonely star system far from the Republic's reach. This star system, called "Meliter" is unique because it is the only known stable triple star system, and also contains an abandoned Kor Sestor station that the Couriers modified to serve as their home.  
From there, they continued to serve as a transport company, but instead of general cargo transport they now helped with things like humanitarian aid, relocation of refugees of war, or simply delivering goods to private customers who feel like their stuff is safer with the Couriers rather than some inexperienced pilot. The Couriers primarily use Bulk Freighters equipped with Jump Drives *(they get the drives from Korath raids, they managed to move some warship to their system to defend against them)* but disguised as merchant ships.  

#### Chapter 1  

Your first contact with the Couriers (besides randomly stumbling upon their star system) is one of their Bulk Freighters landing in the same spaceport as you. It turns out that this particular freighter often appears on this planet with deliveries of exotic goods for some local rich retiree. You have the option to approach the ship, where you meet one of the retiree's private guards who oversees the unloading, but he recognizes you and tells you perhaps more than he's allowed to. From this information you learn that there are rumors that this ship comes from a star system "up north".  
If you refuse to inspect the ship, you are then given a second option to unlock the Courier mission arc in the form of a disabled Courier ship in a random uninhabited star system. Once you assist it, its crew will thank you and tell you to meet their boss in the Courier star system.  

Once you first land on the Courier space station, you meet up with their CEO Vladimir Novak. He recognizes that you have a Jump Drive and a lot of experience with the Korath and other aliens alike, and offers you to do some work for them. This work is mainly composed of simple cargo transport missions. After you do a few of the Courier jobs, the station gets attacked by a Korath raid.  
This raid is much bigger than anything they experienced before and consumes a big chunk of the Courier fleet (although they do manage to capture few Korath Raiders and Chasers). Because of this, the Couriers come up with a plan to prepare for future raids; they ask the Remnant to give them access to their shipyards. The Remnant agree, but only partially, allowing the Couriers to purchase only the Starling warship *(the reason I thought the Remnant would help is because both the Couriers and Remnant are in a similar situation; a breakaway group of humans living in separation, constatly threatened by the Korath - although further in the story the similarities start to fade away)*.  
The Couriers decide to use the Starling to its full potential, and exploit its cloaking ability to set up early warning systems around nearby star, so at the very least they have time to evacuate civilians from their station. Thanks to this they soon notice the Korath preparing for another - even larger - raid. Because the Couriers have very little warships, and buying new ships in the human space would raise too much suspicion, they get in contact with one of their long-time customers who lives in the Hai space and they acquire a fleet of Shield Beetles.  
Once again you help them defeat the Korath raid, but shortly before that you are also intorduced to Christian Zimmerman (Chris), a chief Courier scientist who is in charge of translating old Kor Sestor information database that was left on the station.

After the raid, Chris finds out that this star system was abandoned by the Kor Sestor because an alien entity appeared here and slaughtered most of them. Later it is also revealed that the space station is in fact one large weapon designed by the Sestor to create temporary hyperspace links and use them to channel energy of three stars at once to its target system. This weapon misfired at some point, and due to some weird anomaly managed to link with an alien star system at the edge of the observable universe, which is how this alien entity (a warship) got there.  
You and Chris then attempt to trace the steps of the alien ship, because Chris thinks that the ship left the system and went somewhere else into hiding. However, after you come up empty-handed, Chris realizes that this alien ship is still in the Courier system. When it defeated the Sestor, it travelled to the far edge of the solar system and went into a deep state of hibernation, only to be woken up by the recent fights with the Korath. Now this ship is headed towards the Courier station, so evacuation starts.  
After analyzing the ship, Chris realizes that the only way it can be destroyed is by forcing all three stars in the system to go supernova. To do this, Chris wants to use the station's weapon to knock one of the three stars out of its orbit so it would collapse into the other two.  
Meanwhile, the Korath are preparing for another huge raid, which arrives almost at the same time as the alien ship. You escort the last batch of Courier transport ships out of the system, while Chris stays behind in the station to operate the weapon. He also set up special solar-powered shields in the hope that he and the station will be able to withstand the full force of three stars exploding.  
Once you and the Courier transports arrive at your destination, the star system is temporarily deleted from your map and you all go your separate ways.  
Several weeks later, the star system becomes available again as the supernovae died down. When you travel there, you find out that the Courier station indeed survived. When you dock with it, you meet both Novak (who's traveled there before you) and Chris.  
Chris then returns to Earth where he works in a research lab together with doctor McKay. McKay's research team is usually forced to work on military projects for the Republic, but when Chris brings the Kor Sestor database most of them start working on it.  
You then have the option to meet up with Chris on Earth. He tells you that while he was firing the station's weapon, he thinks that it created a wormhole that leads to the edge of the Milky Way.  

#### Chapter 2 (not finished)

You, Chris, and McKay then manage to use some technology recovered from the alien ship to traverse the wormhole, where you find several completely uninhabited - but mostly habitable - star systems. Together with Chris you tell the news to Novak, who agrees to put the Couriers back together and move to those new star systems.  
While you are transporting Novak to one of the planets, McKay takes his own ship and gathers enough people to start a small colony. You are then free from any Courier work while they are bringing in more people and expanding said colony.  
At some point you encounter a Courier World-Ship in human space (they found the World-Ship heavily damaged and abandoned but patched it up again) preparing to take hundreds of people to the Courier star cluster.  
They ask you to escort them, and when you arrive on the Courier planet you notice that instead of a small camp the colony now grew to a proper town.  

You then help the Couriers to further establish their colonies by disabling some Korath Raiders so that the Couriers can take their power generators, and once the colonies are set up and the Couriers start manufacturing their own ships capable of travelling through the wormhole, you are tasked to join their fleet on a diplomatic mission to establish relations with the Republic, Free Worlds, and the Syndicate. This goes well and the Couriers start once again sending cargo ships to the human space, except this time they don't have to be undercover. ***(this is roughly where the finished story ends)*** The situation is then stable, there aren't many large Courier missions, instead you focus more on side-stories of different Courier planets; for example, when you land on the main manufacturing world you can start a small mission arc where you help the Courier engineers develop a new ship, or when you land on the Courier homeworld you are tasked with several bounty missions.  

Chapter 2 stars concluding when a large Pirate raid occurs in the Courier star cluster. This group of pirates managed to ambush multiple Courier convoys, plundered their Jump Drives and keystones, and then went on to enrich themselves using Korath ships and outfits. The Couriers suffer many losses, mainly due to the fact that none of their planets was prepared for an orbital strike, so the Courier researchers and engineers come together to start work on a new warship that would deter the pirates. Chris and McKay then step in and reveal that they managed to fuly translate Sestor blueprints that explain how to manufacture the Met Par Tek 53 warships, which are much stronger than anything they could build using human technology.  
The Courier version of the Met Par Tek 53 is weaker than the Sestor variant; it uses mainly human outfits and weapons, and also has to be crewed, but it is still stronger than any Pirate vessel. Once a few prototypes are created, you are tasked to escort them around several Pirate systems in a show of force, but because you don't know where the Pirate raid came from you can't fully retaliate just yet.  
Chapter 2 concludes when the Met Par Tek 53 production picks up - some Korath outfits are also reverse-engineerd and enter production, and the ship becomes available for purchase on the Courier homeworld.

#### Chapter 3 (planned)  

In the introduction of ch3 I kinda want to introduce some other Sestor ships, namely the Tek Far 71 and 78 and both the Korath fighter and drone.  

In the middle the Couriers would become much stronger than other humans (thanks to the Korath tech), and would send warships to occupy Pirate systems until the group that ambushed their freighters surrenders. I want there to be some minor conflict between the Republic and the Couriers, because the Republic would insist that they'll take care of the Pirates, but the Couriers would still keep increasing their military presence around the Republic which would in turn increase the tensions between the two.  
However, it is then found out that the Pirate group managed to infilatrate Courier ranks and now also owns the Sestor ships, which will culminate in a series of large battles between the Couriers and Pirates, with both of them using powerful Korath technology.

The final battle happens on Courier's home turf when a huge Pirate fleet full of extremely powerful ships (and maybe nukes?) defeats the Courier fleet that protected the wormhole. But just before the Pirates reach the Courier homeworlds, the Ar'leng step in, insisting that the Couriers killed one of their own and now have to pay the consequences. The Pirates, thinking that it's some other Courier fleet, attack the Ar'leng, but are immediately wiped out by the powerful weapons, and now you and the Couriers are stranded in the star cluster and have to reason with the aliens.
