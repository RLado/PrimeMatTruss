# PrimeMatTruss
These are a set of custom functions for Truss Matrix Analysis on the HP Prime. Basically these functions are aimed at obtaining the stiffness matrix of a given set of nodes and elements. From there its easy to obtain forces and displacements by solving the equation F=K*D, with the built in CAS solver function.

Here is an example of how it's used:
buildStiffness([[0,0],[0.8,0],[1.6,0],[2.4,0],[3.2,0],[2.4,2.9],[1.6,2.9],[0.8,2.9]],[[1,2],[2,3],[3,4],[4,5],[5,6],[6,7],[7,8],[1,8],[2,8],[3,6],[3,7],[3,8],[4,6]])

##########################################################

