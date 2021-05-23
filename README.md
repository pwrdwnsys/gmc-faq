
# Galactic Mining Corp FAQ (Unofficial)

This is the unofficial, work-in-progress FAQ for Galactic Mining Corp by Windybeard Games.

**For filing bug reports or getting assistance in relation to an issue not covered in this FAQ, please visit the [GMC Steam Discussions](https://steamcommunity.com/app/1218500/discussions/)**.

## GRAPHICS

### The graphics look strange or the text is blurred/pixellated

This appears to be an issue on Windows 10 systems with High DPI monitors. To resolve this:

- In the Steam Client, right-click on Galactic Mining Corp and select "Properties..."
- Click "Local Files" in the sidebar.
- Click the "Browse..." button.
- Right-click the file GalacticMiningCorp.exe and select "Properies" from the menu.
- In the window that appears, select the "Compatibility" tab.
- Click the "Change high DPI Settings" button.
- Under "High DPI scaling override", tick the box "Override High DPI scaling behaviour" and set the "Scaling Performed By" option to "Application".
- Click OK to close the DPI settings.
- Click OK to close the game executable properties.
- Launch the game.


## SOUND

### Sometimes sounds get louder, or sounds play even when volume is set to zero.

Most music/SFX issues should have been resolved in Patch 2, released Sunday 23rd March 2021.


## GAME SAVES

### Where are save games located?

Games save files are located in `Documents\GMC` with the filename ending `.arr`.


### My game isn't being saved!

This appears to be an issue with some instances of Windows's built-in security protections, or third-party security tools preventing the save files being written to disk.

1. Check if the Windows built-in "Controlled Folder Access" feature has been enabled:

- Open the  "Windows Security" App.
- In the sidebar, click "Virus & Threat Protection"
- Under "Ransomware Protection", click the text "Manage ransomware protection"
- If "Controlled folder access" is set to "On", click the text "Allow an app through Controlled folder access"
- Click "+ Add an Allowed App"
- Select "Recently blocked apps"
- Select the GalacticMiningCorp game executable.

2. Check with your PC's anti-virus/anti-malware software support site to find out how to identify and whitelist the `Documents\GMC` folder and/or `GalacticMiningCorp.exe`

3. For other tools such as CCleaner might intefere with the save process. Follow vendor documentation on how to whitelist the game executable or save folder.


## CONTROLLERS / GAME PADS

### Can I use a gamepad or alternative controller to the mouse?

It is acknowledged there are some players who cannot use a mouse or would prefer to use an alternative controller for accessibility. At present, GMC is designed to be played entirely with a mouse. Adding gamepad/controller support would require a full rework and completely different control scheme, and this is not currently being developed. This is something that the developer would love to add in future, but as a solo developer it is down to the matter of available hours and development time.


## GAMEPLAY

### HQ / Base Building

#### I can't build all the rooms that I have researched

Part of HQ management is selecting the right combinations of rooms with the crew slots and powerups they afford you. To change an old room to a newly researched one, select the room in the HQ screen, then remove remove all of the crew - once this has been done, a button to remove the room will become available. Click this to remove the room and then the space will be free for building again.


### Fusion of items

#### What is "Fusion"?

Fusion merges one type of resource into another. It rewards you with experience and research points, which can be much faster than collecting the items directly during drilling operations.

### Nano Drills

#### Can I deploy nano drills to different drill sites at the same time?

You can deploy your nano drills to one site at a time - they are deployed as a single group to a drill site. The more drills in the deployment, the more resources that are brought back each time.


### Unlocking Crew

#### I am only finding a few of the items I need to unlock crew contracts - this going to take a long time!

Different planets have different rarity levels of tiles.


### Gravity (the "G" level)

#### What does gravity do?

Gravity can be thought of as a difficulty level - the higher the 'G' level, the tougher the planet is to drill. But it is a little deeper than that, as gravity affects the density of tiles as you get further down towards the core. Gravity also increases the speed at which the elemental damage rate increases as you descend.

### Monsters / Enemies

#### Can monsters be killed?

Yes, triggering a well-timed TNT crate will kill most monsters that fall in its radius of explosion.


### Arcade Mini Games 

#### Do I have to complete the arcade games to progress?

No, Banana Drama and the other arcade games aren't compulsory. 


#### Where do I find the arcade games?

These can be found by exploring the squares of each galaxy.

### Market

#### Powerup Crates

Powerup Crates are one time purchase unlocks.
These will then spawn in the world while you're drilling.

#### Stat Booster

Stat Booster are one time purchase unlocks.
These will grant you a permanent stat bonus on unlock.

#### Nano Drill

Nano Drills unlocks grant you one additional Nano Drill per unlock.
For more information see [Nano Drills](#Nano-Drills)

#### Boost Capacity & Chest Value

Those upgrades are infinite and incremental. They grant you a bonus to either your Boost Capacity or Chest Value with each unlock.
