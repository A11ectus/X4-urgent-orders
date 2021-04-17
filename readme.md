Urgent Orders
by Allectus

github: https://github.com/A11ectus/X4-urgent-orders

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

Some Notes:

	* Urgent is as close as I can manage to a force-move.  The ship will not attempt to cancel the order to respond to attacks and critically will not engage it's override flee order if it comes under fire.  This serves as a reasonable escape mechanism for capital ships but may be suicide for fighters as they will fly in a straight line at constant speed (flee behaviour for small ships gives them access to evasive manoeuvres that this command will skip).  Use wisely, commander.

See here for a demonstration: https://youtu.be/JyAwMSAZFuc

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
