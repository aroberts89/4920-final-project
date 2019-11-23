Final Project
Aaron Roberts
CSCI 4920 - Game Programming

-- Files

* Screenshot.png
Shows an enemy running at the core.

* FinalProject.uproject
Unreal Engine project file.

* Content/FinalProject
Contains most of the new files
unique to this project (as opposed to heavy borrowing from
previous homework assignments).

-- Play Instructions

Open FinalProject.uproject in Unreal Editor and press play.

An enemy wave spawner, located a little ways directly in front of the
player's spawn point, will spawn 3 enemies. These enemies will run
straight at the "core", the large silly-looking object in the middle of
the arena.

If they touch the core, they'll do 1 point of damage to it.

The core has 3 health points. If all 3 enemies reach and damage it,
then a "DEFEAT" message will be displayed.

If the player shoots and destroys at least 1 enemy (so that the core isn't
destroyed), a "VICTORY" message will be displayed.