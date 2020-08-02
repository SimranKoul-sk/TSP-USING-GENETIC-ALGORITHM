# tsp
Traveling salesman problem (TSP) is a classiccombinatorial optimization problem, which is to
find a shortesttour route for a traveling salesman in the predefined quantity ofcities. The constraints
of TSP require that the traveling salesman can only visit each city just once and return back tothe
starting city. TSP has a wide range of applications in manyareas..
Traveling salesman problem(TSP) is a classiccombinatorial optimization problem. The goal is to
find theshortest tour that visits each city in a given list exactly once andthen returns to the starting
city.
ABOUT METHODOLOGY
───────────────────────────────────────
GREEDY
A greedy algorithm is an algorithmic paradigm that follows the problem solving heuristic of
making the locally optimal choice at each stage with the hope of finding a global optimum. In
many problems, a greedy strategy does not in general produce an optimal solution, but nonetheless
a greedy heuristic may yield locally optimal solutions that approximate a global optimal solution
in a reasonable time.
For example, a greedy strategy for the traveling salesman problem (which is of a high
computational complexity) is the following heuristic: "At each stage visit an unvisited city nearest
to the current city". This heuristic need not find a best solution, but terminates in a reasonable
number of steps; finding an optimal solution typically requires unreasonably many steps. In
mathematical optimization, greedy algorithms solve combinatorial problems having the properties
of matroids.

BRANCH AND BOUND 
Branch and bound isan algorithm design paradigm for discrete and combinatorial optimization
problems, as well as mathematical optimization. A branch-and-bound algorithm consists of a
systematic enumeration of candidate solutions by means of state space search: the set of candidate
solutions is thought of as forming a rooted tree with the full set at the root. The algorithm explores
branches of this tree, which represent subsets of the solution set. Before enumerating the candidate
solutions of a branch, the branch is checked against upper and lower estimated bounds on the
optimal solution, and is discarded if it cannot produce a better solution than the best one found so
far by the algorithm.
The algorithm depends on the efficient estimation of the lower and upper bounds of a region/branch
of the search space and approaches exhaustive enumeration as the size (ndimensional volume) of
the region tends to zero.

GENETIC ALGORITHM(GA)
In computer science and operations research, a genetic algorithm (GA) is a metaheuristic inspired
by the process of natural selection that belongs to the larger class of evolutionary algorithms (EA).
Genetic algorithms are commonly used to generate high-quality solutions to optimization and
search problems by relying on bio-inspired operators such as mutation, crossover and selection.
In a genetic algorithm, a population of candidate solutions (called individuals, creatures, or
phenotypes) to an optimization problem is evolved toward better solutions. Each candidate
solution has a set of properties (its chromosomes or genotype) which can be mutated and altered;
traditionally, solutions are represented in binary as strings of 0s and 1s, but other encodings are
also possible.
The evolution usually starts from a population of randomly generated individuals, and is an
iterative process, with the population in each iteration called a generation. In each generation, the
fitness of every individual in the population is evaluated; the fitness is usually the value of the
objective function in the optimization problem being solved. The more fit individuals are
stochastically selected from the current population, and each individual's genome is modified
(recombined and possibly randomly mutated) to form a new generation. The new generation of
candidate solutions is then used in the next iteration of the algorithm. Commonly, the algorithm
terminates when either a maximum number of generations has been produced, or a satisfactory
fitness level has been reached for the population.
A typical genetic algorithm requires: 
1. a genetic representation of the solution domain,
2. a fitness function to evaluate the solution domain. 

Conclusion:
From the output graphs we can observe that although the normal Genetic Algorithm code
for TSP works faster than the code for greedy and branch and bound, it is way far
from the optimum solution. In some cases like Ulysses22 cities problem, the
normal GA algorithm provided a better solution. For some problems like Burma14
with very less number of cities, both the algorithms provided optimum solutions in
the number of generations specified.
We can hereby conclude that for problems with larger number of cities, the GA
with greedy and branch and bound seed, code for TSP works way better than the
normal GA code. 
