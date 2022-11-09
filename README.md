##  Factory Furniture Production Plan Using Linear Programming-Gurobi Optimization

<img target="_blank" src="https://github.com/dipakml/Linear-Programming-using-Gurobi-Optimization-Python-s-inbuilt-Scipy-/blob/master/gurobi.jpg" width=300>

### Table of Content
  * [Overview of Linear Programming](#overview-of-linear-programming)
  * [Problem Statement](#problem-statement)
  * [Solving Using Gurobi Optimization](#solving-using-gurobi-optimization)




### Overview of Linear Programming 
Optimization is the process of finding maximum or minimum value of a given objective by controlling a set of decisions in a constrained environment. In simple words, an optimization problem consists of maximizing or minimizing a real function by systematically choosing input values from within an allowed set and computing the value of the function.

The real function (objective function) can be the cost of delivering goods from a warehouse to its customers which we would like to minimize by choosing the optimal route and optimal set of vehicles (decision variables) to deliver the goods given a limited number of drivers and time (constraints). This is a generic case of Route Optimization in the world of Operations Research and Optimization.

Another very famous problem in the field of Computer Science is TSP or Travelling Salesman Problem, wherein we want to find the shortest route or least costly route to travel across all cities, given the pairwise distances between them. In this case, our objective function becomes minimizing the total distance (or total cost) travelled, decision variables become binary variables which tell whether the traveller should travel from City i to City j and constraints are applied such that the traveller covers all the cities and does not visit a city twice. We will also be handling a simpler but similar kind of problem today.


###  Problem Statement

<img target="_blank" src="https://github.com/dipakml/Factory-Furniture-Production-Plan-Using-Linear-Programming-Gurobi-Optimization/blob/master/problem_statement.PNG" width=1200>





### Solving Using Gurobi Optimization
The Gurobi Optimizer is a state-of-the-art solver for mathematical programming. The solvers in the Gurobi Optimizer were designed from the ground up to exploit modern architectures and multicore processors, using the most advanced implementations of the latest algorithms.

First we need to install gurobipy using pip install:
Open cmd & type pip install gurobipy
OR
In Jupyter notebook type !pip install gurobipy
<img target="_blank" src="https://github.com/dipakml/Linear-Programming-using-Gurobi-Optimization-Python-s-inbuilt-Scipy-/blob/master/gurobi_install.jpg" width=1200>


Next steps:
- Create a new model
- Create variables
- Set objective function
- Add constraints
- Solve



### Technologies Used  
![](https://forthebadge.com/images/badges/made-with-python.svg) 

<img target="_blank" src="https://github.com/dipakml/Linear-Programming-using-Gurobi-Optimization-Python-s-inbuilt-Scipy-/blob/master/gurobi.jpg" width=300>


