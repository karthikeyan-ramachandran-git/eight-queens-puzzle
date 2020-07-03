# Eight queens puzzle - using Genetic algorithm
**Karthikeyan Ramachandran**

## About
### Eight queens puzzle
The eight queens puzzle is the problem of placing eight chess queens on an 8×8 chessboard so that no two queens threaten each other; thus, a solution requires that no two queens share the same row, column, or diagonal. 

### Genetic algorithm
Genetic algorithms are *randomized search algorithms* that have been developed in an effort to *imitate the mechanics of natural selection and natural genetics*. Genetic algorithms operate on string structures, like biological structures, which are evolving in time according to the rule of *survival of the fittest* by using a randomized yet structured information exchange. Thus, in every generation, a new set of strings is created, using parts of the fittest members of the old set. 

## Steps involved
1. Initial population is generated with chromosomes containing random genes.
2. Fitness score of the population is calculated.
3. Based on the fitness score, parents are selected for mating.
4. Crossover and Mutation are performed on the selected parents, to produce offsprings.
5. Offsprings are added to the population and Fitness score is calculated.
6. Process is stopped if max-fitness score is found, else repeated from Step 3 to 5

## Contents:
* [Eight queens puzzle - Code](https://nbviewer.jupyter.org/github/karthikeyan-ramachandran-git/eight-queens-puzzle/blob/master/Eight_queens_puzzle.ipynb)
* [Eight queens puzzle - Explanation](https://nbviewer.jupyter.org/github/karthikeyan-ramachandran-git/eight-queens-puzzle/blob/master/Eight_queens_puzzle_explaination.ipynb)

**References:**
* [The 8 Queen Problem - Numberphile](https://youtu.be/jPcBU0Z2Hj8)
* [Genetic Algorithms - The Nature of Code](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6bJM3VgzjNV5YxVxUwzALHV)
* [Introduction to Genetic Computing](https://github.com/datasigntist/deeplearning/blob/master/Introduction_to_Genetic_Computing_2.ipynb)
