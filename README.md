# Spriter-Player-for-Phaser
**2016-07-08**

- added rest of easing functions - quartic, quintic, bezier,
- corrected loading tag from JSON files.

</br>
</br>

**2016-04-17**

Code is split into Spriter Player and Test example of usage.</br>
Newly, there are both Spriter Player and minimized version of player in Build directory.</br>
In Build directory you can also find Typescript definitions in spriter.d.ts file.

</br>
</br>

**2016-03-25**

Fixed bug when creating multiple instances of SpriterGroup pointing to the same Spriter animation (instances shared some variables with each other).

</br>
</br>

**2016-02-20**

Added Pro features:
 - character maps
 - tags
 - variables (int and float variables are not interpolated)
 - events
 - sound events (instead of playing sound directly, the player fires event with name of sound to be played)

Most of the code is rewritten.
 
Currently only loading of .scml (.xml) and .scon (.json) produced by Spriter export works. Loading of minimized versions and loading of binary will be added later.

</br>
</br>

**2015-10-30**

Play animations made with Spriter in Phaser engine. Load .xml, .json or special compact binary format.

Supports only features in free version of Spriter.

Can load .xml/.scml and .json/.scon exported directly from Spriter or files minimized with [SpriterMinimizer] (https://github.com/SBCGames/SpriterMinimizer) as well as compact binary output created with SpriterMinimizer.

In [src/States/Test.ts] (https://github.com/SBCGames/Spriter-Player-for-Phaser/blob/master/Spriter/src/States/Test.ts) play with loading .xml, .json, .bin.

