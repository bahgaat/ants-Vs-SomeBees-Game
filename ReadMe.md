# Ants Vs. SomeBees

This is a tower defense defense game called Ants Vs. SomeBees. As the ant queen, you populate your colony with the bravest ants you can muster. Your ants must protect their queen from the evil bees that invade your territory. Irritate the bees enough by throwing leaves at them, and they will be vanquished. Fail to pester the airborne intruders adequately, and your queen will succumb to the bees' wrath. This game is inspired by PopCap Games' Plants Vs. Zombies ®.

Core concepts

The Colony. This is where the game takes place. The colony consists of several places that are chained together to form a tunnel where bees can travel through. The colony has some quantity of food that can be expended to deploy ant troops.

Places. A place links to another place to form a tunnel. The player can place a single ant into each place. However, there can be many bees in a single place.

The Hive. This is the place where bees originate. Bees exit the hive to enter the ant colony.

Ants. Ants are the usable troops in the game that the player places into the colony. Each type of ant takes a different action and requires a different amount of food to place. The two most basic ant types are the HarvesterAnt, which adds one food to the colony during each turn, and the ThrowerAnt, which throws a leaf at a bee each turn. You will be implementing many more.

Bees. Bees are the antogonistic troops in the game that the player must defend the colony from. Each turn, a bee either advances to the next place in the tunnel if no ant is in its way, or it stings the ant in its way. Bees win when at least one bee reaches the end of a tunnel.

Queen Ant: There is one queen ant in the whole colony. She is able to attack bees but she also has a special ability of fortifying the other ant troops. Bees can also win if they destroy the queen ant

To play a graphical game, run:

python gui.py

![](



There are many options to configure:

-h, --help show this help message and exit
-d DIFFICULTY sets difficulty of game (test/easy/medium/hard/insane)
-w, --water loads a full layout with water
--food FOOD number of food to start with when testing

usage:

python3 ants.py [-h] [-d DIFFICULTY] [-w] [--food FOOD]

For more information: https://inst.eecs.berkeley.edu/~cs61a/sp18/proj/ants/
