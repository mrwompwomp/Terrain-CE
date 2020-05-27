# Terrain-CE
Terrain CE is currently a TI-Basic experiment of mine in generating a height map and representing it like terrain in an isometric view.

Download here: https://github.com/Michael2-3B/Terrain-CE/raw/master/TERRAIN.8xg
(You will get a GENERATE.8xp file and a DISPLAY.8xp file, which must be run in that order.)

Isometric:

![Isometric View](https://raw.githubusercontent.com/Michael2-3B/Terrain-CE/master/isometry.png)

Top:

![Top Down View](https://raw.githubusercontent.com/Michael2-3B/Terrain-CE/master/topdown.png)

Runthrough:

![Runthrough of Program Gif](https://raw.githubusercontent.com/Michael2-3B/Terrain-CE/master/runthrough.png)

Blue represents a low area, and black is a high area.

The generator algorithm provides height values in a matrix that are no more than 1 higher or lower than the neighboring nodes.
The smoothing code afterwards removes one block dips and spikes.

Forum Thread:
https://www.cemetech.net/forum/viewtopic.php?p=285909#285909
