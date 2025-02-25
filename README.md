# Travelling-Salesman-Problem
Travelling Salesman Problem Using Genetic Algorithms
Path Representation was used and 8 crossovers are implemented - PMX, MPX, Alternating Edge, Genetic Edge Recombination, Order1, Order2, Cycle, Position.
Roulette Wheel Selection is used as the selection criteria.
Mutation is done by swapping two indices of city. Iterations and Elitism are varied as a hyperparameter.

![Images.](https://github.com/tejasvi96/Travelling-Salesman-Problem/blob/main/Solution.png?raw=True)

![Images.](https://github.com/tejasvi96/Travelling-Salesman-Problem/blob/main/Solution_best.png?raw=True)

Set the parameters in the config.yaml.

```
main:
 file_name : 'City_Coordinates.txt'
 crossover : 'PMX'
 pop_size : 50
 tsp_len : 100
 iterations : 100
 elitism : 1
```

Run the code as

```
  python tsp_code.py
```
