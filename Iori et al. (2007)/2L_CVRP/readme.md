Original Source: http://or.dei.unibo.it/sites/or.dei.unibo.it/files/instances/2l_cvrp.zip


The .txt files contain 180 instances for the two-dimensional Capacitated Vehicle Routing Problem (2L-CVRP). They are in the form:

---------------------------------------------
Instance: ***
Class: ***
   ***  number of customers (no depot)
   ***  number of vehicles
   ***  number of items
Capacity - height - width of vehicles
   ***    ***    ***
Node - x - y - demand
  0    ***    ***    ***
  1    ***    ***    ***
 ...
Node - number of items - h - w for each item
  0    0
  1    ***    ***    ***    ***    ***
 ...
---------------------------------------------

where "***" represent the values to be read.
"Instance" gives the name of the original CVRP instance used for obtaining the complete graph and the weights. For the notation we used We refer to: P. Toth and D. Vigo. The Vehicle Routing Problem. SIAM Monographs on Discrete Mathematics and Applications, Philadelphia, 2002. Some instances may be modified in the numbering of the nodes, in order to have always the depot as node 0. "Class" gives the value of the class used for the random generation of the items for each customer.

If you are using these instances, please refer to:

-) M. Iori. Metaheuristic algorithms for combinatorial optimization problems. PhD thesis, DEIS, University of Bologna, Italy, 2004.

-) M. Iori, J.J. Salazar Gonzalez and D. Vigo. An exact approach for vehicle routing problems with two-dimensional loading constraints. Technical Report OR/03/04, DEIS, University of Bologna, 2003.

-) M. Gendreau, M. Iori, G. Laporte and S. Martello. A tabu search heuristic for the vehicle routing problem with two-dimensional loading constraints. Technical Report OR/04/1, DEIS, University of Bologna, 2004.

For any question on the subject, feel free to contact:
Manuel Iori
miori@deis.unibo.it
University of Bologna, Italy
