Springies
=========
Compsci 308 Project 02
Name: Gang Li
Design Document

first we have a map containing the different "fixed" points on the structure the user creates then store the nodes as their current location under "no gravity" condition and their distance to the closest nodes they are linked to.
The Mass class is also incorporated into the all map structure, giving each part of the object a "Mass" weighting.
Using both the weight and distance information, we can divide the nodes into different levels within the structure. The top most level of nodes will be flat to the surface should the gravity parameter be changed to uppermost boundary; the bottom level of nodes vice versa.
Springs can be achieved by recording the past positions of nodes and moving the pivots back and forth among its past positions, each time inching closer to the final coordinates.
The friction parameter can be incorporated into this as it determines the speed at which the structure moves on the surface and thereby fixating the number of ocsillations possible under the same JBox physics model.

