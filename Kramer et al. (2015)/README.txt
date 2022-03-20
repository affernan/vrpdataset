Source: https://w1.cirrelt.ca/~vidalt/resources/PRP-Instances-Krameretal.zip
//--------------------------------------------------------------------------\\
//---- Additional Benchmark instances for the Pollution-Routing Problem ----\\
//--------------------------------------------------------------------------\\

- Adding to the benchmark instances from the PRPLIB, this new benchmark consists of two additional sets (Set B and Set C) of instances with tighter time windows. 
- The time horizon of these new sets is 32400 seconds (as in those from the PRPLIB).
- The time-window width of each customer in Set B was randomly selected between the interval [2000, 5000] seconds with uniform probability, whereas in Set C it was randomly selected between [2000, 15000] seconds.
- Each set contains nine different groups with 20 instances, resulting in 360 new instances.
- The groups are separated according to the number of customers, varying from 10 to 200 customers.
- For more information about instances generation, please read the paper: R. Kramer et al., A matheuristic approach for the Pollution-Routing Problem, European Journal of Operational Research (2014), http://dx.doi.org/10.1016/j.ejor.2014.12.009

The format of each file is the same as those from the PRPLIB, as given below:

(Number of Customers)
-----------------------

(Vehicle Curb Weight Maximum Payload (in kg))
--------------------------------------------

(Minimum Maximum Speed Level (in km/h))
--------------------------------------------

(Distance Section (in metres))
--------------------------------
FULL MATRIX

(Node Section)
----------------
Node Number | City Name | Demand (in kg) | Ready Time (in sec) | Due Time (in sec) | Service Time (in sec) 
