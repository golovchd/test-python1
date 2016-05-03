# test-python1
Q2.
Suppose you will be driving form city A to city B with a car which has
a small tank.  Every road intersection has a gas station, and gas stations only
exist at road intersections.  Therefore, you would like to pick a path in which
the largest distance you travel between two gas stations is minimized (assume
roads are one-directional).
(I)
(2 points).
Give (in the form of pseudo code) an efficient algorithm for ending a path with the desired property.
(II)
(2 points).
Give a python Implementation.  Your program should accept
as input a list of pairs of gas stations between which there is a road, and
the length of that road.  It should output a path from 1 to n, as a list of
nodes, with the desired property (assume A = 1 and B = n).
For instance:
Function on "roads = [(1,2, 1),(1,3,4), (2, 3, 3), (2,5,5),(3,4,3),(3,5,7),
(4,2,1),(4,5,3),(4,6,4),(5,4,1),(5,6,1)]" should return "path =[1;2;3;4;5;6]".
