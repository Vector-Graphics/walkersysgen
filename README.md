# walkersysgen

Walker Solar System Generator: a planetary system generator that actually gets it right


I have found a lot of different solar system generators over time, and all of them have had some kind of issue, so I decided to make one that doesn't. 
Use this for your RPG settings, please!


"Generate system" generates one star system.


"Generate sector" generates 125 star systems, the approximate amount located in a 34x34x34 ly sector of space.


"Generate 500 systems" does exactly what you'd expect.

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

