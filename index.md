## From DNA sequences to metabolic interactions: \
building a pipeline to extract key metabolic processes

A proposal by Haris Zafeiropoulos

### Overview of the project
In constraint-based metabolic modelling, physical and biochemical constraints define a polyhedral convex set of feasible flux vectors. Uniform sampling of this set provides an unbiased characterization of the metabolic capabilities of a biochemical network. The corresponding polyhedra typically lie in hundreds or thousands of dimensions. Fast convergence to the stationary uniform distribution is crucial from a computational point of view, to enable reliable and tractable sampling of genome-scale biochemical networks.

### Tests
This proposal is not among the ideas listed from the `GeomScale` group. 
As it is close the `Inferring microbial interactions` proposed coding project, 
and after contacting the mentors,
I implemented those tests in the framework of my proposal. 

**Easy:**
Compile and run VolEsti. Use the R extension to visualize sampling in a polytope.

**Medium:**
Import the e.coli dataset from bigg and create a matrix in R

**Hard:**
Support lower dimensional polytopes in volesti and use existing methods to sample from them

You may find my tests [here](tests.html).
