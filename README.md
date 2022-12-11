# Artificial-intelligence-course-experiment-
Coloring a map of China based on genetic algorithm using four-color theorem. 

The problem of coloring maps has always been solved with the help of the four-color theorem. That is, only four colors need to be used as the coloring strategy of the map, and it is guaranteed that two adjacent areas are not filled with the same color. Genetic algorithm is an important algorithm in the field of artificial intelligence to find the optimal solution to a problem by simulating the real-world nature's "survival of the fittest" mechanism. Genetic algorithms have maintained their importance in the field of artificial intelligence for many years, and improved algorithms based on genetic algorithms have been proposed, so they have obvious advantages in solving problems. For example, it is highly scalable and can be easily combined with other algorithms (e.g., annealing, neural networks, etc.) to solve problems; the evaluation function (fitness function) in search is simple to construct and easy to understand and use; and the search is based on the population of each generation, so it is parallel.

Based on the idea of genetic algorithm, we set a population size of 100, a maximum number of iterations of 500, and a variation probability of 0.3, and calculate the ratio of the fitness of each individual to the overall fitness in the population each time, so as to give different weights to each individual, and randomly select two more advantageous individuals for replication and mutation to generate new individuals. The optimal goal is found in the process of continuously reproducing to generate new individuals and iteratively generating new populations, and the problem of coloring a map of China with the four-color theorem is solved.

Therefore, in this experiment, we use genetic algorithm to implement the map coloring problem based on the four-color theorem, and in several experimental tests, we obtain more excellent results on the map of China.
