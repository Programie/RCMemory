# Weapons

* Enabling address: int8, 1 = enabled, 0 = disabled
* Ammo address: int32
* Gold address: int8, 1 = gold, 0 = normal

| Name          | Enabled  | Ammo     | Gold     |
| ------------- | -------- | -------- | -------- |
| Suck Cannon   | 2013d5d1 |          | 2013e629 |
| Bomb Glove    | 2013d5d2 | 2013d558 | 2013e62a |
| Devastator    | 2013d5d3 | 2013d55c | 2013e62b |
| Visibomb Gun  | 2013d5d5 | 2013d564 | 2013e62d |
| Taunter       | 2013d5d6 |          | 2013e62e |
| Blaster       | 2013d5d7 | 2013d56c | 2013e62f |
| Pyrocitor     | 2013d5d8 | 2013d570 | 2013e630 |
| Mine Glove    | 2013d5d9 | 2013d574 | 2013e631 |
| Walloper      | 2013d5da |          | 2013e632 |
| Tesla Claw    | 2013d5db | 2013d57c | 2013e633 |
| Glove of Doom | 2013d5dc | 2013d580 | 2013e634 |
| Morph-o-ray   | 2013d5dd |          | 2013e635 |
| R.Y.N.O.      | 2013d5df | 2013d58c | 2013e637 |
| Drone Device  | 2013d5e0 | 2013d590 | 2013e638 |
| Decoy Glove   | 2013d5e1 | 2013d594 | 2013e639 |

Note: Gold state of R.Y.N.O. only changes the color.

# Gadgets

* Enabling address: int8, 1 = enabled, 0 = disabled
* Gold address: int8, 1 = gold, 0 = normal

| Name           | Enabled  | Gold     |
| -------------- | -------- | -------- |
| Heli-Pack      | 2013d5ca | 2013e622 |
| Thruster-Pack  | 2013d5cb | 2013e623 |
| Hydro-Pack     | 2013d5cc | 2013e624 |
| Sonic Summoner | 2013d5cd | 2013e625 |
| O2 Mask        | 2013d5ce | 2013e626 |
| Pilot's Helmet | 2013d5cf | 2013e627 |
| Swingshot      | 2013d5d4 | 2013e62c |
| Hydrodisplacer | 2013d5de | 2013e636 |
| Trespasser     | 2013d5e2 | 2013e63a |
| Metal Detector | 2013d5e3 | 2013e63b |
| Magneboots     | 2013d5e4 | 2013e63c |
| Grindboots     | 2013d5e5 | 2013e63d |
| Hologuise      | 2013d5e7 | 2013e63f |
| Gadgetron PDA  | 2013d5e8 | 2013e640 |

Note: The gold state only changes the color which also does not have any effect on most gadgets (e.g. boots).

# Items

* Enabling address: int8, 1 = enabled, 0 = disabled

| Name         | Enabled  |
| ------------ | -------- |
| Hoverboard   | 2013d5e6 |
| Map-o-matic  | 2013d5e9 |
| Bolt Grabber | 2013d5ea |
| Persuader    | 2013d5eb |

# Misc

| Address  | Type          | Description | Values                            |
| -------- | ------------- | ----------- | --------------------------------- |
| 2015ee98 | int32         | Bolts       |                                   |
| 2015f6a8 | int32         | Debug menu  | 0 = disabled, 4294967295 = active |
| 201416f8 | int16         | Health      |                                   |
| 2014bfc4 | bytearray[40] | Gold Bolts  | 1 = found, 0 = not found          |
| 2013f4d0 | float32       | Position X  |                                   |
| 2013f4d4 | float32       | Position Y  |                                   |
| 2013f4d8 | float32       | Position Z  |                                   |