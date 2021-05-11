Urgent Orders:
============
By: Allectus

Translation: FAIL! Chapi (DE), TiomTang (CN)

Github: https://github.com/A11ectus/X4-urgent-orders
Steam: https://steamcommunity.com/sharedfiles/filedetails/?id=2459574093
Nexus: https://www.nexusmods.com/x4foundations/mods/683/

Mod effects:
============
Adds additional high priority orders to the right click menu: Attack-Immediate, Fly-Immediate, Fly-Same Plane, Fly-No Recall, and various combinations thereof.

Requirements:
=============
SirNukes Mod Suppot API

What the mod does:
==================

This mod adds several orders to the right click menu:

* AI Order: Attack, Immediate -- Attack, with order placed at the front of the order queue

* AI Order: Fly and Wait, Immediate -- Fly and Wait, with order placed at the front of the order queue

* AI Order: Fly and Wait, Immediate/Same Plane -- Fly and Wait, with height set by current ship position rather than the ecliptic and order placed at the front of the order queue

* AI Order: Fly and Wait, Same Plane -- Fly and Wait, with height set by current ship position rather than the ecliptic

* AI Order: Fly and Wait, No Recall -- Fly and Wait, the ships will not recall subordinates

* AI Order: Fly and Wait, No Recall/Same Plane -- Fly and Wait, with height set by current ship position rather than the ecliptic and ships will not recall subordinates

* AI Order: Fly and Wait, Urgent -- Fly and Wait, but the order is placed at the front of the order queue, the ships do not respond to enemy attacks, and the ships do not recall subordinates

* AI Order: Fly and Wait, Urgent/Same Plane -- Fly and Wait, with height set by current ship position rather than the ecliptic, the order is placed at the front of the order queue, the ships do not respond to enemy attacks, and the ships do not recall subordinates

* AI Order: Dock and Wait, Urgent -- Dock and Wait, but the order is placed at the front of the order queue, the ships do not respond to enemy attacks, and the ships do not recall subordinates

Some Notes:

	* Urgent is as close as I can manage to a force-move.  The ship will not attempt to cancel the order to respond to attacks and critically will not engage it's override flee order if it comes under fire.  This serves as a reasonable escape mechanism for capital ships but may be suicide for fighters as they will fly in a straight line at constant speed (flee behaviour for small ships gives them access to evasive manoeuvres that this command will skip).  Use wisely, commander.
	
	* Urgent orders may still be interrupted by the comm-player-for-instructions behavior, which could result in an automatic flee behavior being assigned while it awaits your response.  Either respond to the com and tell them to continue, or allow it to time out (~10 sec) and they will resume the urgent command.  I'm still considering how best to handle this (I'm somewhat reluctant to stop that interrupt due to possible unforseen consequences).  See the v1.1 release video for a breakdown of how it behaves currently.

See here for a demonstration: https://youtu.be/JyAwMSAZFuc

V1.1 Release Video: https://www.youtube.com/watch?v=04zg0NxCEbA

Install:
========
-Unzip to 'X4 Foundations/extensions/al_urgent_orders' / subscribe on Steam

-Make sure the sub-folders and files are in 'X4 Foundations/extensions/al_urgent_orders' and not in 'X4 Foundations/extensions/al_urgent_orders/al_urgent_orders'.

-Installation is savegame safe

Uninstall:
==========
-Delete the mod folder / unsubscribe on Steam.

History:
========
1.0, 2021-04-17: Initial release
1.1, 2021-04-18: Added DE translation; Added "Dock and Wait, Urgent"; Allowed "Fly..." commands to take other objects as targets; Fixed bug in "...Urgent" commands that would cause them to not properly ignore attacks
1.2, 2021-05-11: Added support for Wing Hotkeys Mod; Added Attack Targets in Range, Immediate command; Corrected position offset error when camera was tilted; Added CN translation