# terrancommand
Simple Modification for the Starship Troopers - Terran Command Demo

TLDR:  Adding these 2 configuration files to the mission folder for Peace Of Mine will add in some additional playable units/increase population & war supplies.
Hopefully the dev’s are cool with this post.
I have really enjoyed the demo and look forward to the full release since it’s clear that the developers have a strong foundation.  Like with all games/demos I like to poke around to see what can be modified for additional challenges/fun so I’m sharing these files that add in additional human units, increase population size and war supplies. 
Note: This ONLY applies to the last mission of the demo. AND it is possible the game might freak out if you build a ton of units.  My game personally decided to freeze time after I had too many units on screen and wouldn’t let any units move.

The following units have been added into the final mission “peace of mine”:
Tactical_Officer
Rocketeers
Heavy_Troopers
Fleet_Liaison
Marines
E-Pulse_Infantry
Power_Infantry
Power_Infantry_Hover
Power_Rocketeers
Power_Rocketeers_Hover
Power_Heavy
Power_Heavy_Hover
M11_Marauder_HM
M11_Marauder_FM
M11_Marauder_GM
Psi_Ops
Elite_Guard

The units will spawn in somewhat on top of each other since I couldn’t be bothered to mess with the XYZ coordinates for them to spawn.
Installation
Step 1. Browse to the installation of the demo to locate the mission folder, in my case it is 
“C:\Program Files (x86)\Steam\steamapps\common\Starship Troopers - Terran Command Demo\Starship Troopers_Data\StreamingAssets\Scenarios\Kwalasha_Peace_of_Mine”
Step 2. Make a backup of the files scenario.json AND triggers.json
Step 3. Copy paste the modified scenario.json AND triggers.json into the directory
Step 4. Fire up and play the mission Peace of Mine /have fun

Additional Notes: As with any demo or game currently in development the assets aren’t in their final form, so be prepared for some clunkiness. 
If you want to try modifying it yourself:  If you are familiar with programming, it really isn’t that difficult to make additional changes to add in additional bug types/modify events
I encourage you to look at units.csv and other data within the game directory.  
The game WILL NOT load missions if:
- the .csv files are currently open
- you borked the number of "SoldierCount": 2,  "Members": 2, or jacked up the number of position data for the units.
For example, if you tell the game there’s only supposed to be 4 soldiers/members and you only less than or greater than position data, the mission will fail to load.
Make backups and enjoy!

