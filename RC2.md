# Weapons

| Name             | Enabled[1] | Ammo[2]  | Level[3]      | Upgrade[4]  | Normal[5] | Upgraded[6] | Mega[7] | Ultra[8] |
| ---------------- | ---------- | -------- | ------------- | ----------- | --------- | ----------- | ------- | -------- |
| Clank Zapper     | 201a7b89   | 2013972c | 2013990c      | 201395f1    | 9         |             | 73      |          |
| Bomb Glove       | 201a7b8c   | 20139738 |               | 201395f4    | 12        |             | 115     |          |
| Visibomb Gun     | 201a7b8e   | 20139740 |               | 201395f6    | 14        |             | 117     |          |
| Sheepinator      | 201a7b90   |          | 20139928      | 201395f8    | 16        | 72          | 109     | 110      |
| Decoy Glove      | 201a7b91   | 2013974c |               | 201395f9    | 17        |             | 118     |          |
| Tesla Claw       | 201a7b92   | 20139750 |               | 201395fa    | 18        |             | 114     |          |
| Chopper          | 201a7b96   | 20139760 | 20139940      | 201395fe    | 22        | 65          | 83      | 84       |
| Pulse Rifle      | 201a7b97   | 20139764 | 20139944      | 201395ff    | 23        | 66          | 87      | 88       |
| Seeker Gun       | 201a7b98   | 20139768 | 20139948      | 20139600    | 24        | 67          | 85      | 86       |
| Hoverbomb Gun    | 201a7b99   | 2013976c | 2013994c      | 20139601    | 25        | 70          | 103     | 104      |
| Blitz Gun        | 201a7b9a   | 20139770 | 20139950      | 20139602    | 26        | 68          | 91      | 92       |
| Minirocket Tube  | 201a7b9b   | 20139774 | 20139954      | 20139603    | 27        | 69          | 99      | 100      |
| Plasma Coil      | 201a7b9c   | 20139778 | 20139958      | 20139604    | 28        | 62          | 101     | 102      |
| Lava Gun         | 201a7b9d   | 2013977c | 2013995c      | 20139605    | 29        | 63          | 95      | 96       |
| Lancer           | 201a7b9e   | 20139780 | 20139960      | 20139606    | 30        | 60          | 79      | 80       |
| Synthenoid       | 201a7b9f   | 20139784 | 20139964      | 20139607    | 31        | 61          | 93      | 94       |
| Spiderbot Glove  | 201a7ba0   | 20139788 | 20139968      | 20139608    | 32        | 78          | 105     | 106      |
| Bouncer          | 201a7ba5   | 2013979c | 2013997c      | 2013960d    | 37        | 76          | 97      | 98       |
| Miniturret Glove | 201a7ba9   | 201397ac | 2013998c      | 20139611    | 41        | 64          | 89      | 90       |
| Gravity Bomb     | 201a7baa   | 201397b0 | 20139990      | 20139612    | 42        | 71          | 81      | 82       |
| Zodiac           | 201a7bab   | 201397b4 |               | 20139613    | 43        |             |         |          |
| RYNO II          | 201a7bac   | 201397b8 |               | 20139614    | 44        |             |         |          |
| Shield Charger   | 201a7bad   | 201397bc | 2013999c      | 20139615    | 45        | 77          | 107     | 108      |
| Walloper         | 201a7bb5   |          |               | 2013961d    | 53        |             | 116     |          |

* [1] Enabled address: int8, 1 = enabled, 0 = disabled
* [2] Ammo address: int32
* [3] Level address: int32
* [4] Upgrade address: int8
    * [5] Normal value
    * [6] Upgraded value
    * [7] Mega value
    * [8] Ultra value

# Gadgets

* Enabling address: int8, 1 = enabled, 0 = disabled

| Name          | Enabled  |
| ------------- | -------- |
| Heli-Pack     | 201a7b82 |
| Thruster-Pack | 201a7b83 |
| Swingshot     | 201a7b8d |
| Gravity Boots | 201a7b93 |
| Grindboots    | 201a7b94 |
| Dynamo        | 201a7ba4 |
| Thermanator   | 201a7ba7 |
| Tractor Beam  | 201a7bae |
| Charge Boots  | 201a7bb6 |
| Hypnomatic    | 201a7bb7 |

# Items

* Enabling address: int8, 1 = enabled, 0 = disabled

| Name             | Enabled  |
| ---------------- | -------- |
| Hydro-Pack       | 201a7b84 |
| Mapper           | 201a7b85 |
| Commando Suit    | 201a7b86 |
| Armor Magnetizer | 201a7b87 |
| Levitator        | 201a7b88 |
| Glider           | 201a7b95 |
| Electrolyzer     | 201a7ba6 |
| Megacorp Helmet  | 201a7baf |
| Biker Helmet     | 201a7bb0 |
| Box Breaker      | 201a7bb2 |
| Infiltrator      | 201a7bb3 |

# Misc

| Address  | Type          | Description                |
| -------- | ------------- | -------------------------- |
| 201a7b82 | int8          | Have Clank (1/0)           |
| 201a7a80 | int32         | Bolts                      |
| 201a7ae8 | bytearray[30] | Skill Points (1/0)         |
| 201a7a88 | int8          | Nanotech level (read only) |
| 2018c36c | int32         | Health                     |
| 201a7a94 | int32         | Nanotech upgrade           |
| 201a7a84 | int32         | Raritanium                 |
| 20189f20 | float32       | Position X                 |
| 20189f24 | float32       | Position Y                 |
| 20189f28 | float32       | Position Z                 |
| 20221890 | int32         | Space mission 1 enemies    |
| 20221d50 | int32         | Space mission 2 enemies    |
| 201a7aa2 | int32         | Crystals                   |
| 2187fa81 | int32         | Dobbo Boss health          |
| 2029fc34 | int32         | Ship Nuke ammo             |
| 21ff1b94 | int32         | Weapon menu row            |
| 21ff1b98 | int32         | Weapon menu column         |