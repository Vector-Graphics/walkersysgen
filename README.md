# walkersysgen

Walker Solar System Generator: a planetary system generator that actually gets it right


I have found a lot of different solar system generators over time, and all of them have had some kind of issue, so I decided to make one that doesn't. 
Use this for your RPG settings, please!

CSV TABLES:

`... star type`:

|`star type`  | Meaning     |
| ----------- | ----------- |
| -1          | not present |
| 0           | white dwarf |
| 1           | M dwarf     |
| 2           | K dwarf     |
| 3           | G dwarf     |
| 4           | F dwarf     |
| 5           | A dwarf     |
| 6           | B dwarf     |

`parent body`:

|`parent body`| Meaning     |
| ----------- | ----------- |
| -1          | orbits star(s) |

`composition`:

|`composition`| Meaning     |
| ----------- | ----------- |
| 0           | rocky       |
| 1           | icy         |
| 2           | carbonaceous|
| 3           | metallic    |
| 4           | ice giant   |
| 5           | gas giant   |

`type`:

|`type`       | Meaning     |
| ----------- | ----------- |
| 0           | uberplanet  |
| 1           | unterplanet |
| 2           | moon of unterplanet|
| 3           | moon of uberplanet with size index between 0-11|
| 4           | moon of uberplanet with size index between 12-23   |
| 5           | moon of uberplanet with size index between 24-35   |

`atmosphere thickness`:

|`atmosphere thickness`      | Meaning     |
| ----------- | ----------- |
| -1           | jovian  |


`atmosphere base gas`:

|`atmosphere base gas`      | Meaning     |
| ----------- | ----------- |
| -1           | jovian  |
| 0           | no atmosphere  |
| 1           | nitrogen |
| 2           | carbon dioxide |

`liquid`:

|`liquid`      | Meaning     |
| ----------- | ----------- |
| 0           | no liquid  |
| 1           | water |
| 2           | ammonia |
| 3           | methanum |
| 4           | nitrogen |


`temperature`:

|`temperature`      | Meaning     |
| ----------- | ----------- |
| 0           | 50K|
| 1           | 70K|
| 2           | 100K |
| 3           | 120K |
| 4           | 150K |
| 5           | 170K |
| 6           | 190K |
| 7           | 220K |
| 8           | 250K |
| 9           | 280K |
| 10          | 310K |
| 11           | 340K |
| 12           | 375K |
| 13           | 425K |
| 14           | 500K |
| 15           | 600K |
| 16           | 750K |
| 17           | 900K |
| 18           | 1200K |

`liquid coverage`:

|`liquid coverage`      | Meaning     |
| ----------- | ----------- |
| -1           | superoceanic |


`life`:

|`life`      | Meaning     |
| ----------- | ----------- |
| 0           | no life |
| 1           | unicellular |
| 2           | multicellular |
